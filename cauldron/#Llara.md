# Llara


## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);


if(qglobals["Llara"] ~= nil) then


**You say:** `kanthuk`




>**Llara says:** I take it you're here to find out more about [Amstaf].


**You say:** `amstaf`




>**Llara says:** I've known Amstaf since he was a child. We grew up in the same city together. Ever since I've known him there's always been something [unusual] about him.


**You say:** `unusual`




>**Llara says:** When we were growing up we used to venture outside the city gates. Some times we would encounter a wandering ghoul or an undead spirit of some sort. He was always able to quickly dismiss the undead being with very little effort. I [learned] many things growing up with Amstaf.


**You say:** `learn`




>**Llara says:** Amstaf told me many things when we were younger. Once Amstaf told me that life isn't about how you get there, it's about where youup. I miss my dear friend. Its been a long time since I've seen him. The night of the snowstorm I dreamt about him. I remember seeing Amstaf's face. I saw something I've never [seen] before.


**You say:** `see`




>**Llara says:** I saw desperation. I spoke to many people who knew Amstaf trying to find out if anyone heard anything about that night. No one knew anything about it. When I had reached the dwarven hunting grounds I ran into a woman named Walnan. She kept rambling on and on about the power of the Orb and something about Magi\`kot. I didn't understand what she was saying. She didn't know anything about my situation either, but she did tell me that there were others that may be able to help me. She told me that I should find [Ruathey].


**You say:** `ruathey`




>**Llara says:** Ruathey is known for her ability to look into people's souls and find truth. Though I wasn't able to find Amstaf, I was able to recover his sword. I believe that by having his sword I am closer to finding him. Take this note to Ruathey and tell her that I sent you.



**You receive:**  [Note to Ruathey](/item/2417)



eq.delete_global("Llara");

end

## Turn-Ins




if **You turn in:** [A Pendant](/item/2414)


>**Llara says:** Oh my, this belongs to Amstaf! Where did you get it?


 **You receive:** 0 (+500 exp)


eq.set_global("Llara","ghoul",0,"D30");

**This NPC *should* return incorrect items given.**
;
