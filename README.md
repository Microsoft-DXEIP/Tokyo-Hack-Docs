# Getting Started with the Microsoft Bot Framework

### The Microsoft Bot Framework provides a platform for you to build interactive conversational Bots. The Bots you build can support multiple end points, or channels. A channel is the way people will engage with the Bot you build. Examples of channels are Skype, SMS, Slack, Kik, and Facebook Messenger. 

### INSERT INFO ON TUTORIAL

</br>

# Prerequisites

1. Install Git: Go to <https://git-scm.com/downloads> and download the installer for your Operating System. Follow the steps to install git. 
2. We'll need some Bot Framework specific tools. In your browser navigate to <https://docs.botframework/en-us/downloads>. This page has links and instructions for the tools we need to build our bot. </br> We will refer to this page as the **docs** from now on.
3. First, we need a way to test our bot. From the docs install the bot framework for your Operating System.
    
    * **Windows**:
        1. Under tools click the link for [Bot Framework Emulator (Windows)](https://download.botframework.com/bf-v3/tools/emulator/publish.htm)
        2. From this page click install and you will be prompted to install the Bot Emulator application.
    
    * **macOS or Linux**: 
        1. Under tools click the link for [Bot Framework Emulator (Console)](https://aka.ms/bfemulator). This wil give you a .zip file.
        2. Unzip this file.
        3. Install [Mono](http://www.mono-project.com/download/#download-mac). Select your operating system and click Download.
        4. In your terminal type > $ mono BFEmulator.exe
4. Our ultimate goal is to get our chatbot working on Skype so you will need a Skype account. Go to <https://www.skype.com/> and sign up for an account. Also download the desktop app.
5. To allow our Bot to work on Skype without deploying it to Azure, we need a third party tool called ngrok. Go to <https://ngrok.com/download> and follow the steps to download it.

---
### Great! We now have the tools to get us started with the Bot Framework.

### Now choose an SDK to work with. The Bot Framework currently supports .NET and NodeJS SDKs.

> ### **Note:** If you plan on using the .NET SDK, while not required, the docs will assume you are running Visual Studio on Windows.

6. Choose an SDK to work with and make sure you have the necessary tools to work with that framework.
    
    * **NodeJS**:
        1. Go to <https://nodejs.org/en/download> and download the installer for your operating system. Follow the installer steps to get node. You should install Node version 4 or higher.
        
        2. Feel free to use any text editor you'd like although we recommend [Visual Studio Code](https://code.visualstudio.com).
    
    * **.NET**: 
        1. **VERY IMPORTANT TO DO BEFORE THE HACK STARTS:** </br> Install Visual Studio 2015 (latest update), you can download the community version here for free: <https://www.visualstudio.com> 
        </br> **Important:** Please update all VS extensions to their latest versions Tools->Extensions and Updates->Updates
        
        2. Download and install the Bot Application template. Download the file from the direct download link [here](http://aka.ms/bf-bc-vstemplate).
            </br>Save the zip file (do not extract the contents) to your Visual Studio 2015 templates directory which is traditionally in "%USERPROFILE%\Documents\Visual Studio 2015\Templates\ProjectTemplates\Visual C#\"
            </br></br>
            **Note:** This step isn't necessary as we will be cloning a Quickstart template but it will allow you to make a new bot in the future so it's worth doing.

</br>



# Creating a basic Bot

## Now let's start writing some code.

### Download the Quickstart project for the SDK you will be working with.

## If you're using NodeJS: 

Clone this repo
```
    git clone https://github.com/billba/bot-quickstart-js.git
```
Install Node modules
```
    npm install
```
Run
```
    npm run watch
```
### If you're using C# .NET: 

Clone this repo
```
    git clone https://github.com/kabirkhan/bot-quickstart-.NET.git
```

Press F5 to run the project in Debug Mode

### You can also find these repositories by following the links below.
### [NodeJS Repsitory](https://github.com/billba/bot-quickstart-js) | [.NET Repository](https://github.com/kabirkhan/bot-quickstart-.NET)

---
</br>