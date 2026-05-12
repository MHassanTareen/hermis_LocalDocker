> apt update && apt install -y \
curl \
git \
python3 \
python3-pip \
nodejs \
npm

> curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash

> hermes --help
> hermes setup
> hermes gateway run

to automate the gateway run:
> nohup hermes gateway run > gateway.log 2>&1 &
