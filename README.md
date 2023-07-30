# Project_hushhproto

Build a mobile app for iOS or Android that has a simple search engine interface (think google) or a search bot (think chatGPT or bard) with a simple mobile UI that runs against 3-5 valuable personal data takeouts of yours (think gmail, LinkedIn, google maps, google chrome search and browsing history, Instagram, Facebook, WhatsApp, etc). This search and chat interface should work against atleast 3 valuable large personal datasets of yours. You can use the data takeout api and service available by Google, Facebook, Instagram, Apple, LinkedIn to take all your personal data out of these companies' databases. They all offer this for free and you can read up more about how to do this using google or chatGPT. If you aren’t comfortable with mobile app development you could do the same as a developer focused api that a front end developer can use to emulate the same behavior.
Please note You are free to use any of the latest technologies including chatGPT, GitHub Copilot, or Replit to build this prototype including using open source LLMs and cutting edge vector databases like pinecone. The demo should highlight how this search or chatbot is useful to you as a user.
Remember You are the target user of the prototype.

If you’re not a software developer and aren’t keen on learning how to write and build software - you’re open to avoiding the software part of this exercise but still build the necessary artifacts to pitch your concept; highlight the business, product and technology innovation you’re looking to build and drive here and ultimately how the concept is going to help build great value for the world at scale by helping users on some aspects of their most valuable data.

- As a DataEngineer our focus will be on pulling data from any open source API and do transformation,store, and Analyzing.
## [Video Link](https://www.youtube.com/watch?v=JaByuFZXEkg)

![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/3d271900-137c-434f-a33f-f6f06f330edd)



STEP 1:- Create a two Linked List 
One for source connection information.
Another for destination connection information.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/cf4f00dc-74eb-41be-89c1-95c3643809a3)



Step 2:- Create a Source Rest Dataset.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/15768cc6-04bc-4f67-8bf5-e738391b57bb)


Step 3:- Create a Sink generic dataset for storing those pulled file.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/1423ff80-4685-48ce-867f-3877280efc03)


Step 4:- Now Create a for each activity for pulling Api data and in items choose dynamic content and create array for pulling required country name.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/7e7fadfd-a35b-4626-9dac-7f0592db8cb5)


Step 5:- Now under for each activity create copy activity to fetch from source and move it to destination.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/0aab57d0-1b89-4dec-a094-e5cb8cf96cfd)
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/2b1b78f8-f88c-4694-b92d-47220f688e9a)


Step 6:- After successful pipeline run it will generate those file in ADLS location on given path.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/44cf7b2d-b645-4582-ab7c-e6c82b6f1112)


Step 7:- Now for analysis we can either download those file and use databrics or we can read that path also and do the analysis. In our case we will download and upload there for analysis.
![image](https://github.com/utsavsingh22/Project_hushhproto/assets/60449352/13fa8548-57f3-4965-a2fd-e4b02304fb16)
