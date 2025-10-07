# Guilty Gear Strive: Gameplay Fundamentals

This document outlines the absolute foundational mechanics and concepts of Guilty Gear Strive. It is intended for a user (human or AI) with no prior knowledge of the game or fighting games in general.

Section 1: The Language of Combat - Numpad Notation
To understand any combo, guide, or technical discussion, you must first learn the universal language for describing joystick and button inputs: Numpad Notation.

This system uses the numbers on a keyboard's numpad to represent the eight directions on a joystick or D-pad, assuming the player is facing right.

7 8 9
4 5 6
1 2 3
5: Neutral (joystick is not being pushed)

6: Forward

4: Back

8: Up

2: Down

9: Up-Forward

7: Up-Back

1: Down-Back

3: Down-Forward

Attack Buttons:

P: Punch

K: Kick

S: Slash

HS: Heavy Slash

D: Dust

Example: A standard fireball motion is "Down -> Down-Forward -> Forward + Punch". In numpad notation, this is written as 236P. Dizzy's "Michael Sword" is 214S or 214HS.  This notation is the standard for all files in this repository.    

Section 2: The Flow of Battle - Movement & Universal Actions
Ground Movement
Walking: Pressing 4 (away from opponent) or 6 (towards opponent).

Running/Dashing: Quickly tapping 6 twice and holding it. This is the primary way to close distance on the ground.

Backdash: Quickly tapping 4 twice. A quick burst of backward movement that has some invincibility frames at the start, allowing you to evade attacks.

Aerial Movement
Jumping: Pressing 7, 8, or 9. You can block while jumping backwards (7), but not while jumping straight up or forward.

Double Jump: Pressing an upward direction again while in the air.

Air Dash: Quickly tapping 6 twice or 4 twice while in the air for a burst of horizontal movement.

Universal Attacks
Throws: Performed by pressing 6D or 4D when very close to the opponent. Throws are unblockable and beat an opponent who is just blocking.

Dust Attack (5D): A slow, overhead attack that must be blocked high. If it hits a grounded opponent while fully charged, it launches them for a unique aerial combo sequence.

Sweep (2D): A low attack that knocks the opponent down, creating a Hard Knockdown (HKD). This is a critical state that allows you to set up offensive pressure while the opponent is getting up.

Section 3: The Art of the Combo - Gatlings and Cancels
A "combo" is a sequence of attacks that the opponent cannot block after the first hit connects. In Guilty Gear Strive, combos are primarily built using a system of cancels.

A cancel is when you interrupt the animation of one move by immediately inputting another. This allows moves to flow together much faster than they would otherwise.

The Combo Hierarchy
The basic rule for building combos is a "bottom-up" system:

Normal to Normal (Gatling): Lighter, faster normal attacks can be canceled into heavier normal attacks. The most common route is P > K > S > HS. You can also often cancel a standing normal into the same crouching normal (e.g., 5K > 2K).

Normal to Command Normal: Most normal attacks can be canceled into a character's unique command normals (e.g., a 6P anti-air).

Normal to Special: Almost any normal attack can be canceled into a special move (e.g., 5S > 236P). This is the most common way to end a basic ground combo and secure a knockdown.

Special to Overdrive: Most special moves can be canceled into an Overdrive (super move) for high damage.

Example: A very basic combo for many characters might be 5K > 2D. Here, the 5K attack is canceled into the 2D sweep. The 2D provides a Hard Knockdown, which is a strategically powerful ender.

This system of cancels is the fundamental building block of all offense in the game.

Section 4: The Math of Pain - Damage Scaling
Not all hits in a combo do full damage. The game has several systems in place to reduce damage as a combo goes on, a concept known as Damage Scaling.

Proration
The very first hit of your combo can apply an initial damage penalty to the entire rest of the combo. Lighter, faster attacks (like 2P or 2K) often have heavy proration, meaning a combo started with them will do significantly less damage overall than one started with a heavy attack like c.S (close Slash).

R.I.S.C. Level and Gravity Scaling
As a combo continues, each successive hit does less damage. This is tied to the R.I.S.C. Gauge. When you hit an opponent, their R.I.S.C. level decreases (even going into negative values you can't see). The lower the R.I.S.C. level, the more the combo is scaled and the less damage each hit does.

This also affects how "heavy" the opponent becomes. As scaling increases, gravity also increases, causing the opponent to fall faster during air combos. This makes longer, more complex juggles difficult or impossible without spending meter.

Strategic Implication: This is why a 3-hit combo can sometimes do more damage than a 10-hit combo. The goal is not always to do the longest combo, but the most efficient one. This is especially critical for Dizzy, as her Freeze mechanic instantly maxes out this scaling, severely reducing her combo damage and giving the opponent a massive amount of resources.`
