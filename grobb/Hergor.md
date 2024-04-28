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





if  **Faction** >= Amiable and  **You turn in:** [Fungus Spore Pie](/item/12210)


>**Hergor says:** Mmmmm... Mm... Mmm! Dat smells gud! Me gets more fat and gets more strength. You dus gud job weekling. Me gives you dis armer. It keeps you from getting bashed gud. Now gos away. Me no share pie wit weekling.


* __Faction:__ [Da Bashers](/faction/235) (5)


* __Faction:__ [Broken Skull Clan](/faction/222) (-1)


 **You receive:** eq.ChooseRandom( [Large Raw-hide Skullcap](/item/2161), [Large Raw-hide Mask](/item/2162), [Large Raw-hide Gorget](/item/2163), [Large Raw-hide Tunic](/item/2164), [Large Raw-hide Shoulderpads](/item/2165), [Large Raw-hide Cloak](/item/2166), [Large Raw-hide Belt](/item/2167), [Large Raw-hide Sleeves](/item/2168), [Large Raw-hide Wristbands](/item/2169), [Large Raw-hide Gloves](/item/2170), [Large Raw-hide Leggings](/item/2171), [Large Raw-hide Boots](/item/2172)) (+500 exp)

**This NPC *should* return incorrect items given.**
