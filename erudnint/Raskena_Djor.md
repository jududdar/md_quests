# Raskena Djor


## Dialog

**You say:** `hail`



>**Raskena Djor says:** Greetings. What brings you to Raskena? Did Ghanlin send you?

**You say:** `ghanlin`


>**Raskena Djor says:** Then let us begin your first task. I require some components for an experiment I have been meaning to conduct. If you could [gather] them for me, I will make sure that you are rewarded.

**You say:** `gather`


>**Raskena Djor says:** In Toxxulia Forest you should be able to find some fire beetles. I require two fire beetle legs and two fire beetle eyes. Once you have collected them, bring them to me for your reward.
end

## Turn-Ins




if( **You turn in:** [Fire Beetle Eye](/item/10307), [Fire Beetle Eye](/item/10307), [Fire Beetle Leg](/item/13250), [Fire Beetle Leg](/item/13250)) then 


>**Raskena Djor says:** You have passed your first task. Nice work. Take this spell as your payment.


 **You receive:** eq.ChooseRandom( [Spell: Sphere of Light](/item/15373), [Spell: Frost Bolt](/item/15054), [Spell: True North](/item/15205), [Spell: Minor Shielding](/item/15288), [Spell: Shock of Frost](/item/15372), [Spell: Numbing Cold](/item/15374)) (+150 exp)

**This NPC *should* return incorrect items given.**
;
