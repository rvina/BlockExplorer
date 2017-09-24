# Freelabit-Blockchain-Explorer
Block explorer for Freelabit CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon freelabitd. It should be accessible from the Internet. Run freelabitd with open port as follows:
```bash
./freelabitd --rpc-bind-ip=0.0.0.0 --rpc-bind-port=31006
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon. You will also need to go through the API pages and update the links to point to your daemon IP as well. The API pages are located in the "q/" directory, the index.php file must point to your daemon IP. You must change all 4 of them "hashrate" "reward" "supply" "height"
