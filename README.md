My Discord
--------

<a href="https://discord.com/users/1025245410224263258"  align="center">
    <img src="https://lanyard.cnrad.dev/api/1025245410224263258?theme=dark&bg=171515&borderRadius=5px&animated=true&idleMessage=15%20year%20old%20solo%20dev">
  </a>

# Discord-Chat-bot 🤖
This is a [Python](https://www.python.org)-based Discord self chatbot using the `discord.py-self`

# Preview 👀
![image](https://user-images.githubusercontent.com/91066601/236717834-e3f6939f-3641-425c-b9f7-424a38f86ac4.png)


## Commands ⚙️⚙️
- For all commands use `~help` in discord 
# Steps to install and run 🚩 :
### Step 1. 🎬 Git clone repository
```
git clone https://github.com/mishalhossin/Discord-Chatbot-Gpt4Free
```
### Step 2. 📁 Changing directory to cloned directory
```
cd Discord-Chatbot-Gpt4Free
```
### Step 3. 🔑 Getting discord user token
[![How to get discod token](https://img.youtube.com/vi/0b_BXzHyhIg/0.jpg)](https://www.youtube.com/watch?v=0b_BXzHyhIg)


### Step 4. 🔑 Get hugging face Access Tokens from [here](https://huggingface.co/settings/tokens)
## Read or Write it dosent matter (I use Write)
![image](https://user-images.githubusercontent.com/91066601/236681615-71600817-774a-430c-8cec-8e6710a82b49.png)

### Step 5. 🔐 Rename `example.env` to `.env` and put the discord token and hugging face access token. It will look like this:
```
HUGGING_FACE_API=hf_access_token_from_step_4
DISCORD_TOKEN=your_discord_user_token_from_step3
```
### Step 6. ⚙️ Install all the dependencies
```
pip install -r requirements.txt
```
### Step 7. Put your discord user id in config.json
Go in your discord setting and enable dev mode



![image](https://github.com/mishalhossin/Self-AI-Chatbot/assets/91066601/06a79bec-d852-4d1a-aef4-ddda0d52c25f)




Click you profile and copy user id


![image](https://github.com/mishalhossin/Self-AI-Chatbot/assets/91066601/34c9517a-a9ff-4333-8460-98b53837119e)


### Step 8. 🚀 Run the bot and run ~toggleactive
```
python main.py
```


### 🏁 Finally talk to the bot
#### There are 2 ways to talk to the ai
- Invite your bot and DM (Direct message) it | ⚠️ Make sure you have DM enabled
- if you want it in server channel use **~toggleactive** 
- For more awesome commands use **~help**

![image](https://user-images.githubusercontent.com/91066601/235474066-d805b10b-168b-4965-b623-6b37470ca6bb.png)

# ✨✨✨  Other ways to run ✨✨✨

### Using docker to run :whale:
- Have a working bot token
- Follow up-to step 5
#### Install docker compose on linux machine :
```
apt update -y ; sudo apt upgrade -y; sudo apt autoremove -y; sudo apt install docker-compose -y
```
#### Start the bot in docker container :

```
sudo docker-compose up --build
```
### Using replit to run ☁️
- Follow all the steps except `step 1`
- Have a replit account
- Please note `.env` found in secrets tab of replit :

![image](https://user-images.githubusercontent.com/91066601/235810871-5d4c1469-35fd-42d2-a3a2-3382002877cb.png)

- Config `secrets` in replit like this :

![image](https://user-images.githubusercontent.com/91066601/235811115-689c40e8-660a-448d-83dd-194631324436.png)

# [![Try on repl.it](https://repl-badge.jajoosam.repl.co/try.png)](https://repl.it/github/mishalhossin/Discord-Chatbot-Gpt4Free)

###### Want something nsfw ? then check this out: [SEX-GPT](https://github.com/mishalhossin/Gpt3-sexbot-discord) (KInda outdated rn)
