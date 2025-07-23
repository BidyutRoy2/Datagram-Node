Run Datagram CLI Node Run Your VPS or WSL

`sudo apt update && sudo apt install screen`

`screen -S datagram`

`wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux && sudo mv datagram-cli-x86_64-linux /usr/local/bin/datagram-cli`

`sudo chmod +x /usr/local/bin/datagram-cli`

`datagram-cli run -- -key YOUR_API_KEY`

Get Licenses Key : https://dashboard.datagram.network/wallet?tab=licenses

➡️ Video Link : https://odysee.com/@HiddenGem:8/Datagram-cli-Node-Setup

Example : `datagram-cli run -- -key f9ab29bb4330e81b515c91f3a567e197`
