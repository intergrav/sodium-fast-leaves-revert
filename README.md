Sodium version 0.4.11 and later includes a change to the fast leaves to fix a mipmapping issue. While the end goal of fixing the issue is achieved, it has a side effect of causing the fast leaves to have a new texture that some users may not like, with the black texture being slightly brighter:

#### Sodium's new fast leaves
![Sodium's Fast Leaves](https://i.imgur.com/0ql9uGf.png)

This pack simply changes these textures back to the Mojang defaults:

#### Fast leaves revert
![Fast Leaves Revert](https://i.imgur.com/8IJyaNK.png)

### Please keep in mind that this will break fancy leaves, as this pack does it's thing by simply making all leaves opaque no matter what. You will have to turn off the resource pack when enabling fancy graphics.

<details>

<summary>Why was this made?</summary>

Originally, this pack was created because during development of Sodium 0.4.10 they had suggested a solution that looked like this, almost like better grass on trees!

![Old solution to the mipmapping issue](https://i.imgur.com/tGY0lem.jpg)

They had then realized that it made leaves look very bad, and went with a different approach to solving it - utilizing the Vanilla Tweaks "nicer fast leaves" texture. It definitely looks better now - but I'll leave this pack up as it could still be viable for some people.

</details> 
