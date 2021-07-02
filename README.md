# CatBot

![Screen Shot 2021-05-25 at 4 49 38 PM](https://user-images.githubusercontent.com/54850909/119572981-39012180-bd79-11eb-8071-91940a9c1076.png)

## About

CatBot is a virtual feline that mimics how a real cat might behave in human conversation. That is, it responds when it wants to, and ignores you otherwise. Mention food, naps, vacuums, or the infamous red dot in conversation and it will react. Otherwise, CatBot will lose interest and fall asleep. Its purpose is for fun rather than any practical purpose and is meant for anyone, cat lover or not. My goal was to make CatBot seem as interactive as possible by including the user’s name in replies and adding reactive cat emoticons for some extra drama. It is made up of several else-if statements that use regular expressions to test the user’s input against some expected responses. Since CatBot is limited by the structure of the system, the conversation terminates after 6 to 7 exchanges. Based on the input, it will return the most appropriate reply. It only accounts for a very small number of cases, so if the user enters a word the system doesn’t expect, it will answer with the default reply. 

CatBot is much different from a real-life chatbot because it doesn’t process the input semantically, meaning it has no real understanding of what the user said. Chatbots process the meaning of the input and have a very flexible structure. They don’t follow a strict, limited structure like CatBot. If I had the time and knowledge to improve CatBot in these areas, I would use more than just regular expressions to process input and work on making the structure more natural and adaptable.
