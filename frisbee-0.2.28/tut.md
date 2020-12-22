# 8-BIT ULTIMATE
*#THROWEVERYDAY*

This Pico-8 game is a simple replica of *Ultimate Frisbee.*

Its like football, but instead of a football, its a disc -- and you cannot run with the disc.
You have to throw the disc within 10 mississippi of a defender marking you. He will stand close and count to 10.
You will see a lot of the game's rules present in this cartridge. Double team, out of bounds, disc pulls, stall counts, and so on.

Let's quickly go over the controls.

## What Guy Am I?

![alt text1][pic1]

Your selected player will display a *pink* letter above his head. You will always control someone from the orange team.
Note that when you're on offense, you are in control of the game; the action revolves around you. On defense, its up to you to react.

On offense, you will control the *cutters* who are trying to get open for a pass. You can switch players by pressing x/o buttons.
Pressing the same button twice will execute a throw to that cutter.

On defense, you will control whichever player has a 'y' above his head. You cannot switch players, except if your player is marking on the thrower.
In that case, the game will convenience you to a fielding position. 

## Running

![alt text1][pic2]

Press (and then release) a direction on your d-pad buttons to **run.** Tap very quickly and your player will **stop running.**
Stopping running is useful in a lot of situations.
Player will **dash** after gaining enough momentum and then changing direction.
Skillful cuts may cause a defender's legs to buckle.

## Throwing

![alt text1][pic3]

Press the button twice, and you will throw to that player. The game will apply some curve to your throw, so you might get some lucky ones!

## The Handblock

![alt text1][pic4]

If you throw a disc directly through your mark, he is probably going to block it. It is a big challenge for disc handlers.
It is good to throw deep on the force side (See? He is forcing you to one side.), and short to the guarded side ("break side").
In this case, our thrower is trapped on the sideline. It is sometimes worth losing a few yards just to swing to the break side.

## Double Team Foul

![alt text1][pic5]

It is not really fair to surround the thrower. The game will reset the stall count for this foul.

## That's all!
### Nice to Have (But Won't Fix) List
- On-screen messages for turnovers, etc
- Disc out of bounds is inbounding way too deep most of the time.
- Goalline "iso" plays. At least ignore double team fouls in goalline situations.
- Score cap at 7 points.
- Some team stats.

### Acknowledgements
***stefvdw* 's Bezier Curves** demo/code helped me out quite a bit. I used the code for disc flight paths.
I have randomized the control point with the aide of some trig functions.
If you want to see a little more of this, you can press x and o and a direction, to manually manipulate the control point while disc is in-flight.
I left it that part there just for kicks.
Thanks to *stefvdw* for the awesome curves code.
https://www.lexaloffle.com/bbs/?tid=34770


**Succer by *Reload*** is an "OG" Pico-8 game replicating soccer. The developer wrote a nice story for it in PICOZINE #3.
I did not know about Manhattan Distance, but I learned it from that article and put it in this game.
The whole article was very nice. I followed his design pretty closely, either intentionally or unintentionally.
But I think 70% * Manhattan Distance is, for me, working even better. I dunno.
https://www.lexaloffle.com/bbs/?tid=2614

Thanks!

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
[pic1]:  https://mal2994.github.io/frisbee-0.2.28/uf28_4.gif "text1"
[pic2]:  https://mal2994.github.io/frisbee-0.2.28/uf28_14.gif "text1"
[pic3]:  https://mal2994.github.io/frisbee-0.2.28/uf28_6.gif "text1"
[pic4]:  https://mal2994.github.io/frisbee-0.2.28/uf28_5.gif "text1"
[pic5]:  https://mal2994.github.io/frisbee-0.2.28/uf28_13.gif "text1"
