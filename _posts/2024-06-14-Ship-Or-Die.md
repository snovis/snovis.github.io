---
layout: post
title: Ship Or Die
date:  2024-06-14 15:00
chapter: 0
categories: [Blog, Writing,Storytelling,Anecdote]
excerpt: The Story of Shipping a Video Game.
---  
## Ship or Die
I am standing in the middle of the team room at Rainbow Studios watching the flurry of activity surround me as we enter the final phases of shipping the video game Splashdown.  We are trying to unseat the king of all jetski racing games, Nintendo's Wave Race. And we have less than 40 hours to submit our final build to Sony to make our deadline.  These are the dark days of development.  The Grind. No one has slept in days.  Every direction I look I see tired, haggard faces full of determination. This is it, the final death march to ship.

I think it was Yogi Berra who said, the first 90% of a project takes 90% of the time, and the last 10% of the project takes another 90% of the time.  We are definitely in the last 10%.  Artists, Engineers, Animators, Testers, Designers, Game Programmers, Audio deisgners - _everyone_ is focused on pulling this game together.

Building a game is a lot like building a ship in a bottle.  It looks like a pile of sticks until the model builder pulls the string and stands the ship up.  This is the moment when it's time to stand up the ship.  I am checking in with each of the team leads when Jason comes up to me, a huge look of relief on his face and says, "It's done."  Not the game. The user interface.

The team had taken on the ambitious project of rebuilding our entire user interface game engine to bring it up to industry standards for look and feel. And now there it was, in the game, fully operational.  "Let's see it!" I say enthusiastically. I could use some good news.  Jason showed me the beautiful animations, the incredible number of options, and the slick way the icons, buttons, and sliders blended with the art design for the game and the levels. It was a huge leap forward.

Then Jason moved from the character selection screen to the level selection screen, showed me some more awesomeness.  The whole room is feeling releaved... until Jason navigates _back_ to the character selection screen.

"What happened?" I ask.
"What happened to what?" He said.
"Our settings.  Everything we picked.  Their gone."
"Oh," Jason said then sat their for what felt like forever.  "Yeah, well the game doesn't save the state of every screen."

I felt dumbfounded.  "Are you telling me that _every time_ I go through this screen, I have to repick _all_ my options?"

Jason nodded.  "Yeah, all the screens are like that."

My sense of dread is back.  I couldn't believe it.  Didn't he know how annoying that would be to actually use in real life?  Didn't he understand that this beautiful interface was going to practically _ruin_ the play experience?

I turned so we could face each other.  "You have to fix that."

Jason shook his head.  "There's no way to fix that.  We don't have enough time.  Besides, it meets the game specifications."

"Jason, we can't ship it like that.  This is a **must fix**."  At the studio, "Must fix" was a code word for a change we wanted to make at the studio, that the publisher, or even the platform maker might not require.  A must fix was about our commitment to make a great game.

"I'm telling you we can't.  There's no way to fix this."

It was late, probably one in the morning by this point, and suddenly all the joy and optimism of completing the user interface let out of the room like air leaking out of a balloon.  The other artists and engineers in the open plan office turned back to their screens and keyboards, leaving Jason and I having an awkward conversation no one wanted to be a part of in the middle of a crowded room.

I took a deep breath. I could see Jason's face turning red. I can't tell if he is getting ready to cry, or punch me.  Perhaps both.  

"Look," I lean back a little giving him some space.  "Maybe we can't fix it.  Maybe we don't have enough time.  But we have to _try_.  I need you. to try."

Jason rocked from one foot to another.

"Why don't you go home, get some rest, and we'll revisit this in the morning."  One of the lead programmers liked to say, "Nothing good gets checked in after midnight."  We were all tired, but I also knew if we stayed we were going to get nowhere.

Jason nodded, picked up his coat and brushed past me.  Yeah, he was definitely pissed.  But was he pissed at me?  Or pissed that he had overlooked such a fundamental aspect of the game design?  I couldn't tell.  I hoped he was more mad at himself than at me for pointing it out.  But, you know, shoot the messenger, chances are his frustration was pointed in my direction.

I turned my attention to the next fire, and we started to work our way through the mountain of bugs coming in from test.  I didn't tell anyone else that missing our submission would not only be bad for sales, we had a major milestone payment attached to that submission.  Without it, we might not make payroll.  But I also knew, if we shipped a bad user experience, it would be awful for the studio's reputation and our ability to get new game contracts.

I managed to get a cat nap on the couch in my office.  And when there was nothing to do, hell, it's a game studio.  You pick up a controller and play.  Around eight the next morning, Jason returned.  He was bursting with energy.  "I've got it!  I know how to fix it!"

He raced to his PC which was still on from the night before and started to type away furiously.  A couple of hours later, he booted up the game and triumphantly showed me how he could change the settings on each screen, and then navigate back and forth without losing any settings.  I wanted to give him a giant hug. Instead I asked him, "How'd you do it?"

He shrugged a little sheepishly.  "Originally I thought I would have to deal with each button, checkbox, and selector individually, then it dawned on me in the shower that could write the entire memory object to the storage card between screen loads.  It slows down the transitions a little - by like 0.1 seconds, but I can treat the entire screen like ONE thing and it works."

Now we could chear!

We managed to ship our game on time, and Splashdown went on to earn a MetaCritic score of 84 - not bad for an independent developer and sell nearly a million copies.  I still to this day believe in my heard if we had not fixed that user interface we would not have sold a thousand copies, let alone a million.

Looking back, I'm reminded of something a Disney Executive once told me.  "We have to focus on quality.  While quality does not guarantee success, if you ship crap, your customers may never forgive you."  At the end of the day, making video games is about one thing, and one thing only. Putting fun in a box.  No matter how stressful it was, having that clarity gave me the courage to make the right call.  We were not going to ship the game with a frustrating user experience.  It was not fun. It did not belong in the box.

But I also realized, that in that moment, rather than focus on being right, I focused on asking for help.  For believing in Jason.  I asked him to try.  I think at times that's all we can do, is do our best.  And when we do our best, I think we can live with the rest, what ever that is.  To me, this is the essence of vulnerability, and in taking the kinds of risks that let you make great games.
