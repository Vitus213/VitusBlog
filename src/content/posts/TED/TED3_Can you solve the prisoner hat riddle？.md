---
published: 2024-6-25 20:37:00
updated: 2024-6-29 19:37:00
title: Solve the prisoner hat riddle?
tags: [学习笔记,TED]
description: 这是一场与英语的较量,TED之每日坐牢
category: TED
id: TED_3
---



# Can you solve the prisoner hat riddle？

> [MP3](https://www.ted.com/talks/alex_gendler_can_you_solve_the_prisoner_hat_riddle)

## Key

1. ten people facing forward in size order 

2. each of you have a white/black hat on you heads,you should guess your hat color,you can only see the hat color of the people who are front of you.

3. odd or even , the first can use the black/white to show odd /even,if prisoner one see odd numbers black ,he say black,and if prisoner two see odd numbers black,he should say black ,because he can guess his hat is white ,the same can be said.

4. Recursion!

![image-20240629040149871](https://cdn.jsdelivr.net/gh/zhzvite/picgoroom@img/img/202406290401115.png)



## Article

You and nine other individuals have been captured by super intelligent alien overlords. The aliens think humans look quite tasty, but their civilization forbids eating highly logical and cooperative beings. Unfortunately, they're not sure whether you qualify, so they decide to give you all a test. Through its universal translator, the alien guarding you tells you the following: You will be placed in a single-file line facing forward in size order so that each of you can see everyone lined up ahead of you. You will not be able to look behind you or step out of line. Each of you will have either a black or a white hat on your head assigned randomly, and I won't tell you how many of each color there are. When I say to begin, each of you must guess the color of your hat starting with the person in the back and moving up the line. And don't even try saying words other than black or white or signaling some other way, like intonation or volume; you'll all be eaten immediately. If at least nine of you guess correctly, you'll all be spared. You have five minutes to discuss and come up with a plan, and then I'll line you up, assign your hats, and we'll begin. Can you think of a strategy guaranteed to save everyone? Pause the video now to figure it out for yourself. 

（Answer in: 3  2  1）



The key is that the person at the back of the line who can see everyone else's hats can use the words "black" or "white" to communicate some coded information. So what meaning can be assigned to those words that will allow everyone else to deduce their hat colors? It can't be the total number of black or white hats. There are more than two possible values, but what does have two possible values is that number's parity, that is whether it's odd or even. So the solution is to agree that whoever goes first will, for example, say "black" if he sees an odd number of black hats and "white" if he sees an even number of black hats. Let's see how it would play out if the hats were distributed like this. The tallest captive sees three black hats in front of him, so he says "black," telling everyone else he sees an odd number of black hats. He gets his own hat color wrong, but that's okay since you're collectively allowed to have one wrong answer. Prisoner two also sees an odd number of black hats, so she knows hers is white, and answers correctly. Prisoner three sees an even number of black hats, so he knows that his must be one of the black hats the first two prisoners saw. Prisoner four hears that and knows that she should be looking for an even number of black hats since one was behind her. But she only sees one, so she **deduces**(to use the knowledge and information in order to understand something ) that her hat is also black. Prisoners five through nine are each looking for an odd number of black hats, which they see, so they figure out that their hats are white. Now it all comes down to you at the front of the line. If the ninth prisoner saw an odd number of black hats, that can only mean one thing. You'll find that this strategy works for any possible arrangement of the hats. The first prisoner has a 50% chance of giving a wrong answer about his own hat, but the parity information he conveys allows everyone else to guess theirs with absolute certainty. Each begins by expecting to see an odd or even number of hats of the specified color. If what they count doesn't match, that means their own hat is that color. And every time this happens, the next person in line will switch the **parity**(the state of being equal) they expect to see. So that's it, you're free to go. It looks like these aliens will have to go hungry, or find some less logical organisms to **abduct**(to take someone away by force ).

