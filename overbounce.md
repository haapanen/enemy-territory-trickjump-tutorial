Overbounce
==========

This tutorial aims to teach you how to jump overbounce jumps. It will cover the OB detector, sticky, "regular" overbounce and "vertical" overbounce.

What is overbounce?
-------------------

Overbounce is simply a speed boost you get when hitting a platform at certain speeds, so essentially when falling from certain heights. It can be used to to perform tricks that would otherwise be impossible, so it's good to know how it's done.

OB heights can be calculated, but trickjumpers don't have to worry about that. In etjump there's something called an overbounce detector which can be enabled with the cvar `etj_drawOB "1"`.

How the overbounce detector works
---------------------------------

The OB detector is there to show you when you can overbounce. It does this by showing you 3 different letters: **F**, **J** and **B**, which are short for Fall, Jump and Below.

**F** (Fall) shows when you are aiming at a surface that will give you an overbounce if you simply fall there from where you are now. It will take into account your vertical speed, so it works while you're in the air, as well.

**B** (Below) works very much like **F**, but instead of showing up when you aim at a surface that will give you an overbounce, it shows when such a surface is directly under you. You can imagine it drawing a straight line from your feet to the ground. It will only work when you're in the air (or holding on to a ladder).

**J** (Jump) indicates Jump OB heights. When you're standing on a surface and pointing at a surface, it will show if jumping from your current surface to the one you're pointing at will give you an overbounce.

Sticky
------

Often when you fall from a small overbounce height, which is common, you will "have a sticky" afterwards. This will prevent you from doing most overbounce jumps.

The OB detector will show you if you have a sticky, if you aim at the surface you're standing on. It will show either **FJ** or just **F**. You can get rid of the sticky by jumping while standing still, either twice or just once depending on whether you had **FJ** or **F**. Remember to save after jumping or you will have to do it again the next time you load.

Some overbounce jumps require you to have a sticky, but those are less common. The heights for sticky overbounce jumps are different from the non-sticky ones.

Regular overbounce
------------------

This type of overbounce is simple. You just delay pressing space as you hit a surface. If you hold jump before you hit the ground, you won't get a speed boost. You have to press space immediately after you hit the ground though, or you'll lose the speed you gained because of friction.

When falling to a slick (icy) surface, you will simply get a boost and keep the additional speed even if you don't jump at all.

Vertical overbounce
-------------------

A vertical overbounce (VOB) allows you bounce up(not directly) with the speed you gain from your fall. There are a few conditions that have to be met, though:

*   you need to fall from an overbounce height (obviously)
*   your horizontal speed has to be 0 units per second when you touch the ground
*   you need to use `+strafe` and move your mouse

Before you start attempting VOB jumps, you will need to bind `+strafe`. Bind it to any key you like, but use a key that you can easily reach.

There are also a few cvars you might find useful:

    etj_drawSpeed2
    m_side
    m_forward

Setting your `etj_drawSpeed2` to `1` will show you a speedometer that you can use to verify that your horizontal speed is 0 UPS.

`m_side` and `m_forward` change your mouse sensitivity when using +strafe. Some people choose to set their `m_side` to `0`, so that they can only bounce backwards and forwards. If you find you're constantly bouncing too low, either move your mouse slower or lower your `m_forward`, or both.

To do a vertical overbounce:

1.  Find an overbounce height (**F** or **J**).
2.  Fall or Jump down to the surface.
3.  Reset your horizontal speed while in the air, for example by hitting a wall directly or hitting a corner.
4.  Hold your `+strafe` button when hitting the surface, and move your mouse to the direction you want to go.
5.  Do *not* jump.
6.  Do *not* press any of your movement keys until after you have bounced.

If you move your mouse slower, you will bounce higher with less horizontal speed. If you move your mouse faster, you will bounce lower but with higher horizontal speed. Whether or not you use sprint changes the set of speeds you are able to get from the bounce.

Gaining speed after a vertical overbounce is done the same way as usual.