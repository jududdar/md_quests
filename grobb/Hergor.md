# Hergor


## Dialog

**You say:** `hail`



>**Hergor says:** Whats you wants!!  Me great master of da bashers.  Me tinks yooz must be lookin' fer trainin'.  Yooz looks like a weaklin'.  Me train yooz and yooz helps me get fatter.  Well!!  Are yooz gonna [helps Hergor get fatter]?!!

**You say:** `get fatter`



if **Faction** >= Amiable then



>**Hergor says:** Yooz makes da good choice.  Me nevers get enuff ta eats.  Eats more and gets more stronger. me always say.  Yooz gos and speaks wit carver Cagrek.  Yooz tell him [Hergor wants his fungus dung pie].  Yooz duz dis and me gives you sum rawhide armer or tatters armer.


elseif **Faction** >= Indifferent then



>**Hergor says:** More service to da bashers, den me listen.


else



>**Hergor says:** Me smell death coming your way!  Da bashers no like you. Hey!  Me am basher!

end



## Turn-Ins





if  **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_783.png" alt="" /> <a
                                href="/item/12210" data-url="12210" class="tooltip-link link">Fungus Spore Pie</a>) then 


>**Hergor says:** Mmmmm... Mm... Mmm! Dat smells gud! Me gets more fat and gets more strength. You dus gud job weekling. Me gives you dis armer. It keeps you from getting bashed gud. Now gos away. Me no share pie wit weekling.


Your faction standing with [Da Bashers](/faction/235) got better (<span class='text-success'>+5</span>)


Your faction standing with [Broken Skull Clan](/faction/222) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/2161" data-url="2161" class="tooltip-link link">Large Raw-hide Skullcap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2162" data-url="2162" class="tooltip-link link">Large Raw-hide Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_643.png" alt="" /> <a
                                href="/item/2163" data-url="2163" class="tooltip-link link">Large Raw-hide Gorget</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/2164" data-url="2164" class="tooltip-link link">Large Raw-hide Tunic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/2165" data-url="2165" class="tooltip-link link">Large Raw-hide Shoulderpads</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2166" data-url="2166" class="tooltip-link link">Large Raw-hide Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2167" data-url="2167" class="tooltip-link link">Large Raw-hide Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_634.png" alt="" /> <a
                                href="/item/2168" data-url="2168" class="tooltip-link link">Large Raw-hide Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2169" data-url="2169" class="tooltip-link link">Large Raw-hide Wristbands</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2170" data-url="2170" class="tooltip-link link">Large Raw-hide Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_635.png" alt="" /> <a
                                href="/item/2171" data-url="2171" class="tooltip-link link">Large Raw-hide Leggings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2172" data-url="2172" class="tooltip-link link">Large Raw-hide Boots</a>) (+500 exp)

 

**This NPC *should* return incorrect items given.**
