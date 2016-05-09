#HTML5 Game Development with Phaser
##Belén Albeza - Mozilla

Why make HTML5 games? Because we can

---

###The Game Loop
- load & setup
- update game logic according to input
- render game world

---

###Phaser
- create WebGL & 2D canvas

Images are not common in gaming, sprites are more popular. 

####Sprites
- image-based game entities
- usually animated

---

Don't destroy sprites, mark them as zombies. Recycle zombie sprites instead of using new. Easy to implement with Phaser.Group.

Phaser supports audio that is supported by HTML5 and also CSS fonts and bitmap fonts.

Phaser has b-boxes which are very fast but not very accurate collisons. Phaser handles rectangles or circle hit boxes. It also has two physics engines; Arcade and P2.
