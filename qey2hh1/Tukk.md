# Tukk
## Dialog

**You say:** `hail`



>**Tukk says:** Great!! I have fifty acres to seed and now I have visitors stopping by to waste my time!!

**You say:** `follower of Karana`



>**Tukk says:** Yes. I am a follower of Karana, the Rainkeeper. It is He who keeps the plains fertile.

**You say:** `blanket`



e.self:Say(string.format("With the frequent rains, I find my only need is a blanket to keep me warm during the long cold nights. Thank Karana the temple has begun to send young %s to deliver extra blankets.",e.other:Class()));

**You say:** `karana bandits`



>**Tukk says:** The Karana bandits are rogues who operate in the plains. I have heard there are bounties for the bandits. Within the Temple of Thunder in Qeynos, Cleric Gehna offers one for bandit spectacles and Paladin Chesgard offers one for bandit sashes.
end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_790.png" alt="" /> <a
                                href="/item/12102" data-url="12102" class="tooltip-link link">Temple Blankets</a>) then


>**Tukk says:** Thank you, protector of Karana. This will be handy when the cold rushes into the valley. Allow me to offer you some provisions for your journey. And, might I add, the [Karana bandits] have begun to operate much closer to Qeynos.


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+5</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+2000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
