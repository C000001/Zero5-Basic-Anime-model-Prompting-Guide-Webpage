We have another prompt from the MeinaMix gallery:

>[!success] Positive Prompt:
>(best quality), ((masterpiece)), (highres), extremely detailed girl, solo, sharp focus, ((((((flower shop)))))), ((cinematic lighting)), (((character(((1 girl)))))), solo, (((beautiful plain pink t shirt))), pants, standing, light smile, closed mouth, (((((sharp focus))))), (((((masterpiece illustration))))), ((((medium shot)))), shiny hair, short hair, blonde hair, curly hair, hair between eyes, beautiful detailed eyes, blue eyes, jewel-like eyes, diamond-shaped pupils, large breasts, animal ears, beautiful detailed jewel leather collar, backpack, black legwear,
<p>Broken up:</p>

>[!success] Positive Prompt:
><font color=EDED96>Boilerplate</font> (best quality), ((masterpiece)), (highres), extremely detailed girl, solo, 
><font color=EDED96>Camera</font> sharp focus,
><font color=EDED96>Background</font> ((((((flower shop)))))), 
><font color=EDED96>Lightning</font> ((cinematic lighting)), 
><font color=EDED96>Character</font> (((character(((1 girl)))))), solo, (((beautiful plain pink t shirt))), pants, standing, light smile, closed mouth,
><font color=EDED96>Camera</font> (((((sharp focus))))), 
><font color=EDED96>Boilerplate</font> (((((masterpiece illustration))))), 
><font color=EDED96>Camera</font> ((((medium shot)))), 
><font color=EDED96>Character</font> shiny hair, short hair, blonde hair, curly hair, hair between eyes, beautiful detailed eyes, blue eyes, jewel-like eyes, diamond-shaped pupils, large breasts, animal ears, beautiful detailed jewel leather collar, backpack, black legwear,

Oof that's kinda all over the place. The person still got a good picture, but I do wonder how many bad pictures it also generated. Especially with this many colour prompts, which have a tendency of [[1.3 Token bleed and Token fighting|bleeding]]... 
<p>Let's clean it up a little. </p>
>[!success] Positive Prompt:
><font color=EDED96>Character</font> solo, (((character(((1 girl)))))), solo, (((beautiful plain pink t shirt))), pants, standing, light smile, closed mouth, shiny hair, short hair, blonde hair, curly hair, hair between eyes, beautiful detailed eyes, blue eyes, jewel-like eyes, diamond-shaped pupils, large breasts, animal ears, beautiful detailed jewel leather collar, backpack, black legwear,
><font color=EDED96>Background</font> ((((((flower shop)))))), 
><font color=EDED96>Camera</font> sharp focus, (((((sharp focus))))), ((((medium shot)))), 
><font color=EDED96>Lightning</font> ((cinematic lighting)),
><font color=EDED96>Boilerplate</font> (((((masterpiece illustration))))), (best quality), ((masterpiece)), (highres), extremely detailed girl,
<p>We can already see a lot of repetitive tags again. Also, the bracket usage is quite hard to adjust. We will detail why and what to do instead in the bracket section. For now, let's just keep it as is.
</p> 
<p>Let's look at the generations again :3</p> 
<p>First, the old prompt:</p>

<a href="https://cdn.discordapp.com/attachments/1017817227245924432/1092429599616540762/grid-0016-3933055293.png">link to pic</a>
<img src="https://lh4.googleusercontent.com/1A6IED6O6OKRi8o6QX12OS9PwYeArzEGi_NDFfSvc3u7i2Gqk09XKfB3__3aENeutAGA6QtgI5Ma1ulgZIq0fx-clQmDQE3Nhg9bW2ujTEQNMx4-VXkW8IYkQlpgoO_XIXRmMijYMOYol3RW">
<p>Now, the adjusted prompt:
</p>
<a href="https://cdn.discordapp.com/attachments/1017817227245924432/1092429617970827345/grid-0017-3933055293.png">link to pic </a>
<img src="https://lh4.googleusercontent.com/WyU24TdIFzdnT52KWWnGHEIacd1cwj276zcaGEKbQO7WI70qKPVvGZI6mD0JYCEYVsIhfuJ2bL8XRmqJ3leK3IKT6nALr0WSE4I_uTTLujWZ9od3hkasXT0RmAk60-4vfd8ADYnENQokpLjY">
<p>
Overall, our adjusted prompt respects <font color=EDED96>cinematic lightning</font> a lot more. The mouth is also <font color=EDED96>consistently closed</font>. The hair style is relatively consistent, but for some reason ours is <font color=EDED96>completely missing</font> the "beautiful detailed jeweled collar". I'm not sure why, but it might be too far to the back for it to properly add. The other prompts might also steal too much attention from this token. To fix this, I would move both the backpack and the jewelry accessory to the front, and I would adjust the <a href="INSERTLINKHERE">weights</a> appropiately. </p>
Next: [[Example 4 - Girl Fights Dragon]]