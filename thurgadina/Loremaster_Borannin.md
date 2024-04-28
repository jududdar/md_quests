# Loremaster Borannin


## Dialog

**You say:** `hail`



>**Loremaster Borannin says:** Greetings, Soandso, please be seated and hear the Grand Historian, he is among the wisest of our people.

**You say:** `for the crown`



>**Loremaster Borannin says:** Those eager to prove their loyalty to the Dain may do so by completing tasks that I have been commissioned to assign. If you wish to begin your service, return to me with four toes of our enemy, the Kromrif.

**You say:** `task`



>**Loremaster Borannin says:** Every year the Dain replaces the trophies in his trophy room. There is a reward given for the best new trophy obtained. I intend to win this year and I will upgrade your prayer shawl for assisting me. Fill this box with ten Kromrif heads and bring me the combined contents along with the burlap shawl. I will submit the best one for the Dain's consideration.


**You receive:**  [Preservationists Box](/item/17102)

**You say:** `chore`



>**Loremaster Borannin says:** The council agrees that you have demonstrated a disdain for our enemy, the Kromrif, that rivals our own. They now ask that you demonstrate your loyalty to the Dain by humbling yourself and serving our people. Give this, my seal, to Mordin. He will instruct you further.


**You receive:**  [Borannin's Seal](/item/1420)

**You say:** `brewing`



>**Loremaster Borannin says:** Ahh yes, good to see you again, Soandso. I wish it were under better circumstances that we meet today. For some time now we have sent teams of our finest rogues to gather intelligence for the Dain. Tanik Greskil is one of our best. He was recently sent into the heart of Kael Drakkel on a very important mission and has not returned. He is now long overdue, and fearing the worst, our wise council has asked me to dispatch a rescue party to determine what has become of him and return him to safety. I have decided to give you this opportunity to build upon the trust you have earned from the council. Will you accept this mission?

**You say:** `accept this mission`



>**Loremaster Borannin says:** The council will be pleased to hear of your acceptance. Scour the regions surrounding the city of the Giants. Discover what happened to Tanik and, if possible, return him to Thurgadin. If you are successful, remember to hand me your woven shawl. We seem to be running low on them, but I must say Mordin has never had so much help in the kitchen. Anyway, I will eagerly await word of your findings. Good luck, and may Brell protect you.

**You say:** `advance my reputation`



>**Loremaster Borannin says:** Soandso! Thank Brell you're here. I was about to send one of my Lorekeepers looking for you. It appears that the information Tanik acquired is most perilous indeed. The Dain has called an emergency session of the council and I must attend. We don't have the luxury of waiting for an appropriate task to arise, you must advance as soon as possible. Unfortunately, I have neither the time, nor the components to fashion the next few shawls for you. Ask Rexx Frostweaver about the prayer shawl and follow his direction carefully.
end

## Turn-Ins





if **You turn in:** [Runed Coldain Prayer Shawl](/item/1199)


>**Loremaster Borannin says:** Incredible! Never before has an outlander been skilled and determined enough to craft our sacred rune. You are now worthy of the Dain's most perilous task. You should seek an audience with the Dain immediately. Show him your Runed Prayer Shawl; he will give you the task that has been prepared for you. If the Dain is away show your Shawl to Chamberlain Krystorf and he will call for him.


 **You receive:**  [Runed Coldain Prayer Shawl](/item/1199) 

elseif **You turn in:** [Frost Giant Toes](/item/29125), [Frost Giant Toes](/item/29125), [Frost Giant Toes](/item/29125), [Frost Giant Toes](/item/29125)


>**Loremaster Borannin says:** Ahh, well done! On behalf of the Dain I thank you for making a dent in the number of our sworn enemy. Please accept this as a token of our appreciation. It is trivial, I know, but if you are as loyal as you claim to be, it will increase in power over time. It just so happens I have a [task] to further demonstrate your loyalty, Soandso.


ColdainFaction(e);


 **You receive:**  [Burlap Coldain Prayer Shawl](/item/1175) (+10000 exp)

elseif **You turn in:** [Burlap Coldain Prayer Shawl](/item/1175), [Preserved Kromrif Heads](/item/1174)


>**Loremaster Borannin says:** Ahh, some fine specimens indeed, Soandso. I will have the best of these mounted at once, wish me luck in the contest! Here is the Cloth Prayer Shawl of our people. Before I forget, the council has issued yet another [chore] for you to complete.


ColdainFaction(e);


 **You receive:**  [Cloth Coldain Prayer Shawl](/item/1176) (+25000 exp)

elseif **You turn in:** [Cloth Coldain Prayer Shawl](/item/1176), [Seal of Thoridain](/item/1422)


>**Loremaster Borannin says:** Well done, Soandso, the council will be impressed with your effort. Here is the woven prayer shawl, wear it with pride. I know there is talk of great plans for you, be sure to come back and ask me what the council has [brewing].


ColdainFaction(e);


 **You receive:** None 

elseif **You turn in:** [Woven Coldain Prayer Shawl](/item/1177), [Taniks note](/item/1560)


>**Loremaster Borannin says:** Words cannot express our gratitude for your deeds outlander, you have saved a hero of our people from certain death. Please accept this, the Fur-lined shawl, as a token of our sincere appreciation. You are indeed among the most highly regarded " .. e.other:Race() .. "s to set foot in Thurgadin. The next time we meet be sure to ask me how to further advance your reputation with the coldain.


* __Faction:__ [Coldain](/faction/406) (20)


* __Faction:__ [Dain Frostreaver IV](/faction/405) (5)


* __Faction:__ [Kromzek](/faction/448) (-2)


* __Faction:__ [Kromrif](/faction/419) (-10)


 **You receive:**  [Fur-Lined Coldain Prayer Shawl](/item/1178) (+100000 exp)

**This NPC *should* return incorrect items given.**

function ColdainFaction(e)

* __Faction:__ [Coldain](/faction/406) (10)

* __Faction:__ [Dain Frostreaver IV](/faction/405) (2)

* __Faction:__ [Kromzek](/faction/448) (-1)

* __Faction:__ [Kromrif](/faction/419) (-5)