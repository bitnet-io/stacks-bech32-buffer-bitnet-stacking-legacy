# stacks-manual-stacking-script-sandbox-explorer
# requires node preferrably node v20 or node v21 + bash

# installing node

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

or

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash


bash: source ~/.bashrc

zsh: source ~/.zshrc

ksh: . ~/.profile

```

then the install command 

```
nvm install 21
nvm use 21
```

```
wget https://github.com/bitnet-io/stacks-manual-stacking-script-sandbox-explorer/releases/download/bash-node-script/BITNET-HASH-BUFFER.tar.gz
tar -xvf BITNET-HASH-BUFFER.tar.gz
cd BITNET-HASH-BUFFER/
./bitnet-legacy-address-to-hashbyte-buffer.sh


```
