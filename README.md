# Relayers

Our relayer infra is selfhosted with gigabyte fiber connection. We are running four instances of hermes which support 26 chains. Our RPC are hosted on four baremetal servers. You will find in this repository a description of our servers, the conf of our relayers and the set of channels that we support.

## Server

One Intel(R) Xeon(R) CPU E5-2650 (12C/24T) v4 @ 2.20GHz, 96GB ECC RAM, 2X1TB + 1X2TB M2 Nvme for RPC, 4X1TB SSD for services  

One Intel(R) Xeon(R) Silver 4214 (12C/24T) CPU @ 2.20GHz, 288GB ECC RAM, 2 X ASUS Hyper M.2 x16 Gen 4, 8X1TB + 1X2TB M2 Nvme for rpc, 4X1TB SSD for services  

One AMD Ryzen 9 5900X (12C/24T) @ 3,7 Ghz, 128GB ECC RAM, 1 X ASUS Hyper M.2 X16 PCIe 3.0, 6X1TB M2 Nvme for rpc, 1TB SSD for services  

One AMD Ryzen 5 3600 (6C/12T) @ 3,6 Ghz, 128GB ECC RAM,  2X1TB M2 Nvme RAID0, 2*500Gb  M2 Nvme RAID0  

## Relayer conf  

[Relayer00](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/ConfigRelayer00.toml)  
[Relayer01](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/ConfigRelayer01.toml)  
[Relayer02](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/ConfigRelayer02.toml)  
[Relayer03](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/ConfigRelayer03.toml)  
[Relayer04](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/ConfigRelayer04.toml) 

## Supported chains  
[Axelar](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#axelar)  
[Band](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#band)  
[Bitcanna](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#bitcanna)  
[Chihuahua](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#chihuahua)   
[Coreum](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#coreum)  
[Cosmos Hub](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#cosmos-hub)  
[Decentr](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#decentr)  
[Desmos](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#desmos)  
[Emoney](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#emoney)  
[Fetch](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#fetch)  
[Gitopia](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#gitopia)  
[Gravity Bridge](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#gravity-bridge)  
[Ixo](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#ixo)  
[Kava](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#kava)  
[Ki Chain](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#ki-chain)  
[Kujira](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#kujira)  
[Kyve](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#kyve)  
[Lum](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#lum)  
[Noble](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#noble)  
[Osmosis](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#osmosis)  
[Passage](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#passage)  
[Provenance](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#provenance)  
[Quasar](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#quasar)  
[Quicksilver](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#quicksilver)  
[Stargaze](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#stargaze)  
[Teritori](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#teritori)   
 
----------------

### _Axelar_  
 
Axelar, channel-2, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Cosmos Hub, channel-293, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq)  

Axelar, channel-2, [axelar14uyp...63a](https://www.mintscan.io/axelar/account/axelar14uyfxlv00lj0qhcwt7vms2rsf7kxuld7sww63a), Cosmos Hub, channel-293, [cosmos14uy...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u)  

Axelar, channel-3, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Osmosis, channel-208, [osmo16vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj) 

Axelar, channel-14, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Kujira, channel-9, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)  

Axelar, channel-17, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Ki Chain, channel-19, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)  

Axelar, channel-18, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Stargaze, channel-50, [stars1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf)

Axelar, channel-21, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Fetch AI, channel-14, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0) 

Axelar, channel-32, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Bitcanna, channel-15, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/address/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2) 

Axelar, channel-75, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Kyve, channel-1, [kyve1evdj...xqu](https://www.mintscan.io/kyve/account/kyve1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt8sdxqu)

Axelar, channel-114, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Ixo, channel-23, [ixo14uy...q70](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70)

Axelar, channel-116, [axelar14uy...63a](https://www.mintscan.io/axelar/account/axelar14uyfxlv00lj0qhcwt7vms2rsf7kxuld7sww63a), Provenance, channel-9, [pb16vmp...g4u](https://www.mintscan.io/provenance/address/pb16vmp7sz28pnvgz6f3zm6q93y39jsd33aazwg4u) 

Axelar, channel-120, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Coreum, channel-6, [core14uy...fa8](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70)

Axelar, channel-122, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), teritori-1, channel-61, [tori14uy...mpv](https://www.mintscan.io/teritori/account/tori14uyfxlv00lj0qhcwt7vms2rsf7kxuld7k50mpv)

Axelar, channel-153, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Chihuahua, channel-78, [chihuahua1evdj...726](https://www.mintscan.io/bitcanna/address/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2) 

----------------  

### _Band_ 

Band , channel-12, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), Desmos, channel-1, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), ibc-profiles   

Band , channel-83, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), Osmosis, channel-148, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)  

Band , channel-157, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), Desmos, channel-148, [osmo1tdl8...ej9](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq)  

Band , channel-159, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), Coreum, channel-20, [core16vmp...klm](https://www.mintscan.io/coreum/account/core16vmp7sz28pnvgz6f3zm6q93y39jsd33a8zaklm)  

---------------- 

### _Bitcanna_ 

Bitcanna , channel-1, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Osmosis , channel-51, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Bitcanna, channel-3, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Cosmos , channel-232, [cosmo1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Bitcanna , channel-8, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Gravity Bridge , channel-0, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws)

Bitcanna , channel-15, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Axelar , channel-32, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

----------------

### _Celestia_

----------------

### _Chihuahua_

Chihuahua , channel-7, [chihuahua1evdj...726](https://www.mintscan.io/chihuahua/address/chihuahua1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptntd726), Osmosis , channel-113, [osmo1tdl...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

Chihuahua , channel-78, [chihuahua1evdj...726](https://www.mintscan.io/chihuahua/address/chihuahua1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptntd726), Axelar , channel-135, [axelar1evd...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

----------------

### _Coreum_

Coreum , channel-2, [core14uy...fa8](https://www.mintscan.io/coreum/address/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8), Osmosis , channel-2188, [osmo16vm...awj](https://www.mintscan.io/osmosis/address/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj)

Coreum , channel-6, [core14uy...fa8](https://www.mintscan.io/coreum/address/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8), Axelar , channel-120, [axelar16vmd...9np](https://www.mintscan.io/axelar/address/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Coreum , channel-7, [core16vm...klm](https://www.mintscan.io/coreum/address/core16vmp7sz28pnvgz6f3zm6q93y39jsd33a8zaklm), Gravity , channel-142, [gravity16vm...4ag](https://www.mintscan.io/gravity-bridge/address/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag)

Coreum , channel-9, [core14uy...fa8](https://www.mintscan.io/coreum/address/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8), Cosmoshub , channel-660, [cosmos16vm...dcq](https://www.mintscan.io/cosmos/address/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq)

Coreum , channel-17, [core14uy...fa8](https://www.mintscan.io/coreum/address/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8), Kujira , channel-122, [axelar16vmd...9np](https://finder.kujira.network/kaiyo-1/address/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

Coreum , channel-18, [core14uy...fa8](https://www.mintscan.io/coreum/address/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8), Kava , channel-142, [kava14uy...0vm](https://www.mintscan.io/kava/address/kava14uyfxlv00lj0qhcwt7vms2rsf7kxuld7g4v0vm)

Coreum , channel-19, [core16vm...klm](https://www.mintscan.io/coreum/address/core16vmp7sz28pnvgz6f3zm6q93y39jsd33a8zaklm), Noble , channel-49, [noble16vm...9qw](https://www.mintscan.io/noble/address/noble16vmp7sz28pnvgz6f3zm6q93y39jsd33au0s9qw)

Coreum , channel-20, [core16vm...klm](https://www.mintscan.io/coreum/address/core16vmp7sz28pnvgz6f3zm6q93y39jsd33a8zaklm), Band , channel-159, [band11evd...jns](https://www.mintscan.io/band/address/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns)

---------------- 

### _Cosmos Hub_ 

Cosmos, channel-141, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Osmosis , channel-0, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Cosmos, channel-204, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq), Ixo , channel-1, [ixo14uy...q70](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70)

Cosmos, channel-223, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Ki Chain , channel-1, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)

Cosmos, channel-232, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Bitcanna , channel-3, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2)

Cosmos, channel-256, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Fetch AI , channel-3, [fetch1evd...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0)

Cosmos, channel-277, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Kava , channel-0, [kava1evdj...9np](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal)

Cosmos, channel-281, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Gravity Bridge , channel-17, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5)

Cosmos, channel-293, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq), Axelar , channel-2, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Cosmos, channel-293, [cosmos14uy...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Axelar , channel-2, [axelar14uy...63a](https://www.mintscan.io/axelar/account/axelar14uyfxlv00lj0qhcwt7vms2rsf7kxuld7sww63a)

Cosmos, channel-314, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Provenance , channel-6, [pb16vmp...g4u](https://www.mintscan.io/provenance/account/pb16vmp7sz28pnvgz6f3zm6q93y39jsd33aazwg4u)

Cosmos, channel-343, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq), Kujira , channel-0, [kujira16vmp...9np](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

Cosmos , channel-431, [cosmos16vmp...9dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq),Teritori , channel-10, [tori1evdj...esg...2hk](https://www.mintscan.io/teritori/account/tori14uyfxlv00lj0qhcwt7vms2rsf7kxuld7k50mpv)

Cosmos, channel-467, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Quicksilver , channel-1, [quick14uy...qrw](https://www.mintscan.io/quicksilver/account/quick14uyfxlv00lj0qhcwt7vms2rsf7kxuld7lygqrw)

Cosmos, channel-660, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq), Coreum , channel-9, [core14uy...fa8](https://www.mintscan.io/coreum/account/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8)

Cosmos, channel-730, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Stargaze , channel-239, [stars14uy...03d](https://www.mintscan.io/quicksilver/stargaze/stars14uyfxlv00lj0qhcwt7vms2rsf7kxuld7qu003d)

---------------- 

### _Decentr_ 

Decentr, channel-1, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s), Osmosis , channel-181, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Decentr, channel-2, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s), Gravity Bridge , channel-58, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5)

---------------- 

### _Desmos_ 

Desmos, channel-1, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), Band , channel-157, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), oracle

Desmos, channel-2, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), Osmosis , channel-135, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

Desmos, channel-32, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), Band , channel-12, [osmo1tdl8...ej9](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns)

---------------- 

### _Emoney_ 

E-Money, channel-0, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9), Osmosis , channel-37, [osmo116vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj)

E-Money, channel-14, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9), Sifchain , channel-19, [sif16vmp...mht](https://www.mintscan.io/sifchain/account/sif16vmp7sz28pnvgz6f3zm6q93y39jsd33a332mht)

E-Money, channel-15, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9), Juno , channel-9, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu)

E-Money, channel-26, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9), Axelar , channel-6, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

E-Money, channel-27, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9), Kujira , channel-21, [kujira1...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

---------------- 

### _Fetch_ 

Fetch, channel-10, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0), Osmosis , channel-229, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Fetch, channel-14, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0), Axelar , channel-21, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

Fetch, channel-16, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0), Cosmos Hub , channel-526, [cosmos1evd...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

---------------- 

### _Gitopia_ 

Gitopia, channel-0, [gitopia1evd...8ym](https://gitopia.exploreme.pro/account/gitopia1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptwx88ym), Osmosis , channel-781, [osmo1evd...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

---------------- 

### _Gravity Bridge_ 

Gravity Bridge, channel-0, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws), Bitcanna , channel-8, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2)

Gravity Bridge, channel-7, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Stargaze , channel-6, [stars14uyf...03d](https://www.mintscan.io/stargaze/account/stars14uyfxlv00lj0qhcwt7vms2rsf7kxuld7qu003d)

Gravity Bridge, channel-8, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws), Juno , channel-31, [juno1evdj...tvy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Gravity Bridge, channel-10, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Osmosis , channel-144, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

Gravity Bridge, channel-17, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Cosmos , channel-281, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u)

Gravity Bridge, channel-37, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws), Ki Chain , channel-11, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)

Gravity Bridge, channel-58, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Decentr , channel-2, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s)

Gravity Bridge, channel-83, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Kujira , channel-11, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk)

Gravity Bridge, channel-107, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Kujira , channel-50, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk)

Gravity Bridge, channel-142, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Coreum , channel-7, [core16vm...klm](https://www.mintscan.io/coreum/account/core16vmp7sz28pnvgz6f3zm6q93y39jsd33a8zaklm)

---------------- 

### _Ixo_ 

Ixo, channel-1, [ixo14uy...q70](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70), Cosmos Hub , channel-204, [cosmos16vm...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq)

Ixo, channel-4, [ixo1evdj...z0t](https://www.mintscan.io/ixo/account/ixo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt0t7z0t), Osmosis , channel-38, [osmo1...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Ixo, channel-23, [ixo14uy...q70](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70), Axelar , channel-114, [axelar16vm...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Ixo, channel-25, [ixo14uy...q70](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70), Kava , channel-128, [kava14uy...0vm...9np](https://www.mintscan.io/kava/account/kava14uyfxlv00lj0qhcwt7vms2rsf7kxuld7g4v0vm)

Ixo, channel-26, [ixo1evdj...z0t](https://www.mintscan.io/ixo/account/ixo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt0t7z0t), Noble , channel-15, [noble14uy...6zj](https://www.mintscan.io/noble/account/noble14uyfxlv00lj0qhcwt7vms2rsf7kxuld7urd6zj)

---------------- 

### _Kava_ 

Kava, channel-0, [kava1evdj...dal](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal), Cosmos, channel-277, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Kava, channel-1, [kava1evdj...dal](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal), Osmosis, channel-143, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Kava, channel-116, [kava16vm...sw8](https://www.mintscan.io/kava/account/kava16vmp7sz28pnvgz6f3zm6q93y39jsd33age3sw8), Kujira, channel-95, [kujira14uy...2hk](https://finder.kujira.network/kaiyo-1/address/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk)

Kava, channel-116, [kava14uy...0vm](https://www.mintscan.io/kava/account/kava14uyfxlv00lj0qhcwt7vms2rsf7kxuld7g4v0vm), Kujira, channel-95, [kujira1evd...gxj](https://finder.kujira.network/kaiyo-1/address/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

Kava, channel-128, [kava14uy...0vm](https://www.mintscan.io/kava/account/kava14uyfxlv00lj0qhcwt7vms2rsf7kxuld7g4v0vm), Ixo, channel-25,[ixo14uy...q70](https://www.mintscan.io/ixo/account/ixo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7t4xq70)

Kava, channel-142, [kava14uy...0vm](https://www.mintscan.io/kava/account/kava14uyfxlv00lj0qhcwt7vms2rsf7kxuld7g4v0vm), Coreum, channel-18, [core14uy...fa8](https://www.mintscan.io/coreum/account/core14uyfxlv00lj0qhcwt7vms2rsf7kxuld78wqfa8)

---------------- 

### _Ki Chain_ 

Ki chain, channel-0, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Osmosis, channel-77, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Ki chain, channel-1, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Cosmos, channel-223, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Ki chain, channel-11, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Gravity Bridge, channel-37, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws)

Ki chain, channel-19, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Axelar, channel-17, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

---------------- 

### _Kujira_ 

Kujira, channel-0, [kujira1evdj...gxj](https://finder.kujira.network/kaiyo-1/address/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), Cosmos, channel-343, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq)

Kujira, channel-3, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk), Osmosis, channel-259, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

Kujira, channel-7, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), Stargaze, channel-49, [star1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf)

Kujira, channel-9, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), Axelar, channel-14, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Kujira, channel-11, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk), Gravity Bridge, channel-83, [gravity16vpm...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag)

Kujira, channel-19, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk), Lum, channel-7, [lum1evdj...e7v](https://www.mintscan.io/lum/account/lum1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt95ae7v)

Kujira, channel-21, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), E-money, channel-27, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9)

Kujira, channel-31, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), Juno, channel-97, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu)

---------------- 

### _Kyve_ 

----------------

### _Lum_ 

Lum, channel-3, [lum1evdj...e7v](https://www.mintscan.io/lum/account/lum1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt95ae7v), Osmosis , channel-97, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu)

Lum, channel-7, [lum1evdj...e7v](https://www.mintscan.io/lum/account/lum1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt95ae7v), Kujira , channel-19, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk)

----------------

### _Osmosis_ 

Osmosis , channel-0, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw), Cosmos , channel-141, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u)

Osmosis , channel-37, [osmo16vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj), E-money , channel-0, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9)

Osmosis , channel-38, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw), Ixo , channel-4, [ixo1evdj...z0t](https://www.mintscan.io/ixo/account/ixo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt0t7z0t)

Osmosis , channel-47, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw), Sifchain , channel-4, [sif14uyf...y4h](https://www.mintscan.io/sifchain/account/sif14uyfxlv00lj0qhcwt7vms2rsf7kxuld73ahy4h)

Osmosis , channel-51, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2), Bitcanna , channel-1, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2)

Osmosis , channel-75, [osmo16vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj), Stargaze , channel-0, [star1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf)

Osmosis , channel-77, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2), Ki Chain , channel-0, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)

Osmosis , channel-115, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Lum , channel-3, [lum1evdj...e7v](https://www.mintscan.io/lum/account/lum1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt95ae7v)

Osmosis , channel-135, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Desmos , channel-2, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq)

Osmosis , channel-143, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2), Kava , channel-1, [kava1evdj...dal](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal)

Osmosis , channel-144, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Gravity Bridge , channel-10, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag)

Osmosis , channel-148, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Band , channel-83, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns)

Osmosis , channel-169, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2), Juno , channel-47, [juno1evdj...tvy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Osmosis , channel-181, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw), Decentr , channel-1, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s)

Osmosis , channel-208, [osmo16vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj), Axelar , channel-3, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Osmosis , channel-221, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Rizon , channel-1, [rizon1evdj...p8q](https://www.mintscan.io/rizon/account/rizon1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptnrup8q)

Osmosis , channel-222, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw), Provenance , channel-7, [pb16vmp...g4u](https://www.mintscan.io/provenance/account/pb16vmp7sz28pnvgz6f3zm6q93y39jsd33aazwg4u)

Osmosis , channel-229, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2), Fetch , channel-10, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0)

Osmosis, channel-236, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Galaxy, channel-0, [galaxy1evdj...sq2](https://explorer.postcapitalist.io/cosmos/account/galaxy1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvpxsq2)

Osmosis , channel-259, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Kujira , channel-3, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk)

Osmosis , channel-362, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9), Teritori , channel-0, [tori1evdj...esg...2hk](https://teritori.explorers.guru/account/tori1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptj2hesg)

----------------

### _Passage_ 

----------------

### _Provenance_ 

Provenance , channel-7, [pb16vmp...g4u](https://www.mintscan.io/provenance/account/pb16vmp7sz28pnvgz6f3zm6q93y39jsd33aazwg4u), Osmosis , channel-222, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Provenance , channel-6, [pb16vmp...g4u](https://www.mintscan.io/provenance/account/pb16vmp7sz28pnvgz6f3zm6q93y39jsd33aazwg4u), Cosmos, channel-314, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u)

----------------

### _Quasar_ 

----------------

### _Stargaze_ 

Stargaze , channel-0, [star1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf), Osmosis , channel-75, [osmo16vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj)

Stargaze , channel-5, [stars1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf), Juno, channel-20, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), 

Stargaze , channel-6, [stars14uyf...03d](https://www.mintscan.io/stargaze/account/stars14uyfxlv00lj0qhcwt7vms2rsf7kxuld7qu003d), Gravity Bridge, channel-7, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5)

Stargaze, channel-45, [stars14uyfxl...03d](https://www.mintscan.io/stargaze/account/stars14uyfxlv00lj0qhcwt7vms2rsf7kxuld7qu003d), Sifchain , channel-71, [sif16vmp...mht](https://www.mintscan.io/sifchain/account/sif16vmp7sz28pnvgz6f3zm6q93y39jsd33a332mht)

Stargaze, channel-49, [star1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf), Kujira, channel-7, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

Stargaze, channel-50, [stars1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf), Axelar, channel-18, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

----------------

### _Teritori_ 

Teritori , channel-0, [tori1evdj...esg...2hk](https://teritori.explorers.guru/account/tori1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptj2hesg), Osmosis , channel-362, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

Teritori , channel-10, [tori1evdj...esg...2hk](https://www.mintscan.io/teritori/account/tori14uyfxlv00lj0qhcwt7vms2rsf7kxuld7k50mpv), Cosmos , channel-431, [cosmos16vmp...9dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq)

Teritori , channel-11, [tori1evdj...esg...2hk](https://www.mintscan.io/teritori/account/tori14uyfxlv00lj0qhcwt7vms2rsf7kxuld7k50mpv), Juno , channel-164, [juno16vmp...xklu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu)

----------------
