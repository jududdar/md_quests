# Grum



[Grum](/npc/201327) is a level 46 Ogre Warrior that spawns in [Plane of Justice](/zone/201).








## Dialog

if(e.language == 7 and e.other:GetLanguageSkill(7) >= 100) then


**You say:** `Hail`




e.self:Say("Huh?'  He lifts his head and looks at you with a blank expression.  'Whoz you?  Mez not expectin visitors.  Mez in [trouble].",7);


**You say:** `trouble`




e.self:Say("Ya, trouble big.  Real big dis time.  Stupid Grum, wez been told to guard some little shorty by da big man in da black robe.  Grum had to watch her during da night while the others went to make sure dat the humeyz been scared off.  But da shorty, she wuz so perdee.  So perdee...  When da otherz come back, dey found Grum.  Grum all alone with a flower behind his ear and big smilin all over.  Mez alwayz been stupid for da perdee ones.'  He looks down at something that he holds in his lap, and you notice it is a small, wilting daisy.",7);


else


>*Grum 'does not appear to understand you.'*
end