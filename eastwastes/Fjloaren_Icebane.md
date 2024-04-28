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





if **Faction** >= Apprehensive and  **You turn in:** [Giant Sack of Supplies](/item/25266)


>**Fjloaren Icebane says:** Thank you for bringing the supplies, Soandso. This season has not treated my clan well.  The winds have grown colder and the Coldain are now brazen enough to hunt the same animals we do.  Take this torque back to Svekk and he will repay you for the supplies.


* __Faction:__ [Kromrif](/faction/419) (5)


* __Faction:__ [Kromzek](/faction/448) (1)


* __Faction:__ [Coldain](/faction/406) (-2)


* __Faction:__ [Claws of Veeshan](/faction/430) (-1)


 **You receive:**  [Velium Torque](/item/25278) (+500 exp)

**This NPC *should* return incorrect items given.**
