# Shrub Marwood

## Dialog

**You say:** `hail`



>*Shrub Marwood brushes pollen off of his tunic. 'Aachoo!! Oh!! Hello. Please look around. Unless you are a [druid looking for work].'*


e.self:DoAnim(55);

**You say:** `druid looking for work`



>**Shrub Marwood says:** Good. I need a stout adventurer to go to the wilds and find me a few items. I need some tump stumps - one Kromdul and one Kromdek type. I also need a mantrap root. Get me those three things and I will give you this handy shillelagh I found in the forest.


e.self:DoAnim(48);

**You say:** `fertile crop`



>**Shrub Marwood says:** Looking to get hold of my family druid spell, ehh? It doesn't come without a price. Lucky for you all I need is for you to run a small errand for me. Go fetch me a Sarnak farsight crystal, some Sarnak nightdust, some strathebone heal silk and some powder of Tsu. Do that and I will give you a copy of my family secret.


e.self:DoAnim(60);
end

## Turn-Ins



local text1 = "Hey!! Trying to pull a fast one?!! I said I wanted tump stumps of Kromdek and Kromdul type and a mantrap root!!";



local text2 = "If you want the [Fertile Crop] druid spell, I must insist that you complete your small task.";



if **You turn in:** [Mantrap Root](/item/12960), [A Tump Stump](/item/12955), [A Tump Stump](/item/12958)


>*Shrub Marwood tosses the mantrap root out the window.. SPLASH!! 'I made a mistake. I didn't need that one. Here is the shillelagh I told you about. I found it in some burned out woods far from here. I cleaned it up and found it had a spark of mana so I had it enchanted with a few charges of my spell, [Fertile Crop]. Hope you like it.'*


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (3)


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Dark Oak Shillelagh](/item/12953) (+25000 exp)

if **You turn in:** [A Farsight Crystal](/item/11579), [Pouch of Dust](/item/12753), [Strathbone Silk](/item/12957), [Shaman Powder](/item/12959)


>**Shrub Marwood says:** Great work! I wish I had the coin to hire you on permanently. Maybe I will, when I find the lost trade city of Torsis. Here is the spell I copied for you. Careful, the ink is still drying.


* __Faction:__ [Inhabitants of Firiona Vie](/faction/248) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (3)


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Legion of Cabilis](/faction/441) (-1)


* __Faction:__ [Pirates of Gunthak](/faction/313) (-1)


 **You receive:**  [Fertile Crop](/item/12954) (+25000 exp)

**This NPC *should* return incorrect items given.**





