---
layout: post
title: Ship Or Die
date:  2024-06-14 15:00
chapter: 0
categories: [Blog, Writing,Storytelling,Anecdote]
excerpt: The Story of Shipping a Video Game.
---  
## Ship or Die
I am standing in the middle of the team room at Rainbow Studios watching the flurry of activity surround me as we enter the final phases of shipping the video game Splashdown.  We are trying to unseat the king of all jetski racing games, Nintendo's Wave Race. And we have less than 40 hours to submit our final build to Sony to make our deadline.  No one has slept in days.  Every direction I look I see tired, haggard faces full of determination. This is it, the final death march to ship.

I think it was Yogi Berra who said, the first 90% of a project takes 90% of the time, and the last 10% of the project takes another 90% of the time.  We are definitely in the last 10%.  Artists, Engineers, Animators, Testers, Designers, Game Programmers, Audio designers - _everyone_ is focused on pulling this game together.

Building a game is a lot like building a ship in a bottle.  It looks like a pile of sticks until the model builder pulls the string and stands the ship up.  This is the moment when it's time to stand up the ship.

I am trying to be available for last minute, or final hour coordination. I do not want to camp anyone, or transmit the stress I am feeling, but I can't go away either. Too often a critical choice, or an approval needs to be made, and although I was the president of the studio, in many ways my job in the final hours is to act as executive producer.  When everything is going well, I am here for support and encouragement.  When things don't go well, I'm the fan the preverbal shit has to hit.

I am checking in with each department lead when Jason comes up to me, a huge look of relief on his face. He says, "It's done."  Not the game. The user interface. But the game needs the UI to ship so this is great news.

Jason and his team had taken on the ambitious project of rebuilding the user interface module for our game engine.  This would effect every game going forward.  They wanted to make our UI feel cutting edge, something other companies would strive to replicate. And now here it was, in the game, fully operational.  Eleventh hour or no, it was a huge accomplishment.

"Let's see it!" I say enthusiastically. I could use some good news.  Jason showed me the beautiful animations, the incredible number of options, and the slick way the icons, buttons, and sliders blended with the art design for the game and the levels. It was a huge leap forward.

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

I take a deep breath and let it out.  I think that went well...

I turn my attention to the next fire, and we started to work our way through the mountain of bugs coming in from test.  I didn't tell anyone else that missing our submission would not only be bad for sales.  Only I know we also have a major milestone payment attached to the submission.  Without it, there's a good chance we don't make payroll.  But I also know, if we ship a bad user experience, it would crush the studio's reputation and with it our chances of getting another game contracts.  Publishers hate being late.  But what they are terrified of spending millions of dollars on a game that doesn't sell.

I managed to get a cat nap on the couch in my office.  And when there was nothing to do, hell, it's a game studio.  You pick up a controller and play.  So I played, and talked, and visited.  For a game executive waiting for a gold master disk can feel a lot like waiting for a baby to be born.  You can't go home.  You can't sleep.  And you can't do much to help except give emotional support.

My mind kept returning to the UI.  Could we ship with it like that?  No.  No way.  It was a true must fix.  Around eight am, Jason returned.  He looked fresh compared to the rest of us and he was bursting with energy.  "I've got it!  I know how to fix it!"

He raced to his PC, still on from the night before, and started hammering away on the keyboard.  A few of hours later, he booted up the game and triumphantly showed me how he could change the settings on each screen, and then navigate back and forth without losing any information.  The game remembered what you wanted.  I wanted to give him a giant hug. Instead I asked, "How'd you do it?"

He shrugged a little sheepishly.  "Originally I thought I would have to deal with each button, checkbox, and selector individually.  That would take forever.  But then I realized I could write the screen object to the storage between screen loads.   Basically save the whole screen like it was one thing, which... technically it is.  It slows down our loading screens, but not enough to be noticeable."  The save made the transitions 0.1 seconds longer.

People literally started to cheer, if not from genuine happiness then from the relief that a major stumbling block to shipping had been hurdled.  

We did ship the game on time.  Splashdown went on to earn a MetaCritic score of 84 - not bad for an independent developer.  And it sold over a million copies. Even now I believe if Jason had not fixed the user interface we would not have sold a even a thousand copies.

Looking back, I'm reminded of something a Disney Executive once told me.  "We have to focus on quality.  While quality does not guarantee success, if you ship crap, your customers may never forgive you."  At the end of the day, making video games is about one thing, and one thing only. Putting fun in a box.  No matter how stressful it was, having that clarity gave me the courage to make the right call.  We could not ship the game with a frustrating user experience.  It was not fun. It did not belong in the box.

But I also realized, that in that moment, rather than focus on being right, I focused on asking for help.  I believed in Jason, so I asked him to try.  Sometimes our best is all we can do.  And when we do our best, it is possible to live with the rest, what ever that is.  To me, this is the essence of vulnerability, and in taking the kinds of risks that let you make great games.
