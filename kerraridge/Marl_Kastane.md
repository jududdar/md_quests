# Marl Kastane


## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);



**You say:** `Hail`



>**Marl Kastane says:** Begone!! You do not have the will to do the things I require!

**You say:** `will of Innoruuk`



>**Marl Kastane says:** You speak of a myth, friend. Such an object does not exist in this age and the secret of its creation lies locked in my mind, where it shall stay. It has been passed down through generations in my line, not to be revealed to a soul until the prophecy has come to pass.

**You say:** `prophecy`



if **Faction** >= Apprehensive +23 and qglobals["Marl"] ~= nil) then



>**Marl Kastane says:** I suppose it is time for the secret to be shared. Ages ago, two brothers were born. Glohnor was highly favored by the pompous Lightbringer, whose name we do not utter. Lhranc was chosen by the Prince of Hate to bring destruction and turmoil to the sons of men. The one thing they shared in common was their love of the fair priestess, Kyrenna. Kyrenna fell deeply in love with Glohnor. When Lhranc discovered this, he was overcome with rage and unwisely attacked his brother, who happened to be far more adept in combat. The fight cost Lhranc dearly. He lost his dignity as well as an eye in the struggle. He was ordered to leave Freeport and live his life in exile from the only home he had ever known.


elseif **Faction** >= Apprehensive +17 then



>**Marl Kastane says:** My apologies, Soandso, I have said too much already. Instead, I have an errand to occupy your thoughts. Take this as proof that you are sent from me and find my brother in Paineel. I haven't spoken with him in some time now and his well being is essential to our family's destiny.



**You receive:**  [Seal of Kastane](/item/14375)


**You say:** `Lhranc`



if **Faction** >= Apprehensive +23 then



>**Marl Kastane says:** Lhranc wandered the deserts of Ro for weeks, sinking deeper into depression and giving in to rage. Reports from the local merchants and caravans had him roaming the dunes muttering to himself incoherently. Eventually, he was forgotten, blending in with the hermits and madmen common to that region, forgotten by all save one.


**You say:** `one`



if **Faction** >= Apprehensive +23 then



>**Marl Kastane says:** Innoruuk had not forsaken Lhranc. Once his rage and hate had matured and sufficiently altered his soul, the dark prince summoned him and gave him dominion over the demons that had enslaved his mind. He was given a weapon that made him powerful enough to slay any enemy that stood in his way. He was to become the first human to harness the power of the almighty shadowknight. After years of traveling and teaching mankind his newfound abilities, Lhranc sneaked back into Freeport through a series of sewers in search of revenge against his brother and in hopes of kidnapping Kyrenna, the source of his obsession. Waiting until Glohnor was alone, Lhranc sprang from the shadows and slew his brother. This was the act that brought about his curse.


**You say:** `curse`



if **Faction** >= Apprehensive +23 then



>**Marl Kastane says:** As I said, Glohnor was highly favored by the Lightbringer. When the contemptible god of honor discovered what had been done, he transformed Lhranc into a deformed spectral knight and placed him in the ruined city. Lhranc then used what remained of his power to summon Kyrenna to his side and bind her there in a timeless, seamless sphere. He struggled for centuries to break her will and convince her to serve Innoruuk, certain that together they could remove his curse. But then, there was the prediction.


**You say:** `prediction`



if **Faction** >= Apprehensive +23 then



>**Marl Kastane says:** The prophecy states that one day Kyrenna will escape the clutches of Lhranc and that she will resurrect Glohnor. Together, it reads, they will destroy Lhranc and undo all he has done. I trust that I do not need to tell you, Soandso, that this would decimate our foothold in Norrath. When the prophecy was written, its words spread across the land. A dark council was held to construct a plan that would frustrate the words of the prophets. My ancestors were responsible for robbing Glohnor's tomb and securing his remains. For generations we have been charged with the duty of guarding those remains and the secret plan, should the corpse be discovered.


**You say:** `secret plan`



if **Faction** >= Apprehensive +23 then



>**Marl Kastane says:** The plan is a last resort only to be tried if Kyrenna indeed escapes and the remains are discovered. Judging by my brother's words that time is now. It will take the most powerful hero all the courage and dedication he can muster to complete the ritual.


**You say:** `complete the ritual`



if **Faction** >= Apprehensive +23 then



>**Marl Kastane says:** It would seem we have no choice, and this is our only hope. I must first make a dark shroud. To do this I must stain it with the blood of an innocent. Go find me this rare blood so I can start the creating of the shroud.

end

## Turn-Ins




if( **You turn in:** [Note to Marl](/item/14376)) then


>*Marl Kastane reads the note, eyes widening in panic. He raises his eyes to you and says, 'This is grave news, friend. If the prophecy is allowed to be fulfilled, our strength will vanish into obscurity. Goodness and purity will spread like a plague across the land and the servants of Hate will be powerless to stop it!'*


* __Faction:__ [Truespirit](/faction/404) (3)


eq.set_global("Marl","1",1,"F");

elseif( **You turn in:** [Blood of Kyrenna](/item/14381)) then


>**Marl Kastane says:** Here, you take this shroud. You must now find the spirit of glohnor and place this item on him. This should force him back into his mummified body and then you must destroy this newly raised form and return to me its wrappings.


* __Faction:__ [Truespirit](/faction/404) (5)


 **You receive:**  [Dark Shroud](/item/14377) 


eq.delete_global("Marl");


**Marl Kastane despawns.**

elseif **Faction** >= Apprehensive +28 then


if( **You turn in:** [Glohnor wrappings](/item/14379)) then



>**Marl Kastane says:** You've done it! Your efforts will stand as a tribute to our kind for time eternal, my friend. Although nothing could possibly serve as a just reward for your accomplishments, please accept this as well as my eternal gratitude. It has been fashioned from the wraps of the mummy and shall protect you well.



* __Faction:__ [Truespirit](/faction/404) (5)



 **You receive:**  [Will of Innoruuk](/item/14370) 


**This NPC *should* return incorrect items given.**
