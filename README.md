--[[

                      _        _                     _           _           _  __          
                     | |      | |              ____ | |         | |         | |/ _|         
  _ __ ___   __ _  __| | ___  | |__  _   _    / __ \| |__   __ _| |_ ___  __| | |_ _____  __
 | '_ ` _ \ / _` |/ _` |/ _ \ | '_ \| | | |  / / _` | '_ \ / _` | __/ _ \/ _` |  _/ _ \ \/ /
 | | | | | | (_| | (_| |  __/ | |_) | |_| | | | (_| | | | | (_| | ||  __/ (_| | ||  __/>  < 
 |_| |_| |_|\__,_|\__,_|\___| |_.__/ \__, |  \ \__,_|_| |_|\__,_|\__\___|\__,_|_| \___/_/\_\
                                      __/ |   \____/                                        
                                     |___/                                                  

]]

getgenv().Username = "" -- The username of the person you want to have full control over the bots.
getgenv().Prefix = "?" -- With what symbol the cmds should start with. (e.g. if its . then .cmds if its ; then ;cmds)
getgenv().Bots = {"","","","","",""} -- The display names of the bots you gonna run the script on.
getgenv().logChat = false -- If true it will start logging message to the discord webhook after running the script. If false it wont start logging messages until you run logchat enable.
getgenv().webhook = ""  -- Discord webhook url for logging.

loadstring(game:HttpGet("https://raw.githubusercontent.com/yuviydiscord/controlthing/refs/heads/main/ControlThing.lua" ))()
