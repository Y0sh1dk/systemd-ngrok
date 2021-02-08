**Modified for use on ARM**

# Installation

1. `git clone https://github.com/Y0sh1dk/systemd-ngrok.git`
2. `cd systemd-ngrok`
3. `chmod +x install.sh`
4. Get authtoken from https://dashboard.ngrok.com/get-started/setup
5. `sudo ./install.sh <authtoken>`
6. Check https://dashboard.ngrok.com/status/tunnels 

# Config
1. Edit `/opt/ngrok/ngrok.yml`
2. `sudo systemctl restart ngrok.service`