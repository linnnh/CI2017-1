# Assignment 9

- [x] 1. Complete all assignments that you have not submitted yet. This Sunday 11:59pm is the hard deadline for all assignments in this class, including this one.

- [x] 2. Modify your embedded chatbot from Assignment 8 to understand and speak a language different from English.

- [x] 2.1 ASR: find line 
      recognition.lang = "en-US";

in verbal.js and edit it for another supported language code. [Here is a list of supported languages as of 4 years ago](http://stackoverflow.com/a/14302134), more languages might be supported now.

- [x] 2.2. TTS:
      Find some non-English voices from the list of TTS voices that is printed in the console log (As described in Assignment 8). Make your character speak in that non-English voice. 

- [x] 2.3 Dialogue:

Modify your FSM logic (regular expressions) in verbal.js to match the user_said variable when it returns the language you have chosen (different from English). It make help to print user_said variable into console.log() so that you can see what google ASR returns for that language.

![demo.gif](https://github.com/linnnes/CI2017/blob/master/hw9/demo.gif)

- [x] 3. Earlier we have learned about expressing emotions and personality via a conversational agent. Another dimension that humans tend to perceive and express is cultural background. 

[Read this paper from our Stanford neighbors Heidy Maldonado and Barabar Hayes-Roth.](https://hci.stanford.edu/publications/2004/CrossCultBelievability0304/CrossCultBelievability0304.pdf)

Have a short write up answering the following questions:
1. What is "culture"?
2. Why is it useful to express culture?
3. How can an agent express culture?
4. Many of you have characters that are not human-like (a cat, a burger, etc.) Would you consider them expressing some culture? If yes, why and how would you do that. If no, then why not?

---

Assignment 9 deliverables:
- GitHub directory hw9 with your code for a non-english embodied chatbot
- A text file inside the same directory that answers questions 1-4 in part 3 of this assignment.




