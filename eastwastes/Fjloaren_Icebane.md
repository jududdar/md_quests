# Fjloaren Icebane






## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Fjloaren Icebane says:** What is it you want, " .. e.other:Race() .. "?  I have no time to speak with your kind.


else



**Fjloaren Icebane says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `supplies`



if **Faction** >= Apprehensive then



>**Fjloaren Icebane says:** If you have supplies give them to me fool.  Do not keep me waiting!


else



**Fjloaren Icebane says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `coldain`



if **Faction** >= Apprehensive then



>**Fjloaren Icebane says:** The Coldain have created several small outposts within  these wastes.  They hunt the same beasts we do for food and have made this season unbearable.  Our war bands will crush them yet though!


else



**Fjloaren Icebane says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins





if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/25266" data-url="25266" class="tooltip-link link">Giant Sack of Supplies</a>) then 


>**Fjloaren Icebane says:** Thank you for bringing the supplies, Soandso. This season has not treated my clan well.  The winds have grown colder and the Coldain are now brazen enough to hunt the same animals we do.  Take this torque back to Svekk and he will repay you for the supplies.


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+5</span>)


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+1</span>)


Your faction standing with [Coldain](/faction/406) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_535.png" alt="" /> <a
                                href="/item/25278" data-url="25278" class="tooltip-link link">Velium Torque</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**
