### Mining ERG - AutoLykos
##### ERG mining works with 4GB GPU and above (NVidia/AMD)

For ERG wallet we are going to use [coinex](https://www.coinex.com/register?refer_code=fgt2n) (trading platform) so we can easily trade it to XRP or USDT or any other coins. 

Store to coinex > Trade on coinex > withdraw to Binance (USDT/XRP) -> Binance P2P

[ERG Wallet](https://www.coinex.com/register?refer_code=fgt2n)
Minimum ERG deposit: 0.001
Minimum USDT withdrawal: 1
Minimum XRP withdrawal: 20
see [Deposit/Withdrawal fee](https://www.coinex.com/fees?type=deposit&refer_code=fgt2n) for more info.

 1. Create your [coinex account](https://www.coinex.com/register?refer_code=fgt2n)
 2. Verify and login to your coinex account.
 3. Click Asset > Deposit
 4. Click on Coin Type and search for ERG.
![enter image description here](https://i.imgur.com/dZ02iuu.png)
 5. Copy your ERG wallet deposit address
![enter image description here](https://i.imgur.com/YmIXXFA.png)

For mining pool, you can use [ergo nanopool](https://ergo.nanopool.org/). Default minimum payout is 5 ERG, you can customized this by setting email value on your miner.

### Hive OS:

 1. Create new Flight Sheet
 2. Coin = ERG
 3. Wallet = Select your wallet or Add Wallet (paste your [coinex ergo wallet](https://www.coinex.com/register?refer_code=fgt2n))
 4. Select mining pool (nanopool)
 5. Select miner, use Nanominer for nvidia and SRBMiner for AMD. be sure to add your email so you can customized your payout.
 6. and thats it.


### Windows:

I dont use miner on windows, but it looks something like this;

**using nanominer:**
pool/algo and other settings can be configured via config.ini

    nanominer.exe -algo Autolykos -coin ERG -wallet YOUR_ERG_WALLET -rigName YOUR_ETH_WORKER

[Download/More info here](https://bitcointalk.org/index.php?topic=5089248)


**using SRBMiner**

    SRBMiner-MULTI.exe --disable-cpu --algorithm autolykos2 --pool ergo.herominers.com:10250 --wallet ergo-wallet-here --password worker-name-here --gpu-boost 3

[Download/More info here](https://bitcointalk.org/index.php?topic=5190081.0) 


