<link rel="stylesheet" href="/styles.css">
<a href="/index.html">back</a>
#Actions
- 5 Types of Actions (And their Icons)
	1. Single Action (single arrow)
	2. Two Action Activities (double arrow)
	3. Three Action Activities (triple arrow)
	4. Free Action (hollow arrow)
	5. Reaction (uno reverse arrow)
- Free actions and reactions typically have triggers
	- You cannot do both a free action and a reaction in response to the same trigger
### Basic Actions
- Every creature can do these except in extreme circumstances

| Action       | Type     | Tags                | Requirements | Description                  |
| ------------ | -------- | ------------------- | ------------ | ---------------------------- |
| Aid          | reaction | n/a                 | yes          | grant bonus to ally          |
| Crawl        | single   | move                | yes          | move 5 ft while prone        |
| Delay        | free     | n/a                 | yes          | Hold your whole turn         |
| Drop Prone   | single   | move                | no           | fall prone                   |
| Escape       | single   | attack              | no           | escape things                |
| Interact     | single   | manipulate          | no           | use an object or swap items  |
| Leap         | single   | move                | no           | jump forward or up           |
| Ready        | double   | concentrate         | no           | hold 1 action or free action |
| Release      | free     | manipulate          | no           | drop something               |
| Seek         | single   | concentrate, secret | no           | look for someone/something   |
| Sense Motive | single   | concetrate, secret  | no           | sense motive                 |
| Stand        | single   | move                | no           | get up from prone            |
| Stride       | single   | move                | no           | move up to speed             |
| Strike       | single   | attack              | no           | you attack                   |

#### Aid (reaction)
**Trigger:** An ally is about to make a skill check or attack roll
**Requirements:** An ally accepts aid and you have prepared to help
- **Crit** grants +2 (maybe more depending on proficiency (master or higher))
- **Success** grants +1
- **Crit Fail** -1 penalty
#### Crawl (single)
#moveAction
**Requirements:** You are prone and your speed is at least 10
- move 5 feet
- staying prone
#### Delay (free)
**Trigger:** Your turn beings
- You delay your initiative position until after someone else's turn
- No reactions until your turn begins
- If you don't take your turn you just lose your turn
#### Drop Prone (single)
#moveAction 
- You fall prone
#### Escape (single)
#attackAction
- Attempt to escape grabbed, immobilized, or restrained.
- Unarmed attack check, or acrobatics, or athletics
- **Crit** free and can **Stride** up to 5 feet
- **Success** Free
- **Crit Fail** not free and can't attempt again until your next turn
#### Interact (single)
#manipulateAction
- grab an object
- draw a weapon
- swap items
- open door
- etc...
#### Leap (single)
#moveAction
- Horizontal jump up to 10 feet for speed of 15+ and 15 for speed of 30+
- Vertical jump up to 3 feet vertically and 5 feet horizontally
#### Ready (double action)
#concentrateAction
- prepare to use an action at a trigger you decide
- Must be a single action or free action
- Can't already have a trigger
#### Release (free)
#manipulateAction
- Drop something
- Does not trigger actions triggered by the manipulate trait
#### Seek (single)
#concentrateAction #secretAction
- Find hiding stuff
- Typically 30 feet or less
- Secret perception check rolled by the GM
- **Crit** You know the location of undetected/hidden creatures/objects
- **Success** Undetected is now hidden hidden is now observed. 
#### Sense Motive (single)
#concentrateAction #secretAction 
- Secret perception check to read a creature
- **Crit** You know the true intentions
- **Success** You no if a creature is behaving normally, but not true intentions
- **Failure** You believe what they want you to believe
- **Crit Fail** You misunderstand their intentions
#### Stand (single)
#moveAction 
- You stand up from being prone.
#### Step (single)
#moveAction 
**Requirements** your speed is at least 10 feet
- carefully move 5 feet 
- doesn't trigger reactions
- Cannot step into difficult terrain
- must use land speed
#### Stride (single)
#moveAction 
- Move up to your speed
- Can't split it up
#### Strike (single)
#attackAction 
- Roll attack roll against AC
#### Take Cover (single)
**Requirements** Benefitting from cover, prone, or near somewhere you can take cover
- Improve your cover condition
