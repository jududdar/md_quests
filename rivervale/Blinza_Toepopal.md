# Blinza Toepopal
## On NPC Spawn

**Set a timer** named *jillin* for 550 seconds
## Timer(s)

if(timer == "jillin") then


>**Blinza Toepopal says:** [Jillin]? Jillin? Where did he go? Hrumph!
end

## Dialog

**You say:** `hail`



>**Blinza Toepopal says:** Hello, Soandso.  Welcome to the Fool's Gold!  Cards are upstairs, drinks are down here.  Have fun!

**You say:** `jillin`



>**Blinza Toepopal says:** Jillin is my courier. He was supposed to take this pot of [stew] over to Deputy Lowmot in Guardian Stronghold. It is just about ready and Mayor Gubbin hates cold stew!

**You say:** `stew`



>**Blinza Toepopal says:** Here. Take it to Lowmot. The stew is already paid for but the good Deputy usually tips Jillin quite well. Hurry! It's getting cold!


**You receive:**  [Carrot Stew](/item/13959)
end

## Turn-Ins




if ( **You turn in:** [Crate of Carrots](/item/13958)) then


>**Blinza Toepopal says:** Well it is about time!  The mayor gets very upset if he does not have the freshest of carrots in his stew.  Here is the money for the carrots.  Be off with you.  Now, where the heck did [Jillin] go?


* __Faction:__ [Deeppockets](/faction/241) (1)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (-1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Carson McCabe](/faction/329) (1)


 **You receive:** 0 (+10 exp)

elseif ( **You turn in:** [Crate of Fine Carrots](/item/13957)) then


>**Blinza Toepopal says:** Oh excellent! These carrots are perfect! The finest Reebo has ever sent us. The mayor will be so pleased. Here is the payment for the carrots. Excuse me, but I must finish preparing the stew. Hmm. Where the heck did [Jillin] go?


* __Faction:__ [Deeppockets](/faction/241) (5)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (-1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Carson McCabe](/faction/329) (1)


 **You receive:** 0 (+20 exp)

elseif ( **You turn in:** [Crate of Rotten Carrots](/item/13971)) then


>**Blinza Toepopal says:** What are these?!  I am trying to make stew for the mayor and you bring me ROTTEN CARROTS?!  Have you no sense??  Take these back to Reebo.


* __Faction:__ [Deeppockets](/faction/241) (-5)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (-1)


* __Faction:__ [Carson McCabe](/faction/329) (-1)


 **You receive:**  [Crate of Rotten Carrots](/item/13972) 

**This NPC *should* return incorrect items given.**
;

