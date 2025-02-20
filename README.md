# Enhancing AI Non-Playable Characters Project using Environmental Awareness and LLM's (Python-Based)

### Project Description
  This project showcases the early stages of research in including environmental factors to LLM queries in Retrieval Augemented Generation (RAG) to improve AI-Based NPC's. At this stage I've reworked and made Akshit Ireddy's work more concise by only focusing on the Screen Capture feature. This means that the dialogue produced by the AI NPC's are able to take into account day/night within the game and speak in context to their surroundings, like normal people would! At this stage however, it is limited to only working on Genshin Impact, and in particular the environment capture is limited to the time of day.

### Challenges and Ideas for the Future
  I found it quite challenging at first as it was my first time using many of the technlogies present (including but not limited to: coding in python, utilising the RAG technique, and incorporating the Cohere LLM API) however, I believe that this was a very useful opportunity to learn and improve my skillset. In particular I believe I struggled with conceptually understanding how to go from learning about the RAG technique to having it in my own code. Akshit Ireddy's work here was incredibly valuable and allowed me to make a connection between what I had learnt and what I needed to do, and as such let me incorporate it into my own work. 

  Additionally when I first began working on his repository, I faced many issues with mismatching dependencies, mainly because the project was about a year old and many updates and changes had occured to varying libraries. As such, learning to change and update dependencies and track how to correctly manage them was a new task for me, requiring a lot of python library documentation reading! 

  In the future I would have enjoyed continuing to develop this project feature so that it can work for more games besides Genshin Impact (which it is currently configured towards). Additionally I would like to work on adding more environmental aspects outside of the time of day, such as weather or location as well. 

## Motivation
  In particular I enjoy working on game-based projects but this was a creative opportunity for me to learn about incorporating AI and LLM's, in particular Cohere and grow my skills. As such I was motivated and also highly incentivised to continue to work on this project.
  
## Reasoning for Building this Project
  I built this project as part of my university coursework! More specifically, my goal was to research into existing methods for incorporating AI methods and LLM's into video games, and more specifically in RPG games. From my brief research I found that although many games have begun utilising AI in their games it is not as commonly known and not as well represented in RPG games, hence a missing gap in research in this field that could be explored.  
  
## Gaps in Field Addressed
  My goal for this project was to improve or add functionality to Akshit Ireddy's project [Interactive-LLM-Powered-NPCs](https://github.com/AkshitIreddy/Interactive-LLM-Powered-NPCs). 
  In particular I was able to show room for development in adding environmental awareness to RPG games, and more specifically the AI NPC's. For more information on the data I collected and how I performed my experiment for this project feel free to reach out to me at sonirohan05@gmail.com :))

## Learning Accomplished
  Some of the biggest things I learnt about were how to look at and understand python documentation and read and understand another persons code. This was particularly important for this project as there were many aspects of this code that I had little to no experience with so learning how to understand the large concepts that the project was overlooking, the importance of comments, and a lot of python basics.
  
## Set-up and Download
To set up this project:
1. Clone the repository:
   ```sh
   git clone https://github.com/Enhance_AI_NPCs.git
2. Install dependencies: 
   pip install -r requirements.txt
and then simply make sure you have Genshin Impact open in the background, and a second monitor connected to enable the screen capture feature. Upon running the main file, the screen capture will open upon which you can select the game screen and then ask away in the terminal to talk to the NPC!! Enjoy :)
