Glossary: Frame Data and Hitbox Concepts
This document defines the core technical terms used to describe the properties of moves in Guilty Gear Strive. A deep understanding of these concepts is essential for analyzing character matchups, developing combos, and making informed decisions during a match.

Part 1: Frame Data Fundamentals
Frame
The single, indivisible unit of time in a fighting game. Guilty Gear Strive runs at 60 Frames Per Second (FPS), meaning one frame is equal to 1/60th of a second. All move properties—speed, duration, and advantage—are measured in frames.

The Three Phases of an Attack
Every attack in the game is broken down into three distinct phases, measured in frames.

Startup Frames: The period of time from when you press an attack button until the move can actually hit the opponent. A move with fewer startup frames is faster. During startup, the move has no hitbox and cannot damage the opponent.

Active Frames: The period of time when the move's hitbox is present and can connect with an opponent. A move with more active frames is easier to time as a "meaty" attack on an opponent's wakeup.

Recovery Frames: The period of time after the active frames have ended, during which your character is returning to a neutral state and cannot perform any other action (unless the move is canceled). A move with more recovery frames is "less safe" and leaves you vulnerable for longer if it whiffs or is blocked.

Part 2: Frame Advantage
Frame advantage is the concept that determines who can act first after an attack has been blocked or has landed a hit. It is a time gap, measured in frames, between when the attacker recovers from their move and when the defender recovers from being hit or blocking. Understanding frame advantage is the key to knowing when it's your turn to attack and when you must defend.

On-Block Advantage
This is the frame advantage when your attack is blocked by the opponent. It is the most critical piece of data for understanding pressure and safety.

Plus on Block (+): A positive value (e.g., +2) means the attacker recovers before the defender is out of blockstun. The attacker has the advantage and can act first, allowing them to continue their offensive pressure. A move that is plus on block is a powerful pressure tool.

Minus on Block (-): A negative value (e.g., -7) means the defender recovers before the attacker. The defender has the advantage and can act first. The attacker is now on the defensive.

Safe vs. Unsafe:

A move is considered "unsafe" if its negative on-block value is large enough for the opponent to land a guaranteed attack before you recover. For example, if a move is -10 on block, and the opponent has an attack with 7 frames of startup, they can punish you every time.

A move is "safe" if its negative on-block value is small enough that the opponent's fastest attack cannot punish you before you are able to block again.

On-Hit Advantage
This is the frame advantage when your attack successfully hits the opponent.

A positive value means the attacker recovers significantly faster than the opponent, who is reeling from the hit (a state called "hitstun"). This is what allows for combos. If a move is +8 on hit, any follow-up attack with a startup of 8 frames or less will connect before the opponent can block, creating a "link" and continuing the combo.

Part 3: Hitboxes, Hurtboxes, and Special Properties
While frame data governs the timing of an attack, hitboxes and hurtboxes govern its spacing. Understanding these invisible geometries is key to understanding why certain moves beat others, even when they seem to come out at the same time.

Hitbox
The invisible area of an attack that can deal damage to an opponent. In training mode and hitbox viewers, this is typically represented by a red box. For an attack to connect, its hitbox must overlap with the opponent's hurtbox.

Hurtbox
The invisible area that defines where a character can be hit. In viewers, this is typically represented by a green box. If an opponent's hitbox overlaps with your hurtbox, you will take damage. Some moves have a cyan hurtbox during their startup or active frames, which indicates that getting hit in this area will result in a Counter Hit.

Key Properties
Disjointed Hitbox: A highly advantageous property where a move's hitbox extends significantly beyond the character's own hurtbox. This allows the attacker to hit the opponent from a range where the opponent cannot hit them back. Dizzy's j.S is a prime example of a move with a large, disjointed hitbox.

Invincibility (Invuln): A state during which a character's hurtbox is temporarily removed, making them immune to being hit. Invincibility can apply to specific attributes:

Strike Invuln: Invincible to strikes (punches, kicks, weapon attacks). This is the property of most reversal Overdrives and Dragon Punches (DPs).

Throw Invuln: Invincible to throws. All characters have throw invincibility for the first 5 frames of their wakeup animation.

Projectile Invuln: Invincible to projectiles. Many advancing special moves have this property, allowing them to pass through fireballs.

Upper-Body Invuln: A common property of 6P attacks. The character's upper hurtbox is removed, allowing the move to cleanly beat most aerial attacks.

Low Profile: A property of certain moves (usually crouching attacks) where the character's hurtbox is lowered so much that it can go under high-hitting attacks, causing them to whiff.

Armor: A property that allows a character to absorb one or more hits without being interrupted or put into hitstun. The character still takes damage, but their attack continues. Potemkin's 'Slide Head' special move famously had a point of armor before it was removed in Patch 1.48.   

Part 4: Common Fighting Game Terminology
This section defines common slang and technical terms used by the fighting game community to describe specific situations, strategies, and techniques.

Okizeme (Oki): A Japanese term that refers to the strategy of applying pressure to an opponent as they are getting up from a knockdown. A character with strong "oki" can force the opponent into a difficult guessing game the moment they recover. This is the core of Dizzy's and Millia's offensive game plan after a hard knockdown.

Meaty: An attack timed to be active on the very first frame an opponent wakes up from a knockdown. A successful meaty forces the opponent to block or use an invincible reversal, beating any other wakeup option. Dizzy's K-Fish is often used to hit "meaty".   

Safe Jump: A specific type of meaty attack where a jumping attack is timed to hit the opponent on their wakeup, but the attacker is able to land and block before the opponent's invincible reversal can punish them. It is a powerful offensive tool that safely beats most defensive options.

Frame Trap: An offensive technique where a player intentionally leaves a small gap (a few frames) in their blockstring. This gap is designed to bait the opponent into thinking it's their turn to attack. The attacker then uses a delayed follow-up move that will counter-hit the opponent's attempt to interrupt.

Mix-up: An offensive situation where the attacker presents multiple threats that require different defensive responses, forcing the opponent to guess. Common mix-ups include High/Low (forcing a guess between a standing and crouching block) and Strike/Throw (forcing a guess between blocking an attack and teching a throw).   

DP (Dragon Punch): A universal term for a special move that has invincibility on startup, making it a powerful reversal tool to escape pressure. Named after the "Shoryuken" from the Street Fighter series. Most characters have a DP or a reversal Overdrive.

Reversal: Any action performed on the first possible frame after recovering from a non-neutral state (such as blockstun or knockdown). This term is most often used to refer to an invincible attack used as a defensive escape.

Tick Throw: A strategy where an attacker performs a light, fast, and safe-on-block attack and immediately follows it up with a throw. The initial light attack conditions the opponent to block, making them vulnerable to the subsequent throw.

Fuzzy: A high-level defensive technique where a player inputs multiple defensive options in rapid succession to cover several of the opponent's mix-up options. Examples include "Fuzzy Block" (quickly switching from low to high block) or "Fuzzy Jump" (blocking for a moment and then jumping).
