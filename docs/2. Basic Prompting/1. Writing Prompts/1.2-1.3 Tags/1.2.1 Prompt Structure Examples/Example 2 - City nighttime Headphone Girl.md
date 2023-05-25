
We have this prompt from a picture on the MeinaMix gallery:

>[!success] Positive Prompt: 
(extremely detailed CG unity 8k wallpaper, masterpiece, best quality, ultra-detailed, best shadow), beautiful detailed glow, cowboy shot, cinematic lighting, 1girl, (beautiful detailed face, beautiful detailed eyes), Mischievous eyes, blue eyes, happy expression, full lips, black pink jacket, hood jacket, (white shirt),  shorts, legs, (wear headphone:1.4), knee-high socks, normal breast, pink hair, shoulder-length hair, hair cover ears, short hair, dynamic pose, lithe form, five fingers, cinematic, proper fingers, city background

<p>This is hard to read. First, we are going to add paragraphs and group it. </p>
>[!success] Positive Prompt:
><font color=EDED96> Boilerplate</font> (extremely detailed CG unity 8k wallpaper, masterpiece, best quality, ultra-detailed, best shadow),<br>
><font color=EDED96>Lightning</font> beautiful detailed glow,<br> 
><font color=EDED96>Camera</font> cowboy shot, <br>
><font color=EDED96>Lightning</font> cinematic lighting, <br>
><font color=EDED96>Character </font> 1girl, (beautiful detailed face, beautiful detailed eyes), Mischievous eyes, blue eyes, happy expression, full lips, black pink jacket, hood jacket, (white shirt),  shorts, legs, (wear headphone:1.4), knee-high socks, normal breast, pink hair, shoulder-length hair, hair cover ears, short hair, <br>
><font color=EDED96>Pose</font> dynamic pose,<br> 
><font color=EDED96>Character</font> lithe form, five fingers,<br> 
><font color=EDED96>Lightning</font> cinematic, <br>
><font color=EDED96>Character</font> proper fingers, <br>
><font color=EDED96>Background</font> city background <br>

Notice how the layers are all over the place? 

Let's try grouping it using my format above. 
>[!success] Positive Prompt:
><font color=EDED96>Character</font> 1girl, (beautiful detailed face, beautiful detailed eyes), Mischievous eyes, blue eyes, happy expression, full lips, black pink jacket, hood jacket, (white shirt),  shorts, legs, (wear headphone:1.4), knee-high socks, normal breast, pink hair, shoulder-length hair, hair cover ears, short hair, lithe form, five fingers, proper fingers, <br>
><font color=EDED96>Pose</font> dynamic pose, <br>
><font color=EDED96>Background</font> city background,<br>
><font color=EDED96>Camera</font> cowboy shot, <br>
><font color=EDED96>Lightning</font> beautiful detailed glow, cinematic lighting, cinematic,><br> 
><font color=EDED96>Boilerplate</font> (extremely detailed CG unity 8k wallpaper, masterpiece, best quality, ultra-detailed, best shadow)<br> <br>

This is much more understandable! The model can understand this better, and so do we! We didn't even fix the tags yet! We'll tackle that in the tags section. 

Let us actually analyze what the changes did, using the same seed:

Prompt from user of the site:

<a href="https://cdn.discordapp.com/attachments/1017817227245924432/1092429059801227384/grid-0013-1118555960.png">link to pic</a>
<img src="https://lh6.googleusercontent.com/IGiQjshs_9fsCDwGmaIiAdVSSSQ4btJl8MD5LJxRsdVMstHCv9xgPeSNtrPpp487SdnxhCh47zQoaxzREcV_zX0Ujb75ryqIqh8h2ErRPpHGWUNtIDsQzuuakAaLwSMZJsRZHagN_yNfJD-w">

Adjusted prompt order:

<a href="https://cdn.discordapp.com/attachments/1092187641706987540/1092195789624836238/grid-0014-3933055293.png">link to pic</a> 
<br>
<img src="https://lh3.googleusercontent.com/LcsCpAd1aFRFx1z9Ucas3oMuEB44loBRtpRhMGi1KkO5qdvj1U2AGJ5KKeKG2XtarVi5YCAPYGg9IJAgGqBK4U0trOdUhGj6vgDAoIuPXI5Qunpi9k8_j0HS04UR9kHLHok7AVidgJiAdmkD">

>[!note] Note:
>If you have troubles comparing these, open the links, and swap between the tabs (Firefox: Ctrl + Up / Down arrow). Concentrate on one picture at a time.

Comparison:
<ul>
<li> Some values, like the <font color=EDED96>white shirt</font>, are more represented in our generations compared to theirs. 
<li> The expression itself looks a bit more doll-like (which can be because of the CG token), which we didn't really specify in both prompts. 
<li> The <font color=EDED96>"hair covers ears"</font> prompt was not respected by any generation. 
<li> I'd say that our generations look a bit more cinematic, but honestly there is only a minor improvement; <font color=EDED96>but if you create a batch of a hundred pictures</font>, our prompt will make a number of them closer to the prompt. 
</ul>
Next: [[Example 3 - Flower shop girl]]