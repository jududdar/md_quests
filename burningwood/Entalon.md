# Entalon
## Dialog

**You say:** `hail`



>*Entalon smiles at you with a wide grin. 'You are quite brave to approach me and speak. On any other day, I would not give you the opportunity. Fortunately for you, I am preoccupied with my master's [quest].'*

**You say:** `quest`



>**Entalon says:** I have but a small task, to find the scribblings of Jarldyn. A Fier'Dal has stolen them. The scribblings will be illegible, but they must be returned to my master who has rightfully won them in battle. If you find them, bring them to me with an emerald plume and I will grant you an audience with my master. Be forewarned, it may be a one way trip.
end

## Turn-Ins



if( **You turn in:** [Scribblings](/item/12990), [Stoneleer Emerald Plume](/item/12755)) then 


>**Entalon says:** Ha ha ha!! Fool! I have what I need. Now you are granted an audience with a noble sarnak lord, not my master. I am quite sure he shall do away with you. Ha ha ha!!


 **You receive:** 0 (+5000 exp)


e.other:MovePC(87,-4039,6280,-53); 

**This NPC *should* return incorrect items given.**





