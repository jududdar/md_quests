# Ping Fuzzlecutter


## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>**Ping Fuzzlecutter says:** Lucky me! Someone has littered Freeport with good merchandise.




## Dialog

**You say:** `hail`



>**Ping Fuzzlecutter says:** Step right up!  The name's Ping Fuzzlecutter, groomer to the royal crowns of Norrath and alchemist of fine hair care products.  It was I who took the grey out of Felwithe, who added curls to Kaladim and tamed the tangles of Moggok of Oggok.  Step right up and find yourself a new look!  Hey, is that a bald spot?!

**You say:** `coffin`



>**Ping Fuzzlecutter says:** You're looking for a craftsman, are you? Well look no further! For I, Ping Fizzlecutter, am the best in all the lands! Or at lest this side of Freeport. So you're the one that Valeron was talking about, eh? Well, while you were off traipsing around the lands he and I discussed the details of the coffin. I require nothing less than these [components]. Get me them and I will gladly make you a coffin any king would be proud to be buried in!

**You say:** `components`



>**Ping Fuzzlecutter says:** I require a diamond, a star ruby, a pearl, a [special fire emerald], a sapphire, a fire opal, and two enchanted platinum bars. Take this bag and combine the items once you have them all and bring it back to me.





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17512" data-url="17512" class="tooltip-link link">Empty Gem Bag</a>

**You say:** `special fire emerald`



>**Ping Fuzzlecutter says:** Now the fire emerald I want is not the normal one you receive from most jewelers. There is one jeweler I know who has the special one I want. Last time I heard, she had traveled to the elven outpost. Just ask her about special fire emeralds.

**You say:** `repair the toupee`



>**Ping Fuzzlecutter says:** Ah!! You have a toupee to repair. It must be the [Mane Attraction]. I gave a one out and it seems to always fall to pieces. Seeing as it has a 100 season warranty and I only created it 5 seasons ago, I suppose I can do it. Do you want me to [make the Mane Attraction].

**You say:** `what is the mane attraction`



>**Ping Fuzzlecutter says:** The Mane Attraction is a special toupee I created for a Gnome junker. He wasn't getting much attention at the taverns till I created the eye catching toupee. He became one Charismatic Gnome after that. Unfortunately, it seems to fall to pieces to easy and since it has a warranty, I have to fix it for him every time at no charge!! I will never make another. 

**You say:** `make the mane attraction`



>**Ping Fuzzlecutter says:** If you have the original tattered toupee then I can do it. Before you give it to me I will also need three other items. I require two clumps of hair from a Hulking Gorilla and a strand of hair from a [certain mermaid].

**You say:** `certain mermaid`



>**Ping Fuzzlecutter says:** I encountered a particular mermaid with beautiful hair!! She had beautiful golden tresses. I used a lock of her hair to create the Mane Attraction. That was a while back when I was in Faydwer.
end



## Turn-Ins



local text = "You want a Mane Attraction? Not until I get the two clumps of gorilla hair, the tattered toupee and a lock of hair from a certain mermaid.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/6710" data-url="6710" class="tooltip-link link">Full Gem Bag</a>) then 


>*Ping Fuzzlecutter smiles broadly as he rifles through the bag, then looks up at you and says, 'Bout time! Here is the coffin as promised.'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1142.png" alt="" /> <a
                                href="/item/17080" data-url="17080" class="tooltip-link link">Gem Encrusted Casket</a> 

 



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_794.png" alt="" /> <a
                                href="/item/12335" data-url="12335" class="tooltip-link link">A Clump of Gorilla Hair</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_794.png" alt="" /> <a
                                href="/item/12335" data-url="12335" class="tooltip-link link">A Clump of Gorilla Hair</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1001.png" alt="" /> <a
                                href="/item/12338" data-url="12338" class="tooltip-link link">A Lock of Hair</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/12337" data-url="12337" class="tooltip-link link">A Tattered Toupee</a>) then


>**Ping Fuzzlecutter says:** You are a good helper. Here you go. One genuine, charismatic, lady magnet, zero to hero making Mane Attraction!! Guaranteed to lower prices world wide. Guaranteed to last forever.. Err.. Well,.. It has a 1000 year warranty at least.


Your faction standing with [Coalition of Tradefolk](/faction/229) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+5</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got better (<span class='text-success'>+3</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1001.png" alt="" /> <a
                                href="/item/12254" data-url="12254" class="tooltip-link link">Mane Attraction</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**



