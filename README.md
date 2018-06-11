# TS3_StripeControl
Use a cheap MagigHome WiFi-RGBW-Stripe-Controller and the pyTSon plugin for TeamSpeak3 to monitor the Audio-Status of your microphone or of your current channel.

Based on https://github.com/pathmann/pyTSon_repository/blob/master/eventlog.py


## TS3_MicLight
You can define colors to show the state of your microphone (sending/muted/idle)

## TS3_StatusLight
Changed Version of TS3_MicLight, uses The LED-Stripe-Channels for the Events:__
RED    = mic and/or speakers are muted__
GREEN  = you are speaking__
BLUE   = someone else is speaking__
WHITE  = nobody is speaking, nothing is muted__

So, tere are also possible mixed Colors:__
CYAN    = BLUE + GREEN = someone else is speaking and you are speaking__
MAGENTA = BLUE + RED   = someone else is speaking and your mic is muted__
YELLOW  = RED + GREEN  = Something went really wrong, you can't speak in TeamsPeak while yous Mic is muted (I never hat YELLOW)
