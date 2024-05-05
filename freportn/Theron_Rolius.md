# Theron Rolius



[Theron Rolius](/npc/8075) is a level 61 Human GM Paladin that spawns in [North Freeport](/zone/8).



## Dialog

**You say:** `hail`



>**Theron Rolius says:** Greetings, Soandso!  To enter these grounds is to proclaim your faith in the Truthbringer.  In this city you shall find no greater allies than the Knights of Truth.  We urge all knights and clerics who oppose the hand of the Freeport Militia to [join the crusade].

**You say:** `join the crusade`



>**Theron Rolius says:** Then take arms against the Freeport Militia!  They serve no one save Sir Lucan, the fallen knight.  From this day forth, I put a bounty upon all militia members.  For every bashed milita helm, a reward!!  If you are not prepared to battle the militia just yet, you may [assist in other areas].

**You say:** `assist in other areas`



>**Theron Rolius says:** I have need of one such as you.  I have been awaiting a message. I will need a young acolyte to [retrieve the message] for me or there are also some [fishing duties] I wish to delegate.

**You say:** `retrieve the message`



if **Faction** >= Amiable then



>**Theron Rolius says:** Thank you, Soandso. Venture to the Commonlands.  There, by a lake, will be a courier from the great city of Qeynos.  Tell him you are from the Hall of Truth.  He will have a message for you to deliver to Eestyana Naestra.


elseif **Faction** >= Indifferent then



>**Theron Rolius says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Theron Rolius says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `fishing duties`



>**Theron Rolius says:** I have been creating shields for the crusade.  Right now I work on the sharkskin shield for the knights.  I require two shark skins. Unfortunately, most sharks are too dangerous for the squires.  I have begun using [reef shark] skins.  Will you hunt the [reef sharks]?

**You say:** `reef shark`



>**Theron Rolius says:** Reef sharks are the smallest and most docile of the sharks.  Even a young acolyte can slay one.  I have heard there are some in the Ocean of Tears.  I need a young acolyte to [hunt] reef sharks.  I require their skins.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/17937" data-url="17937" class="tooltip-link link">Empty Shark Sack</a>

**You say:** `hunt`



>**Theron Rolius says:** I thought I spied the shoulders of a swimmer upon you! Take this large sack. Travel to the Ocean of Tears. There are numerous reef sharks there. I shall require no fewer than two shark skins. When the full sack is combined and returned to me, I shall reward you.

**You say:** `heal`



>**Theron Rolius says:** If you require the binding of wounds you should speak with Palious Jartan in the temple. He will be glad to help you.



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/13921" data-url="13921" class="tooltip-link link">Damaged Militia Helm</a>) then


>**Theron Rolius says:** Fantastic work, my young knight.  Here is a small token of the my appreciation.  I would offer you a sharkskin shield, but I have made only a few and the paladins are testing them.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+25</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+5</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** 0 (+1000 exp)

**You receive coin:** 3 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/13873" data-url="13873" class="tooltip-link link">Sack of Sharkskins</a>) then


>**Theron Rolius says:** Thanks for the hard work, here is a shield to help you in your duties.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+25</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-3</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+5</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_759.png" alt="" /> <a
                                href="/item/13868" data-url="13868" class="tooltip-link link">Sharkskin Shield</a> (+500 exp)

 

**This NPC *should* return incorrect items given.**
;

