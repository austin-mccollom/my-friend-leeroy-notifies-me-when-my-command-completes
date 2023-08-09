# my-friend-leeroy-notifies-me-when-my-command-completes
Bash scripting to play a sound and/or send you a text message when a shell command completes.

append one to the end of the long-running command:
If you just want the audio to play: `; bash lj.sh`
If you want the audio to play and get a text message: `; bash lj.sh ; bash sms.sh`

Need to change the phone number and put a [textbelt](https://textbelt.com/) key into sms.sh

For example:
`node index.js ; bash lj.sh ; bash sms.sh`
