# Arbogast
## Dialog

miller = eq.get_entity_list():GetMobByNpcTypeID( [\#Miller](/npc/160376));



**You say:** `hail`



>**Arbogast says:** Hello there weary adventurer. do you come seeking the truth?

**You say:** `truth`



>**Arbogast says:** The truth is a precarious thing, twisted and torn by those that would deceive for their own nefarious purposes.  That is why there are people like me to guide the ignorant masses that know no better than to believe that which they are told.


if(miller.valid) then



miller:Say("Yeah, you tell 'em Arbogast!  I bet this one doesn't even know what's going on right under his nose in this here city.  Like for example, you probably don't even know the truth about about his importantness Phenic Dionicas do you?");


**You say:** `phenic`



>**Arbogast says:** He that battles what he truly is only truly battles himself.  Phenic Dionicas for years has made quite a show of his war on the Vampyres of Tenebrous.  This misdirection of truth serves only to keep people from discovering that he himself is a foul demon of the night.  Miller and I, for our singular vision of that which is true, are not well liked in this city and so cannot obtain proof for your disbelieving eyes.

**You say:** `proof`



>**Arbogast says:** You wish to see the truth for yourself?  That is good, you will be taking your first step down a winding road to the only fulfillment this existence has to offer: enlightenment.  Take this flask of water, I have blessed it such that it will singe the skin of the unholy.  Go to Phenic Dionicas and give it to him, then you will see... you will see.


if(miller.valid) then



miller:Say("Yeah, splash it right in his unliving face!");



**You receive:**  [Arbogasts Holy Water](/item/29899)

**You say:** `tsaph`



>**Arbogast says:** When you fake your death to discredit another you only discredit yourself when another sees your death was faked.  Yes, you heard me correctly, Tsaph Katta lives on here in this city, can you guess who it is he pretends to be?


if(miller.valid) then



miller:Say("Ooh! I know, I know!  Nathyn Illuminious!!!");



>**Arbogast says:** Yes, yes, I know you know... very good Miller



miller:Emote("beams a smile your way.");


**You say:** `exist`



>**Arbogast says:** You are beginning to see the truest truths as the only true truths now, are you not? That large blue orb that hangs in the Luclin sky from time to time is nothing more than an overgrown comet. What appear to be land masses and other geological features are in actuality powerful illusions cast upon the comet by Tsaph Katta himself so that panic does not spread amongst the ignorant masses. I am not one to spread conjecture, but it is possible that Katta's astronomers have discovered that the comet is hurtling slowly toward Luclin and will destroy all life on the planet, so you can see why he would want to keep the truth about the [Exodus] from his journal.

**You say:** `exodus`



>**Arbogast says:** The Exodus is the single biggest lie propagated onto the people of Katta Castellum in the known history of the intelligent races. Hogwash I tell you.


if(miller.valid) then



miller:Say("A bloody, boldfaced lie!");



>**Arbogast says:** A story told to children. Tsaph Katta wove together a tale of Seru trying to kill him on the fantasy world of 'Norrath' and how the entire combine fled here to escape from him... a wheel of lies, do you see how they interconnect? Why, I'll bet that even in Shadowhaven, the very site of this alleged 'Exodus' and home to one of the grandest libraries you will ever see, not a single shred of reliable evidence regarding such an event could be found. HA! You bring me a book on this 'Exodus' and Miller here will eat his hat! Especially if the book is wrapped in that gold paper I gave you...

end

## Turn-Ins



miller = eq.get_entity_list():GetMobByNpcTypeID( [\#Miller](/npc/160376));



if **You turn in:** [Phenics Water](/item/29898)


>**Arbogast says:** He simply gave this to you?  Cunning indeed for him to cover his weakness so thoroughly- he must have powerful protective enchantments in place, no doubt put in place by his good friend and associate, Tsaph Katta!


* __Faction:__ [The Truth](/faction/1577) (10)


 **You receive:**  [Silver Wrapping Paper](/item/17516) (+100000 exp)

elseif **You turn in:** [A Silver Wrapped Book](/item/29692)


>**Arbogast says:** Ahh, you have retrieved the memoirs, let me see.' Arbogast opens the book and starts flipping through pages, 'Yes here, you... no, wait it must be back... hrmmm, maybe he... but it must... Well, that was pretty clever of old Tsaph Katta, removing any record of who he truly is- probably did it to cover up the fact that Norrath does not really exist.


* __Faction:__ [The Truth](/faction/1577) (10)


 **You receive:**  [Gold Wrapping Paper](/item/17517) (+100000 exp)

elseif **You turn in:** [A Gold Wrapped Book](/item/29694)


>**Arbogast says:** Ahhh, excellent... I am glad to see your interest piqued. It is the truth that will liberate the masses when the masses fail to liberate the truth. To continue to divine and demystify the truth from the mistruth, I employ a powerful component known to the Akheva as 'Akuel xi ans Vius' which translated means 'Thing that tells Truth.


* __Faction:__ [The Truth](/faction/1577) (10)


 **You receive:**  [Black Wrapping Paper](/item/17518) (+100000 exp)


if(**spawned NPC:**  [Yavik Teralin](/npc/160226)) then



eq.get_entity_list():GetMobByNpcTypeID( [Yavik Teralin](/npc/160226)):Say("It translates to 'Gift of the Dark' you fool!");



>**Arbogast says:** Oh, the foolish and naive, they are the salt of the land... anyhow, bring me two of these wrapped in the black paper you have and I shall reward you, my new ally of truth, with a cherished robe that was given us by Seru himself. Isn't that right Miller? Miller...


elseif **You turn in:** [A Black Wrapped Item](/item/29695)


>**Arbogast says:** Oh, would you look at that?


* __Faction:__ [The Truth](/faction/1577) (10)


 **You receive:** 0 (+100000 exp)


if(miller.valid) then



miller:Emote("looks a bit distressed and says to Arbogast, 'You said he would die getting these and we could keep...' Arbogast silences Miller with a kick under the table and smiles broadly at you, 'Well done and my very sincere thanks to you. The cloak is in the bank, Miller and I each hold a piece of it. We will go get it for you now.' Miller and Arbogast lean in close to each other and discuss this in whispers for a moment before getting up and heading out, Miller looking most dejected.")



miller:CastToNPC():DoAnim(27);



>**Arbogast says:** Right then, let's get going Miller.



miller:CastToNPC():AssignWaypoints(24);



eq.start(23);

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 9) then


if(miller.valid) then



miller:Emote("and Arbogast do their business with the bank, Miller retrieving a heavy brown cloak and Arbogast a beautiful golden clasp. They look up at each other, unable to bear the thought of actually parting with their treasures when Arbogast says, 'You know what? I think we'll keep them. Thanks for your help, don't be a stranger. Come now Miller, let's not be a bother.' With that, they both tear off out the door");



miller:Say("Wait for me!");



eq.spawn2(160111,26,0,miller:CastToNPC():GetX(),miller:CastToNPC():GetY(),miller:CastToNPC():GetZ(),miller:CastToNPC():GetHeading());



**Despawn NPC:**  [\#Miller](/npc/160376)



**Spawn NPC:**  [\#Arbogast](/npc/160004) at this location.


**Arbogast despawns.**
end
