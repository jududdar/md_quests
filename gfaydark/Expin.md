# Expin
## Dialog

**You say:** `hail`



>**Expin says:** How are you, my friend?  You must be a [new scout of Kelethin].  I would hope so.  We dearly need more recruits.  Most of the Fier'Dal choose the path of the ranger.

**You say:** `new scout of kelethin`



if **Faction** >= Amiable then



>**Expin says:** Good. I have an easy, but very important, task for you. We require all young members to cleanse these woods of the troublesome pixie tricksters. Take this pouch, fill it with pixie dust, and when it is combined, return it to me. I just may have some used armor lying around for you.



**You receive:**  [Empty Pouch](/item/17957)


elseif( **Faction is** == Indifferent) then



>**Expin says:** The Scouts of Tunare have no quarrel with you, but perhaps a few less Crushbone Orcs would prove your worth. Then we shall speak.


else



>**Expin says:** You dare to speak with a loyal member of the Scouts of Tunare?!  You are truly foolish!  Run away, while you still can.


**You say:** `dark assassin`



>*Expin squints at you and says, 'So you have heard about him as well? I had heard of him through the rogue grapevine, so I was wary when the home guard spoke of the arrival of a dark stranger. I was approaching him from behind and some loud ranger clompipng about in the bushes must of spooked him, for off he ran. As he was running I took the liberty to swipe a piece of paper protruding from his pocket.' Expin mumbles to himself, 'Now where did I put that note?'*

**You say:** `not satisfied`



>**Expin says:** I told you not to tell me.
end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [Pouch of Pixie Dust](/item/12109)) then 


>**Expin says:** Good work, scout!!  You have earned this reward.  It is all we have at the time.  I am certain you are satisfied.  If not, then do not let me hear of it.


* __Faction:__ [Scouts of Tunare](/faction/316) (15)


 **You receive:** eq.ChooseRandom( [Patchwork Tunic](/item/2104), [Patchwork Cloak](/item/2106), [Patchwork Sleeves](/item/2108), [Patchwork Pants](/item/2111), [Patchwork Boots](/item/2112)) (+800 exp)

elseif( **You turn in:** [Crumpled Piece of Paper](/item/16390)) then 


>**Expin says:** Ahhh! You found it! Here let me make you a copy and put this in a secure spot so I don't lose it again.


 **You receive:**  [Remiss Sketch](/item/24098) (+50 exp)

**This NPC *should* return incorrect items given.**


