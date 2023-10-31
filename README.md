Eq WebChat
2
Eq WebChat Classification
Objective – Implement data-driven solution to automate the process of web chat 
classification.
Challenge – Manging large volume of monthly data and reading long web chats to 
classify ensuring timely and accurate response.
Approach – Leveraging data science techniques to automate and classify web chat
3
Data Collection - 5186 Labelled Records, 81 Categories
Pre-processing – Removing Stop words, Removing Person/Agent name, Removing 
system generated message.
Eq WebChat Classification
4
Before cleaning 
10:26:13 info: Thank you for choosing to chat with us. An agent will be with you shortly.
10:26:16 info: You are now chatting with <AgentName>.
10:26:16 info: 
10:26:16 info: 
10:26:23 <Customer Name>: Hello
10:26:41 <AgentName>: Good Morning, How can I help?
10:27:15 <Customer Name>: Hi <AgentName>, I'm trying to create a payment but the save payment doesn't show even I completed all the 
details.
10:27:42 <Customer Name>: The save payment button doesn't appear even I completed all the details
10:28:00 <AgentName>: Have you selected the account type. you need to select whether it is personal or business
10:28:18 <Customer Name>: Yes, I did
After cleaning
Hi Im trying create payment save payment show even completed details save payment button appear even completed details selected 
account type need select whether personal business Yes details complete selected verify Payee apotion option Let try says match beneficiary 
bank yet signed payee verification tool says atch happy details click continue showed know Authorisation Issues Desk
5
Model training
80% of the labelled is used for training the model and remaining 20% is to test the model 
performance.
Performance
Model has accuracy of 80%. In general, you can achieve above 90% accuracy but dure 
to large no of labels and less amount of data for few labels resulted in 80% accuracy.
Since the accuracy was bit low, a confidence score has been added against each 
prediction so that end user can just focus on label with less confidence to have a double 
check.
6
Named entity recognition
Text/Document Classification
Sentiment analysis
Similar examples of NLP
