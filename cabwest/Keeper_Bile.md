# Keeper Bile
## Dialog

**You say:** `hail`



>*Keeper Bile bows before you as a gesture of kindness and respect. 'Greetings. I am Bile, Keeper of the Apprentice Ranks. My knowledge is that of the first circle of necromancy. I was once a great necromancer, but now i have a greater calling to protect the words of Kotiz. I also Conduct many tests to ensure the spells are deciphered correctly. I am in need of an apprentice to [collect components.]*

**You say:** `collect components`



if **Faction** >= Amiable then



>*Keeper Bile takes out a tattered scroll and looks upon its words.'Hmm. Yes. I will need the following; One large scorpion pincer, one sabertooth cub canine and two brittle skulls. Bring these to me and I shall pay you and if I have an overscribed spell, I shall give you that also.*


elseif **Faction** >= Indifferent then



>**Keeper Bile says:** No Iksar resident will have anything to do with you!


else



>**Keeper Bile says:** No Iksar resident will have anything to do with you!   Away from here before you find yourself dead.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Brittle Iksar Skull](/item/12739), [Brittle Iksar Skull](/item/12739), [Large Scorpion Pincer](/item/12659), [Sabertooth Cub Canine](/item/12426)) then


>*Keeper Bile tosses the items into a nearby box and reaches into a sack at his feet. He hands you your reward. 'This spell is going to need some major testing. I can always use more of the same components.'*


* __Faction:__ [Brood of Kotiz](/faction/443) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:** eq.ChooseRandom( [Spell: Cavorting Bones](/item/15338), [Spell: Clinging Darkness](/item/15344), [Spell: Coldlight](/item/15339), [Spell: Disease Cloud](/item/15340), [Spell: Endure Cold](/item/15225), [Spell: Fear](/item/15229), [Spell: Grim Aura](/item/15346), [Spell: Leering Corpse](/item/15491), [Spell: Lifespike](/item/15502), [Spell: Lifetap](/item/15341), [Spell: Locate Corpse](/item/15342), [Spell: Numb the Dead](/item/15347), [Spell: Poison Bolt](/item/15348), [Spell: Reclaim Energy](/item/15331), [Spell: Sense the Dead](/item/15221), [Spell: Siphon Strength](/item/15343)) (+100 exp)

**This NPC *should* return incorrect items given.**
