# Attributes

There are three centers of intelligence - body, mind, and social. Each center governs how well a character will interact with their surroundings in the various situations they may come across.

The centers are split into:
- "strength" - how well a character can effect the world through that center and 
- "awareness" - how well a character can perceive the world through that center.

## Attribute descriptions

- Body Strength: A traditional view of "strength." How much mass a character can move, how much force they can hit with, etc.
- Body Awareness: Agility. How accurately a character can move and contort their body to perform various actions
- Social Strength: Speech Giving, Pursuassion, Bartering. How well a character can communicate thoughts and emotions to another and influence that person's decisions.
- Social Awareness: Empathy, Sympathy, Insight. How well a character can perceive others' intentions, actions, words, and how the character is being perceived.
- Mental Strength: Puzzling, Cartography, Navigation, Deciphering. How well a character can reason about things.
- Mental Awareness: Sensing, Seeing, Hearing, Smelling, Researching. How well a character can gather information from the outside world.

## Attribute Shorthand

It can get tedious writing out all characters of each attribute every time they are used. Instead, we combine the first letter of the attribute and the first letter of the dimension.

- Body Strength: BS
- Body Awareness: BA
- Social Strength: SS
- Social Awareness: SA
- Mental Strength: MS
- Mental Awareness: MA

## Using Attributes

There are two major ways to use these attributes.

1. Straight Attribute Roll

This is analogous to the common concept of a "dexterity saving throw." When a situation occurs where characters need to react to something in a straight forward manner, you set the difficulty and ask players to roll OVER the number you set (you don't necessarily have to tell them what the difficulty is). A player rolls that number and adds their attribute to that roll.

Use the [probability tool](https://winstonpuckett.com/products/probability) to determine how likely it is a player will succeed.

2. Skill Roll

*See the skill table below for a list of skills*

There are often times when your players will attempt something with a more nuanced skill set necessary. In these circumstances, you can ask players to make a roll using whatever combination of attributes you prefer.

There are many common skills in games - cooking, sneaking, melee attacks, and ranged attacks for instance which it may be helpful to pre-calculate. These are listed in the skill table below so that your players don't have to do math repetitively.

## Guidelines in using attributes (for new DMs)

### Not rolling for things the characters already figure out.

It may be tempting to hand your players a puzzle, then have them roll MS to figure out how to solve it. Sometimes dumb characters make smart moves. If a player finds the answer, they should be allowed to progress the story. Especially if they can find a way for the solution to fit into the character they are playing.

It might also be tempting to have players roll for persuassion. This is more acceptable, but needs to be done in the right context. Sometimes your players make a brilliant speech - their characters should be able to say those words. When you roll for social strength, have it be about whether that was the right thing to say to that person. Maybe they made a really intimidating speech, but their character is wearing clothes which don't make it very intimidating coming out of their mouth. Maybe they said something really wise to convince George to stay, but they used the same words George's wife used right before she walked out on him.

In general, these attributes never alter the player's actions for their character - only the outcomes.

### Not rolling for everything

Make your players roll for things they care about. It may not be a roll to cook for your camp tonight, but if you're in town cooking rations, it might be exciting to roll for how many rations you can make before you'll have to return to town.

Every roll should mean something. Listen to your players for whether this roll will have an impact on their experience at the table.

## Skills

Skills are simply common combinations of attributes that would be useful to have around. Below is a list of all skills plus their attribute combintations. Instead of recalculating this, just go to the character maker (TODO) and plug in your character's attributes. 

- Hit points (HP): BS + MS + 10
- Armor Class (AC): BA + SA + 10

- Melee Attack: BS + BA
- Ranged Attack: MS + MA

- Initiative: MA + BA + SA

- Stealth: (BA + MA + SA) / 3
- Pursuassion: (SS * 2) + SA
- Intuition: SA

- Lock Picking: MS + MA

- Healing: (BA + MA + (MS * 2)) / 3

- Movement Speed: 5

## Proficiencies

TODO

## Items

Items such as daggers, armor, spy glasses are represented on cards. These cards contain all rules for how to use that item including how many limbs that item takes up, its intended purpose, attribute requirements, etc. 

Your character must meet all requirements in order to use the item effectively. If your character does not meet all requirements, the DM may decide how the item applies. For instance:
- Your character doesn't meet the BA requirements, so the DM decides that on a fail of 4 or more, your character deals damage to themselves instead of the opponent. 
- Perhaps your character attempts to use two spears at once (which would require four hands). In this case, you have + 1 damage when you hit, but -4 chance to hit.
- Maybe your character attempts to wear two sets of armour at one time. You're asked to role a D20. On anything below 10, the second set of armour is damaged. 10-19, it's simply impossible to get it on. On a 20, you can wear both sets of armour at once, but you have to have the BA necessary or you can't move at all.

Here's an example item:

```
Assassin's Dagger:

Requirements:
- One hand
- BA: 2
- MA: 3

Melee Attack Damage: 1 D12 + 1
Ranged Attack Damage: 2 D8
```

```
Chainmail Armour:

Requirements:
- Covers full body except head, feet, hands.
- BA: 1

AC: +2
Sneak: -2
```

## An aside on classes and races

The first time I played a classless, raceless system I was shocked by how excellent it was to focus on those as story telling elements instead of elements that effect stats.

In playing Cairn, I was an outlaw named Loop. Because there were no special abilities associated with that background, I focussed on playing out the intentions of an outlaw being in a band of people out to rescue the king's son. Upon meeting another rescue party, I attempted to rob them while they were sleeping. The adventuring party laughed as I looted dead bodies smelling strongly of vommit. The experience was different for the group *because* I was an outlaw. When I've played rogues in the past, I have tended to stick to lawful good - focussing on skillset. This was a much more full role playing experience

In playing Vaeson, I was a fey changling named Chad Chadbourne. I was part of a monster hunting group that hunted all sorts of dark creatures - including the fey. Playing out hiding my identity from the rest of the party and eternally searching for my heritage (my reason to join the hunting group) was incredibly rewarding. I normally play fey/elf/spiritually-in-tune creatures when I play a TTRPG, but this was the first time that my background played into how I interacted with the world. All without a focus on "choosing an elf cause it gives me better dexterity."

In both of these scenarios, the class and race drew me further in to playing out the character. Your character should have a rich background. That background should be central to how you play out your character, not a means to a better attribute.

As an aside to this aside, associating races and attributes does not translate well beyond a fantasy world of elves and dwarves. That, however, is a discussion for another day.

# Combat

## Taking a turn

Every character roles for initiative (Initiative skill + D20). Players take turns in order of initiative from highest to lowest. In the case of a tie, the side that started the combat goes first.

Once turn order is established, each character can move up to their full movement (normally 5 spaces [25 feet]) and take an action. Theoretically, turns should be 5 seconds long.

### Attacking

When your character makes an attack, they roll 3 D6 and add them up. If that number is greater than the target's AC, you hit.

Weapons specify how to roll damage. If you're using an unusual object as a weapon, the DM specifies how to roll damage.

### Doing something other than attacking

You are not restricted to attacks. You can also:

- Dodge: Give the first attack against your character disadvantage.
- Dash: Take up to your character's full movement again.
- Anything else that your character could do within 5 second.
- Start doing something that will take more than 5 seconds.

