# Kelkim Menkia


## Dialog

**You say:** `hail`



>*Kelkim Menkia sighs as she looks over her lute. 'My lute was mangled by those damnable gnolls. I have no idea how I'm going to get a new set of strings for it. They were so rare.'*

**You say:** `rare`



>**Kelkim Menkia says:** I only use the finest lute strings on my lute. My uncle got them for me from across the world. His name was Zendrik the Wurmslayer. As his name implies, he killed many wurms and drakes. The strings for my lute were all made from the guts of the wurms and drakes he slew.

**You say:** `wurms and drakes`



>**Kelkim Menkia says:** The strings were from a chromodrac, a red wurm and a huge onyx drake. It always sounded so wonderful.' Kelkim sighs, looking off to the horizon. As she shakes her lute angrily, she says, 'I'll kill all of you dirty gnolls!
end

## Turn-Ins




if **You turn in:** [Chromodrac Gut](/item/20527), [Red Wurm Gut](/item/20528), [Onyx Drake Gut](/item/20529)


e.self:Emote(string.format("snatches the gut strings from your hand and immediately begins to string her lute. 'This is wonderful, I will be able to play my lute again soon! Take this old sheet of music I found - I don't think I will have much use for it. My new desire is to bash gnoll heads in with my lute. Safe travels to you, %s.",e.other:GetName()));


 **You receive:**  [Maestros Symphony Page 25](/item/20377) (+5000 exp)

**This NPC *should* return incorrect items given.**

