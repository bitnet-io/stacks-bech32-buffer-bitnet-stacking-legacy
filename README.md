# THIS IS FOR LEGACY USING ADDRESS-VERSION 0x19 STARTING WITH B

# for segwit addresses (starting with bit) see this html tool

* https://github.com/bitnet-io/stacks-bech32-buffer-bitnet-stacking-segwit



# for use with BitStacks "stacking"
* https://explorer.bitnft.io/sandbox/contract-call/SS000000000000000000003E020GD.pox/stack-stx?chain=mainnet


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

# EXAMPLE STACKING "MANUALLY" USING STACK-STX FUNCTION CALL
# this example is using 20,000 BitStacks STX
# 20,000 = 20,000 + 6 zeros (6 zeros are added for the STX 6 digit decimal system)
# 20000000000

![s1](https://github.com/bitnet-io/stacks-manual-stacking-script-sandbox-explorer/releases/download/bash-node-script/example-stacking.png)

# https://explorer.bitnft.io/sandbox/contract-call/SS000000000000000000003E020GD.pox/stack-stx?chain=mainnet


# running the script to make your own bitnet legacy address into a hashbuffer string to use with the stack-stx function for manual stacking

```
wget https://github.com/bitnet-io/stacks-manual-stacking-script-sandbox-explorer/releases/download/bash-node-script/BITNET-HASH-BUFFER.tar.gz
tar -xvf BITNET-HASH-BUFFER.tar.gz
cd BITNET-HASH-BUFFER/
./bitnet-legacy-address-to-hashbyte-buffer.sh


```




* (originally referenced from here)
* https://github.com/stacks-network/docs/issues/817#issuecomment-723303272
