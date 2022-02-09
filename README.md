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
        
       
