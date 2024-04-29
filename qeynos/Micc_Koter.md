# Micc Koter
## Dialog

**You say:** `hail`



>**Micc Koter says:** Oh, hello, Soandso.  Don't mind my associate Klieb over there.  He gets quite grumpy when he drinks.  We are relatively new here ourselves but have made some fast friends in Qeynos.  This is a city of opportunity.

**You say:** `paw of opolla`



>**Micc Koter says:** Some guy, don't know who he was, was in here claiming he had a lead where to find some information on the Paw of Opolla. I don't know anything about it except it is supposed to be the paw of some old gnoll bitch and have some magic powers. Buy me a Brandy and I might tell you where he was going.

**You say:** `ranger`



>**Micc Koter says:** Beats me. Try going to the north near Surefall Glade. That is where those goodie goodies tend to hang out.

**You say:** `gnoll`



>**Micc Koter says:** A gnoll is a stupid dog that walks upright. They are dirty and stinky and hate humans. Just like my pal Klieb here. Heh!


**Signaled to:**  [Klieb Torne](/npc/1071)
end

## Turn-Ins



local text = "Hey...  Better get me another one... I can't quite remember...  Heh heh...";




if( **You turn in:** [Brandy](/item/13034), [Brandy](/item/13034)) then


>**Micc Koter says:** Oh yes. Now I remember.. Ha ha.. He said he was going into the Plains of Karana to look for some gnoll lover by the name of Caninel. He said Caninel knew something about the location of the Paw of Opolla. It sounds like a bunch of rat crap to me , I never heard of no one named Caninel. But off he went.. Heck , finding one person in the Plains of Karana without a [ ranger ] to guide you is like looking for a clean spot on ol'Klieb here. Ha ha!!

**This NPC *should* return incorrect items given.**



## Signals

if(e.signal == 1) then


>**Micc Koter says:** Ha ha ha ha!

elseif(e.signal == 2) then


>**Micc Koter says:** Lighten up, will ya, Klieb? You act like a dang [gnoll] sometimes..
end
