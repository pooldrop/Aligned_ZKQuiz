# Aligned ZK Quiz 

You can use both VPS and codespaces for Aligned 

-----

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

- Just press Enter

```
source $HOME/.cargo/env
```

```
curl -L https://foundry.paradigm.xyz | bash
```
```
source /root/.bashrc
```

> If you use codeapaces you should use ` source ~/.bashrc `

```
foundryup
```

```
sudo apt update
sudo apt install build-essential
```

```
sudo apt update
sudo apt install pkg-config libssl-dev
```

```
export OPENSSL_DIR=/usr/lib/ssl
export OPENSSL_LIB_DIR=/usr/lib/ssl/lib
export OPENSSL_INCLUDE_DIR=/usr/include/openssl
```

> If you use codespaces you should use this :
``` console
export OPENSSL_LIB_DIR=/usr/lib/x86_64-linux-gnu
export OPENSSL_INCLUDE_DIR=/usr/include/openssl
```

```
apt install make 
apt install make-guile
```

>If you use codespaces you can use ` sudo apt install make `


```
git clone https://github.com/yetanotherco/aligned_layer.git && cd aligned_layer
```

## Create new wallet
```
cast wallet new-mnemonic
```


## Import wallet

```
cast wallet import --interactive ~/.foundry/keystores/mywallet.json
```

- Get faucet on Ethereum Holeskey
------
```
cd examples/zkquiz
```

```
make answer_quiz KEYSTORE_PATH=~/.foundry/keystores/mywallet.json
```
> Enter password

> Press Y 

- Quiz answers 

1. c

2. c

3. a

> Press Y

