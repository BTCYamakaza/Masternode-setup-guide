# UPDATE Instructions (Updating your VPS from 2.3 to 3.0.6)

## Note: This assumes that you've already updated your Windows/Mac wallet to the latest version here:

https://github.com/nodiumproject/Wallets


## If your Windows/Mac wallet is already upgraded, continue below:

First off, make sure you adjust the session timer for your session as you might get kicked from your VPS session if you don't

![](https://github.com/zaemliss/installers/blob/master/timeout.png)

Once that's done,

1. Log into your VPS
2. in your SSH session, type:

```
cd ~
wget https://raw.githubusercontent.com/nodiumproject/Masternode-setup-guide/master/update/update3.0.6.sh
chmod +x update3.0.6.sh
./update3.0.6.sh
```

... and follow the on-screen instructions.
