# a prisoner
## Dialog

**You say:** `hail`



>**a prisoner says:** Rrrribit.. Please, let me go!! I don't want to be eaten!!

**You say:** `glib sent me`



>**a prisoner says:** Liessss. ...Groakk.. I do not believe you!! Bring me proof. Bring me the necklace of a basher!! ..Groakk..
end

## Turn-Ins



if ( **You turn in:** [Intestine Necklace](/item/13311)) then


>**a prisoner says:** Groak.. So you are a friend to the froglok. ..Grooakk.. I am soon to die. My precious legs are a delicacy here. Before I go I must contact my brother Grikk. He is a froglok forager in Innothule. Give him this vial. He will know what it means


 **You receive:**  [Empty Vial](/item/13375) (+500 exp)

elseif ( **You turn in:** [Ochre Liquid](/item/13376)) then


>**a prisoner says:** Grooak.. You have done much to help me. This will come in handy soon. Thank you. Here is Marda's information. Take it to her. They must know. Farewell.


 **You receive:** eq.ChooseRandom( [Tattered Note](/item/18884), [A Tattered Cloth Note](/item/18885)) (+500 exp)

**This NPC *should* return incorrect items given.**
