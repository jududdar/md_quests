# Guard Leopold


## Dialog

**You say:** `hail`



>**Guard Leopold says:** Hail, Soandso. You had best keep moving. One who stands around too long in Qeynos Hills tends to get surprised by vicious creatures.

**You say:** `donation.* temple.* thunder`





>**Guard Leopold says:** Why, yes! I would love to donate to the Temple of Thunder. My father was a brave and noble member of that order. Here you are. You should ask Guard Cheslin also. His father and mine are both members of Thunder. Now, move along!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13294" data-url="13294" class="tooltip-link link">A Donation</a>

**You say:** `blackburrow`



>**Guard Leopold says:** Blast those dogs!  The Sabertooths is what they call themselves around here.  They have a nest, or whatever you call it, up there east of Surefall Glade.  We can always use help here, keeping those dirty gnolls away from our fine city.  Talk to Captain Tillin in South Qeynos and tell him you want to join the fight.
end



## Arrive at Waypoint Script

if(e.wp == 2) then


e.self:DoAnim(29);
end
