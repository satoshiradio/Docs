# Ringtools-Web

**Note: **Installing ringtools-web on your own node at this moment requires some experience with the command-line. This will be improved in the near future. You can also use the public version on [https://ringtools.djuri.nl/](https://ringtools.djuri.nl)

See the [ringtools-web documentation](https://dsbaars.gitbook.io/ringtools-web/basic-usage) for basic usage.

### Manually add to Umbrel app-store

1. SSH to your umbrel node
2. Go to the folder `~/umbrel/apps`
3. Download the modified registry data `wget https://raw.githubusercontent.com/dsbaars/umbrel/ringtools-web/apps/registry.json`
4. Create the ringtoolsweb folder and enter it `mkdir ringtoolsweb && cd ringtoolsweb`
5. Download the docker-compose file `wget https://raw.githubusercontent.com/dsbaars/umbrel/ringtools-web/apps/ringtoolsweb/docker-compose.yml`
6. Now you can log in to umbrel and find it in the app store (without icon and screenshots unfortunately.
