# Phenocryst
## Dialog

if( **Faction is** >= Indifferent) then


**You say:** `hail`




>*Phenocryst speaks with a soundless voice, as if you are hearing your own thoughts. 'We sense you are attempting communication with us but do not understand what it is you are trying to convey. We are eager to know more. Perhaps there is one who knows the language of the stone and will speak with us'*


elseif(**You possess item:**  [Velium Focus](/item/1693) x 1



**You say:** `help you`





>*Phenocryst speaks from within your mind as well as conveys a sense of joy empathically. It is said that the harbringer will find all of our people and unite them. When we join we will know all of our experiences and perhaps then be aware of how to proceed with the next step in our asscention. We implore you to find others like us and make them aware of us. You know the language of the stone and can tell them. We await your return with proof that you have spoken to them.*




elseif(**You possess item:**  [Velium Focus](/item/1701) x 1



**You say:** `find what`





>*Phenocryst says in the form of thoughts, We must call to it. We must make ourselves heard past these rocks though. A menhir must be constructed to amplify our voice. The stones we will need are not found in this area though. We hear whispers of stones far away that have the ability to channel and amplify our thoughts. We ask you to gather these stones for us harbinger.*



**You say:** `gather`





>*Phenocryst thoughts flood your mind, 'Thank you Harbinger. We need 3 crystals. One of Beryl, one of Stibnite, and one of the purest Iron. These minerals will only be found deep within the earth where the geology is relatively stable. This Focus will aid you in finding the right crystals. Return it to me with the 3 crystals and we will construct our Menhir. Please hurry Harbinger, our prophecy awaits.*




**You receive:**  [Elbaite Focus](/item/1694)




e.other:NukeItem( [Velium Focus](/item/1701));



end

## Turn-Ins





if( **You turn in:** [Velium Focus](/item/1692)) then 


>*Phenocryst speaks to you from within your mind, You know the stone! This is wonderful! The fullfillment of the prophecy is now one step closer. The most ancient of the stone tells us that one not of stone will come forth and act as our harbringer of asscention. We believe you to be our harbringer. Please help us!*


* __Faction:__ [Geonid Collective](/faction/458) (100)


 **You receive:**  [Velium Focus](/item/1693) 

elseif( **You turn in:** [Velium Focus](/item/1701)) then 


>*Phenocryst sends it's thoughts to you, a feeling of disappointment washes over you, It seems the others are not aware of themselves yet. We are alone..So many questions yet we can find no answers. We have been given a very special gift but without direction we are lost. We must find who has made us aware of ourselves and why it has done so.*


* __Faction:__ [Geonid Collective](/faction/458) (100)


 **You receive:**  [Velium Focus](/item/1701) 

elseif( **You turn in:** [Azurite Focus](/item/1698), [Holy Symbol of Zek](/item/1699), [Holy Symbol of Zek](/item/1699), [Holy Symbol of Zek](/item/1699)) then


>*Phenocryst thoughts become your own, a feeling of joy overwhelms you, 'Because of you we can at last speak with our maker. We were once given a gift, and we ask that you accept this gift from us now so that we may come closer to that which we owe our sentience to. Now. ,we must construct the Menhir.*


* __Faction:__ [Geonid Collective](/faction/458) (100)


 **You receive:**  [Phenocrysts Focus](/item/1700) 

elseif( **You turn in:** [Elbaite Focus](/item/1694), [Reddish Crystal](/item/1695), [Heavy Metallic Crystal](/item/1697), [Bent Metallic Crystal](/item/1696)) then 


>*Phenocryst makes no sound but it's voice fills your mind. We have always held our memories within the earth and stone but only recently have we become aware of them. We do not know what happened or who gave us this wonderful gift but we can now access those memories and are aware of it's storage. With that knowledge has come questions and desires. When the prophecy comes to be then we will have our answers and fulfill our desires.*


* __Faction:__ [Geonid Collective](/faction/458) (100)


 **You receive:**  [Azurite Focus](/item/1698) 


**Spawn NPC:**  [accolyte of Zek](/npc/119032) at (**y:** -690.21, **x:** 408.10)


**Spawn NPC:**  [accolyte of Zek](/npc/119032) at (**y:** -985.80, **x:** -564.04)


**Spawn NPC:**  [Bloodpriest Ioukond](/npc/119034) at (**y:** 254.44, **x:** 303.02)


>*Phenocryst familiar thoughts flood into your mind again, You truly are the Harbinger, take this Focus as a mark of your friendship with us. Now we can construct the Menhir, we need .. the stones speak.. , There is a problem. Ones of flesh are coming, the large ones, 3 of them. They must not disturb us while we construct the Menhir! Please stop them Harbinger! bring us proof of their distruction along with your Focus and then we will begin the calling. Our asscention is at hand!*


**Set a timer** named *depop* for 3600 seconds

**This NPC *should* return incorrect items given.**

## Timer(s)

**Despawn NPC:**  [Bloodpriest Ioukond](/npc/119034)

**Despawn all instances of:**  [accolyte of Zek](/npc/119032)