# Noresa Sparkle
## Dialog

**You say:** `hail`



>**Noresa Sparkle says:** He.. Hello. Wou.. would you like to buy something? Be quick or [Kizdean] will return!

**You say:** `Kizdean`



>**Noresa Sparkle says:** Sshhh..Please..save me. Get..rid..of..him.

if(e.other:IsSelfFound() == 1 or e.other:IsSoloOnly() == 1) then


**You say:** `Hail`




>**Noresa Sparkle says:** You might also call to Glyssa Sonshaw in Freeport if you seek enchantments of silver and gold.

end

## Turn-Ins




if **You turn in:** [A Sparkle Purse](/item/17931)


>**Noresa Sparkle says:** Oh!!! Thank you. You are my hero. I have been held captive by that horrid dark elf for weeks. Please take this. It was the key to a gem case which was stolen from me by an unseen rogue. If you find the gem case you can take it and the key to the original craftsman. He can open it with only two keys.


 **You receive:**  [A Tiny Key](/item/12352) (+15000 exp)

**This NPC *should* return incorrect items given.**
;