# Jali Kaliio


## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Jali Kaliio says:** Greetings outsider. I trust you have [peaceful intentions] while visiting our village?


else



>**Jali Kaliio says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `peaceful intention`



if **Faction** >= Dubious +300 then



>**Jali Kaliio says:** That is good to hear. Those filthy kobolds have caused enough trouble. We do not need more enemies.' Jali turns around and glances at another Kejekan. This one seems somewhat ill. Her fur is coming out in patches and strange sores cover her body. 'That is my wife, Yuio. She has come down with a sickness, no doubt caused by those accursed kobolds.' Anger wracks Jali's face as he speaks. 'I would ask you for [help] but you are a stranger and owe us nothing. Of course if you did assist me, I would be forever grateful.


else



>**Jali Kaliio says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `help`



if **Faction** >= Dubious +300 then



>**Jali Kaliio says:** Oh thank you. You are most kind. I fear that there is not much time left for my dear Yuio. Please speak to [Khonza Ayssla]. She is most wise and perhaps can find some cure for this affliction.


else



>**Jali Kaliio says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `khonza ayssla`



if **Faction** >= Dubious +300 then



>**Jali Kaliio says:** Khonza Ayssla is the village's High Shaman. She teaches the ancient ways of Okanjo and is most wise. If she cannot assist you I do not know who can. I would go myself but I am too worried to leave my dear wife behind. When you find Khonza, tell her that Jali sent you. Please hurry, friend!


else



>**Jali Kaliio says:** You have done much to anger the spirits thus you are not accepted by our people.

end



## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1157.png" alt="" /> <a
                                href="/item/6976" data-url="6976" class="tooltip-link link">Vial of Healing Liquid</a>) then


>**Jali Kaliio says:** Khonza Ayssla gave this to you? We must try it at once then.' Jali opens the vial and gently tilts back Yuio's head. He pours the liquid into her mouth and waits. Miraculously, Yuios fur begins to take on a healthy sheen and the sores begin to disappear! Yuio falls into Jali's arms then goes slack, passing out. 'She needs much rest. I cannot begin to thank you enough for helping us. Please accept this as a reward. It is not much but it should be of some use. You are indeed a friend of ours and if you ever need shelter from the wilds, please visit us again.


Your faction standing with [Kejek Village](/faction/5011) got better (<span class='text-success'>+5</span>)


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_890.png" alt="" /> <a
                                href="/item/6952" data-url="6952" class="tooltip-link link">Wakizashi of the Frozen Skies</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
