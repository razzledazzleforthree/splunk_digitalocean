# splunk_digitalocean
Splunk Lab on DigitalOcean


https://github.com/dmuth/splunk-lab

## Set up SPLUNK_LOGS environment variable
- Create SPLUNK_LOGS folder then run
```
sudo nano /etc/environment
SPLUNK_ARGS="/logs"

## Starting up Splunk Lab Docker Container
```bash
SPLUNK_START_ARGS=--accept-license \
   bash <(curl -s https://raw.githubusercontent.com/dmuth/splunk-lab/master/go.sh)
```

## Install BOTSv1 or BOTSv2 dataset
