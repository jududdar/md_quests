# Gans Paust
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>*Gans Paust glances at you and hurriedly makes a gesture of religious meaning before you and says, 'Yes, yes, I hereby bless you in the name of Prexus. May your catch be plentiful and your nets never snag. Are there any other fishermen seeking a blessing? I'm very busy.'*


else



**Gans Paust says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `your brother`



if **Faction** >= Indifferent then



>**Gans Paust says:** What? How do you know fo my brother? Ahh I assume Breya told you. He's been gone for quite some time with no word sent on his progress or his wellbeing. I need to find someone to [check on him].


else



**Gans Paust says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `check on him`



if **Faction** >= Amiable then



>**Gans Paust says:** Thank you, Soandso. He's one of our people's most knowledgeable geologists and has left to survey an island out in Erud's Crossing. He was sending monthly reports until two weeks ago when his report never showed up. I'm worried something may have happened to him. Take this note to Yelesom and bring back something to assure me of his safety. A reward fitting a Deepwater Knight shall be yours upon your success.



**You receive:**  [Ganss note to Yelesom](/item/18173)


elseif **Faction** >= Indifferent then



>**Gans Paust says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Gans Paust says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


## Turn-Ins




if **You turn in:** [A tattered note](/item/18724)


>**Gans Paust says:** Yes. welcome friend! Here is your guild tunic. You'll make a fine addition to the Deepwater Knights. Go see Dleria, she will get you started in your studies.


* __Faction:__ [Deepwater Knights](/faction/242) (100)


* __Faction:__ [High Council of Erudin](/faction/266) (15)


* __Faction:__ [Heretics](/faction/265) (-15)


 **You receive:**  [Old Blue Tunic*](/item/13544) (+20 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Yelesom's Reports](/item/1771)


>**Gans Paust says:** Ahhh, thank you for your effort, Soandso. I'm glad he's doing ok despite the theft. I now award you the Sleeves of Midnight Sea. May they protect you until the time of our glorious redemption.





* __Faction:__ [Deepwater Knights](/faction/242) (25)


* __Faction:__ [High Council of Erudin](/faction/266) (3)


* __Faction:__ [Heretics](/faction/265) (-3)


 **You receive:**  [Midnight Sea Mail Sleeves](/item/1763) (+2500 exp)

**This NPC *should* return incorrect items given.**
;

