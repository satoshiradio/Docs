@RingLeader I use the tool of @stijnbtc (https://github.com/StijnBTC/Ringtools) for checking the fees and the channels. You can install this on your node as follows:

1: ssh into your node:
`ssh umbrel@umbrel.local`
 (or your node FQDN or IP)


2: First to be on the safe side update pip:

`pip3 install --upgrade pip`

3: Run command:

`git clone https://github.com/StijnBTC/Ringtools`

4: After downloading go to Directory Ringtools:

`cd Ringtools`

5: Run command:

`pip3 install -r requirements.txt`
 (this takes some time, so be patient)

6: Put all public keys of the nodes and Telegram Usernames in the ring order, seperated by a `,` in `pubkeys.txt` (See the pinned post in the Telegram group)

`nano pubkeys.txt`

7: Run command to create channels.txt:

`python3 ringtools.py check --write-channels`

8: Finally, run the tool with the following command:

`python3 ringtools.py  -f -l status`

9: You can also use this tool to check if everyone opened their channels to the right node with the following command:

`python3 ringtools.py check`

You can close it with Ctrl+C

#ringtools #disable #status #false #true #monitoren #stijnbtcisawesome #english