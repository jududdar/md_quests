# Tumpy Irontoe
## Dialog

**You say:** `hail`



>**Tumpy Irontoe says:** Welcome to Irontoe's! The finest watering hole this side of Oggok! If you're looking for anything special and it ain't behind the bar, just ask. Maybe I can make it.

**You say:** `tumpy tonic`



>**Tumpy Irontoe says:** So you want a Tumpy Tonic? I can make you one. All I need is a flask of water and a kiola nut. The kiola nut can be bought in the Ocean of Tears island chain.

**You say:** `trumpy`



>**Tumpy Irontoe says:** Trumpy...  I have not seen him in ages!  We were both members of the Irontoe Brigade.  Last I heard, he was drinking his life away in the great city of Qeynos.

**You say:** `drumpy`



>**Tumpy Irontoe says:** Sounds like you ran into one of my old pals from the Irontoe Brigade. I hope he is doing okay. Ah, those were the days...
end

## Turn-Ins



local text = "Okay. Where are the other ingredients?";



if( **You turn in:** [Kiola Nut](/item/13340), [Water Flask](/item/13006)) then 


>**Tumpy Irontoe says:** Here you go. One Tumpy Tonic. Don't drink that too fast now.


 **You receive:**  [Tumpy Tonic](/item/12114) (+10 exp)

**This NPC *should* return incorrect items given.**
