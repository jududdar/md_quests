# Shera Banneth
## On NPC Spawn

**Set a timer** named *sit* for 100 seconds
## Dialog

**You say:** `hail`



>**Shera Banneth says:** I dun wanna talk to anyone, go away! Dun ask me [why]!

**You say:** `why`



>**Shera Banneth says:** My you are dense? Well I canna say I dinna expect it from a " .. e.other:Race() .. ". Aren't you afraid you are gonnaup like my [husband]?

**You say:** `husband`



>**Shera Banneth says:** My husband was Suili Banneth.  He was a foul drunk of the worst sorts, never an 'onest day o' work in his life.  Well I found a man worth my time so a lil hemlock in Suili's ale at night an he dinna wake up.  I guess his family was upset aboot tha, so they petitioned ta sen' me 'ere.
end

## Timer(s)

if(e.timer == "sit") then


e.self:SetAppearance(1);


**Set a timer** named *stand* for 2 seconds

elseif(e.timer == "stand") then


**Stop timer** named *stand*


e.self:SetAppearance(0);


**Set a timer** named *sit* for 100 seconds
end