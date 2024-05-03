# Lily Ashwood


## Dialog

**You say:** `hail`



>**Lily Ashwood says:** Hello there, Soandso. You wouldn't by chance happen to be a ranger, would you?'

**You say:** `ranger`



>**Lily Ashwood says:** I sure love a strong ranger. Especially Ganelorn Oast. He's so dreamy and handsome. I think one day he's going to ask me to marry him.


**Signaled to:**  [Devin Ashwood](/npc/54085)

**You say:** `take him the letter`



if(**Your level** >= 50) then



>*Lily Ashwood smiles sweetly. 'Thank you sooo much.' *



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/20876" data-url="20876" class="tooltip-link link">A love letter (Sealed)</a>


else



**Lily Ashwood says one of the following:**

>Someone with your skills is more suited to beetle slaying.  Run along, now.

>This matter is far too advanced for you to handle.  Come back after you've killed a few more large rats.

>It's much safer for you to spend time fishing than on a dangerous issue like this.

>I think I saw a gnoll pup you could probably defeat, a few miles back.

end



## Signals

if(e.signal == 1) then


>*Lily Ashwood sulks*

elseif(e.signal == 2) then


>*Lily Ashwood laughs. 'In your dreams, little brother.' *

elseif(e.signal == 3) then


>**Lily Ashwood says:** Oh! If you're going to see him, would you please take this letter to him? I trust you, since you're a ranger and all
end

