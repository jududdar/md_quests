# Priestess Tarafol


## Dialog

**You say:** `hail`



>**Priestess Tarafol says:** Oh, these poor forsaken souls. We must do whatever we can to help them. So far I've been unable to find anything that can cure their afflictions. I'm not even certain there is a cure. The least I've been able to do is ease some of their suffering.

**You say:** `cure`



if **Faction** >= Apprehensive then



>**Priestess Tarafol says:** I'm not certain what causes the disease that inflicts most of these people. I believe it's from living down in these caverns for so long. It seems most people have a natural immunity, but the few who are stricken are cursed to slowly rot to death. A most horrible and painful way to die. I wish I could do more than just ease their pain.


else



**Priestess Tarafol says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `help`



if **Faction** >= Apprehensive then



>**Priestess Tarafol says:** You would be willing to do that? That would be great! I've heard of the possible curative powers of many things here on Luclin. I've been so busy here that I haven't been able to go out and search for any of the needed compounds. If you would be so kind as to collect some things for me I would be very appreciative.


else



**Priestess Tarafol says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `collect`



if **Faction** >= Apprehensive then



>**Priestess Tarafol says:** Ok, I need you to find these things... Underbulk Bile, Razorfungus Spores and Saprophyte Spores. You should be able to be find them within the nearby cavern systems. Please return to me once you have acquired all the ingredients. Thank you very much for assisting. Good luck.


else



**Priestess Tarafol says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end

## Turn-Ins





if **Faction** >= Apprehensive and  **You turn in:** [Underbulk Bile](/item/32403), [Razor Fungus Spores](/item/32510), [Saprophyte Spores](/item/19836)


>**Priestess Tarafol says:** Thank you so much!! These will help so much in trying to find a cure for these people. Here, take this as a token of my gratitude.


 **You receive:**  [Tarafols Pendant](/item/19842) 

**This NPC *should* return incorrect items given.**