# Cipse Tospyr
## Dialog

**You say:** `hail`



>**Cipse Tospyr says:** Hello, Soandso. I welcome you to the Temple of Divine Light. I am the resident healer. If you should ever require the power of Quellious to [bind wounds], [cure disease] or [cure poison], speak with me and I shall help you.

**You say:** `bind wounds`



>**Cipse Tospyr says:** I shall be pleased to help you with your wounds. The Temple of Divine Light requires a tribute of four gold before I may perform the service.

**You say:** `cure disease`



>**Cipse Tospyr says:** Your malady will be nothing more than a memory, but before that can be, we ask that a donation of two gold coins be offered.

**You say:** `cure poison`



>**Cipse Tospyr says:** You must pay the tribute of three gold before I cast the toxin from your body.
end

## Turn-Ins




if **You turn in:** gold = 4


**Cipse Tospyr casts:** [Healing](/spell/12) on target.

elseif **You turn in:** gold = 3


**Cipse Tospyr casts:** [Cure Poison](/spell/203) on target.

elseif **You turn in:** gold = 2


**Cipse Tospyr casts:** [Cure Disease](/spell/213) on target.

**This NPC *should* return incorrect items given.**
;  
