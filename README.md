# How to make a token in the solana blockchain

Create your own crypto currency from scratch for web3 using solana cli & metaplex


### Main Page:
  - https://solana22.vercel.app


## Links:
  - https://phantom.com/
  - https://docs.solanalabs.com/cli/install
  - https://docs.anza.xyz/cli/install/
  - https://github.com/webduno/solana_token22_metadata_gen
  - https://spl.solana.com/token-2022
  - https://fluxbeam.xyz/app/liquidity



## Commands:

```
solana-keygen new --no-bip39-passphrase

cat C:\Users\Equipo\.config\solana\

spl-token create-token --enable-metadata --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb

spl-token create-token  --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb

spl-token create-account TOKEN_ADDRESS

spl-token initialize-metadata TOKEN_ADDRESS "FUN coin" FUN https://solana22.vercel.app/gen/F/metadata_FUN.json

spl-token mint TOKEN_ADDRESS 10000  

spl-token authorize TOKEN_ADDRESS  mint --disable

spl-token authorize TOKEN_ADDRESS  freeze --disable
```

## Metadata Structure:
```
{
    "name": "Newest Coin Token",
    "symbol": "NEWCOIN",
    "description": "This is a token program on the Solana blockchain, defining a common implementation for fungible tokens",
    "image": "https://solana22.vercel.app/image.png"
}    
```


## Example Metadata Files:

- A
  - [ALL](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/A/metadata_ALL.json), [AND](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/A/metadata_AND.json), [ARE](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/A/metadata_ARE.json), [ANY](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/A/metadata_ANY.json), [ASK](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/A/metadata_ASK.json)

- C
  - [CAN](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/C/metadata_CAN.json), [CAT](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/C/metadata_CAT.json), [CUT](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/C/metadata_CUT.json)

- F
  - [FOR](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/F/metadata_FOR.json), [FAR](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/F/metadata_FAR.json), [FUN](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/F/metadata_FUN.json)

- H
  - [HAD](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/H/metadata_HAD.json), [HAS](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/H/metadata_HAS.json), [HER](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/H/metadata_HER.json), [HIS](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/H/metadata_HIS.json), [HOW](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/H/metadata_HOW.json)

- M
  - [MAN](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/M/metadata_MAN.json), [MAP](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/M/metadata_MAP.json), [MAY](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/M/metadata_MAY.json)

- O
  - [OUT](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/O/metadata_OUT.json), [ONE](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/O/metadata_ONE.json), [OUR](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/O/metadata_OUR.json)

- S
  - [SHE](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/S/metadata_SHE.json), [SEE](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/S/metadata_SEE.json), [SAY](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/S/metadata_SAY.json)

- T
  - [THE](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/T/metadata_THE.json), [TWO](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/T/metadata_TWO.json), [TRY](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/T/metadata_TRY.json)

- W
  - [WAS](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/W/metadata_WAS.json), [WHO](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/W/metadata_WHO.json), [WHY](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/W/metadata_WHY.json)

- Y
  - [YOU](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/Y/metadata_YOU.json), [YES](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/Y/metadata_YES.json), [YET](https://raw.githubusercontent.com/webduno/solana_token22_metadata_gen/refs/heads/main/gen/Y/metadata_YET.json)



## Generated Folders:
  - View all folders: https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/
  - [A](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/A), [B](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/B), [C](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/C), [D](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/D), [E](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/E), [F](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/F), [G](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/G), [H](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/H), [I](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/I), [J](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/J)
  - [K](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/K), [L](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/L), [M](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/M), [N](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/N), [O](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/O), [P](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/P), [Q](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/Q), [R](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/R), [S](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/S), [T](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/T), [U](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/U)
  - [V](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/V), [W](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/W), [X](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/X), [Y](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/Y), [Z](https://github.com/webduno/solana_token22_metadata_gen/tree/main/gen/Z)
