# Will Treewalker
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Will Treewalker says:** Children of the trees, friend and protector of nature. We are brothers and sisters to the wolves and bears. The call of the Great Pine has filled your soul and you have found your way here to be tested. Are you ready to be tested?

**You say:** `ready to be test`



>**Will Treewalker says:** The tests of old are difficult and dangerous, but the rewards for perseverance are great. I hold rewards for three tests. The test of the Wolf, test of the Bear and the test of the Tree.

**You say:** `test of the wolf`



>**Will Treewalker says:** So you wish to take the test of the wolf, do you? Go forth unto the islands and find an azure tessera, black face paint, and a worn leather mask.  Bring them back to me, but not until you have all three, and you shall be rewarded.

**You say:** `test of the bear`



>**Will Treewalker says:** Ah, the test of the bear it is. Find in this plane a copper disc, a nature walker's sky emerald, and a mantle of woven grass. Bring all three at one time to me for your reward.

**You say:** `test of the tree`



>**Will Treewalker says:** The test of the tree is said to be a test of Nature and only those stout of limb and bark will succeed. Bring to me a diaphanous globe, some hardened clay and a spiroc battle staff. Hand them all to me at once and the reward will be yours.
end

## Turn-Ins



if( **You turn in:** [Azure Tessera](/item/20930), [Black Face Paint](/item/20728), [Worn Leather Mask](/item/20729)) then 



>**Will Treewalker says:** Take this mask, nature friend.


 **You receive:**  [Drake-Hide Mask](/item/2706) (+100000 exp)



**Will Treewalker despawns.**

elseif( **You turn in:** [Copper Disc](/item/20936), [Mantle of Woven Grass](/item/20731), [Nature Walker's Sky Emerald](/item/20730)) then 


>**Will Treewalker says:** This mantle will protect you from the winds on your journeys naturewalker.


 **You receive:**  [Nature Walker's Mantle](/item/2705) (+100000 exp)



**Will Treewalker despawns.**

elseif( **You turn in:** [Diaphanous Globe](/item/20943), [Hardened Clay](/item/20732), [Spiroc Battle Staff](/item/20733)) then 


>**Will Treewalker says:** Great work, Soandso.


 **You receive:**  [Shillelagh](/item/6411) (+100000 exp)



**Will Treewalker despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Will Treewalker despawns.**



