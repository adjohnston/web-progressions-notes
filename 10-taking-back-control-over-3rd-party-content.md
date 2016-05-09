#Taking Back Control Over 3rd Party Content
##Yoav Weiss - Akamai

Our ecosystem is broken!

---

###Who is to Blame?
Business ask you to add some third party content but they ruin your performance or user experience. Such as GA, they aren't bad people, they optimise for their users not yours.

We have no say on what third parties do, once they are put on our sites. 

Ads account for 50% of mobile data. They also now make up more space used on our sites removing relevance to content.

---

###Ad Blockers
Ad blockers have given control back to users. iOS 9 includes a content blocker. Opera now has a native ad blocker.

---

###Walled Gardens
Users have begun to fear links as they are slow or could be toxic. Apps are now being created to avoid having ads and toxic third party content to be shown to users.

They offer guaranteed performance with users knowing they wont be slow or heavy in terms of page/data weight. Publishers feel they now have to use the apps.

Advertisers got the message. LEAN & DEAL (targetted at publishers) unfortunately we now have ad blocker blockers with the result of ad blocker blocker blockers.

---

###How to Fix it?
The first sign of civil unrest was `do not track`. IE10 offered a welcome message asking the user if they wanted DNT and the resounding answer was yes with advertisers ignoring the users wishes. In the future we'll need something enforcible.

Content Performance Policy - Unofficial draft
This makes the browser the enforcer.

Sandbox Policy
  - no-sync-script
  - no-sync-xhr
  - no-docwrite
  - no-modals
  - no-plugins
  - no-auxillary-contexts
  
---

###How Would it Work?
The top level document would pass down these rules to child level documents. Would stop downloading when size limits are hit. Limit CPU and bandwith. Certain resources are given priority accordingly.
