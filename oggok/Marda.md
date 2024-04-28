# Marda
## Dialog

**You say:** `hail`



>**Marda says:** Welcome to intelligence, young Soandso! Did you think all ogres were inept? Ha!! I hope you show the glimmer. We shamans need more within our ranks. Our race needs to evolve!! So, are you one of the smart ogres or have I spoken too many syllables?

**You say:** `smart ogre`



if **Faction** >= Indifferent then




>**Marda says:** Well, I suppose your intelligence shall grow. You will have to do. I have a mission for you. First, go and speak with Grevak of the Greenblood Knights. He will have a job for you. After you have performed some manner of service and advanced at least 5 ranks, return to me and ask me about my secret mission.


else



>**Marda says:** Knights! Come at once. There is a foe of the Greenbloods to deal with.




**You say:** `syllable`



>**Marda says:** As I thought. Perhaps you would fare better speaking with the Crakneks.

**You say:** `secret mission`



if **Faction** >= Amiable then




>**Marda says:** I have heard of your advancements. You are a fine addition to Oggok. I require your skill in handling a delicate matter. I want you to run out to the Bouncer's keep near the entrance to Oggok. There, you shall find a froglok named Glib. He will pose no threat to you. He has come on business and I have promised him protection. Tell him the Greenblood shaman sent you. He shall fill you in. Go at once.



**Spawn NPC:**  [Emissary Glib](/npc/49127) at (**y:** -205.3, **x:** 383)


elseif **Faction** >= Indifferent then




>**Marda says:** There is much you must do to prove your loyalty to the cause of the Greenbloods.


else



>**Marda says:** Knights! Come at once. There is a foe of the Greenbloods to deal with.



end

## Turn-Ins





if **You turn in:** [Tattered Note](/item/18884)


>**Marda says:** I see you finally decided to return. Hmmm. What is this? Those little hoppers have done well. What!! So the troll scum have been aiding our foes, the lizards!! The lizard mystics are trained by this troll shaman called Zimbittle. Find him!! Kill him. Bring me his shaman pouch!! Now!!


* __Faction:__ [Shamen of War](/faction/394) (10)


 **You receive:** None 

elseif **You turn in:** [A Sealed Letter](/item/18886)


>**Marda says:** I see you finally decided to return. Hmmm. What is this? This troll called Zimbittle. Find her! Kill her. Bring me proof she dead!

elseif **You turn in:** [A Tattered Cloth Note](/item/18885)


>**Marda says:** What is this? More information? There seems to be a larger plan in the making. B'Dynn sounds like a Dark Elf name. I do no like the sound of this.  You must go quickly to North Ro.  Find this Dark Elf.  Find out what he knows.  any way you can.


* __Faction:__ [Shamen of War](/faction/394) (20)


 **You receive:** None 

elseif **You turn in:** [Zimbittles Pouch](/item/17929)


>**Marda says:** Ahhh!! Good work. You are a bright one. Now let us see if you can master this spell. Learn it well and may it bring you much glory.


* __Faction:__ [Shamen of War](/faction/394) (25)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
