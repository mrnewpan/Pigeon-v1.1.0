wget -O - https://github.com/palomachain/pigeon/releases/download/v1.1.0/pigeon_Linux_x86_64.tar.gz | \
tar -C /usr/local/bin -xvzf - pigeon
chmod +x /usr/local/bin/pigeon

pigeon version
App version: v1.1.0
Build commit hash: c301c73fef9aee128fe43231b8e525b4a1612c4a

sudo systemctl start pigeond
