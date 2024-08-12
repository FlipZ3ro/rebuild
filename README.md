# COAL CLI

Thanks for JustPandaEver

DONATE JustPanad
```
FqX4B7prPuZa1HjmJbWQtLH6GYYqUTT9wzWr55XQTbyE
```

REBUILD FROM : https://github.com/JustPandaEver/ore-cli

A command line interface cryptocurrency mining.

## Install Dependancies

```
sudo apt update && sudo apt upgrade && sudo apt-get install -y pkg-config libssl-dev
```
```
sudo apt-get install build-essential
```
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
sudo apt install cargo
```

## Add wallet

```
cd $HOME 
nano id.js
```
Paste your private keys
CTRL + X = Y

## Clone Repo & Runing

```
git clone https://github.com/FlipZ3ro/rebuild
```
```
cd rebuild
```
```
cargo build --release
```

Running code
```
cargo run --release mine --keypire /root/id.js
```
