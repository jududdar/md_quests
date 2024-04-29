# Wenglawks Kkeak
## Dialog

**You say:** `hail`



>**Wenglawks Kkeak says:** Greetings, Soandso, I have heard of you. My name is Wenglawks Kkeak. Welcome to my humble home. My sources tell me you are a [mercenary]. Is this true?

**You say:** `mercenary`



>**Wenglawks Kkeak says:** Well then, I suppose you might be [looking] for work. Are you?

**You say:** `looking`



>**Wenglawks Kkeak says:** I have been looking for a few good people to deliver goods for me. I have several [deliveries] to clients which must be made soon. My last delivery person ended up dead, unfortunately.

**You say:** `deliveries`



>**Wenglawks Kkeak says:** I have three clients whose orders must be taken care of. These will not be simple deliveries. I want you not only to deliver the items but to assist them if they need help using their packages. Do you wish to hear of the first task I have for you?

**You say:** `first task`



>**Wenglawks Kkeak says:** One of my clients lives on the shores of the Iceclad Ocean. His name is Sojan. Supposedly he is some kind of pirate from the other lands. However, I could not care less what he calls himself. He paid me well to acquire him a set of Coldain tools and they were not easy to come by. Are you willing to take this [package] to Sonjan?

**You say:** `deliver good`






>**Wenglawks Kkeak says:** Wonderful, Soandso. Take this note to Kellek and he will give you the tools.


**You receive:**  [Voucher for Toolset](/item/25279)

**You say:** `undertake`






>**Wenglawks Kkeak says:** In the great divide there is a small outpost of kromrif. In that outpost you will find Bekerak, my client. I have acquired this new hunting spear for him and he may wish to test it out. Because of one simple mistake, once in my past, he thinks all of my wares are shoddy. I need the payment for the transaction still so don't let him get away without giving it to you. Take this voucher to Kellek and he will give you the spear.


**You receive:**  [Voucher for Spear](/item/25280)

**You say:** `third client`






>**Wenglawks Kkeak says:** Are you sure you will be up to this journey? It will take a hardened person to survive the trip. Let alone find my client. Do you really [want to go] out into the dangerous lands in the west?

**You say:** `want to go`






>**Wenglawks Kkeak says:** I'm not sure if I can [trust] you with this. If you die on the trip, I will be losing profit! The other deliveries were much simpler, I remind you. Can I really [trust] you as far as I can throw you? Wait, that's a bad example - I could probably throw you quite far.

**You say:** `trust`






>**Wenglawks Kkeak says:** I will curse your immortal soul if you fail, Soandso. In the depths of the icy waters of the cobalt scar lives an outcast siren who preys upon her own kind. We have a deal, I will provide her with an excellent hunting net and she will provide me with a giant cloak made of the scales of her kind. Take this voucher to Kellek and deliver the net. Do whatever it takes to get my cloak.


**You receive:**  [Voucher for Mechanical Net](/item/25281)
end

## Turn-Ins





if( **You turn in:** [Message to Wenglawks](/item/28600),platinum = 200) then





>**Wenglawks Kkeak says:** Here is the information your employer requested. Now be gone. I have more business to take care of.


 **You receive:**  [Message to Herald](/item/28601) 

elseif( **You turn in:** [Receipt](/item/20474)) then 


>**Wenglawks Kkeak says:** I assume the delivery went well? You can have these as payment. One of my customers just decided he does not wish to buy them. They are rather sturdy! I do have another task available if you wish to [undertake] it.


 **You receive:**  [Engraved Bone Pauldrons](/item/25062) (+1000 exp)

elseif( **You turn in:** [Giant Icewurm Talisman](/item/25130)) then 


>**Wenglawks Kkeak says:** He has reconsidered the offer, you say? This is most excellent! I hope this will be acceptable payment for your troubles, Soandso. My cash situation is not the best at this point in time. I do have a [third client] who needs delivery...


 **You receive:**  [Bracer of Midnight](/item/25061) (+1500 exp)

elseif( **You turn in:** [Giant Siren Scale Cloak](/item/25110)) then 


>**Wenglawks Kkeak says:** It is truly a sight to behold. This is the most fashionable cloak I have yet to see. Even King Tormax will be green with envy. This old bag has served me well, I hope you find it to your liking.


 **You receive:**  [Wenglawks Manly Purse](/item/17049) (+2000 exp)

elseif( **You turn in:** [Helssen's Voucher](/item/1722)) then 


>**Wenglawks Kkeak says:** So you are the mercenary I have been hearing about! Not what I expected. Anyway, here is your reward. Carry it well. Also, this noble's seal will prove your loyalty to anyone who is skeptical.


 **You receive:**  [Girdle of Reflection](/item/1719) (+2000 exp)


 **You receive:**  [Noble's Seal](/item/1723) 

elseif( **You turn in:** [Note to Wenglawks](/item/29068), platinum = 100) then


>**Wenglawks Kkeak says:** Here is the information your employer requested. Now be gone. I have more business to take care of.


 **You receive:**  [Dispelling device](/item/29626) 

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 23) then


if(**spawned NPC:**  [Graggaz Fleshflayer](/npc/113066) or **spawned NPC:** 113166 or **spawned NPC:**  [Wevek Redforge](/npc/113065)) then



**Zone Wide Emote:** <span class="text-warning">*Wenglawks Kkeak says 'Well well, how is business going today gentlemen?'*</span>



**Zone Wide Emote:** <span class="text-warning">*Graggaz Fleshflayer says 'You're not wanted around here, Wenglawks. Go back to your bar and count your ill gotten gains.'*</span>



**Zone Wide Emote:** <span class="text-warning">*Kevelak Whitefang says 'I hope Bvellos finds out what you've been up to.  Your head would look nice on a pike in front of Dragon Death Keep.'*</span>



**Zone Wide Emote:** <span class="text-warning">*Wevek Redforge says 'What is it you want, Wenglawks?  We're honest merchants around here.'*</span>



elseif(e.wp == 24) then


if(**spawned NPC:**  [Graggaz Fleshflayer](/npc/113066) or **spawned NPC:**  [Wevek Redforge](/npc/113065)) then



**Zone Wide Emote:** <span class="text-warning">*Wenglawks Kkeak says 'Hold your tongues fools.  How dare you accuse me of such things when I come here simply to extend an offer to you.  If you are not interested in a proposition I am sure I can find someone else...'*</span>



**Zone Wide Emote:** <span class="text-warning">*Graggaz Fleshflayer says 'Watch what you say, Wevek.  You mightup with a knife in your back if you don't deal with this knave.'*</span>



**Zone Wide Emote:** <span class="text-warning">*Wevek Redforge says 'I'm not interested in any of your 'deals.'  I won'tup face down with a knife in my back like your delivery man...'*</span>


elseif(e.wp == 25) then


if(**spawned NPC:**  [Wevek Redforge](/npc/113065)) then



**Zone Wide Emote:** <span class="text-warning">*Wenglawks Kkeak says 'Very well then. I see you are all fools. Enjoy trading with the outlanders while you can.  My business will continue to thrive long after they are gone.'*</span>



**Zone Wide Emote:** <span class="text-warning">*Wevek Redforge says 'Your days are numbered, Wenglawks.  Enjoy them while you can.  Rallos Zek does not smile upon traitors.'*</span>

end