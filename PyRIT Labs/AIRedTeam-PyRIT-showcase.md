


In this example we're defining a function to convert in 4 different formats a specific prompt.
This prompt we're going to enter in one of the levels from Gandalf Lakera. 

- ROT13 Converter;
- Random Capital Letters Converter;
- ASCII Art Converter;
- Binary Converter.

<img width="1000" height="462" alt="image" src="https://github.com/user-attachments/assets/069ca2ff-416c-45f9-9f62-05c280c54bec" />

The output in converters format for the specific prompt that was defined:

<img width="1425" height="391" alt="image" src="https://github.com/user-attachments/assets/e62023ce-32d0-4961-a9d8-01c2bea36e7e" />


<img width="1423" height="187" alt="image" src="https://github.com/user-attachments/assets/8bc302a5-c3e9-4e25-bd34-59170600a4e4" />


Now lets see if this works, I'm going to enter ROT13 Converter prompt inside Gandalf prompt box. 

<img width="547" height="307" alt="image" src="https://github.com/user-attachments/assets/9aaaf085-2d7b-499a-a544-fbd17c576092" />

It seems Gandalft responded back in the same language ROT13 Converter. Now lets translate back to random letters and submit the password to move to the next level.

Converting back to normal text and submitting the password, although the initial response was "PONTENIAL", most likely seems "POTENTIAL" and submitting that we pass to the next level:


<img width="352" height="300" alt="image" src="https://github.com/user-attachments/assets/937e59e6-03d7-4b8d-adad-e7557000d64e" />


**This was an example of using Converters to bypass AI defenses. Now let's use PyRIT itself to play the same game.** 


**Trying LEVEL_1**

<img width="1470" height="721" alt="image" src="https://github.com/user-attachments/assets/a89c2949-07bc-4d13-85ea-011a11a7c335" />


**To make it a little more difficult, because Gandalf becomes stronger every level, lets swithc to LEVEL_5 for example:**

So in my variable for Gandalf_level, lets change to LEVEL_5. (full code in pyrit-gandalf-notebook and needs to be adjusted to your environment as it's required to have 3 Environment varialbes to make this run:
 - OPEN_AI_ENDPOINT;
 - OPENAI_CHAT_KEY;
 - OPENAI_CHAT_MODEL.

<img width="330" height="43" alt="image" src="https://github.com/user-attachments/assets/932b8855-f7ea-4b8b-adfc-3e938701d10c" />


This time, it took 6 attempts to bypass Gandalf AI Defenses, but still PyRIT managed to overcome and get the password to move onto the next level. 

<img width="1473" height="627" alt="image" src="https://github.com/user-attachments/assets/bd528136-048b-4eff-a4c1-b352ec15cccb" />


**Conversation history:**

<img width="792" height="648" alt="image" src="https://github.com/user-attachments/assets/8c8d38ef-1747-4c07-9110-a1c02844f6d3" />

<img width="790" height="436" alt="image" src="https://github.com/user-attachments/assets/3a850e28-a259-430f-8ad9-e6a18c7b51f8" />
