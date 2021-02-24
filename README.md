# Sequin Blockchain Explorer
Block explorer for Sequin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon Sequind. It should be accessible from the Internet. Run Sequind with open port as follows:
```bash
./Sequind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=12898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Donate: [SQN] 

### Note
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
