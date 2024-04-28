# Davorre Bloodthorn



## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Davorre Bloodthorn says:** Greetings. Perhaps within that husk you call a body there is some worth? Are you [experienced] in your craft, young one, or are you a [neonate]?


elseif **Faction** >= Indifferent then



>**Davorre Bloodthorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Davorre Bloodthorn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `neonate`



if **Faction** >= Amiable then



>**Davorre Bloodthorn says:** Well then, child, I may still have a task for you. Will you [make use of your pathetic cowardice], then, eh?


elseif **Faction** >= Indifferent then



>**Davorre Bloodthorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Davorre Bloodthorn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `pathetic cowardice`



if **Faction** >= Amiable then



>**Davorre Bloodthorn says:** I see. This will not be the first time for you, I am sure. Take this list to Auhrik Siet\`ka. His writing has become illegible in his old age, but he shall clarify what it is he needs you to do. Do as he says, child, and perhaps you will prove yourself a bit more worthy than the rotting flesh he will most likely have you return to him.



**You receive:**  [A Rolled Up Note](/item/14041)


elseif **Faction** >= Indifferent then



>**Davorre Bloodthorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Davorre Bloodthorn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `experienced`



if **Faction** >= Amiable then



>**Davorre Bloodthorn says:** Ahhhh, a youth doth approach me with such confidence! That is to be commended in and of itself. Ordinarily, I would turn you away without a second glance, but perhaps you can be of some use. Tell me, child, are you [willing to assist] me in a small, yet important, task?


elseif **Faction** >= Indifferent then



>**Davorre Bloodthorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Davorre Bloodthorn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `willing to assist`



if **Faction** >= Amiable then



>**Davorre Bloodthorn says:** Good, child. Deliver this note to Veisha Fathomwalker. You shall find her patrolling the outer regions of Toxxulia Forest. I trust that you will keep your eyes to yourself in this matter. Now go, and please travel within the veil of night, so you will not be seen by those whose minds are still clouded with delusions of Erudin's grandeur.



**You receive:**  [Rolled up Note](/item/12998)


elseif **Faction** >= Indifferent then



>**Davorre Bloodthorn says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Davorre Bloodthorn says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** [Veisha's Engagement Ring](/item/12997)


>**Davorre Bloodthorn says:** Only a few years have passed and her heart has already forgotten me. No doubt she has found another to warm her bed. Go, find her new lover, and bring me nothing less than his head.


* __Faction:__ [Heretics](/faction/265) (5)


* __Faction:__ [Deepwater Knights](/faction/242) (-5)


* __Faction:__ [Gate Callers](/faction/254) (-5)


* __Faction:__ [Craftkeepers](/faction/231) (-5)


* __Faction:__ [Crimson Hands](/faction/233) (-5)


 **You receive:** 0 (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Phaeril Nightshire's Head](/item/12996)


>**Davorre Bloodthorn says:** Apparently her choice in suitors has drifted to the most pathetic of wretches ever to slither Odus. You have done well, child. I ask of you one last task before my message to Veisha is complete. Here, deliver this to her with my most sincere regards.


* __Faction:__ [Heretics](/faction/265) (5)


* __Faction:__ [Deepwater Knights](/faction/242) (-5)


* __Faction:__ [Gate Callers](/faction/254) (-5)


* __Faction:__ [Craftkeepers](/faction/231) (-5)


* __Faction:__ [Crimson Hands](/faction/233) (-5)


 **You receive:**  [A Locked Chest](/item/12995) (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Veisha Fathomwalker's Head](/item/12994)


>**Davorre Bloodthorn says:** My revenge has been satisfied. Thank you, my child. You have proven yourself to be a most worthy asset to our cause. Here, I no longer have any use for this, my ties to the old life are now severed.


* __Faction:__ [Heretics](/faction/265) (20)


* __Faction:__ [Deepwater Knights](/faction/242) (-20)


* __Faction:__ [Gate Callers](/faction/254) (-20)


* __Faction:__ [Craftkeepers](/faction/231) (-20)


* __Faction:__ [Crimson Hands](/faction/233) (-20)


 **You receive:**  [Battle Worn Halberd](/item/5526) (+6000 exp)

**This NPC *should* return incorrect items given.**






