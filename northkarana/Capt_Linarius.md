# Capt Linarius
## Dialog

**You say:** `hail`



>**Capt Linarius says:** Hail, traveler! You are free to rest within this keep or within any of my towers along the roads to Qeynos. My guards shall keep watch over you. While you tread upon the roads, be warned that there are [local dangers] as well as rumors of [corrupt guards].

**You say:** `corrupt guards`



>**Capt Linarius says:** I have heard rumors of dissension among my guards. I will reward any fine resident for the death of these traitorous guards. If you find you must kill one, bring his guard bracelet back to me. I cannot allow such men among my guards. Be sure they are corrupt, or I shall have your head as well.

**You say:** `local dangers`



>**Capt Linarius says:** My guards report daily to me of dangers in the plains. Lately, they've been telling me of rumors of [Lord Grimrot].

**You say:** `lord grimrot`



>**Capt Linarius says:** My guards have heard rumors of this Lord Grimrot. It is said that he is a powerful shadowknight who is raising an army of undead. Such things should be reported to the Temple of Life. Journey to Qeynos and speak with Camlend Serbold. Tell him of Lord Grimrot.
end

## Turn-Ins



local cgb =  **You turn in:**  { [Guard Bracelet](/item/13303)}


if **Faction** >= Apprehensive and (cgb > 0))  then 


repeat


>**Capt Linarius says:** What a pity. Such a promising soldier. I thank you for ridding us of this corruption and offer you this as a reward. It is nothing more than junk which littered the roadways of the Plains of Karana. I hope you can find a use for it.





* __Faction:__ [Guards of Qeynos](/faction/262) (10)


* __Faction:__ [Antonius Bayle](/faction/219) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-2)


* __Faction:__ [Merchants of Qeynos](/faction/291) (1)


 **You receive:** None 



cgb = cgb - 1;


until cgb == 0



if **You turn in:** [Guard Bracelet](/item/13304)


>**Capt Linarius says:** You fool! You have killed a fine and outstanding guard. You shall pay dearly for this!


**Capt Linarius attacks you.**

**This NPC *should* return incorrect items given.**

end