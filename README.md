# E2023-02 Wireguard VPN in 5 Minutes

Please keep in mind that WireGuard is peer-to-peer by design and the simple configuration that you find here covers only the usecase of a client that want to connect to your home network

# Quick Start

1. Install Wireguard on your System on Debian based systems you can use apt-get install wireguard
2. generate prrivate/public key pairs on both systems with wg genkey | tee privatekey | wg pubkey > publickey
3. Create a configuration file for the server and your client
4. Start the tunnel for example with systemctl start wg-quick@wg0 on both systems
5. Check if the tunnel is working with wg show


## Call to action
If you like what I do consider to (star & watch here on Github) or (like & subscribe to [ILTPWC on YouTube](https://www.youtube.com/@ILTPWC))