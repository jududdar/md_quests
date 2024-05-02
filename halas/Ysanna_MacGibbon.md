# Ysanna MacGibbon


## Signals

if(e.signal == 1) then


>**Ysanna MacGibbon says:** The mammoth calf hides are used to shield our beasts of burden from the icy wind. You are probably now asking what shields us Northmen from that same icy wind eh? Well, along with many other furs and leathers, we have come to find that [gnoll fur] of all things is a good insulator against the cold. Look at their tiny bodies and it's obvious their fur does something good.
end

## Dialog

**You say:** `gnoll fur`



>**Ysanna MacGibbon says:** You should not be asking where or what a gnoll is, but asking how I make use of that patch fur I find on their corpse. It is quite simple, take four pieces of gnoll fur and sew them together. Take the result and sew four of them together. And again with that product. In theyou will have a bundle of tailored gnoll fur. You can either return it to me or keep it for yourself.

**You say:** `dark assassin`



if **Faction** >= Indifferent then



>**Ysanna MacGibbon says:** That poor lad! I saw him in the tundra being chased by that big bear of Tundra Jack. I never liked that bear of his since the day he ate my poor dog Thunderpaw. Anyways i say Iceberg chasing the assassin and grabbed my trusty ahlspiess and threw it, aiming right for his big head. Can you believe I missed?? I hit his side instead. Iceberg ripped my ahlspiess out and ripped it into pieces and then went whining of to Tundra Jack. Serves that bear right! He ate my dog!


else



**Ysanna MacGibbon says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `ahlspiess`



if **Faction** >= Indifferent then




>**Ysanna MacGibbon says:** Ahhhh my beloved shrieking ahlspiess, it was nice i was able to help a fellow assassin out but i really do miss it. The dark assassin gave me a sketch of paper he said was very valueable but it still pains me to be without my favourite throwing weapon. If you go get me another I would gladly part with this sketch.


else



**Ysanna MacGibbon says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_842.png" alt="" /> <a
                                href="/item/1330" data-url="1330" class="tooltip-link link">Patched Gnoll Fur Bundle</a>) then



>**Ysanna MacGibbon says:** You have done well. Here is a small reward for your effort.





Your faction standing with [Rogues of the White Rose](/faction/305) got better (<span class='text-success'>+5</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_801.png" alt="" /> <a
                                href="/item/1349" data-url="1349" class="tooltip-link link">Fang of the Wolf</a> (+6000 exp)

**You receive coin:** 0-1 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 


elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/7507" data-url="7507" class="tooltip-link link">Shrieking Ahlspiess</a>) then



>**Ysanna MacGibbon says:** Yay! You got another one for me! I'm so happy! Here as I promised is the sketch.


Your faction standing with [Rogues of the White Rose](/faction/305) got better (<span class='text-success'>+5</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1004.png" alt="" /> <a
                                href="/item/24097" data-url="24097" class="tooltip-link link">Sluggish Sketch</a> 

 







**This NPC *should* return incorrect items given.**
