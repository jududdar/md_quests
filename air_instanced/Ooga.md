# Ooga
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Ooga says:** Euh? You come see Ooga about shaman tests? Me can test in shrink, the snake, or witch doctor! What yuz want to test in?

**You say:** `shrink`



>**Ooga says:** Ohh! Dat gud tes, me know cuz me did it. Me had get a Efreeti War Club, Djinni Statuette, sum Corrosive Venom an sum Wooden Bands. Was hard for Ooga, me took long to get dem. Yuz give all to me at sam time me give yuz what me got.

**You say:** `snake`



>**Ooga says:** Mmm, tes of snake not too bad, me did It an still alive. When me did It, me got Emerald Spiroc Feather, Bixie Essence, an Spiritualists Ring. Me get gud stuff for dat. Yuz giv me stuff all at once an me give to yuz what me got.

**You say:** `witch doctor`



>**Ooga says:** Oh! Now yuz got In da big mojo, me had big hard time wit dis one. Me got In lot of trouble when me got Efreeti War Maul, Thickened Nectar, Fire Sky Ruby an Symbol Of Veeshan. Yuz giv to me, Me be easy on yuz an giv prize me got.
end

## Turn-Ins



if( **You turn in:** [Efreeti War Club](/item/20845), [Djinni Statuette](/item/20955), [Corrosive Venom](/item/20842), [Wooden Bands](/item/20841)) then 




>**Ooga says:** Excellent! Take this as your reward.


 **You receive:**  [Warhammer of the Wind](/item/27729) (+100000 exp)


**Ooga despawns.**

elseif( **You turn in:** [Emerald Spiroc Feather](/item/20962), [Bixie Essence](/item/20843), [Spiritualist\`s Ring](/item/20844)) then 



>**Ooga says:** This ring should aid you greatly, Soandso. Use it wisely.


 **You receive:**  [Vermilion Sky Ring](/item/27730) (+100000 exp)


**Ooga despawns.**

elseif( **You turn in:** [Efreeti War Maul](/item/20846), [Thickened Nectar](/item/20969), [Fire Sky Ruby](/item/20848), [Symbol of Veeshan](/item/20847)) then 



>**Ooga says:** Your deeds are beyond compare, Soandso. Use Garduk with care though, for it is more powerful than any other weapon you have wielded.


 **You receive:**  [Garduk](/item/11694) (+100000 exp)


**Ooga despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Ooga despawns.**




