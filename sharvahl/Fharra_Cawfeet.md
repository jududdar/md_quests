# Fharra Cawfeet
## Dialog

**You say:** `Hail`



>*Fharra Cawfeet appears to be on the verge of collapsing from exhaustion. 'Please leave this area.  These citizens are very ill.' She says as she rubs her eyes.*

**You say:** `told`



>**Fharra Cawfeet says:** I was called to this house a few days ago, because several members of a recent scouting group have been running slight fevers. The fever is nothing that should alarm you but we will need to tend to them. Tending to the sick is one of our duties as Dar Khura. Would you be [willing] to run some errands for me? I cannot leave these scouts unattended.

**You say:** `willing`



>**Fharra Cawfeet says:** I need you to make a tonic to help aleviate their fevers. Please head into the cavern system just beyond the thicket. Gather the hearts of muck diggers that roam those caverns. Their hearts seem to regulate the temperature of their body and can be used in potions and tonics to control temperature in a similar fashion. Brew two of those hearts with a flask of water and it should produce the tonic I need. Please, fill a blackened clay jar with tonic. Try to make it back before I fall over from exhaustion.
end

## Turn-Ins



if( **You turn in:** [Treated Hopperhide Buckler](/item/3495)) then


>*Fharra Cawfeet looks like she has been awake for many hours. She looks up and says 'Are you here to assist me with these sick citizens? I was told that a few of our newest Dar Khura recruits might be coming to aid me. I could definitly use the help. Here, take the jar while I explain. Were you told about the [tasks] that I need help with?' The room is filled with the smell of aromatic herbs and the sweat of the feverish.*


 **You receive:** GiveAll( [Treated Hopperhide Buckler](/item/3495), [Blackened Clay Jar](/item/17077)) 

elseif( **You turn in:** [Jar of Tonic](/item/5536)) then


>*Fharra Cawfeet perks up when you hand her the jar. 'Many thanks,' she exclaims, as she digs in her medicine bag. 'Your assistance is greatly appreciated. Please take this tincture. It will help to strength your buckler. Mydi Darjik can help you apply it. She is a friend and a wonderful alchemist. Tell her that you need her to treat your buckler. Take care, friend!'*


 **You receive:**  [Strong Smelling Tincture](/item/5537) 

**This NPC *should* return incorrect items given.**
