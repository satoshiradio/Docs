# RingTools (CLI)

Note: This information might be outdated. Please check out the [README](https://github.com/StijnBTC/Ringtools) on GitHub for the latest version.



### Installation

1. Open your SSH client and log into your node
2. Update pip to be sure `pip3 install --upgrade pip`
3. Clone this repository `git clone https://github.com/StijnBTC/Ringtools`
4. Navigate to the right folder `cd Ringtools`
5. Install the requirements `pip3 install -r requirements.txt`

### Usage

1. Put all public keys and telegram usernames, separated with a comma in `pubkeys.txt`
2. Run `checkring` functionality with write to create channels.txt `python3 ringtools.py check --write-channels`
3. Run Ringtools `python3 ringtools.py -f -l status` (When you're ready, hit Ctrl+C)
