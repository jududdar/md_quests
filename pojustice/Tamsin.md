# Tamsin



[Tamsin](/npc/201401) is a level 46 Gnome Necromancer that spawns in [Plane of Justice](/zone/201).








## Dialog

if(e.language == 8 and e.other:GetLanguageSkill(8) >= 100) then


**You say:** `Hail`




e.self:Say("Hail to thee, Soandso.  Sit with me, if ye please.  Were it only that I could offer ye a little more in the way of hospitality.  Tell me a little of Ak'anon, of my dear home; does it [prosper]?",8);


**You say:** `prosper`




e.self:Say("How could it be otherwise?'  A light smile crosses her graceful features.  You perceive a sadness in her eyes.  'I cannot imagine how long I have been here...  here, locked away from the one that I [love], away from my dearest heart.'",8);


**You say:** `love`




e.self:Say("The famous bard Aebriolle spake it best, when he said 'the course of true love never did run smooth'.  So it is, but in my heart I shall carry my [devotion].",8);


**You say:** `devotion`




e.self:Say("In my adolescence, I was flighty; 'tis a most common phenomena I know, but mine led me to the desire for power.  I was so afraid...  afraid of seeing the deaths of friends, my uncle...   death became my enemy.  The Eldrith Collective gave me free reign in my studies, and it was then that my need to overcome my fear of my life'stook me into the works of Shadow.  Foolish, perhaps.  Ye would not be the first to call me such, but a destiny is a destiny, as inevitable as the tides of the sea.  The [Dark Reflection] took me in.'  Her beautiful eyes meet your own with a steady gaze.",8);


**You say:** `Dark Reflection`




e.self:Say("It pains me to hear their name spoken by another, but they took me in and treated me well.  They guided my studies, and showed me...'  A shadow passes between the two of you, and is gone.  'They showed me how to conquer death itself. The Dark Books I studied and, by the time womanhood was upon me, I was a mistress of death, able to command and direct the forces of the afterworlds.  Dark powers there are, Soandso.  Dark powers that course through the ether and the bones of the earth upon which we stand.'  She reaches into her slender, silken robe and produces a locket.  'Curious indeed that even death itself was conquered with love, when my love I did [meet].'",8);


**You say:** `meet`




e.self:Say("My studies, always my life had been my studies.  When searching the woods near to Ak'anon for blackroot, I met my love.  My love, all dressed in traveling garb and radiant as the sun; as like to me as white to black, as life to death itself.  Do ye believe in love at first sight, Soandso?  It takes your heart in its clasp and makes your soul its own, more binding than any ritual of raising or invocation of the dead.  Such was my love: nature walker, protector of the forest, servant of the Rainkeeper.  The effect upon my existence was that of a hurricane to a dandelion...  I was carried away and my [previous life] forgotten.",8);


**You say:** `previous life`




e.self:Say("There is a space in thy life carved by thy actions, and that space can be filled by nothing but thy own destiny.  So it was with me.'  Her expression becomes distant, her delicate lips becoming set and resolute.  'The Dark Reflection had looked for me since my disappearance, since I flew from them so long ago hand-in-hand with the one that had taken my heart.  The Scryer had found me, and whilst we were sleeping under the stars, took me by force.  I was returned to the Reflection in Ak'anon, where upon they did decree my [trial].",8);


**You say:** `trial`




e.self:Say("For my turning from the path of the Dark Studies, for betrayal of their code and the oath I had taken to them in my hasty youth, they were to put me to death.  A woman should be strong in her hour of utmost dread, should she not?  As was I, defiant to the last.  My old tutor, Evazan, could not bear to see such anto his best pupil.  He entreated the Dark Reflection's Provost for mercy on my part, for trial fair.  So, with heart unburdened, I find myself here.  Awaiting my .",8);


elseif(e.message:findi()) then



e.self:Say("Cry not for me, Soandso.  I have lived and I have loved.  In this I am blessed.  I harbour no illusions that my time draws to an but my heart is [glad].",8);


**You say:** `glad`




e.self:Say("Glad, and free.  In the next world I shall meet my Love again, and unfettered by those who would stand between us.'  Her eyes dance with an inner fire, and she smiles as if to comfort you.",8);


else


>*Tamsin 'does not appear to understand you.'*
end
