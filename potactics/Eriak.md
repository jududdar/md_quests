# Eriak



[Eriak](/npc/214073) is a level 70 Rallos Zek Minion Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).



## Dialog

local qglobals = eq.get_qglobals(e.other);

local zeks = tonumber(qglobals.zeks) or 0;


**You say:** `hail`




if ( zeks > 4 ) then



>*Eriak grins at you coldly. 'The twins lie bleeding at the feet of Rallos, and the halls of Drunder shiver with uncertainty. But one challenge lies before you. Face the warlord and his two injured acolytes and the power of Drunder is yours for the taking. The Warlord will not fall easily.  The weapons of dark courage will not be enough, your weapons will require the power of torment to topple the Warlord.*


else



>*Eriak glares at you through blackened eyes of malice. 'Foolish, but brave I suppose. As if that word has any meaning in this place.  Prove yourself on the field of blood if you dare.'*





**You say:** `weapons`



>**Eriak says:** Though your weapons may have been effective against the twins, they will prove of little use against the Warlord.  Temper them with the Torment of Saryn and you may yet be able to cleave the armor of the warlord.  Insanity is not easily manipulated though.  You'll have to suspend it in the blood of zek.


**You say:** `blood`



>*Eriak looks at you silently for a moment.  His eyes scan from your feet up to your face and linger there, staring into your eyes.  He blinks once, slowly. He then draws a dagger from his waist and throws the iron gauntlet from his left hand to the floor.  The dagger drifts across his forearm, and without a sound cuts into his calloused skin.  A trickle of dark blood creeps down his arm and drips into a small vial in Eriak's right hand.  He hands you the vial, staring through your eyes into your soul without a word.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_698.png" alt="" /> <a
                                href="/item/28592" data-url="28592" class="tooltip-link link">A vial of black blood</a>




**You say:** `dark courage`



>**Eriak says:** Deep in the mines of Narikor, the fallen warriors of the Zekarian brood and scheme of a way to escape the halls of Shame and once again take part in the bloodshed of eternal conflict.  The deepest caverns hold an element composed of the essence of warfare.  All of the weapons of Drunder are composed of this essence of war.  Tempered with the powers of Order, you may be able to forge a weapon that can cleave the armor of Zek.  The crystalline essence of Valor will compliment the primal essence of war well.  I know little of the methods of the smiths, but Myrist must certainly hold such knowledge.  Search New Tanaan for your answer mortals.


**You say:** `order`



>**Eriak says:** While the order of the tranquil may be the first to come to your mind, combining the essence of Tranquility with the essence of warfare will prove impossible.  There is another slightly less orderly essence that may prove more malleable.  The children of Marr cling to order with great passion, but they are sometimes prone to the defense of things they hold dear.  You may have better luck with a shard of valor then an aura of tranquility.
end
