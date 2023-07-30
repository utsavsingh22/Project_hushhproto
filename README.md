# Project_hushhproto

Build a mobile app for iOS or Android that has a simple search engine interface (think google) or a search bot (think chatGPT or bard) with a simple mobile UI that runs against 3-5 valuable personal data takeouts of yours (think gmail, LinkedIn, google maps, google chrome search and browsing history, Instagram, Facebook, WhatsApp, etc). This search and chat interface should work against atleast 3 valuable large personal datasets of yours. You can use the data takeout api and service available by Google, Facebook, Instagram, Apple, LinkedIn to take all your personal data out of these companies' databases. They all offer this for free and you can read up more about how to do this using google or chatGPT. If you aren’t comfortable with mobile app development you could do the same as a developer focused api that a front end developer can use to emulate the same behavior.
Please note You are free to use any of the latest technologies including chatGPT, GitHub Copilot, or Replit to build this prototype including using open source LLMs and cutting edge vector databases like pinecone. The demo should highlight how this search or chatbot is useful to you as a user.
Remember You are the target user of the prototype.

If you’re not a software developer and aren’t keen on learning how to write and build software - you’re open to avoiding the software part of this exercise but still build the necessary artifacts to pitch your concept; highlight the business, product and technology innovation you’re looking to build and drive here and ultimately how the concept is going to help build great value for the world at scale by helping users on some aspects of their most valuable data.

- As a DataEngineer our focus will be on pulling data from any open source API and do transformation,store, and Analyzing.
## [Video Link]()
  
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/6d7a3cb7-4f38-4996-a984-af68a5b4fd65)


STEP 1:- Create a two Linked List 
One for source connection information.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/601f7912-c963-4e75-bbbe-5b323cd36fed)
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/4d45a76a-6106-41b8-bcef-c7fbe36ff397)
Another for destination connection information.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/a2a341e7-03e4-486e-8f7d-04a6beed29ab)


Step 2:- Create a Source Rest Dataset.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/d9f1297e-e909-4706-9a56-1efcb7e602fb)

Step 3:- Create a Sink generic dataset for storing those pulled file.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/483f48d6-d0a4-4554-802e-1d1fbaefa025)

Step 4:- Now Create a for each activity for pulling Api data and in items choose dynamic content and create array for pulling required country name.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/b94c8cee-6d96-476f-acd5-29d6f83e2351)

Step 5:- Now under for each activity create copy activity to fetch from source and move it to destination.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/ffc57988-d634-4c1e-99bd-8f882eea0f08)
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/77f0232e-0ded-4c92-9634-2261216b5018)

Step 6:- After successful pipeline run it will generate those file in ADLS location on given path.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/0eb8dc68-456d-48b0-b9c2-d13bdc419097)

Step 7:- Now for analysis we can either download those file and use databrics or we can read that path also and do the analysis. In our case we will download and upload there for analysis.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/d50b2740-35ed-46ec-a8b4-05f83f3c9bed)


