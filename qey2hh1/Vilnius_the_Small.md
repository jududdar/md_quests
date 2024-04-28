# Vilnius the Small


## Dialog

**You say:** `hail`



>**Vilnius the Small says:** Soandso, just because I am short don't mean I can't bounce your " .. e.other:Race() .. " rump all over these hills. Now, do you have something for me, or are you just in search of a rump bouncing?

**You say:** `rump`



>**Vilnius the Small says:** My pleasure to oblige you then. Shall I start on the left side or the right side?


**Vilnius the Small attacks you.**

**You say:** `stanos`



>**Vilnius the Small says:** If you need to ask that question, you do not need to know the answer. At least not from me.

**You say:** `who.* you`



>**Vilnius the Small says:** Vilnius, as I have told you. And yes, I am not as large as most of my kin. But that is a blessing, because my brain is bigger than that of an $race. <grin> I am a Facilitator. I.. facilitate.. jobs. You want something somebody else has, I can arrange for you to have it.. even if that something is their life. That is why I am here now, waiting on something to turn up in my hands before I pass it on to my client. Though I am a bit tired of waiting. My hired help seem to be delayed.

**You say:** `malka`



>**Vilnius the Small says:** Malka Rale works for me from time to time. One of the best thieves I have ever met, and damn handy with a blade. She is long overdue to meet me here. I'm afraid she may have run into trouble in Qeynos.

**You say:** `delayed`



>**Vilnius the Small says:** Yes, delayed. She has always been prompt in the past, but she is several days overdue, and I know for a fact she completed the job. I am beginning to wonder if something happened to her. I would go check, but I run the risk of missing her if she shows up here.

**You say:** `job`



>**Vilnius the Small says:** I need a few more items for a collector. They are rare and valuable, but I will pay you well for your trouble. I need the sword owned by the king of the Frogloks, the sword my distant cousin Karg is so proud of, and the matched set of Painbringer and Fleshripper, held by the kobolds. Return those to me quickly, and we will take it from there, eh?

**You say:** `help`



>**Vilnius the Small says:** Oh, really?  So you are willing to wade into Qeynos to track Malka down, or to find out what happened to her?  Willing to take up the job if she failed?  Willing to risk the wrath of the entire Circle of Unseen Hands?  Wonderful, I do so appreciate enthusiasm!  Send Malka back to me, or deliver the pouch she was hired to steal, either one.  If that works out, maybe we can do more business, I am always looking for new people to help me... Facilitate.
end

## Turn-Ins



local text = "looks at you impatiently, expecting more.";


if **You turn in:** [Stanos' Pouch](/item/28014)


>**Vilnius the Small says:** Ah, very nice. Very nice indeed. Good work, and I hope Malka is able to make it out, good help is hard to find. But in the meantime, I am without an acquisition expert. Do you want the job?


 **You receive:** 0 (+1500 exp)

elseif **You turn in:** [Fleshripper](/item/5411), [Painbringer](/item/5410), [A Mithril Two-Handed Sword](/item/5401), [A Gigantic Zweihander](/item/5308)


>**Vilnius the Small says:** Very good, though how you managed to lug around all these oversized blades amazes me. I feel we can do business now, and Malka still has not shown up. Take this dagger. I had an old client who didn't, um.. pay.. so this was extracted from him. Right after it was inserted in him. For your next job, I need a collection of robes. The Robe of the Ishva, some Shining Metallic robes, an Oracle robe, and a Robe of the Kedge. I am not even sure where all these come from, but they are on my list here, and Rokyl is one of my best clients, so I figure that is your job.


 **You receive:**  [Jagged Diamond Dagger](/item/7506) (+3000 exp)

elseif **You turn in:** [Robe of the Ishva](/item/1357), [Robe of the Kedge](/item/1253), [Robe of the Oracle](/item/1354), [Shining Metallic Robes](/item/1360)


>**Vilnius the Small says:** You do good work, " .. e.other:Race() .. ". Here is another trinket for your trouble, you should be able to make use of it. Malka still hasn't made it back yet, and I have one more order to fill, if you're willing. This one should be easy. My sword collector has decided he wants rapiers now, of all things. He has asked for an Eyerazzia, a Martune Rapier, a Burning Rapier, and a well balanced rapier.


 **You receive:**  [Cazic Quill](/item/7505) (+3000 exp)

elseif **You turn in:** [Burning Rapier](/item/7041), [Martune Rapier](/item/7509), [Eyerazzia](/item/7508), [Well-Balanced Rapier](/item/7020)


>**Vilnius the Small says:** You never cease to amaze me! I never thought you " .. e.other:Race() .. " types could be so good at this sort of work. I have been stuck here and haven't any more trinkets to give you, but perhaps you could take this pouch to its new owner, since I do not have the time to deliver it myself. He will pay you in full, and you can just keep what he gives you, how does that sound? The owner is a man named Stanos Herkanor, and he or his friend Anson are supposed to meet me in Highpass this evening. Do not waste too much time getting there, he is a secretive man, and I can not guarantee he will be around long. Good luck, and maybe we will meet again. It is always a pleasure working with another professional such as yourself!


 **You receive:**  [Stanos' Pouch](/item/28014) (+3000 exp)

**This NPC *should* return incorrect items given.**

