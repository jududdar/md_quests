# Forpar Fizfla








## Dialog

**You say:** `hail`



>**Forpar Fizfla says:** Get out you pesky " .. e.other:Race() .. "! I don't need any " .. e.other:Race() .. " germs! Out, ye filthy beast!

**You say:** `mystical instrument`



>**Forpar Fizfla says:** I have made many mystical instruments in the past. Each one seemed to be better then the last. I have always had a dream of building the world's best lute, but I have yet to find someone brave enough to gather the components needed to make the instrument.

**You say:** `components`



>**Forpar Fizfla says:** To make a mystical lute I will first need to make several pieces. If you bring me the backbone of an ancient fishman, a strong tentacle from one of the long lost amalgyms, and a petrified skull of a lycanthrope I may be able to create the head and neck of the instrument. If you go out and gather these things, make sure to bring me the note I gave you or I might forget who you are. I am getting quite old, you know.

**You say:** `next pieces`



>**Forpar Fizfla says:** The next pieces are a little harder to come by than the last set. To make the body of an instrument that will last for ages to come, I need something very special. The scales of a big red dragon and the scales of a big white dragon will make it unbreakable, as well as giving it a unique look. Some metal bits will allow me to hold the body together. Please, if you gather up these things, bring them to me as soon as possible. I have not felt this good in years!

**You say:** `to go`



>**Forpar Fizfla says:** The lute has a head and body. The only thing missing is a set of strings that will never break! I have heard rumors of a living dead poison dragon in the lands of Kunark. If your were somehow able to get your hands on his guts, I could finish the lute. You would have to bring me the head, the body and the undead dragon gut for lute strings!
end

## Turn-Ins



if( **You turn in:** [Note to Forpar Fizfla](/item/20378)) then 


>**Forpar Fizfla says:** So you know Vedico! How is the lass? If Vedico would give you the time of day, you must be something special. What can I do for you? I hope you have not come to have me make another [mystical instrument].


 **You receive:**  [Forpars Note to Himself](/item/20380) 

elseif( **You turn in:** [Forpars Note to Himself](/item/20380), [Kedge Backbone](/item/20524), [Petrified Werewolf Skull](/item/20525), [Amygdalan Tendril](/item/5520)) then 


>**Forpar Fizfla says:** Wow! I didn't think a " .. e.other:Race() .. " like you would be able to gather all of those things. Forpar rambles around and works with small tools for a good ten minutes before handing you a very fine looking lute head. 'Now, do you want to gather the next pieces for me?


 **You receive:**  [Mystical Lute Head](/item/20535) 

elseif( **You turn in:** [White Dragon Scales](/item/11602), [Red Dragon Scales](/item/11622), [Metal Bits](/item/16905)) then 


>**Forpar Fizfla says:** Wooooooo! You are doing a wonderful job, Soandso. I wish I could go out and gather these things myself.' Forpar sits back down at his desk and pulls several very strange looking tools out. Eventually he looks up at you and says, 'The body is done! Only one more piece to go!


 **You receive:**  [Mystical Lute Body](/item/20536) 

elseif( **You turn in:** [Mystical Lute Head](/item/20535), [Mystical Lute Body](/item/20536), [Undead Dragongut Strings](/item/20526)) then 


>**Forpar Fizfla says:**  'Goodness! I can hardly contain myself! This will be my greatest creation ever!' Forpar sits down, slides the lute head into place and screws it together. After a few minutes, he begins to string the lute with the gut strings of the poison dragon. A wonderful sound fills the air as he strums the lute once and hands it to you.'I hope you find a good use for that! I bet you could play it from the mountaintops and the people below would hear you. Thank you, Soandso, for making my lifelong dream come true!'


 **You receive:**  [Mystical Lute](/item/20538) 

**This NPC *should* return incorrect items given.**







