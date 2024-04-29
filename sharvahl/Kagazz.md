# Kagazz
## Dialog

**You say:** `hail`



>**Kagazz says:** Ale you say? No ale here friend, I am a blacksmith. You'll have to speak loud and clearly by the way, I don't hear so well since the [incident]. Show me your slate if you're looking for work.

**You say:** `incident`



>**Kagazz says:** I was quite a homely yet sensitive lad, bad combination. As I was growing up I was teased mercilessly. In an effort to block out the ridicule I habitually placed my fingers far into my ears. My claws must have done some kind of permanent damage.

**You say:** `fastener`



>*Kagazz squints as he reads your lips, 'Fasteners you say? Show me your slate and I'll make you a deal.*

**You say:** `barkhem`



>*Kagazz blushes a bit and says, 'No no, you are the gem my friend.  You remind me a bit of Barkhem... he was my best student ever.  When the work of being Master Smith got to be too much for someone my age, it was quite easy to decide who would fill my shoes.  These days anyone wanting to learn the ways of the smith go to him.*
end

## Turn-Ins



if( **You turn in:** [Acrylia Slate of Shar Vahl](/item/2877)) then 


>**Kagazz says:** My wife is making some jewelry. Not the sparkly stuff, mind you. She is nearly blind so appearance means little to her. She is intent on making jewelry with a more, uhh, natural feel. Currently she's constructing a special scorpion leg necklace, and is in need of more scorpion legs. I can't leave the shop so I need your help. Fill this box with scorpion legs and I'll pay you with metal fasteners that any merchant will gladly buy.


 **You receive:** GiveAll( [Acrylia Slate of Shar Vahl](/item/2877), [Kagazz's Box](/item/17238)) 

elseif( **You turn in:** [Box of Scorpion Legs](/item/3676)) then 


>**Kagazz says:** Ahh, Soandso! I thank you, my wife will be most grateful. Here are the fasteners I promised you. You know Soandso, there was a time that young, would-be smiths would seek my approval so that they could study the ways of the forge under my tutelage. That was back when I was Master Smith, before I named Barkhem my successor.


 **You receive:**  [Forged Fasteners](/item/3667) (+10 exp)

**This NPC *should* return incorrect items given.**
