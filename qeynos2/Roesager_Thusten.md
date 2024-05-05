# Roesager Thusten



[Roesager Thusten](/npc/2059) is a level 61 Human GM Paladin that spawns in [North Qeynos](/zone/2).



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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/18970" data-url="18970" class="tooltip-link link">Note to Niclaus</a>


elseif **Faction** >= Indifferent then



>**Roesager Thusten says:** The Temple of Life smiles upon you, friend... but such a delicate matter can only be entrusted to our most loyal members.


else



>**Roesager Thusten says:** Your mere presence disgusts me. Please remove yourself from my sight. Until you change yourself and your ways, you are unwelcome in the Temple of Life.

end



## Turn-Ins



if **Faction** >= Dubious and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18802" data-url="18802" class="tooltip-link link">A Sealed Letter</a>) then 


>**Roesager Thusten says:** Rodcet be praised!! This is what we have been searching for! On behalf of the Temple of Life, let me thank you and offer you this small reward for your aid in our war against the Plaguebringer.


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+50</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+25</span>)


Your faction standing with [Bloodsabers](/faction/221) got worse (<span class='text-danger'>-12</span>)


Your faction standing with [Antonius Bayle](/faction/219) got better (<span class='text-success'>+7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_600.png" alt="" /> <a
                                href="/item/14007" data-url="14007" class="tooltip-link link">Potion of Light Healing</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**
;
