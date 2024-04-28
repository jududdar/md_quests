# Urkath Greyface
## On NPC Spawn

**Set a timer** named *wish* for 3000 seconds
## Timer(s)

>**Urkath Greyface says:** Errrrrmf. If only just that [wish] for Urrkath?
## Dialog

if **Faction** >= Dubious then


**You say:** `hail`




>**Urkath Greyface says:** Errr? What you say to Urrrkath? Ah. Hello to you as well, furrrless type person.


**You say:** `wish`




>**Urkath Greyface says:** Wish? Oh. Urrkath old kerran. Urrkath pass on soon. It great disappointment that Urrkath never see beautiful forest of elves. Now all Urrkaath want is sylvani leaf from elf forest. So me can see at least little part of forest.


else


**Urkath Greyface says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins





if **Faction** >= Dubious and  **You turn in:** [Sylvani Leaf](/item/1155)


>**Urkath Greyface says:** Errr? This is.. this is silvani leaf! Rrrrrr.. So nice. This means much to Urrkath, furrrless one. Please, take this for such kind work.


* __Faction:__ [Kerra Isle](/faction/382) (5)


 **You receive:**  [Worn Leather Shoulderpads](/item/2045) (+500 exp)
end





