# Instructor Mussin



[Instructor Mussin](/npc/155127) is a level 50 Vah Shir Warrior that spawns in [The City of Shar Vahl](/zone/155).

local count;


## On NPC Spawn

count = 0;

**Set a timer** named *training* for 10 seconds


## Timer(s)

count = count + 1;

if(count == 1) then


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


>**Instructor Mussin says:** There are several routes available to you as a citizen of Shar Vahl. All citizens are expected to actively participate in the maintenance of our security.

if(count==2) then


>**Instructor Mussin says:** If you have a professional preference, please feel free to explore that area. You are just here to learn the basics of combat and survival.

if(count==3) then


>**Instructor Mussin says:** You'll learn soon enough. There are more than a few dangers beyond these walls. Combat is far from pleasant, but never something to fear. Vah watches over us all.

if(count==4) then


>**Instructor Mussin says:** All right students, before we hand you a set of practice weapons and allow you to unleash your youthful fury on each other, I will run through a series of attacks with you. Proper form is very important and can be attained through both armed and unarmed practice.

if(count==5) then


>**Instructor Mussin says:** You may want to watch this demonstration carefully, because I am going to see how well you paid attention in a few moments. I'd rather find out that you are unable to think and move at the same time now... rather than after one of those grunts down in the pit cracks your furry little skull open. Eyes on me, Recruits!

if(count==6) then


>**Instructor Mussin says:** This first move is a simple kick. If you are planning on becoming a Khala Dun or Khati Sha, you'd better get familiar with this move. The kick complements any series of attacks and can come in quite handy as a means of knocking an enemy off their guard or distracting them for a moment.


e.self:DoAnim(1); 

if(count==7) then


>**Instructor Mussin says:** The bash is another standard Khala Dun Technique. You will need to use your center of balance and leverage to exert as much force into your enemy as possible. The weight of your body bashing into the enemy will usually leave them off balance and dazed for a few moments. That time should be more than enough for you to stage a secondary attack.


e.self:DoAnim(7); 

if(count==8) then


>**Instructor Mussin says:** Next, the Taruun stab technique! This move isn't just for our shadow stalking citizens. Almost everyone should keep this move well practiced and ready!


e.self:DoAnim(2); 

if(count==9) then


>**Instructor Mussin says:** This move works if you are using a staff, spear, or some other form of polearm. You can disable your enemy, by quickly thrusting your weapon into their abdomen. It usually takes the wind right out of them.


e.self:DoAnim(4); 

if(count==10) then


>**Instructor Mussin says:** The two-handed overhead slash! Your enemy's skull will never be the same after the successful completion of this move! Be warned this technique is much slower than many of the others available to you and can leave you open to swift counter attacks.


e.self:DoAnim(3); 

if(count==11) then


>**Instructor Mussin says:** The single-handed overhead swing is a common maneuver and should be practiced to perfection. Watch the way I distribute my weight and move my upper body. You should keep your head up and your eyes focused during every swing. Even with a simple move such as this.


e.self:DoAnim(5); 

if(count==12) then


>**Instructor Mussin says:** Okay, now go over those moves for a moment and prepare to show me what you have learned.


**Set a timer** named *training* for 30 seconds

if(count==13) then


>**Instructor Mussin says:** Please stand and prepare to demonstrate the attacks as I call them out. I understand that your form will be a little sloppy, but that is what practice is for. Will will keep practicing these moves until you can show me that you can be trusted to not injure yourselves with the wooden practice weapons.


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


**Set a timer** named *training* for 5 seconds

if(count==14) then


>**Instructor Mussin says:** First move... the Kick! Attack!


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


e.self:DoAnim(51); 

if(count==15) then


>**Instructor Mussin says:** Now... the Bash! Attack!


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


e.self:DoAnim(51); 

if(count==16) then


>**Instructor Mussin says:** Next... the One-handed Stab! Attack!


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


e.self:DoAnim(51); 

if(count==17) then


>**Instructor Mussin says:** Arlight... Two-handed thrust! Attack!


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


e.self:DoAnim(51); 

if(count==18) then


>**Instructor Mussin says:** Now... smash with both hands! Attack!


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


e.self:DoAnim(51); 

if(count==19) then


>**Instructor Mussin says:** Okay...the One-handed swing! Attack!


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


e.self:DoAnim(51); 

if(count==20) then


>**Instructor Mussin says:** Go ahead and take a seat. As a whole you looked very good. Take a break and we will get ready to go through it again.


**Signaled to:** 155310


**Signaled to:** 155309


**Signaled to:** 155308


**Set a timer** named *training* for 90 seconds

if(count==21) then


count = 0;


**Set a timer** named *training* for 10 seconds
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





