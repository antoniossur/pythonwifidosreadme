# Python WiFi DoS Attack Script.

It's very ease to destroy a WiFi Network using this simple Python script. <br>

The script uses WiFi deauthentication messages to stop all user from accessing a WiFi Network. <br>

In the background, we are using airmon-ng and airodump-ng to launch our attack.

<b>TO LET THIS SCRIPT WORK, YOU MUST NEED A NETWORK ADAPTERS:</b> <br>
Alfa AWUS036NHA: https://amzn.to/3qbQGKN​ <br>
Alfa AWUSO36NH: https://amzn.to/3moeQiI

<br>

## <b>Python Wifi DoS Attack</b>

1. <b>Open Command Prompt (cmd)</b>

```bash
ping google.com -t
```

The ping command it's usually used as a simple way to verify that a computer can communicate over the network with another computer or network device or a server. In this case "google.com"

<br>
<br>

2. <b>Create a file</b>

```bash
nano (name).py
```

Call it whatever you want. For example "wifidos" after the name add ".py". Example: wifidos.py

Copy the code from here: https://github.com/davidbombal/red-python-scripts/blob/main/wifi_dos_type1.py
or the second code: https://github.com/davidbombal/red-python-scripts/blob/main/wifi_dos_type2.py

<br>
<br>

3. <b>Run the script</b>

```bash
python3 (name).py
```

If it doesn't work, type:

```bash
sudo python3 (name).py
```

<br>
<br>

4. <b>Choose WiFi Network</b> <br>
   Press "CTRL + C" then select the WiFi Network that you want to DoS Attack, after it press enter. <br>
   Go back to command prompt and look at the data.

<br>
<br>

5. <b>Stop the DoS Attack</b> <br>
   To let the network work just press again "CTRL + C" and it will work perfectly.

#

<b>NOTE: YOU DO NOT NEED TO KNOW THE PASSWORD OF THE NETWORK TO RUN THE DOS ATTACK. YOU HAVE TO BE IN THE VICINITY </b>

#
<b><h2>Legend:</h2></b>

<b>DoS</b>  = Denial of Service

<b>-t</b>   = ping doesn't time out

<b>.py</b>  = Python 

<b>CTRL</b> = Control

#
Thanks to David Bombal for the scripts. <br>
<br>
© All rights reserved to David Bombal. <br>
<br>
If you need help, watch this video by David Bombal: <br>
https://www.youtube.com/watch?v=iGXB5NanUK4