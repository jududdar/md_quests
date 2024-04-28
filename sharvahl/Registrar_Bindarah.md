# Registrar Bindarah







## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);







**You say:** `certificate`



>**Registrar Bindarah says:** Luckily for you, someone found this blowing around the plaza.


**You receive:**  [Certificate of Taxability](/item/2874)

**You say:** `note`



>**Registrar Bindarah says:** Luckily for you, someone found this stuck in a bush.


**You receive:**  [Note to King Raja](/item/18299)

**You say:** `application`



>**Registrar Bindarah says:** Luckily for you, someone found this on the floor in the bakery.


**You receive:**  [Notarized Application](/item/2897)

**You say:** `acrylia slate`






**You receive:**  [Acrylia Slate of Shar Vahl](/item/2877)
end

## Turn-Ins



local text = "This item, by itself, means nothing to me.";





if **You turn in:** [Application for Citizenship](/item/2873)


>**Registrar Bindarah says:** Young Soandso, I will be happy to process your registration for you. While I etch your name on our people's book of records I will require you to run a couple of errands. Take this certificate to the tax collector and obtain his seal. While you're out doing that, have Mignah create your personal Acrylia slate for you. Bring both the seal and the slate to me as soon as you can.


eq.set_global("Shar_Vahl_Cit","2",5,"F");


 **You receive:**  [Certificate of Taxability](/item/2874) (+300 exp)

elseif **You turn in:** [Stamped Certificate of Taxability](/item/2875), [Acrylia Slate](/item/2876)


>**Registrar Bindarah says:** Ahh, there you are. I was about to send someone looking for you. Everything seems to be in order here, only one task remains. You must gain audience with the king and swear fealty to his highness by handing him this document. Return to me when this is done.


eq.set_global("Shar_Vahl_Cit","4",5,"F");


 **You receive:**  [Note to King Raja](/item/18299) (+300 exp)

elseif **You turn in:** [Note from King Raja](/item/18304)


>**Registrar Bindarah says:** Well done, Soandso, I am honored to be the first to welcome you to citizenship of Shar Vahl! May you serve our society as well as it serves you. Return to your guildmaster and present both the slate and the application to him. The acrylia slate shall henceforth serve as proof of your citizenship.


eq.set_global("Shar_Vahl_Cit","6",5,"F");


>**Registrar Bindarah says:** Oh, by the way, be careful with this as it will be important for recording your service to our society. If you should somehow lose it, ask me about your slate and I will issue you a new one.


* __Faction:__ [Citizens of Shar Vahl](/faction/1584) (400)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
