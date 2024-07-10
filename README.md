# 开发一个完整的NFTMarket的Dapp

## 目标
编写一个智能合约，实现一个完整的NFTMarket Dapp功能，允许用户上架、下架NFT并使用自己部署的ERC20代币进行购买

## 主要功能
- 部署ERC20代币
- 部署NFT用于买卖
- 用户可以将自己的NFT上架到市场，上架时需要指定NFT的合约地址、Token ID以及价格（使用ERC20代币）
- 下架NFT的功能，用户可以在上架NFT后、被别人购买前下架NFT
- 购买NFT，用户可以使用自己部署的ERC20代币购买上架的NFT，购买成功后，NFT转移给买家，卖家收到ERP20代币
- 在Market界面展示出所有上架的NFT（图片、NFT信息）
- NFT信息包括（价格、上架时间、拥有者）

## 测试效果
### 上架
![list](./assets/list.jpg)

### 下架
![delist](./assets/delist.jpg)

### 购买
![buy](./assets/buy.jpg)

