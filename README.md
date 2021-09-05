![punks_with_mask](/punk-with-mask-variety.png)
# CryptoPunks with mask : Hope our punks away from covid-19 virus
 
Thanks to [Larvalabs](https://github.com/larvalabs) for creating cryptopunks in 2017, these lovely punks have been welcomed by crypto enthusiasts and artists all over the world.

With the spread of covid-19 virus, we found that only a few punks had masks, and considering the safety of punks, we decided to put 10,000 punks with their own unique masks.
Currently these punks are already active in Ethereum, TRON, BSC and other virtual spaces, we need to put masks on all of them to ensure their safety. In this project, we will extract the characteristics of each puck, and then combine them with their cyberspace to generate a unique mask for each punk by algorithm. Each mask has its own unique color, and some masks have breathing valves.

We hope the outbreak will end soon and the punk will be safe!

# Algorithm for generating mask
We generated unique masks for each punk, and the generation steps are as follows.
1. By image analysis, we extract the pixel features of each punk.
2. Combine the image features with the network space (TRON, Ethereum, BSC) to generate unique random numbers for each punk.
3. Extract specific bytes from the random number as the color of the unique mask of the punk.
4. make different types of masks according to the features of the punk.

Translated with www.DeepL.com/Translator (free version)

```
./punks_with_mask/mask.py --input="punks.png" --output="mask_punks.png" -chain="TRON"
```
![punks_with_mask](/tron_punks.png)

```
SHA256(tron_punks.png)= 683c9ab5430e9cf98450d50590178777c42e5fea54d70cf2f47e4a0bf47eb1f3
```
This is the official and genuine image of all of the PunksWithMask that have been created on TRON. openssl sha256 tron_punks.png 
To allow verification that the punks being managed by the CryptoPunks Ethereum contract are the same as what you see in the image, we have embedded a SHA256 hash of the image file into the contract. You can generate this hash for the punks image file via a command line similar to openssl sha -sha256 punks.png and compare that to the embedded hash in the contract 683c9ab5430e9cf98450d50590178777c42e5fea54d70cf2f47e4a0bf47eb1f3.


![punks_with_mask](/eth_punks.png)
```
SHA256(eth_punks.png)= 7bb356d6e3769beca1f8819789c1b393a77d9d36c2f1a479f438620b0265a39c
```
![punks_with_mask](/bsc_punks.png)
```
SHA256(bsc_punks.png)= d0ed09abe30cfbf269d107907ff810c95f03c8c351dc681f46bb0d30f4a37db8
```
