# Nemli



[Nemli](/npc/201357) is a level 46 Dwarf Rogue that spawns in [Plane of Justice](/zone/201).








## Dialog

if(e.language == 5 and e.other:GetLanguageSkill(5) >= 100) then


**You say:** `Hail`




e.self:Say("Hail!'  He jumps up and extends you his hand.  'Well met, Soandso!  It's been a while since I saw a friendly face, here in all this gloom, I have to tell ye.'  His feet nearly leave the floor in his excitement.  'Do ye bring word from [Nammy]?",5);


**You say:** `Nammy`




e.self:Say("Aye!'  He nods enthusiastically.  'Aye, Nammy!  Me own dear brother, so he is.  Have ye heard from him?  I've not heard from him since the [job].'",5);


**You say:** `job`




e.self:Say("What a job it was, for two enterprising young men of opportunity like ourselves.  Why, King Butcherblock's chamberlain himself brought us before him, so he did.  Dressed us all up plush-like, and told us about a wealthy elf who'd stolen something o' the King's.  He wanted us to find it... what a lark!  Well, who's we to refuse the kind of [offer] he made, eh?",5);


**You say:** `offer`




e.self:Say("Aye!  He said that this elf had been stealing from the King for a long time, Brell only knows how he managed it.  He said that we could take whatever we wanted from the elf's mansion as payment, but that the book that he was all riled up about... the [book] he wanted back safe and sound in the palace, so he did.",5);


**You say:** `book`




e.self:Say("That he didn't tell us.  I heard rumor that it was something like his family history, or his family tree, or something thereabouts.  Who cares, that's what Nammy and I said!  A job's a job, right?  So's following the directions, we snuck out to this mansion.   All alone it was, standing there in the forest.  Being good at our craft, the locks didn't prove any obstacle, and we were in!'  He shudders.  'Then the lights came on.  We'd been [caught].'",5);


**You say:** `caught`




e.self:Say("Aye, like rats in a trap, so's to speak.'  He thumps his thigh with his fist. 'They seemed to be expecting us, like.  The weirdest thing of all, was that nothing in the house looked elvish at all.  All of it good, honest dwarven stuff.  All dressed up rich and gaudy, a Stout I'd never seen walking in Kaladim told us that he was the mansion's owner.  What a lark!  I'm not sure what's going on, to tell ye truth, but it sounds as if we've got mixed up in the [games] of the nobles.",5);


**You say:** `games`




e.self:Say("Games they are, too.  Little folk like me have no wot of what's going on, ye know.  I don't know if the chamberlain knew who owned the house, or if we got the wrong one maybe...  we followed the directions to the letter, though.  Nammy managed to escape through a window while the guards took me into chains.  He said he'd be back and rescue me when he could!  Come on, Nammy - I need ye now!",5);


else


>*Nemli 'does not appear to understand you.'*
end
