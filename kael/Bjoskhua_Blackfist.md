# Bjoskhua Blackfist
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>*Bjoskhua Blackfist 's lips do not move, though your mind is filled with a voice.  'What is it you want, mortal?  I have little patience for those who do not come here to study.'*


else



**Bjoskhua Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `study`



if **Faction** >= Amiable then



>*Bjoskhua Blackfist looks you over and his voice invades your mind again.  'What is it you wish to study?'*


elseif **Faction** >= Indifferent then



>**Bjoskhua Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Bjoskhua Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `combat`



if **Faction** >= Amiable then



>**Bjoskhua Blackfist says:** Those who walk the path of the fist are fierce indeed.  Stories in my books tell of great contests once held.  Contests of skill without weapons.  Only the body and the warriors' training would keep them alive.  The last warriors to survive would be given a set of magical chest straps as a status symbol.


elseif **Faction** >= Indifferent then



>**Bjoskhua Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Bjoskhua Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `clrakk`



if **Faction** >= Amiable then



>**Bjoskhua Blackfist says:** Clrakk is my youngest brother. He walks a path of shadows and deceit. If he were to battle, it would not be one without weapons or armor. I may use these as a bargaining chip some day. I do not think my family has any more need of these old chest straps.


elseif **Faction** >= Indifferent then



>**Bjoskhua Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Bjoskhua Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `chest strap`



if **Faction** >= Amiable then



>**Bjoskhua Blackfist says:** The chest straps are simply a status symbol to some gladiators and warriors. They are passed down from generation to generation. When a warrior enters one of these contests of the fist, they wear the chest straps of their family. My family was awarded a set of the enchanted chest straps ages ago. None of my brothers save Clrakk would even consider entering the contest.


elseif **Faction** >= Indifferent then



>**Bjoskhua Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Bjoskhua Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `contest`



if **Faction** >= Amiable then



>**Bjoskhua Blackfist says:** Ages ago there was a race of fish men named the Kedge.  Prexus spread them throughout the waters of the world and they were prosperous.  Rumors abound that even near the waters of Velious they had great cities.  All at once they seemed to be wiped from the face of Norrath.  One of the travelers I recently spoke to informed me that a single Kedge may still live in the lands of Faydwer.  As grotesque as it sounds, the backbone of a Kedge may be used to create indestructible scroll cases.  Bring me the backbone of this fishman, if he exists, and you will find yourself a richer person.


elseif **Faction** >= Indifferent then



>**Bjoskhua Blackfist says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Bjoskhua Blackfist says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [Kedge Backbone](/item/20524)) then


>**Bjoskhua Blackfist says:** Excellent, I guess his entire race is now wiped from Norrath. This will indeed make a wonderful scroll case. I am a giant of my word. Take your prized item and be gone, you greedy little beast!


* __Faction:__ [Kromrif](/faction/419) (10)


* __Faction:__ [Kromzek](/faction/448) (2)


* __Faction:__ [Coldain](/faction/406) (-5)


* __Faction:__ [Claws of Veeshan](/faction/430) (-1)


 **You receive:**  [Flayed Coldain-Skin Leggings](/item/25053) (+500 exp)

**This NPC *should* return incorrect items given.**
