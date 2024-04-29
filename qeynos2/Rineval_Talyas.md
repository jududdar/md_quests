# Rineval Talyas
## Dialog

**You say:** `hail`



>**Rineval Talyas says:** Hello, Soandso.

**You say:** `scribe`



>*Rineval Talyas looks at Soandso strangely. 'Who told you this?'*

**You say:** `told me`



>**Rineval Talyas says:** 'I see. If a scribe is what you seek, then bring me the torn books of fire and ice. A donation of 1000 platinum is needed as well. The donation will be offered as a blessing to the gods.
end

## Turn-Ins



local text = "This is not enough. Leave my sight at once!";


if( **You turn in:** [Torn, burnt book](/item/19071), [Torn, Frost covered book](/item/19070), platinum = 1000) then


>**Rineval Talyas says:** Take this book quickly and tell no one about this.


 **You receive:**  [Book of Scale](/item/18302) (+25000 exp)

**This NPC *should* return incorrect items given.**
