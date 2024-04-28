# Roesager Thusten
## Dialog

**You say:** `hail`



>**Roesager Thusten says:** Hail, Soandso!  My name is Roesager Thusten. Paladin of Life.  I am a loyal servant of the Prime Healer and I seek to destroy all who wish to bring death and disease to the land of Norrath.

**You say:** `prime`



if **Faction** >= Dubious then



>**Roesager Thusten says:** Rodcet Nife is the Prime Healer.  It is He who gives us the power to resist the decay and death that Bertoxxulous has released upon Norrath.  The Temple of Life is dedicated to His honor.


else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `disease`



if **Faction** >= Dubious then



>**Roesager Thusten says:** The Plaguebringers are followers of the disease lord, Bertoxxulous. We  believe a sect of them now operates in Qeynos, be we need proof before we can act.


else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `Bertoxxulous`



if **Faction** >= Dubious then



>**Roesager Thusten says:** Bertoxxulous is a vile creature who rules the Plane of Disease. His filthy followers are spreading their stain across all of Norrath. We fear they are already here in Qeynos.



else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `proof`



if **Faction** >= Dubious then



>**Roesager Thusten says:** Someone reported seeing a Plaguebringer roaming about in the hills near Qeynos. We have long suspected that their dark influence was spreading. I am searching for proof that they are now here in Qeynos.  If you find anything, please bring it to me at the Temple of Life.


else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.


**You say:** `temple of life`



if **Faction** >= Dubious then



>**Roesager Thusten says:** The Temple of Life, dedicated to the glory of the Prime Healer, is in the heart of North Qeynos. Enter the glowing disks above the Pool of Jahnda and you will magically appear inside the temple.


else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.




**You say:** `niclaus`



if **Faction** >= Amiable +100 then



>**Roesager Thusten says:** Niclaus Ressinn? Have you seen him? He is one of our paladins who was sent out to investigate the undead sightings in Qeynos Hills. I have a message from Jahnda for him, but I must continue my own search here in Qeynos. Could you take this to Niclaus? Your help would be appreciated.



**You receive:**  [Note to Niclaus](/item/18970)


elseif **Faction** >= Indifferent then



>**Roesager Thusten says:** The Temple of Life smiles upon you, friend... but such a delicate matter can only be entrusted to our most loyal members.


else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.

end

## Turn-Ins



if **Faction** >= Dubious and  **You turn in:** [A Sealed Letter](/item/18802)


>**Roesager Thusten says:** Rodcet be praised!! This is what we have been searching for! On behalf of the Temple of Life, let me thank you and offer you this small reward for your aid in our war against the Plaguebringer.


* __Faction:__ [Priests of Life](/faction/341) (50)


* __Faction:__ [Knights of Thunder](/faction/280) (15)


* __Faction:__ [Guards of Qeynos](/faction/262) (25)


* __Faction:__ [Bloodsabers](/faction/221) (-12)


* __Faction:__ [Antonius Bayle](/faction/219) (7)


 **You receive:**  [Potion of Light Healing](/item/14007) (+100 exp)

**This NPC *should* return incorrect items given.**
;
