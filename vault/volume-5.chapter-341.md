---
id: 2t7gr2hqnyupsan6tajfluz
title: Chapter 341 -
desc: ''
updated: 1687689091246
created: 1687674247179
---

"Actually, it isn't that far off. The standard strategies work," the Sect Leader followed up with a shrug.

"For example-"

Two numbers: 1011 and 1001 appeared one on top of the other.

"If we are to add 11 and 9 in decimal digits, its summing 1 and 9 in the unit's place with a 1 carrying over to the tens place, which gets added to a one. So, 20. In binary, you add the ones in the 2^0, the 1 and 0 in 2^1 and the ones in 2^3, so-"

The addition resolved to get: 2012.

"But since we can't have number greater than one, we need to start carrying over. A 2 in 2^0 means that you can basically add a 1 to the 2^1, so-"

2020

"A 2 in the 2^2 is basically a 1 in the 2^2, so-"

2100

"A 2 in the 2^3 is 1 in the 2^4, so we can add another binary place/"

10100

"Now if you read this binary number, it should also give you 20."

"This just feels longer," Shuri mumbled.

"Maybe for you, sure," the Sect Leader responded. "But if you think about automatic systems, if a decimal place exceeds 1, then it is the same as flipping up a switch in the subsequent decimal place. You don't have to worry about excessive carrying over. All operations are just ones and zeroes, in the end."

"I guess that makes sense," Shuri admitted with a faintly sceptical tone.

"Let us check out the subtraction and the rest," the Sect Leader encouraged.

For Shuri, wrapping her head around this new method of digitally representing numbers was tougher. To that, the Sect Leader said, "There are many reasons it's difficult for you compared to the usual method. For one, you started learning in and were taught primarily in another method. This has become ingrained into so deeply that it's hard to regularise yourself with another. On top of that, this method isn't tractable for common mathematics that you and I use. It's meant for something else altogether."

"That's the thing, I can't see how this can be applied," Shuri said with a defeated sigh. "I feel like I'm missing something important."

"It will make sense once we start logic. With that in place, all this knowledge will come together into a neat bundle," the Sect Leader declared.

Shuri's enthusiasm rose once again as she anticipated the arrival of the crucial puzzle piece that would untangle the mess in her mind right now. But just like yesterday, the Sect Leader glanced at the time and said, "That's it for today."

"What? Why?" Shuri argued in disbelief. "We still have time!"

"Technically, sure. But I have other commitments too, you know," the Sect Leader said with a smile. "But I like your enthusiasm! Once again, let me remind you that it is inadvisable to read up on this topic beforehand."

He chuckled and added, "You're the first student I've told to specifically not read before coming to class. So... I guess, congratulations on being the first..."

After that, Shuri felt herself moving down a familiar chute that directly deposited her back into her body.

____

Following another night of strained sleeping, trying to hold back her urge to devour knowledge, Shuri found herself being siphoned down the dark chute.

"Today's topic is quite heavy, so please stop me if things become difficult or if we're moving too quickly," the Sect Leader prefaced.

"Binary numbers can either be 1 or 0, that has already been established. You can attach meaning to this 1 or 0, by saying that 1 means 'on' and 0 means 'off'. You can also say that 1 is 'true' and 0 is 'false."

"Every decision or action you do or take is preceded by a set of conditions that need to be met. For instance, eating food depends on the precondition of you being hungry. Scratching your skin is preconditioned on whether you are feeling itchy in that location. So, to define an analogy using the previous definitions, if for an action A, you have a precondition B, if B is true, then your brain will send a signal: 1 to execute the action A. On the other hand if it is false, you get a signal: 0 to not execute it."

As the Sect Leader said this, a line formed in front of Shuri. On either side, there were two bulbous dots. Above the left dot, a B showed up, and above the right dot an A did.

B o--------o A

"We can define the behaviour of this system with a truth table:"

| B | A |  
| 1 | 1 |  
| 0 | 0 |

"But what if you have two preconditions for the execution of action A?"

As he said this, the line branched:

B o-------o A  
C o----/

"If both B and C need to be true for A to execute, then what do you do?"

Shuri thought for a while before saying, "It's obvious, right?"

"True, but you need to place something at the intersection that computes the AND in this precondition," the Sect Leader hinted. "In fact, what we put here is a gate called the AND gate."

At the point of intersection, a curved arrow took shape, like a large semi-circle. It had two lines going in from one side that started from the preconditions B and C, and from the other side, a single line exited ending at A.

"With the AND gate, both B and C need to be true for it to trigger:"

| B | C | A |  
| 1 | 1 | 1 |  
| 1 | 0 | 0 |  
| 0 | 1 | 0 |  
| 0 | 0 | 0 |  

"Instead, what if all that you needed was for one of the conditions to be true? Either B OR C?"

"Would you use an OR gate?" Shuri hypothesised.

"Excellent deduction!"

The AND gate was replaced with another curved arrow that looked like a triangle pointing to the right, but with the base at the left arching inwards.

"Can you deduce what the truth table would be like?"

Shuri was presented with an empty table, and a pen materialised in her hand. Carefully, she started to jot down her calculations.

| B | C | A |  
| 1 | 1 | 1 |  
| 1 | 0 | 1 |  
| 0 | 1 | 1 |  
| 0 | 0 | 0 |  

The Sect Leader proceeded to go through a myriad of other gates that started with the NOT gate, which basically inverted the input signal.

| B | A |  
| 1 | 0 |  
| 0 | 1 |  

Then the NAND gate, which basically inverts the output of an AND gate