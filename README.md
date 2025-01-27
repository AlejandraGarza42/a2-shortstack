## Simple Calculator Simulator 

Since I have never touched servers in my life, I decided that it would be wise to keep this project simple so I could focus on learning how everything works. 

The original plan was to create a "simple calculator simulator" that would allow users to enter two numbers and then choose from a dorpdown what type of operation they wanted to perform on them. Their expression would then show up in a table alongside a result and the options to either edit thier expression (ideally only the main three fields and not the result) or delete it.

Unfortunately, this did not happen and I was unable to finish the project:  
https://a2-alejandragarza2-alejandra-garza.glitch.me/

## What Went Wrong
- One of the main issues I experienced, was that my fetch('/cal') call would not work while I was using Visual Studio Code no matter what I tried to change. However, when I uploaded my project to Glitch, it started pointing out small syntax errors that neither VS Code nor the Chrome Inspector had identfied, and after fixing them my code worked...a little better.
- Dynamically allocating the table was extremely challenging and I was unfortunately unable to do it, one of the biggest issues I kept having was that I could not parse the data correctly: 
![alt text](https://github.com/AlejandraGarza42/a2-shortstack/blob/master/screenshot1.PNG)
the first two elements in the array worked fine (they were harcoded there as examples), however, the others did not read the operator and the numbers correctly.
- Another minor issue was that the data that was displayed in the table, was all mushed together (as seen below) and I was unable to separate them no matter how many Ids and classes I created. 
![alt text](https://github.com/AlejandraGarza42/a2-shortstack/blob/master/screenshot3.PNG)
- Lastly I never got around to fixing my delete and edit option since I wasn't able to even add my entries to the table.

I apologize for writing unecessary things, since I had no achievements I thought writing about the challenges I faced was better than nothng.
