# Wu the Enlightened
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Wu the Enlightened says:** Greetings Warrior of mind and body. To prove your worth to me, you must complete a test. Which test do you wish to take? I will permit you to take the test of Tears, Fists, or Tranquility.

**You say:** `tears`



>**Wu the Enlightened says:** The test of tears involves knowing when to release, and when to provide a shoulder for another. Bring me a Spiroc Statuette, a Spiroc Talon, and a Silken Wrap. I will teach you the way.

**You say:** `fists`



>**Wu the Enlightened says:** A monk must know when to use his or her fists, and when to use ones mind. You must decide in this endevour, which you shall use. Return to me, once you have found them, a pair of Brass Knuckles, a White Spiroc Feather, an Ethereal Amethyst, and a Nebulous Sapphire.

**You say:** `tranquility`



>**Wu the Enlightened says:** Ah, the test of tranquility. Only the tranquil monk can achieve enlightenment. Are you such an individual? Time shall tell. Retrieve these items for me. Bring an aged nectar, a Writ of Quellious, and a Tear of Quellious. Then we shall assess your ability.
end

## Turn-Ins



if( **You turn in:** [Silken Wrap](/item/20800), [Spiroc Statuette](/item/20954), [Spiroc Talon](/item/20799)) then 


>**Wu the Enlightened says:** You have moved closer to enlightenment.


 **You receive:**  [Ton Po's Shoulder Wraps](/item/1283) (+100000 exp)


**Wu the Enlightened despawns.**

elseif( **You turn in:** [Brass Knuckles](/item/20803), [Ethereal Amethyst](/item/20801), [Nebulous Sapphire](/item/20802), [White Spiroc Feather](/item/20960)) then 


>**Wu the Enlightened says:** You have moved closer to enlightenment.


 **You receive:**  [Wu's Fist of Mastery](/item/27715) (+100000 exp)


**Wu the Enlightened despawns.**

elseif( **You turn in:** [Aged Nectar](/item/20967), [Writ of Quellious](/item/20804), [Tear of Quellious](/item/20805)) then 


>**Wu the Enlightened says:** You have moved closer to enlightenment.


 **You receive:**  [Golden Sash of Tranquility](/item/11698) (+100000 exp)


**Wu the Enlightened despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Wu the Enlightened despawns.**




