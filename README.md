# The Real "Clueless" Closet - CluelessCloset
My project creates a Clueless-like waredrobe interface that combines the trend-spotting prowess of social media with the personalized insight of GPT technology to create a digital wardrobe assistant. This platform will tailor outfit suggestions to individual preferences and daily requirements bringing a touch of surrealism to fashion visualization, offering a unique, adaptive, and interactive style experience.

Project Notes:

- Please remember to keep your repo private when you create it from this template.
- Be sure to create your report in the **intro-gen-ai** organization. 
- The name of the repo should be the name of the project, or a shortened version of the name.
- Each section should be completed by the deadline indicated. You submit by making a commit of this README.md file. Except for minor edits, please do no change the Proposal, Goals, or Metrics sections after the submission deadline.
- General guidance on formatting writing in markdown files (like this README.md file) is at https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax.
- There is a [recording of the the class discussion on the use of this template](https://vanderbilt.zoom.us/rec/share/RjihScz0Ti7RId0KMj7GWBc8XueS571_JnFqDQwli0AuKLsgaau0j_RcphBjwYtV.HP10ROf2TwPUn6TA?startTime=1697553005000).
- You can sign up for a time to discuss your ideas for the project at https://calendly.com/jesse-spencer-smith. We'll also be discussing project in class on Tuesday after Fall Break.
- Remember that there is an AI Showcase on April 19 (with prizes for Best in Show), so you might want to consider completing your project by then. 

## Project PI/Project Team 
**Due March 21, 11:59pm**

Sara Gomez, sara.m.gomez@vanderbilt.edu, gomezsm, PI

## Project Proposal 
**Due March 21, 11:59pm**

300-1000 words total across all of the sections below

### Description of Problem/Opportunity

Ever since watching the movie "Clueless" as a middle school girl, I have dreamed of having a closet like the one shown in the movie. Alicia Silverstone's character, Cher, is able to generate outfit ideas from the click of a button on a display - the application pairs a handful of items from her closet to give the perfect 90s look. With applications like Pintrest, Tik Tok, and other social apps that utilize a personalized algorithm, we are very close to Cher's closet, however these platforms are often difficult to successfully navigate. In my experience, I often feel as though my crafted algortims are successful at providing things I like, but I struggle to transfer these items into tangible outfits. Using a GPT bot, I want to help users navigate ongoing trends and create my own closet display that can suggest timely and fashionable looks to the user at a highly personalized level. The bot would serve the role of suggesting a daily outfit for the given utility, also accounting for feedback and preference patterns to better match the personal style of the user. 

### Proposed Solution/Approach

My project aims to craft a digital waredrobe interface that merges the convience of social platforms that display trends with the much more nuanced understanding and personalization functionality of GPT technology. It will allow user to more successfully navigate the online trend space. The bot will use images on these social platforms as the information and image source, as well as user-inputted preferential information to shape daily suggestions. Some considerations I want to include are the weather, utility, and trend preference. I also plan to encorporate algorithm understanding to naturally cater to the style of the user with increased use of the GPT. The user will be able to upload images of trends they like, and then everyday they will be able to prompt the bot based on the weather and daily plan. The bot will then suggest a look based on the understanding of the user preferences, and general trends. 

**Some key features I plan to include:**
-> Personalized Fashion Guidance: Tailored to the user's preferences, and relevant daily info provided
-> Dali Image Production: I want to leverage the Dali image generation functionality to provide outfit suggestions; want to emphasize color matching schemes here
-> Adaptive Preference Tracking: I want to create a ongoing database (of sorts) that is produced by the bot and then used by the bot to further fine tune suggestions; this will also be helpful for metric tracking


### Project Outline and Timeline
What are the steps to complete the project? State your milestones and the dates you want to complete them. 

Initial Planning (5 days): Identify key user needs through market research and analysis of exisiting solutions (I want to see if there are comparable applications / existing structures & how they are implementing solutions). Delinate CluelessCloset's primary features, and define specific functionality.

Data Collection and Algorithm Development (1 week): Gather data on color schemes (what actually makes a color match), current trends, clothing appropiate for different climates and utilities - I want to create my own data base of what I will consider to be a successful suggestion. Develop algorithms for uploading images to ChatGPT and how the bot will utilize user information to shape suggestions (want to explore the possibility of creating user profiles). 

Bot Development (2 weeks): Implement the user-friendly chatbot interface and integrate the personalization algorithms as well as the gathered data that will be shaping suggestions. 

Testing and Refinement (2 weeks): Conduct user testing with a diverse group (want to emphasize different use cases here) to collect feedback on usability and effectiveness. Refine the bot based on this feedback.

Launch and Iteration (At Project Deadline): Launch CluelessCloset. Ongoing useability and interactions will be primarily based on the effectiveness of the bot. Depending on time and success, will hopefully be able to monitor user interactions, and continuously update the bot's functionalities and utilized data based on this feedback.

## Goals of project 
**Due March 21, 11:59pm**

Describe 1-5 goals of the project. 
### Goal 1
Dali Image Generation - I want to utilize this functionality to help users visualize the outfit suggestions.

### Goal 2
Feedback tracking - I want the user to be able to provide suggestion feedback that will move to a type of database and further fine-tune suggestions. 

### Goal 3
Personalized suggestions - especially during the testing stage, I want to see different suggestions for each of the different use cases. If the bot is aimed at helping users navigate the online trend space, this needs to be a personalized experience based on their preferences. 

## Project Metrics 
**Due March 21, 11:59pm**

Compose 2-5 metrics to determine the success of the project. These should be measureable, and should translate to a letter grade for each. 
### Metric 1
Ability of the bot to suggest user-specific looks

A - When prompted with a similar utility and weather, the bot provides unique suggestions for 90%+ tested cases. 
B - When prompted with a similar utility and weather, the bot provides unique suggestions for 80%+ tested cases. 
C - When prompted with a similar utility and weather, the bot provides unique suggestions for 70%+ tested cases. 
D - When prompted with a similar utility and weather, the bot only provides unique suggestions for about half of the tested cases. 


### Metric 2
Ability of the bot to suggest outfits that are consistient with current trends and follow general match schemes - will be refering to created database / rubric for this evaluation

A - The bot provides suggestions that include at least one modern trend and follow understood matching scheme in 90%+ tested cases. 
B - The bot provides suggestions that include at least one modern trend and follow understood matching scheme in 80%+ tested cases. 
C - The bot provides suggestions that include at least one modern trend and follow understood matching scheme in 70%+ tested cases. 
D - The bot provides suggestions that include at least one modern trend and follow understood matching scheme in only about half of the tested cases. 


### Metric 3
Ability of the bot to self-monitor based on user feedback, coupled with the ability of the bot to produce feedback database 

A - The bot is able to monitor user feedback and when prompted with the same prompt, the bot provides a different suggestion post-feedback in 90% of cases. 
B - The bot is able to monitor user feedback and when prompted with the same prompt, the bot provides a different suggestion post-feedback in 80% of cases. 
C - The bot is able to monitor user feedback and when prompted with the same prompt, the bot provides a different suggestion post-feedback in 70% of cases. 
D - The bot is able to monitor user feedback and when prompted with the same prompt, the bot provides a different suggestion post-feedback in only about half of cases. 

### Other goals to consider (binary, not scaled) 
Ability to utilize Dali Image Generation 
Ability to create monitor user profiles 

## Self-Evaluation
**Due April 26, 11:59pm**

300-1000 words

Address each of the goals, and assess each of the metrics. Include a statement on each on what you achieved or did not achieve, give support for your assessments.

## Reflection on Learning
**Due April 26, 11:59pm**

500-1000 words

What do you take away from the project? Has this changed how you understand AI? Does and how does this affect future plans for learning, work, or otherwise?

## What's Next?
**Due April 22, 11:59pm**

100-500 words

Do you plan on continuing the project? What will you do with what you've learning?
