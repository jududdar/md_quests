# Urkath Greyface



[Urkath Greyface](/npc/74022) is a level 18 Kerran Monk that spawns in [Kerra Isle](/zone/74).



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





if **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_911.png" alt="" /> <a
                                href="/item/1155" data-url="1155" class="tooltip-link link">Sylvani Leaf</a>) then


>**Urkath Greyface says:** Errr? This is.. this is silvani leaf! Rrrrrr.. So nice. This means much to Urrkath, furrrless one. Please, take this for such kind work.


Your faction standing with [Kerra Isle](/faction/382) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2045" data-url="2045" class="tooltip-link link">Worn Leather Shoulderpads</a> (+500 exp)

 
end





