# Relayers

Our relayer infra is selfhosted with gigabyte fiber connection. We are running four instances of hermes which support 22 chains. Our RPC are host on three baremetal servers. You will find in this repository a description of our servers, the conf of our relayers and the set of channels that we support.

## Server

One Intel(R) Xeon(R) CPU E5-2650 (12C/24T)v4 @ 2.20GHz, 96GB ECC RAM, 2X1TB + 1X2TB M2 Nvme for RPC, 4X1TB SSD for services  
One Intel(R) Xeon(R) Silver 4214 CPU @ 2.20GHz, 288GB ECC RAM, 2 X ASUS Hyper M.2 x16 Gen 4, 8X1TB + 1X2TB M2 Nvme for rpc, 4X1TB SSD for services  

One AMD Ryzen 9 5900X @ 3,7 Ghz, 128GB ECC RAM, 1 X ASUS Hyper M.2 X16 PCIe 3.0, 6X1TB M2 Nvme for rpc, 1TB SSD for services


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
[Juno](https://github.com/Inter-Blockchain-Service/Relayers/blob/main/README.md#juno)  
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

Axelar, channel-3, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Osmosis, channel-208, [osmo16vmp...awj](https://www.mintscan.io/osmosis/account/osmo16vmp7sz28pnvgz6f3zm6q93y39jsd33auhkawj)  

Axelar, channel-4, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Juno, channel-71, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu)  

Axelar, channel-6, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), E Money, channel-26, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9)  

Axelar, channel-14, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Kujira, channel-9, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)  

Axelar, channel-15, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Bitcanna Chain, channel-32, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2)  

Axelar, channel-17, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Ki Chain, channel-19, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)  

Axelar, channel-18, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np), Stargaze, channel-50, [stars1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf)

Axelar, channel-21, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe), Fetch AI, channel-14, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0) 

----------------  

### _Band_ 

Band , channel-12, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), Desmos, channel-1, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), ibc-profiles   

Band , channel-83, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), Osmosis, channel-148, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)  

---------------- 

### _Bitcanna_ 

Bitcanna , channel-1, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Osmosis , channel-51, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Bitcanna, channel-3, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Cosmos , channel-232, [cosmo1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Bitcanna , channel-8, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Gravity Bridge , channel-0, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws)

Bitcanna , channel-10, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Juno , channel-50, [juno1evdj...tvy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Bitcanna , channel-15, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2), Axelar , channel-32, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

----------------

### _Celestia_

----------------

### _Chihuahua_

----------------

### _Coreum_

---------------- 

### _Cosmos Hub_ 

Cosmos, channel-141, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Osmosis , channel-0, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Cosmos, channel-192, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Sifchain , channel-0, [sif14uyf...y4h](https://www.mintscan.io/sifchain/account/sif14uyfxlv00lj0qhcwt7vms2rsf7kxuld73ahy4h)

Cosmos, channel-207, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Juno , channel-1, [juno1evdj...9np](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Cosmos, channel-223, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Ki Chain , channel-1, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)

Cosmos, channel-232, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Bitcanna , channel-3, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2)

Cosmos, channel-277, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc), Kava , channel-0, [kava1evdj...9np](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal)

Cosmos, channel-281, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Gravity Bridge , channel-17, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5)

Cosmos, channel-293, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq), Axelar , channel-2, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Cosmos, channel-314, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u), Provenance , channel-6, [pb16vmp...g4u](https://www.mintscan.io/provenance/account/pb16vmp7sz28pnvgz6f3zm6q93y39jsd33aazwg4u)

Cosmos, channel-343, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq), Kujira , channel-0, [kujira16vmp...9np](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

Cosmos , channel-431, [cosmos16vmp...9dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq),Teritori , channel-10, [tori1evdj...esg...2hk](https://www.mintscan.io/teritori/account/tori14uyfxlv00lj0qhcwt7vms2rsf7kxuld7k50mpv)

---------------- 

### _Decentr_ 

Decentr, channel-1, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s), Osmosis , channel-181, [osmo14uyf...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Decentr, channel-2, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s), Gravity Bridge , channel-58, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5)

---------------- 

### _Desmos_ 

Desmos, channel-1, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), Band , channel-12, [band1evdj...jns](https://www.mintscan.io/band/account/band1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptf3qjns), oracle

Desmos, channel-2, [desmos1evdj...quq](https://www.mintscan.io/desmos/account/desmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyxdquq), Osmosis , channel-12, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

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

Fetch, channel-10, [fetch1evdj...5f0](https://www.mintscan.io/fetchai/account/fetch1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptrrf5f0), Axelar , channel-21, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

---------------- 

### _Gravity Bridge_ 

Gravity Bridge, channel-0, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws), Bitcanna , channel-8, [bcna1evdj...3r2](https://www.mintscan.io/bitcanna/account/bcna1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt2ws3r2)

Gravity Bridge, channel-7, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Stargaze , channel-6, [stars14uyf...03d](https://www.mintscan.io/stargaze/account/stars14uyfxlv00lj0qhcwt7vms2rsf7kxuld7qu003d)

Gravity Bridge, channel-8, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws), Juno , channel-31, [juno1evdj...tvy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Gravity Bridge, channel-10, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Osmosis , channel-144, [osmo1tdl8...ej9](https://www.mintscan.io/osmosis/account/osmo1tdl8wlqx0w8laeqytxx9rphfcu7cm2cyqahej9)

Gravity Bridge, channel-17, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Cosmos , channel-281, [cosmos14uyf...j6u](https://www.mintscan.io/cosmos/account/cosmos14uyfxlv00lj0qhcwt7vms2rsf7kxuld75qcj6u)

Gravity Bridge, channel-37, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws), Ki Chain , channel-11, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)

Gravity Bridge, channel-53, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Rizon , channel-4, [rizon1evdj...p8q](https://www.mintscan.io/rizon/account/rizon1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptnrup8q)

Gravity Bridge, channel-58, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Decentr , channel-2, [decentr1evdj...y2s](https://ping.pub/decentr/account/decentr1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptmsxy2s)

Gravity Bridge, channel-66, [gravity14uyf...2l5](https://www.mintscan.io/gravity-bridge/account/gravity14uyfxlv00lj0qhcwt7vms2rsf7kxuld7ss22l5), Sifchain , channel-60, [sif14uyf...y4h](https://www.mintscan.io/sifchain/account/sif14uyfxlv00lj0qhcwt7vms2rsf7kxuld73ahy4h)

Gravity Bridge, channel-83, [gravity16vmp...4ag](https://www.mintscan.io/gravity-bridge/account/gravity16vmp7sz28pnvgz6f3zm6q93y39jsd33asuh4ag), Kujira , channel-11, [kujira14uyf...2hk](https://www.mintscan.io/kujira/account/kujira14uyfxlv00lj0qhcwt7vms2rsf7kxuld79g62hk)

---------------- 

### _Ixo_ 

Ixo, channel-4, [ixo1evdj...z0t](https://www.mintscan.io/ixo/account/ixo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt0t7z0t), Osmosis , channel-38, [osmo1...zvw](https://www.mintscan.io/osmosis/account/osmo14uyfxlv00lj0qhcwt7vms2rsf7kxuld7umtzvw)

Ixo, channel-11, [ixo1evdj...z0t](https://www.mintscan.io/ixo/account/ixo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt0t7z0t), Sifchain , channel-15, [sif14uyf...y4h](https://www.mintscan.io/sifchain/account/sif14uyfxlv00lj0qhcwt7vms2rsf7kxuld73ahy4h)

---------------- 

### _Juno_ 

Juno, channel-0, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy), Osmosis, channel-42, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Juno, channel-1, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy), Cosmos, channel-207, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Juno, channel-5, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), Sifchain , channel-14, [sif16vmp...mht](https://www.mintscan.io/sifchain/account/sif16vmp7sz28pnvgz6f3zm6q93y39jsd33a332mht)

Juno, channel-9, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), E-Money , channel-15, [emoney1evdj...yu9](https://www.mintscan.io/emoney/account/emoney1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptla6yu9)

Juno, channel-20, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), Stargaze , channel-5, [stars1evdj...dqf](https://www.mintscan.io/stargaze/account/stars1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptyzhdqf)

Juno, channel-31, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy), Gravity Bridge, channel-8, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws)

Juno, channel-47, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy), Osmosis, channel-169, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2), CW20

Juno, channel-50, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy), Juno , channel-50, [juno1evdj...tvy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Juno, channel-58, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy), Ki Chain, channel-8, [ki1evdj...l0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v)

Juno, channel-71, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), Axelar , channel-4, [axelar16vmp...9np](https://www.mintscan.io/axelar/account/axelar16vmp7sz28pnvgz6f3zm6q93y39jsd33aszn9np)

Juno, channel-87, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), Kujira , channel-1, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj)

Juno, channel-97, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), Kujira , channel-31, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), CW20

Juno , channel-164, [juno16vmp...xklu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu), Teritori , channel-11, [tori1evdj...esg...2hk](https://www.mintscan.io/teritori/account/tori14uyfxlv00lj0qhcwt7vms2rsf7kxuld7k50mpv)

---------------- 

### _Kava_ 

Kava, channel-0, [kava1evdj...dal](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal), Cosmos, channel-277, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Kava, channel-1, [kava1evdj...dal](https://www.mintscan.io/kava/account/kava1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptvt5dal), Osmosis, channel-143, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

---------------- 

### _Ki Chain_ 

Ki chain, channel-0, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Osmosis, channel-77, [osmo1evdj...qa2](https://www.mintscan.io/osmosis/account/osmo1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptc9nqa2)

Ki chain, channel-1, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Cosmos, channel-223, [cosmos1evdj...stc](https://www.mintscan.io/cosmos/account/cosmos1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpts7qstc)

Ki chain, channel-7, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Sifchain, channel-40, [sif1evdj...xyn](https://www.mintscan.io/sifchain/account/sif1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt4r0xyn)

Ki chain, channel-8, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Juno, channel-58, [juno1evdj...vy](https://www.mintscan.io/juno/account/juno1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptxvrtvy)

Ki chain, channel-11, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Gravity Bridge, channel-37, [gravity1evdj...gws](https://www.mintscan.io/gravity-bridge/account/gravity1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5wjgws)

Ki chain, channel-19, [ki1evdj...0v](https://www.mintscan.io/ki-chain/account/ki1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpn3l0v), Axelar, channel-17, [axelar1evdj...cqe](https://www.mintscan.io/axelar/account/axelar1evdjzy3w9t2yu54w4dhc2cvrlc2fvnpt5skcqe)

---------------- 

### _Kujira_ 

Kujira, channel-0, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), Cosmos, channel-343, [cosmos16vmp...dcq](https://www.mintscan.io/cosmos/account/cosmos16vmp7sz28pnvgz6f3zm6q93y39jsd33a5v9dcq)

Kujira, channel-1, [kujira1evdj...gxj](https://www.mintscan.io/kujira/account/kujira1evdjzy3w9t2yu54w4dhc2cvrlc2fvnptpkzgxj), Juno, channel-87, [juno16vmp...klu](https://www.mintscan.io/juno/account/juno16vmp7sz28pnvgz6f3zm6q93y39jsd33az7xklu)

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
