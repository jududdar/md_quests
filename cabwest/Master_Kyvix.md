# Master Kyvix
## Dialog

**You say:** `hail`



>**Master Kyvix says:** Quite busy!! Quite busy!! Things must be done. [New components] to be collected!!

**You say:** `New components`



>**Master Kyvix says:** Yes, yes!! I will need components from beyond the gates. I must find an [apprentice of the third rank].

**You say:** `apprentice of the third rank`



if **Faction** >= Amiable then



>**Master Kyvix says:** If you truly be an apprentice of the third circle, then there is a Dark Binder skullcap to be earned. Take this sack and fill it with a creeper cabbage, a heartsting telson with venom, brutling choppers and a scalebone femur. When they are combined within the sack, you may return it to me with your third rank skullcap and and we shall bid farewell to the title, apprentice.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17024" data-url="17024" class="tooltip-link link">Brood Sack</a>


elseif **Faction** >= Indifferent then



>**Master Kyvix says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Kyvix says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `true mission`



if **Faction** >= Amiable then



>**Master Kyvix says:** I have been waiting for a Nihilist to return. His name was Ryx and I fear his love of ale and the high seas has kept him from his mission. All I want you to do is find him. He should be disguised as a worker and he will give you a tome to bring to me. Return it with your Dark Binder Cap. I am sure that is simple enough for one as simple as you. Be sure to give him this.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/12848" data-url="12848" class="tooltip-link link">A Spectacle</a>


elseif **Faction** >= Indifferent then



>**Master Kyvix says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Kyvix says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `Kor Sha Candlestick`



>**Master Kyvix says:** I need the foot and stem of my candlestick. The Stem comes from Sarnaks. The foot has been stolen by Grype, in East Cabilis.
end

## Turn-Ins



local text1 = "I demand a full fish sack and your third circle apprentice skullcap.";

local text2 = "So you are expecting to earn your way to rank of revenant, eh? You shall when I have the base and stem of the candle and your occultist skullcap.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/12420" data-url="12420" class="tooltip-link link">Full Component Sack</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18065" data-url="18065" class="tooltip-link link">A Journal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4263" data-url="4263" class="tooltip-link link">Dark Binder Skullcap</a>) then 






>**Master Kyvix says:** I did not expect you to return. You made me lose a bet with one of the other scholars. Seeing as you have delivered the tome, I shall not harm you, but rather welcome you into the rank of the dark circles. Listen well to the scholars within this tower and seek the [Keepers Grotto] for knowledge of our spells. This drape shall be the sign to all iksar that you walk with the Brood. Now go speak with Xydoz.


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4264" data-url="4264" class="tooltip-link link">Occultist Skullcap</a> (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_732.png" alt="" /> <a
                                href="/item/12853" data-url="12853" class="tooltip-link link">Stem of Candlestick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1013.png" alt="" /> <a
                                href="/item/12852" data-url="12852" class="tooltip-link link">Foot of Candlestick</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4264" data-url="4264" class="tooltip-link link">Occultist Skullcap</a>) then



>*Master Kyvix grabs the candle parts and puts them in an odd pouch, then takes your cap which disintegrates in his palm. He hands you another cap. 'Welcome, Revenant Soandso. You have done well. The Harbinger awaits you. He seeks a [new revenant].'*


Your faction standing with [Brood of Kotiz](/faction/443) got better (<span class='text-success'>+10</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1070.png" alt="" /> <a
                                href="/item/4265" data-url="4265" class="tooltip-link link">Revenant Skullcap</a> (+200 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
