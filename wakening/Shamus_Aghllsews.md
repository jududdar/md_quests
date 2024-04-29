# Shamus Aghllsews
## Dialog

**You say:** `hail`



>**Shamus Aghllsews says:** Welcome to my fiefdom, wayward " .. e.other:Race() .. ". I am Duke Shamus Aghllsews of the Tunarean Court. Only those who pledge friendship or membership to the Court are allowed sanctuary in the Wakening Lands.

**You say:** `pledge friendship`



>**Shamus Aghllsews says:** You must first prove your intentions to the Tunarean Court. I will permit you to participate in an oath of friendship only after you bring me four picks used by the Kromrif Laborers that are attempting to build into our lands.

**You say:** `court`



>**Shamus Aghllsews says:** The Tunarean Court is the name of the hierarchy of Tunares children that inhabit this region of Norrath. We adhere to the old ways of governing our peoples. The Koada'Dal and Feir'Dal have strayed from the old ways since the fall of Takish Hiz and the burning of their once great forest kingdom that has since become the deserts of Ro. As Duke of this court I am the highest ranking Tunarean outside the Plane of Growth.
end



## Turn-Ins





if( **You turn in:** [Kromrif Laborer Pick](/item/30220), [Kromrif Laborer Pick](/item/30220), [Kromrif Laborer Pick](/item/30220), [Kromrif Laborer Pick](/item/30220)) then


>*Shamus Aghllsews grips your hand in his own and recites an oath in an ancient tongue. 'Should you ever seek membership in this court you are required to receive the support of its counts, countesses, barons, and baronesses. Should they deem you worthy you may present their crests to me and with my approval become a citizen of our kingdom. The Kromrif and Kromzek are persistent in their efforts to expand Kael into the forest of Tunare, they are a threat to all houses of the Tunarean Court. A Kromzek architect occasionally visits the building sites. I desire to acquire his blueprints for the expansion of Kael.'*


* __Faction:__ [Tunarean Court](/faction/449) (20)


if(**You possess item:**  [Empty Crest Case](/item/17865) x 1



 **You receive:** 0 (+3500 exp)


else



 **You receive:**  [Empty Crest Case](/item/17865) (+3500 exp)


elseif( **You turn in:** [Kromzek Architect Blueprints](/item/30222)) then


>**Shamus Aghllsews says:** You have my gratitude, Soandso. With these blueprints we can better prepare the forests defenses against the giant invaders. I have yet another favor to ask of you as well. Fill this empty bag with crystallized sulfur. When mixed with the crushed herbs in the other bag it will create an explosion strong enough to destroy stone. Take the two full bags into Kael Drakkel and plant it into a crate of the kromzeks building supplies.


* __Faction:__ [Tunarean Court](/faction/449) (30)


 **You receive:** GiveAll( [Empty Sulfur Collection Bag](/item/17862), [Bag of Crushed Herbs](/item/24860)) (+3500 exp)

elseif( **You turn in:** [Pile of Rubble](/item/22855)) then


>**Shamus Aghllsews says:** You have proven yourself to the Fauns of the Tunarean Court. The destruction of the Kromzeks building supplies will slow their progress for some time.


* __Faction:__ [Tunarean Court](/faction/449) (20)


 **You receive:**  [Crest of the Fauns](/item/24865) (+3500 exp)

elseif( **You turn in:** [Case of Tunarean Crests](/item/1095)) then


>**Shamus Aghllsews says:** Welcome to the Tunarean Court, Thane Soandso! Here is a signet ring to wear in honor of your status among the Tunareans.


* __Faction:__ [Tunarean Court](/faction/449) (50)


 **You receive:**  [Tunarean Signet Ring](/item/8950) (+5000 exp)

**This NPC *should* return incorrect items given.**
