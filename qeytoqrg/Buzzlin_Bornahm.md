# Buzzlin Bornahm


## Dialog

**You say:** `hail`



if( **Faction is** > Apprehensive) then



>**Buzzlin Bornahm says:** Ahoy there, swabby! This here side of the world sure is beautiful, ain't it?


else



**Buzzlin Bornahm says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 6) then


e.self:SetRunning(true);

elseif(e.wp == 4 or e.wp == 7) then


e.self:SetRunning(false);
end
