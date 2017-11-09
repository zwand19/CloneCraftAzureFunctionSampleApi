##CloneCraft Example Azure Function API

Use this repository as a starting point to creating your C# bot for CloneCraft, hosted as an Azure Function.

###Steps to getting started


####Setup Azure Account
1. Create a free Microsoft Azure account and login to portal.azure.com. New accounts start with $200 free credit.
2. Click New -> Compute -> Function App

####Setup Local Repo
1. Clone this repo and open the project in VS2017
2. Right click on the project and hit Publish
3. Choose "Create New" function app and follow the prompts

####Setup Your CloneCraft Account
4. In Azure Portal, copy the api url from the azure function
5. Visit http://clonecraftapp.azurewebsites.net/#/ and hit Login/Register
6. Click Register
7. Register using your api url
8. Go to http://clonecraftapp.azurewebsites.net/#/CloneCraft/game and play human vs your hosted ai. Create a minion with a lot of vision and speed and move them over to the enemy base. If the minions are wandering around, you have your first AI successfully uploaded!

####Setup Local Testing