Lastly, from the MeinaMix gallery: A girl fights a dragon.

>[!success] Positive Prompt
(best quality) (masterpiece), 1girl, solo, epic battle, fire magic, dragon, smoke, flames, sparks, flying debris, intense action, dramatic lighting, dark sky, determination, concentration, wizard hat, robe, staff, fierce expression, powerful stance, adrenaline, magic aura, claws, scales, fire breath, danger, fear, bravery, victory, five fingers, silver hair

<p> First step: Break it up</p>
>[!success] Positive Prompt
><font color=EDED96>Boilerplate</font> (best quality) (masterpiece),
><font color=EDED96>character1/boilerplate</font> 1girl, solo, 
><font color=EDED96>General Description</font> epic battle,
><font color=EDED96>Character1? Forget about the model, even I am confused who this should apply to.</font> fire magic, 
><font color=EDED96>Character 2</font> dragon
><font color=EDED96>Background</font> smoke, flames, sparks, flying debris,
><font color=EDED96>Mood/Style</font> intense action, 
><font color=EDED96>Lightning</font> dramatic lighting, dark sky,
><font color=EDED96>Character1???</font> determination, concentration,
><font color=EDED96>Character1</font> wizard hat, robe, staff, fierce expression, powerful stance, adrenaline, magic aura, 
><font color=EDED96>Character2</font> claws, scales, fire breath, 
><font color=EDED96>Character1</font> danger, fear, bravery, victory, five fingers, silver hair
<p>Now we rearrange it:</p>
>[!success] Positive Prompt
><font color=EDED96>General Description\*</font> epic battle, 1girl fights dragon, fire magic, 
><font color=EDED96>Character1</font> 1girl, solo, wizard hat, robe, staff, five fingers, silver hair, fierce expression, powerful stance, adrenaline, magic aura, determination, concentration, victory, danger, fear, bravery, 
><font color=EDED96>Character2</font> dragon, claws, scales, fire breath,
><font color=EDED96>Style/Mood</font> intense action, 
><font color=EDED96>Background</font> smoke, flames, sparks, flying debris,
><font color=EDED96>Lightning</font> dramatic lighting, dark sky, 
><font color=EDED96>Metadata</font> (best quality) (masterpiece), 

>[!note] Multiple characters are hard. 
><p>They are an entire section in the <a href"INSERTLINKHERE">Intermediate Guide</a>. I added one prompt, "1girl fights dragon", to generally describe the scene. Otherwise, it would say "1girl, dragon, epic battle" and I think that's too confusing for the machine.  <p>

Mood and emotion certainly can belong to style. More details when we go down to individual tagging. Here, I already anticipated it to be harder to execute, so I pushed it more to the front. 

<p>I also did some light intermediate prompting for two characters, resulting in this:</p>
>[!success] Positive Prompt
><font color=EDED96>General Description\*</font> epic battle, 1girl fights dragon, fire magic, BREAK,
><font color=EDED96>Character1</font> 1girl, solo, wizard hat, robe, staff, five fingers, silver hair, fierce expression, powerful stance, adrenaline, magic aura, determination, concentration, victory, danger, fear, bravery, BREAK, 
><font color=EDED96>Character2</font> dragon, claws, scales, fire breath, BREAK,
><font color=EDED96>Style/Mood</font> intense action, 
><font color=EDED96>Background</font> smoke, flames, sparks, flying debris,
><font color=EDED96>Lightning</font> dramatic lighting, dark sky, 
><font color=EDED96>Metadata</font> (best quality) (masterpiece), 

<p>Essentially, I added a few BREAK tags to make sure that Character 1 and Character 2 are processed at different times by the model. I will go more in depth on the BREAK command in the <a href="">Intermediate Guide</a>. For now, just know that it makes character 2 more consistent. </p>
<p>Let's look at some pictures :D</p>
<p>Original:</p>
<a href="https://cdn.discordapp.com/attachments/1017817227245924432/1092430328766922752/grid-0018-3933055293.png">link to pic</a>
<img src="https://lh4.googleusercontent.com/Oetw1mmSQxBJfgCzK2ZiMo71ZHMJtiOpDceZfORqAovSeLh2SWZA-_vJKqYDYK8PTsufb7O8-IOzziKceiCZKmmy-CI83kb3UhZVqQlF4GL65wNKEzX0GKzIR9TZifDJj22zWRY5jXBFlWy2">
<p>Adjusted:</p>
<a href="https://cdn.discordapp.com/attachments/1017817227245924432/1092430406986502255/grid-0019-3933055293.png"> link to pic</a> <img src="https://lh6.googleusercontent.com/hePGi0rz_7ilGRsQ2gQLiQO-kDflpwyZivufeDPxXxrmRaKdAUKz7jBLEV5OCTfudYtVPKesZcHOMhEU8s3ycUEV7efi0iOE2qSSABFsuv--uAB8nhCLQxmoc7rJnzwKt1srEKZAlxSWWNAN">
<p>Adjusted with BREAK:
</p>
<a href="https://cdn.discordapp.com/attachments/1017817227245924432/1092430455233597531/grid-0021-3933055293.png">  link to pic </a>
<img src="https://lh5.googleusercontent.com/f2xO80Sga5G_8QGQkXnkRNFiP6LaZc3nDNopp4x4bB7Cc5eIF3wnFInL2g0mF94aifClAmldUc1lmQkHUT0D9xhvnSwL3flXuduvbD7dkFq9UDCcobHGn7TmBWZJTUamc7TOO7D5ZFqDQDWf">
<p>Our adjustments made the "wizard hat" consistently appear. The staff does look better, but that might be more chance than good prompting (weapons, on a non-specialized model or LoRA, are typically hard.) There are more flames, and they look a lot more blazing. Because of the staff, using fire magic with hands is a lot less prevelant. Instead, we see random, staff-like streaks of flames cross the picture. In none of the pictures did the dragon breathe fire. (Might require better tagging / prompting or more images). </p>
<p>The pictures that we made using BREAK have distinctly more dramatic lightning, and a higher chance of there being one dragon. The dragon and the wizard are not necessarily fighting each other (likely caused by inprecise general prompt) but at least the dragon appears more consistently. In none of them does the character look like they won the fight. There also is no fire aura. "victory" as a prompt might just be too ambiguous. </p>
 Overall we noticed these changes:<br>
<ul>
<li> A higher chance that each tag in the prompt is represented
<li> A higher impact of tags than before <br>
And, most importantly:
<li> Much easier to read for humans.
</ul>
If you are trying to edit or improve a prompt, it helps if you only need to pay to one line instead of trying to look everywhere what you already have added and what is still missing. 


In this section, we dealt with how to structure your prompt. In the next section, we will talk about which tags to use and which ones not. 

Next: [[1.2.2 Individual Tags]]
