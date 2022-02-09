# DiscordLTG
Advanced Synchronous API Wrapper for Discord

## Examples

### Setup Client
```py
discordltg.Bot(
           token = ""
)
```
### On Message Event
```py
while __session_ongoing == True:
      for message in discordltg.get_messages(
          embeds  = False,
          channel = "Id"
      ):
          ## Stuff
```
#### Message Variables
```py
message_flags   = message.split(":")[0
message_author  = message.split(":")[1]
message_id      = message.split(":")[2]
message_content = message.split(":")[3]
```
        
       
