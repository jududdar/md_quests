# Lord Searfire
## Dialog

**You say:** `hail`



>**Lord Searfire says:** Greetings!  May the glory of Solusek Ro burn in your veins.  I am the forge master of this temple.  Called to service by the Burning Prince.  Should you ever need my service and find me gone. have no fear. I shall return.  I must occasionally venture to other realms in service of the temple.  I shall always return. this is my eternal home.

**You say:** `ronium`



>**Lord Searfire says:** You seek ronium.  It is a fine blend of metals.  I alone hold the secret of its formula.  I, and I alone, can offer it to those who serve this temple.  Do you wish a [bar of the alloy]?

**You say:** `armor.* ro`



>**Lord Searfire says:** So you wish to know more of the Armor of Ro?  We have kept it's secret for a long time.  It can only be worn by paladins of high esteem.  They must be crafted by the one who wears it.  Ro wishes his mighty paladins to also be adept in blacksmithing.  They may take to the forge, a mold of the Ro Armor and a bar of the alloy [Ronium].  Then you may forge the armor of Ro.

**You say:** `bar of the alloy`



if **Faction** >= Amiable then   



>**Lord Searfire says:** Take this Sol Cauldron.  Within it shall be combined elements of this world.  You will add to it, melatite, two bars of enchanted platinum, Mistmoore granite, the sands of Ro and soil of Underfoot.  If you be a master blacksmith, the elements shall combine to make the enchanted metal I have named 'ronium.'



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1017.png" alt="" /> <a
                                href="/item/17977" data-url="17977" class="tooltip-link link">Sol Cauldron</a>


elseif **Faction** >= Indifferent then



>**Lord Searfire says:** There is much service to Ro which you must perform.  I cannot trust you until you have proven your worth to us.  Seek service within this temple or join the crusade within the desert of Ro.


else



**Lord Searfire says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

end
