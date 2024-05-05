# Gans Paust



[Gans Paust](/npc/24063) is a level 61 Erudite GM Cleric that spawns in [Erudin](/zone/24).



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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18173" data-url="18173" class="tooltip-link link">Ganss note to Yelesom</a>


elseif **Faction** >= Indifferent then



>**Gans Paust says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Gans Paust says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!




## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18724" data-url="18724" class="tooltip-link link">A tattered note</a>) then 


>**Gans Paust says:** Yes. welcome friend! Here is your guild tunic. You'll make a fine addition to the Deepwater Knights. Go see Dleria, she will get you started in your studies.


Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+100</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+15</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13544" data-url="13544" class="tooltip-link link">Old Blue Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/1771" data-url="1771" class="tooltip-link link">Yelesom's Reports</a>) then


>**Gans Paust says:** Ahhh, thank you for your effort, Soandso. I'm glad he's doing ok despite the theft. I now award you the Sleeves of Midnight Sea. May they protect you until the time of our glorious redemption.





Your faction standing with [Deepwater Knights](/faction/242) got better (<span class='text-success'>+25</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+3</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_543.png" alt="" /> <a
                                href="/item/1763" data-url="1763" class="tooltip-link link">Midnight Sea Mail Sleeves</a> (+2500 exp)

 

**This NPC *should* return incorrect items given.**
;

