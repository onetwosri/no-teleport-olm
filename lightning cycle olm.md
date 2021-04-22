# Guide to no teleport olm
#### by Sri and Fecal

This guide explains how to avoid teleports at olm without counting attacks or using any external plugins/timers. It covers running the mage hand as well as how to get into 4:1 or world scythe for the melee hand. It also covers efficient phase starts that facilitate this. Finally, it includes an [in-depth explanation of what happens to olm's attack cycle when the mage hand dies.](#why-this-method-works)

If you are not interested in any of the theory or explanations and just want the quick and dirty version of the methods, click [here](https://github.com/onetwosri/no-teleport-olm/blob/main/lightning%20cycle%20olm.md#summary).

If you have any questions about anything in the guide or any olm mechanics not covered in the guide, feel free to dm onetwosri#2335 on discord and I will be happy to help to the best of my ability.

**Special thanks to:** Tiprikidi (for original mage hand cycle idea and method, and for reviewing 4:1 setup method) and Sooperpig (for helping with clips and visuals)

## I. Mage Hand

For all phases other than the final phase, olm's attack cycle is as follows:

1. auto
2. null
3. auto
4. crystals
5. auto
6. null
7. auto
8. lightning
9. auto
10. null
11. auto
12. teleports

Meanwhile, running the mage hand can be considered a 3 attack cycle where you attack once from each of 3 locations:
1. melee hand safespot
2. mage side of head
3. the area in between the two safespots (will be called thumb for convenience)

![](https://i.imgur.com/SpPwqmI.png)

Since olm's attack cycle is 12 attacks long and your mage hand cycle is 3 attacks long, you will go through exactly 4 iterations of your mage hand cycle. Here's a side by side comparison of olm's attack cycle vs. yours. Each colored number on the right represents one full mage hand cycle.

![](https://i.imgur.com/KfP3Vk5.png) 

After teleports, both cycles repeat starting from the beginning. Since the cycle always stays the same, you are always at the same spot each time a particular special happens: you're in the melee safespot for crystals, the mage side safespot for lightning, and on the thumb for teleports. That means that every 4th attack that occurs when you are at the thumb is teleports.

Remember that the only time you tank a hit during mage hand is at when you are at the thumb and you splashed from the melee safespot two attacks prior (the exact mechanics of when olm faces middle on a splash vs turns towards mage hand are a bit more complicated but it's not really important so I haven't included it). This means that if you splash from the melee safespot, there is a 25% chance that you will get teleports on the thumb.

Obviously, this is not ideal. It would be much better if the special that occurred at the thumb was lightning or crystals instead of teleports. To make that happen, you have to shift your mage hand attack cycle relative to olm's, as shown below.

![](https://i.imgur.com/C5CIeps.png)

This image shows the three possible ways in which your mage hand cycle can line up with olm's attack cycle. Each one is named based on the special that occurs when you are at the thumb. As you can see, being on either crystal or lightning cycle allows you to avoid getting teleports during mage hand.

Of the two "good" cycles, you want to always be on **LIGHTNING** cycle. This may seem counterintuitive, since crystals are much less annoying than lightning, but this is the **_single most important factor_** for avoiding teles during the melee hand.

### Getting on lightning cycle

When you first start a phase, you are on teleport cycle by default. To get onto lightning cycle, you have to shift olm's attack cycle relative to your own so that he does lightning instead of teles on the thumb. The best time to do this is at the beginning of the phase when you spec the hand, since you want to get off teleport cycle ASAP.

The absolute simplest way to do this is to make sure that you are maging from the melee safespot when olm does his sixth attack. A tick by tick breakdown of standard phase starts is shown below: 

![](https://i.imgur.com/3oylhmK.png)

Note that for p1, your first mage attack will be on the same tick as olm's first attack, and that for p2, you will do one mage attack 3 ticks before olm's first attack (not shown in diagram).

Where you stand before olm's 6th attack does not matter, although you obviously want to avoid as many of olm's attacks as possible.


### Phase start examples

I have included examples of phase starts for many common specing scenarios. 

**You do not need to memorize all of these.**

There are tons of ways to get onto lightning cycle, these clips just represent one way to do it. Feel free to figure out your own methods and do whatever is most comfortable for you. When in doubt, you can always use the 6th attack trick mentioned earlier; at most it will result in you tanking 1 more attack than necessary. Several of the examples below also follow the 6th attack rule.


#### 1 DWH Spec starts

**1. Mage -> DWH (hit) -> Mage**

https://www.youtube.com/watch?v=R-C61WNwyVs

   Note: If you splash the mage hit after hammer, do not run all the way to the melee safespot to avoid tanking a hit, doing so puts you on crystal cycle and you'll have to tank a hit at some point later to get back onto lightning.

**2a. Mage -> DWH (miss or <30) -> Mage**

https://www.youtube.com/watch?v=8Sw3oF2UuU8

   Note: The 4:0 cycle after missing hammer is necessary to shift the cycle from teleports to lightning cycle. In this example I could have avoided tanking a hit by 4:0ing when I splashed instead of waiting and doing it later. The advantage of this method is that you don't tank any hits to shift the cycle, but it costs 1 tick (which you'd lose anyways if you don't have a scythe).
   
   **2b.** https://www.youtube.com/watch?v=7N25g0sNXDY
   
   Alternative method to shift cycle to lightning without losing a tick. Note that running to the mage hand like I did is unnecessary since olm is facing there anyways. You can just afk at the mage hand safespot and tank auto+null then continue running the mage hand. 

**3. Mage (splash) -> DWH -> Mage**

https://www.youtube.com/watch?v=xMd62GX1Wjw

   Note: After my hammer, I was on teleport cycle. To shift to lightning, I ran to the mage hand when I splashed (which conveneniently happened right away). If you don't want to wait for a splash, you can do 1 mage hand cycle and then tank 2 hits at the mage side safespot as shown in example **2b**.
   
   If your DWH doesn't cripple the hand, you can alternatively choose to do a 4:0 cycle instead of running to the mage hand, like in example **2a**.

**4. Mage (hit) -> DWH (hit) -> Scythe -> Mage**

https://www.youtube.com/watch?v=GchYxaHHAqA

**5. Mage (hit) -> DWH (miss) -> Scythe -> Mage**

https://youtu.be/Z05BbMe8RHs

#### 2 DWH Spec starts

**6. Mage -> DWH (miss) -> DWH (miss or hit under 30) -> lance -> mage**

https://www.youtube.com/watch?v=DyUPRsW0Ohs

**7. Mage -> DWH (miss) -> DWH (hit 30+ aka cripple) -> mage**

https://www.youtube.com/watch?v=6ta25GwTezA

   Use this one if you don't have a lance with you even if you don't cripple the hand. Technically you can save energy by just standing still and doing 2 mage attacks after hammering, just like in example #4. I prefer clicking to run to the mage hand as I do my second spec so that I don't need to instantly react to my exp drop in order to do #6.
   
#### Basic knowledge for shifting mage hand cycle

There are a few different ways to shift the cycle:

   1. Tanking a hit instead of moving to the next safespot.
        - This shifts the cycle by 1 (**crystals -> lightning**, or lightning -> teleports, or teleports -> crystals)

   2. Making the head turn from mage side to melee immediately.
        - Examples of this are what happens when you land your dwh or you do a single cycle of 4:0 like in 1 DWH start example #3.
        - This shifts the cycle *forward* by 1 (crystals -> teleports, or lightning -> crystals, or **teleports -> lightning**)
    
   3. Running all the way to the mage hand *without* skipping hits
        - Example is what you do when you cripple the hand with mage->dwh->dwh (#7)
        - This shifts the cycle back by 2 (crystals -> teleports, or lightning -> crystals, or **teleports -> lightning**)

## II. Melee Hand

The advantage of knowing which mage hand cycle you are on is that it makes the timing of teleports somewhat predictable; you know which attacks have a chance of being teleports. For lightning cycle, this happens when you are at the melee safespot. Knowing this allows you to setup the melee hand in such a way that you avoid tanking all attacks that have a chance of being teleports.

This is complicated by the cycle shift that sometimes occurs when the mage hand dies, but all the methods shown below take this into account, so you don't need to worry about it.

An explanation of how this cycle shift works and when it occurs, as well as why the setup methods work is included [here](#why-this-method-works).

### Setting up 4:1

Setting up 4:1 while on lightning cycle is extremely simple; all you have to do is follow one of the following 4 scenarios based on when you cast the attack that kills the mage hand. It might seem confusing at first, but for the most part, the methods are extremely intuitive and once you do them a few times they will become automatic.

All clips include at least part of the mage hand so that you can verify that I'm on lightning cycle. You can skip forward until the mage hand is almost dead in order to see the 4:1 transition.

P.s. many of the clips have scuffed audio and grandma clicks (sorry), but they should still be decent examples

##### Scenario 1: Killing mage hand from the mage side safespot

After killing the mage hand, immediately switch to melee and hit melee hand. The head should turn middle (unless it was already facing middle due to a splash, in which case it will use an attack, which you should ignore). Then, just keep hitting the hand while tanking 2 hits to check where you are in the cycle.

**Examples:**

https://streamable.com/i5rekf

https://streamable.com/304nga

**Note:** There is one scenario in which your 2 check hits will not be accurate. This is shown below. If this happens, don't worry as it doesn't mean you did anything wrong. Just get into 4:1 after lightning.

https://streamable.com/rs1kf3

##### Scenario 2: Killing the mage hand from the thumb area (maging same tick as olm)

If you are maging same tick as olm, then after dealing the killing blow to the hand, run to the melee safespot and hit the hand. Then, tank 1 hit on the thumb before turning the head again, then tank 2 attacks to check the cycle.

**Examples:**

https://streamable.com/hqiedo

https://streamable.com/o8hgvi

##### Scenario 3: Killing the mage hand from the thumb area (maging 1t behind olm)

If you are maging 1t behind olm, then after you kill the hand, run to the melee safespot and hit the hand. Then, tank two hits to check the cycle while making your way to the thumb.

**Examples:**

https://streamable.com/wug42d

https://streamable.com/bxrl5e

##### Scenario 4: Killing the mage hand from the melee safespot

If you kill the mage hand from the melee safespot, turn the head **exactly THREE** times, before tanking two hits to check the cycle. The first head turn is when olm turns from melee safespot to mage side. This means that you only go to the melee safespot if your first lance hit noodles, causing olm to turn middle instead of melee side, as shown in the second example.

**Examples:**

https://streamable.com/brexad

https://streamable.com/cruc4z

##### General advice

Thumb kills are by far the trickiest to learn, as there are two variants and the on-tick variant is somewhat unintuitive. If you are struggling with this, one option is to simply mage 1t behind every time.

If you don't have a scythe, losing a tick to get 1t behind olm doesn't cost you, since you would have to lose a tick transitioning from (on-tick) mage hand to 4:1 anyways. If you do have a scythe, one easy and efficient way to get 1 tick behind without getting off lightning cycle is to replace a mage attack on the thumb with a scythe, as shown below.

https://gfycat.com/malefriendlyitalianbrownbear

![scythe1tbehind](https://user-images.githubusercontent.com/81379323/114262075-de5f6200-9992-11eb-98bf-cf74b0087a4b.gif)

Another way to avoid having to do the same-tick thumb kill setup is to kill the mage hand from further away using the longrange attack style. If you run to a tile that is 1 short of the melee safespot (where you would go to null flamewall), and switch your trident to longrange, the projectile will take longer to land, mimicking the effect of maging 1t behind even if you are attacking on the same tick as olm.

Example: https://www.youtube.com/watch?v=lO8hBVN1qRg

### Why this method works

#### How the mage hand dying affects Olm's attack cycle
Olm’s attack cycle shifts back by 2 attacks if the mage hand dies on the same tick as or 1 tick before either a special attack or a null. In the case that it dies on or 1t before a special, that special is replaced by a null.

In practice this means that:
- If the mage hand dies on/1t before a null, then the next two attacks after the null will be auto + null instead of auto + special.
- If the mage hand dies on/1t before a special, then that special will instead be converted to a null and the next two attacks will be auto + special instead of auto + null.

**Note:**
“When the mage hand dies” refers to the first tick on which its hp bar is no longer visible.

#### In which cases does the cycle shift happen?

The timing of the mage hand dying, and therefore whether or not olm's attack cycle shifts, is based on three things:

1) what tick you are attacking on relative to olm
2) how far away from the mage hand you are when you cast the killing mage attack (important due to trident/sang staff having projectile travel times that vary with distance).
3) where in olm’s attack cycle you are when the mage hand dies

Because most strategies entail either attacking on the same tick as olm or 1 tick after olm, only those scenarios will be covered here.

Both the trident and sang staff have a hit delay of 2 ticks at a range of 2-4 tiles from the target and a hit delay of 3 ticks at a range from 5-7 tiles from the target. This means that when you attack from the mage side safespot, your hitsplat appears on mage hand on the 3rd tick after your attack, and when you attack from either the thumb or the melee safespot, the hitsplat appears on the 4th tick after your attack.

![](https://i.imgur.com/F43JAG2.png)

The mage hand has a death animation that lasts 4 ticks from the time the hitsplat appears. This means that if you attack from the mage side safespot, the hand will die 7 (3 ticks for hitsplat + 4 ticks for animation) ticks later. If you attack from the thumb or the melee safespot, the hand will die 8 (4+4) ticks later.

Since olm does a null or special every 8 ticks, if you attack on the same tick as olm and you cast the killing blow on the mage hand at the same time that he would do a null or special, the mage hand will either die 1 tick before or on the same tick as the next null or special.

**Therefore, if you are running the mage hand while attacking on the same tick as olm, the cycle shift will always happen if you do your final attack at the same time that olm is supposed to do either a null or a special.**

**Note:**
From this point on, "when you kill the mage hand" should be interpreted as "when you cast the attack that kills the mage hand."

But what if you are maging 1 tick after olm?

Attacks from the mage side safespot (or 1-2 tiles short of it) will kill the hand on the same tick as the null/special, while attacks from the thumb or melee safespot will kill the hand 1 tick after the null or special.

**So, if you are running the mage hand while attacking 1 tick after olm, the cycle shift will happen only when you kill the mage hand from the mage side safespot, right after olm was supposed to do a null or a special.**

![](https://i.imgur.com/3TePiLb.png)

#### Applying this to the lightning cycle

Using this information, we can map out all possible kill scenarios for killing the mage hand at different points in lightning cycle. These are shown in the chart below. 

![](https://i.imgur.com/GYDCGTo.png)

**Interpreting the chart:**

Each row covers a different mage hand kill scenario for lightning cycle.

Same tick and 1t behind variants are shown for all 4 thumb kills, since what you do varies depending on what tick you’re attacking

For melee safespot kills, your setup is always the same regardless of which tick you attack on, so 1t variants are only shown for null/special kills, since the cycle shift never happens on auto kills.

- The “OLM” column refers to the point in the cycle that olm is at when you do your final attack on the mage hand.
- The “YOU” column refers to where you are in the mage hand cycle when you attack.
- The “1st-6th attack” columns list the attacks that olm will do after you do your last mage attack.
  -If some of the later attacks in a row are not listed, it is because you will already have set 4:1 by then.
- White cells represent olm's attacks that you avoid by turning the head
- Blue cells represent attacks that you avoid by turning the head unless you splash from the melee safespot just before
- Yellow cells represent attacks that you tank but don’t use to check the cycle.
- Green cells represent attacks that you purposely tank to check where you are in the cycle in order to set up 4:1.

**As you can see from following the chart, doing the 4:1 setups listed earlier allows you to tank hits to check the cycle while avoiding all possible teleports, without requiring you to know which of the 4 possible points in the cycle you are at.**

##### Additional miscellaneous info:

The game also provides an visual indication of when olm registers the mage hand as being dead. The melee hand will briefly “flinch” either on the same tick the mage hand dies or 1 tick after. The check for this flinch to happen appears to be on a 2 tick cycle that aligns with olm’s attack ticks.

Thus, one way to identify that a cycle shift has occurred is if the hand flinches on the same tick as a special or null, but this requires you to know where in the cycle you are, so you'd have to count attacks which is a pain.

However, using the flinch as an indicator is unreliable as the animation is inconsistent and sometimes hard to notice.

Example of normal flinch animation: https://gfycat.com/CluelessMediumDuckbillcat

Example of hard-to-notice flinch: https://gfycat.com/ElatedTastyCarpenterant


### Setting up World Scythe
_Video clips will be added to this section at some point (relatively) soon_

When setting up world scythe, you want to do a specific set of attacks/actions that ensures that the first special you encounter will be either crystals or lightning. These vary depending on which attack you kill the hand at:

##### Scenario 1: Killing mage hand from the mage side safespot
1. Scythe (on tick) at the thumb
2. Lance (1t after olm) at the thumb, then run mage side to keep the head facing center
3. Scythe again on your way to the melee safespot
4. If you get auto'd 1t before your attack at the thumb, then continue to the melee safespot to turn the head. Otherwise stop 1 square short of the melee safespot and tank the next auto before stepping over

To see why this works, consider the case where you do not splash on the attack going from the melee safespot to the mage side. You can encounter one of four attack sequences:
1. head centers (skip blank) - _auto_ - _crystals_
2. head centers (skip auto) - _catch-up auto_ - _auto_ - blank - auto - lightning
3. head centers (skip lightning) - _auto_ - _blank_ - auto - **portals**
4. head centers (skip auto) - _catch-up auto_ - _auto_ - **portals**

The italicized attacks are the attacks you check in step 4 above. By running to the mage side to keep the head facing center, you ensure the head stays center in sequence 3 so you will still be able to skip portals at the melee safespot. By lancing the second hit instead of scything, you ensure that you can attack at the thumb and still be able to reach the melee safespot in time to skip portals in sequence 4. 

_Notes:_ 
- If you splash on the attack before you kill mage hand and the head turns center, then you can do the same thing but will tank an extra attack. For example, instead of center – auto – auto, you would get auto – blank – auto
- Rather than doing scythe - lance, you can scythe twice before running mage side to keep the head facing center. However, if you get auto’d on your way back to the thumb, you will lose ticks as you will need to keep running to melee safespot before attacking again
- If you’re maging 1t behind, replace the first scythe with a lance hit

##### Scenario 2: Killing the mage hand from the thumb area (maging same tick as olm)
1.	Scythe (on tick) at melee safespot
2.	Scythe (1t after olm) at the thumb then immediately run mid to turn the head center
3.	Check the next two attacks (scythe 2t before and 1t before). If you get back-to-back autos, then turn the head melee after the second auto. If you get auto – head turn, then scythe (on tick with the next auto) and turn the head mid after

In this scenario, you can encounter one of four attack sequences:
1. head turns melee (skip auto) - catch-up auto - head turns mid (skip auto) - _crystal_ - _auto_
2. head turns melee (skip blank) - auto - head turns mid (skip lightning) - _auto_ - _head turns melee (blank)_ - auto - **portals**
3. head turns melee (skip auto) - catch-up auto - head turns mid (skip auto) - _catch-up auto_ - _auto_ - **portals**
4. head turns melee (skip portals) - auto - head turns mid (skip blank) - _auto_ - _crystal_

The italicized attacks are the two attacks you check in step 3 above. 

##### Scenario 2b: Killing the mage hand from the thumb area (maging 1t behind olm)
1.	Lance at the melee safespot
2.	Lance twice at the thumb to check the cycle. If you get back-to-back autos, turn the head mid before you start scything 

In this scenario, you can encounter one of four attack sequences:

1. head turns melee (skip auto) - _crystal_ - _auto_
2. head turns melee (skip blank) - _auto_ - _lightning_
3. head turns melee (skip auto) - _catch-up auto_ - _auto_ - **portals**
4. head turns melee (skip portals) - _auto_ - _blank_

The italicized attacks are the attacks you check in step 2 above.

_Notes:_
- You do not necessarily need to lance all 3 times here. You can start scything as soon as you know where you are in the cycle (for example, if you get a crystal or lightning special). You can always start scything after you tank the two attacks to check the cycle
- Alternatively, you can choose to scythe at melee safespot, then continue scything at thumb. However, you will lose ticks if the first two attacks you tank are autos (_i.e._, sequence 3) as you will still need to turn the head mid

##### Scenario 3: Killing the mage hand from the melee safespot
1.	Scythe on tick at the thumb (_do not_ go all the way to the mid safespot)
2.	Scythe (1t after olm) at the thumb then immediately run mid to turn the head center

_Notes:_
- This is the simplest scenario. Portals can happen on olm's 3rd attack after you kill the mage hand. By turning the head mid after your second scythe, you skip portals and ensure the first special you encounter will be crystals or lightning
- If you’re maging 1t behind, replace the first scythe with a lance hit (in this case you can go all the way to the mid safespot). However, in this case, portals can happen on olm's 6th attack after you kill the mage hand. If the first two attacks after you turn the head mid are autos, then step over to the melee safespot after the second auto
- If you want to be consistent between the on tick and 1t behind cases, you can also step over to melee safespot if you get auto-auto on the check attacks in the on tick case, but it is not necessary

## P3/Final Phase

Unfortunately, the methods listed above **do not work** for the final phase. This is because the addition of the healing special means that olm's attack cycle is no longer divisible by 3.

However, by doing conventional methods such as 4:1 (immediately at the beginning of the phase), 4:0, or mage 7:3, you can completely avoid teleports while killing the melee hand, and the odds of getting teleports while doing the mage hand are low enough and represent a small enough timeloss that I would not worry about it.

If you want to 100% avoid teleports, you need to count from the beginning of the phase, which I honestly would not recommend.

## Summary
To avoid teles during mage hand, line up your attack cycle with olm's such that the special you tank in between the safespots when you splash is lightning. The easiest way to do that is just to make sure that you mage from the melee safespot when olm does his sixth attack of the phase. You can also copy the many phase starts shown [here.](https://github.com/onetwosri/no-teleport-olm/blob/main/lightning%20cycle%20olm.md#phase-start-examples)

To avoid teles while setting up 4:1, you must do your check hits slightly differently based on where you do your last attack on the mage hand. The three possible positions are shown below:

1. melee safespot
2. mage side safespot
3. thumb

![](https://i.imgur.com/SpPwqmI.png)

There are 4 scenarios:
1. If you kill the mage hand from the mage side safespot, immediately hit the melee hand and tank your check hits without turning the head any more
2. If you kill the mage hand from the thumb while attacking on the same tick as olm, turn the head to melee safespot, tank a hit on the thumb, then turn the head again before tanking 2 hits to check cycle.
3. If you kill the mage hand from the thumb while attacking 1t after olm, turn the head to the melee safespot then tank your 2 hits to check cycle
4. If you kill the mage hand from the melee safespot, turn the head 3 times, then tank 2 hits to check cycle

You can further simplify this down to 3 scenarios by always maging 1t behind olm. To efficiently transition from maging same tick to 1t behind, you can replace your mage attack from the thumb with a scythe hit: https://gfycat.com/malefriendlyitalianbrownbear

Examples of all 4 scenarios can be found [here](https://github.com/onetwosri/no-teleport-olm/blob/main/lightning%20cycle%20olm.md#setting-up-41).

If you do this correctly, you will never get teleports during any part of olm other than the final phase, where these methods don't work, but you can almost always avoid teleports p3 simply by doing conventional methods like 4:1, 4:0, or m7:3.
