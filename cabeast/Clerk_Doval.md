# Clerk Doval
## Dialog

**You say:** `hail`



>*Clerk Doval takes a sip of lager and looks up at you. 'Ahh! An adventurer of sorts? Looking for work, are we? If you have the time, I might have a bit of a [proposition] for you.'*

**You say:** `proposition`



>**Clerk Doval says:** I was sent by the Legion to deliver a restraining order to a few of the troopers. They have been ordered to stay away from the tavern. They have spent too much time drinking and not enough training. I am to have them initial the restraint order list, but my feet are killing me. Perhaps you could [deliver the restraining order]?

**You say:** `deliver the restraining order`



>**Clerk Doval says:** Here is the restraint order. Go to the troopers and ask them to [sign the restraining order]. Also, make sure to have them sign it in alphabetical order. I am a very big stickler about this. The troopers' names are as follows; Ozlot, Ogmire, Nish Nish, Frogzin, Gummin, Inkin, Roklon, Taer, Fryp and Selbat. When all is done, I shall pay you.


**You receive:**  [Legion Order](/item/18240)









**You say:** `sisters of scale`



>**Clerk Doval says:** I have heard some babble of that.  I know all [about the skulls] of those ancients.


e.self:DoAnim(49);

**You say:** `about the skulls`



>**Clerk Doval says:** I heard the dragon called Trakanon swallowed them up and their skulls now lie within the belly of that vile beast.  Of course, that could be just babble.  One hundred gold coins may give you the tink.


e.self:DoAnim(48);
end

## Turn-Ins



if **You turn in:** [Legion Order](/item/18250)



>**Clerk Doval says:** Thank you so much. I am so glad I did not have to deal with such a rowdy band of troopers as these. Please take some coin and perhaps a book from my personal library.


* __Faction:__ [Cabilis Residents](/faction/440) (3)










* __Faction:__ [Legion of Cabilis](/faction/441) (1)










 **You receive:** eq.ChooseRandom( [The Book of Knowledge](/item/12460), [The Code of Combat](/item/12461)) (+1200 exp)



**This NPC *should* return incorrect items given.**