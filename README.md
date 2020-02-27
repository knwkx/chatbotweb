# Final Year Project Dialogflow Chatbot

**Project Summary**
The objective of this project is to design a full stack web application to compare a variable set of FAQ Chatbot API endpoints. The chatbot platform includes a text input and a speech input for intuitiveness and to cater for real live scenarios(Speech feature for public deployment). For the context of this project, MSF's Baby Bonus is used as a test bed for FAQ question and answer matching. The current APIs used are as follows:<br/>

**FAQ Matching APIs**<br/>
1. Govtech's askJamie (Benchmark for accuracy comparison)<br/>
2. MICL lab's QA matching engine<br/>
3. Google's Dialogflow<br/>
4. Self developed QA engine with Deep Neural Network<br/>

**Speech to Text API**<br/>
1. AISG's Speech to Text<br/>
2. Google's Speech API (To be implemented)<br/>
3. Twilio Speech Lab (To be implemented)<br/>

**Features**<br/>
1. Switchable Text/Speech based input<br/>
2. Multi FAQ Endpoint selection for response visualization<br/>
3. Response similarity comparison<br/>
4. Recommendation for similar questions<br/>

**Deployment Considerations**<br/>
Docker is used to set up 3 microservices React Frontend, Node Backend and Flask Server for response comparison. A docker-compose file is used to start up all microservices for deployment usage.

**Includes:**<br/>
frontend directory(ReactJS)<br/>
backend directory(NodeJS)<br/>
comparison directory(Response comparison API on Flask framework)<br/>
compose directory(Docker compose and env file)<br/>
python directory(python program)<br/>

**=============**<br/>
Master Branch<br/>
**=============**<br/>
This branch includes both Docker builds as well as local builds. Build differences are as follows:<br/>
**Docker Build (DNN endpoint not working)**<br/>
1. Frontend Directory<br/>
2. Backend Directory<br/>
3. Comparison Directory<br/>
4. Compose Directory<br/>

**Local Build (DNN endpoint working)**<br/>
1. Frontend Directory<br/>
2. Backend Directory<br/>
3. Python Directory<br/>

Installation/setup instructions will be provided in each directory.

