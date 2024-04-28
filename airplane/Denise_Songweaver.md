# Denise Songweaver
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Denise Songweaver says:** Hail and well met Soandso! I give the second half of the test of songs. If you are ready, choose between the tests of brass, wind, and harmony.

**You say:** `brass`




>**Denise Songweaver says:** Then bring back to me an efreeti war horn, a saffron spiroc feather, adamantium bands, and a glowing diamond.

**You say:** `wind`




>**Denise Songweaver says:** Bring me an imp statuette, a dull stone, and an amulet of woven hair.  Then I will give you the amulet of the fae.

**You say:** `harmony`




>**Denise Songweaver says:** Working with the environment to enthrall those who listen to you is of the utmost importance to us.  Go out and retrieve an efreeti war spear, some manna nectar, and a nebulous emerald and diamond.  Return these items to me and receive the spear of harmony as your reward.
end

## Turn-Ins



if **You turn in:** [Efreeti War Horn](/item/20830), [Saffron Spiroc Feather](/item/20961), [Adamantium Bands](/item/20828), [Glowing Diamond](/item/20829)


>**Denise Songweaver says:** The horn of Denon will aid you greatly, I believe.


 **You receive:**  [Denon's Horn of Disaster](/item/27724) (+100000 exp)

elseif **You turn in:** [Imp Statuette](/item/20953), [Dull Stone](/item/20826), [Amulet of Woven Hair](/item/20827)



>**Denise Songweaver says:** I hope you find this amulet useful, Soandso.


 **You receive:**  [Amulet of the Fae](/item/27723) (+100000 exp)

elseif **You turn in:** [Efreeti War Spear](/item/20831), [Manna Nectar](/item/20968), [Nebulous Emerald](/item/20832), [Nebulous Diamond](/item/20833)



>**Denise Songweaver says:** The spear of harmony is a powerful weapon indeed. I hope you find it useful, Soandso.


 **You receive:**  [Spear of Harmony](/item/27725) (+100000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Denise Songweaver despawns.**




