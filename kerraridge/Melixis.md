# Melixis
## Dialog

if **Faction** >= Dubious then


**You say:** `hail`




>**Melixis says:** Welcome to Melixis' shop. Rrrr. Feel free to brrrowse thrrrough my warrres. Melixis also find some [shiny tings] she may trade you.


**You say:** `shiny tings`




>**Melixis says:** In Melixis' travels of the Odus, she find a [dull ring], a [kinda shiny ring], and a [really shiny ring].  Maybe you want to trade for those tings?  Rrrr...


**You say:** `dull ring`




>**Melixis says:** For dat ting?  You brrring Melixis some bracket mildew.  Rarr...


**You say:** `kinda shiny ring`




>**Melixis says:** Hmm... Hamed need faerix spores forrr potion. Rrrrr. You brring some to Melixis and she give you the kinda shiny ring.


**You say:** `really shiny ring`




>**Melixis says:** You go find degenerated guk weed and Melixis gives you the really shiny ring.


else


**Melixis says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins





if **Faction** >= Dubious and  **You turn in:** [Guk Bracket Mildew](/item/14042)) then


>**Melixis says:** Many thanks... rrrr... here is dull ring.


 **You receive:**  [Copper Ring](/item/13733) 

elseif **Faction** >= Dubious and  **You turn in:** [Faerix Spores](/item/14043)) then


>**Melixis says:** Melixis thanks you, Hamed will be pleased. A kinda shiny ring is yours.


 **You receive:**  [Silver Ring](/item/13731) 

elseif **Faction** >= Dubious and  **You turn in:** [Degenerated Guk Weed](/item/14044)) then


>**Melixis says:** You done good job, furless one. Here is really shiny ring. Rarr...


 **You receive:**  [Gold Ring](/item/13732) 

**This NPC *should* return incorrect items given.**





