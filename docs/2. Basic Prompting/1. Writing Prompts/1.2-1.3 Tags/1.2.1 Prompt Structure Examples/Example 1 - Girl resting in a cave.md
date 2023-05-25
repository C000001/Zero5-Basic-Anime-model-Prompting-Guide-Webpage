As an example, instead of: 

>[!success] Positive Prompt
>1girl, blue cave, dim light, comfortable, lying down, smile, crystal, deep eyes, 

Do:

>[!success] Positive Prompt
>1girl, lying down, smile, deep eyes, 
>blue cave, crystal, dim light, comfortable, 
  
The model might still execute badly. As an example, the blue from the blue cave can bleed into the girl's dress or something like that. Preventing bleed is more detailed in the <a href="INSERTLINKHERE"> Intermediate Guide</a>.<br>
However, the good prompt is still a lot less confusing to the model. 

### Here's how the model processes the prompt:   <p>In the bad prompt, the model goes through the prompt, and on the 8th token knows the overall composition. By that time, the structures for 1girl, blue cave, dim light, and comfortable were already processed. It then is told that there is a crystal, and that the girl is smiling. Almost every token affects a different area. </p><p>In the good prompt, the model goes through the prompt, and on the third token prepares its structures for lying down. That is the composition roughly that it will go for. It then adds details to the girl first, then to the background. The tags affecting the same area apply at roughly the same time. </p>
Next: [[Example 2 - City nighttime Headphone Girl]]
