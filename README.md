# Discord_Study_Bot

This is a discord bot that allows people to create flash card sets and study in chat

![ezgif com-gif-maker](https://user-images.githubusercontent.com/41452865/139393976-4e059dde-ca58-4593-8aec-fa7067caf698.gif)

## Installation

Bot Setup (needed for bot token and to set bot details)
1. Log in to discord
2. Go to [this link](https://discord.com/developers/applications) and create an application. The name of the application must be somewhat unique
3. Click on 'bot' in the side navigation.
4. On the bot page click add bot and copy the bot token.
5. Save this bot token to be inserted into the python code
6. Replace the bot token string in the python code to your bot token string
7. Have a server that you have bot invite privileges for. Make a yourself a new server if needed.
8. Click on OAuth2 in the side navigation of your application page
9. On OAuth2 page scroll down to the big rectangle with checkboxes labeled 'scopes' right above it. Checkmark 'bot' and click copy for the generated Url.
10. The generated Url is the invite link. When anyone signed in to discord visits this url they have the option to add the bot to one of their servers.
11. Once the bot is added, run the python code and it should work

Code Setup without dev container
 1. Clone repository
 2. Have python3 installed on machine with pip
 3. Run 'pip install discord.py nest_asyncio'
 4. Make sure your bot token string replaces the one in the python file
 5. Run python code
 
 Code Setup with dev container
 1. Clone repository
 2. Install VS-Code
 2. Install vs-code remote-container extension
 3. Open repo folder in VS code
 4. In the bottom left hand corner of the screen click the green angle brackets, from the menu shown select open in container
 4. Make sure your bot token string replaces the one in the python file
 5. Run python code
 
 ## Usage
 Commands
   * **create pack: \<new pack name\>**
      Create a new flash card pack, separate from other flashcard packs with inputed pack name
   * **show pack: \<pack name\>**
      Displays all the cards in this pack
   * **add to \<pack name\>**
      Selects pack to put new cards that are added
   * **term: \<your term or one side of information\>**
      Sets one side of the flash card. This can be Overwritten by texting this again
   * **def: \<your definition or any information for other side of card\>**
      Setss the other side of the card with the new definition
   * **add**
      Adds the created card to the pack selected with 'add to \<pack name\>'
   * **go away quizfish**
      To stop bot
 
