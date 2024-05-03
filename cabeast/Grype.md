# Grype


## Dialog

**You say:** `hail`



>*Grype gulps down the rest of his ale. 'Looks like I'll need another.*

**You say:** `blue talon`



>*Grype takes a swipe at you. 'We used to be the bruisers of the west side. We didn't take nothin' from no one!! Fist and mind was our motto. Now get lost before I introduce my fist to your face. Hmpf. Too late, I see.*


e.self:DoAnim(5);

**You say:** `stein`



if **Faction** >= Amiable then



>*Grype is staggering from one too many pale ales.  'Lishen... Listen here.  I have been forced to cut back on my drinking because my favorite sloshing stein was stolen from me by some stubby little thief in black.  I was jus' minding my own business and picking flowers in the fields of the drixies when he comes and snatches it from me.  Return it to me, and I will give you this treasure I acquired from a sarnak revenant.*


elseif **Faction** >= Indifferent then



>**Grype says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Grype says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!

end



## Turn-Ins



local text = "drinks the ale as if it were a shot. 'Ahhh!! Keep it coming. I think we are going to be good friends. Or something.";



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_709.png" alt="" /> <a
                                href="/item/12862" data-url="12862" class="tooltip-link link">A Stein</a>) then



>*Grype nearly faints. His eyes begin to tear up. 'Oh my sweet stein of sloshing! This is the great treasure. A shiny piece of broken metal! Ha! You never win when you deal with a Blue Talon!*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1013.png" alt="" /> <a
                                href="/item/12852" data-url="12852" class="tooltip-link link">Foot of Candlestick</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_824.png" alt="" /> <a
                                href="/item/12609" data-url="12609" class="tooltip-link link">Cabilis Pale Ale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_824.png" alt="" /> <a
                                href="/item/12609" data-url="12609" class="tooltip-link link">Cabilis Pale Ale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_824.png" alt="" /> <a
                                href="/item/12609" data-url="12609" class="tooltip-link link">Cabilis Pale Ale</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_824.png" alt="" /> <a
                                href="/item/12609" data-url="12609" class="tooltip-link link">Cabilis Pale Ale</a>) then


>*Grype swallows the whole bottle in one gulp. 'Here, go buy yourself a brain. What?!! You expecting something? How about this.. <BUUURRRPPPP!!> Thanks for helping me get through my dry spell, croak!! Never mess with a Blue Talon!!*


 &#127873; **You receive:** 0 (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
