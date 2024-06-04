# Dex223-test deployment

### Sepolia deployment from 17.05.2024. Current

- ABI files: [GitHub](https://github.com/Exzender/Dex223-ABI/tree/main/Sepolia_Double_17-05-2024) 
- Pool Library: 0xE191D7cC4dD4E54F2026EAB36d14CBEf6562c8Cb Verified
- Converter: 0x1245c83de3cc16193de8777ed597b677d789ac94 Verified
- Factory: 0xC7D28E12Bc1744Ac2C78A893F6282412e6D620ab Verified
- NFPM: 0x7dD0c4971FCdB887A13bc377F5C9B94dc88cE74b Verified
- SwapRouter: 0x4e596Bbf211Ef63B1b854728319EA193F175d856 Verified
- Quoter: 0xb47b1598acb61E5604f7D6944120db758E1CeCE4 ERC20 Only Verified
- POOL_INIT_CODE_HASH:
0xeec262796ecc14445f5c61bc47690b549e0fb69dbc0b99b87ae5b61b9707cdf5

#### Pools
- Pool ERC20/ERC223/ERC20/ERC223 ( fee = 3000 ) ( WETH / USDC ) : 
0xC6F53004069bD066EC33C13F0B43E1212B9053D6


### Tokens (Sepolia) ( 03.04.2024; 17.05.2024)

- WETH  ( ERC20 / decimals = 18 ) : 0xb16F35c0Ae2912430DAc15764477E179D9B9EbEa
- WETH223 ( ERC223 / converted ) : 0x4b113093b80700b3c6cfbcaf6c2600e99f419dc2
- USDC ( ERC20 / decimals = 18 / free mint ) : 0xfCCB28483d26EadB90A11cD50e09c12E553fFb22
- WUSDC223 ( ERC223 / converted ) : 0xab70db5e9a39c2671c9635f2fda1f956b5fc070b
- WUSDC223 ( ERC223 / converted on 04.04.2024) : 0xc1F8D30360a653DF760CF154463135fA246d0BeA
- USDT ( ERC20 / decimals = 6 / free mint ) : 0x8dD8F439D3478Badb814F7b84d7a06d467eD3812
- USDT ( ERC223 / converted ) : 0xCa3A4a1C28335fd622d1aB3c763cdD9875C329EE
- DAI ( ERC20 / decimals = 18 / free mint ) : 0x1e6951b73f44E7C71B43Dfc1FFA63cA2eab2cEdA
- TSP1  ( ERC20 / decimals = 18 ) : 0x7F4C5c87C630b3f8a2265FD76413E7d6C7DEbFB4
- TSP2  ( ERC20 / decimals = 6 ) : 0x73a68acd477ABf858fd3b18a9A13d080B781cbE5
- TSP3  ( ERC20 / decimals = 0 ) : 0x78B2BebFb31788372F449a8fD7b9BA7B654B03E4
- TSP4  ( ERC20 / decimals = 18 ) : 0x4817B28641eec4D43266A3BA3347D6d4b8401Ac3
- TSP5  ( ERC20 / decimals = 10 ) : 0x19CE05d621b89cC59c49ebDD36dF9066234963c5
- TSP6  ( ERC20 / decimals = 6 ) : 0xf886E984F9519641fD6C5F78F1573094c6037365


### Sepolia deployment from 01.05.2024 (double standard + external library)
- Pool Library : 0x364b988cf87add09a63b93afbe961b99ff9d5bfa
- Factory (Dex223Factory) : 0xb0085429ff43a2a51ec1b1ac8956a35c19ec008e
- POOL_INIT_CODE_HASH="0xab833028026788c713a927db0b749989cac2bdfce76df735761cac2f9c3ec069"
- NonfungiblePositionManager (DexaransNonfungiblePositionManager) : 0x250155fca186afd41349097791bfffdb2c4c7c28
- SwapRouter (ERC223SwapRouter) : 0xf5bf22509f1368a65b758655ee60522bbe7e4e92
- Quoter (ERC223Quoter) (only for ERC20) : 0x9d5af46fbd55a742969eac7710d54aeff4ace4d9
- Token Converter : 0x1245c83de3cc16193de8777ed597b677d789ac94
- Pool ERC20/ERC223/ERC20/ERC223 ( fee = 10000 ) (USDT / WETH) : 0x56d677f57eba9a64391ffa8228f09217da131f5b
- Pool ERC20/ERC223/ERC20/ERC223 ( fee = 3000 ) ( WETH / USDC ) : 0x63e5f520f5d7603907084d59557e03b7bdb2d021


### Sepolia deployment from 03.04.2024
- Factory (Dex223Factory): 0x41368e68e2eb0a74cba9d4f6b418b487b7df5e58
- POOL_INIT_CODE_HASH="0xb7112e06e4c5b0e55a0560f43cfd041a98b718a5554606cfe637eb31021cc257"
- NonfungiblePositionManager (DexaransNonfungiblePositionManager): 0xc70b2f2db899b8d0e73ee53dbc4b40a12d0e2be5
- SwapRouter (ERC223SwapRouter) : 0xd71B50caF51f39657BA358759c54777FA44357Fb
- Quoter (ERC223Quoter) : 0x16d1672ed60d4618d2f33ffa84eff9c6a074fbce
- QuoterV2 (ERC223QuoterV2) : 0xb77b5e42920957d728174e77f71cd83de15571ee
- Pool ERC223/ERC20 (Dex223 Token B223 / Dex223 Token B): 0x383Abb4CE818b9AB021cb296dCB52328fa602946
- Pool ERC20/ERC20 ( fee = 500 ) (WETH / USDC) : 0x7515e71c06033B9ecBC5993a99c4B7B4b3dDC4d7
- Pool ERC223/ERC223 ( fee = 3000 ) (WETH223 / WUSDC223) : 0xA86BA84f5ab8a57f2C1087888d1376eE26bCBD93
- Token Converter (04.04.2024) : 0x69081d893e9e57e0f333abb9288530370b0c5170
- Token Converter (11.04 with Predict) : 0xbff9cc14137d70c1c589cd5208f228bf2df2cd2c

### Sepolia deployment from 15.03.2024
UniswapV3-compatible contract addresses can be found here.
- Test token B (ERC-20) https://sepolia.etherscan.io/address/0x723fe0a6415a25ec74cf0c4cf33f600f001d1aec
- Test token C (ERC-20) https://sepolia.etherscan.io/address/0xfd5493fc83ce4fe44c951aa244946bd652ac0361#writeContract
- Test token B ERC-223 version https://sepolia.etherscan.io/address/0x1d796072232c797CD07892FffAb79170af07E5d7
- Test token C ERC-223 version https://sepolia.etherscan.io/address/0x3cd18a6f06f1daf91456347e9e3972b8c532d123
- Token Converter https://sepolia.etherscan.io/address/0x258e392a314034eb093706254960f26a90696d4c
- DexaransNonfungiblePositionManager https://sepolia.etherscan.io/address/0xd1d33877abad475d4cb134a3bf87570291cdc305
- Old DexaransNonfungiblePositionManager (almost identical code, minor ERC-223 withdrawal pattern modifications) https://sepolia.etherscan.io/address/0x03bbd7ecb38ef839683ba50319a31bb7dee78da4

### Example transactions
#### ERC-223 liquidity minting:
Deposit token0 to NonfungiblePositionManager https://sepolia.etherscan.io/tx/0x1a8231c68bc88d9a317d04b25aa5a07087445d56ca9e4e2795700ebf238810d2  
Deposit token1 to NonfungiblePositionManager https://sepolia.etherscan.io/tx/0xa185fd6e8b913f09711e89d870c2862b1836fd03120f292ecb3f6763f995365e 
#### Call mint() in NonfungiblePositionManager https://sepolia.etherscan.io/tx/0x0d83830f8703cbf21ce191e37859d69865d3c531ebf031e0bf70b51ecb289606
ERC-20 liquidity minting (note: in this example the ERC-20 depositing pattern is executed with a hybrid token. Hubrid-standard tokens can support both ERC-20 and ERC-223 depositing methods):
Approve token0 to NonfungiblePositionManager https://sepolia.etherscan.io/tx/0x643b7107fd4204c99f0775c4670aa5dff8213599c82f143c25ff494795fa48c4
Approve token1 to NonfungiblePositionManager https://sepolia.etherscan.io/tx/0x09019d1ce6d92317466ec12048c71c028536ea671cf37f73352e15a0dacc0872
#### Call mint() in NonfungiblePositionManager https://sepolia.etherscan.io/tx/0xc48c0a5a7e77ec24bafcabaee080c603227e12b5d8bf10f018e17ea7687f270b
Converting a ERC-20 token to ERC-223 version via TokenConverter:
#### Call createERC223Wrapper() for a given ERC-20 token in TokenConverter if it doesn't exist yet. The transaction will fail if the wrapper already exists https://sepolia.etherscan.io/tx/0xc7ad7df25a98f44ffa0c9720446b6e0930d151f04c4bfa9aeaa7af436157458c
Approve ERC-20 token to TokenConverter https://sepolia.etherscan.io/tx/0x4a7be3c861c2c9869268bdced6cde2638d5900f25ced2f54b5ede561898215be
#### Call wrapERC20toERC223() in TokenConverter https://sepolia.etherscan.io/tx/0x06e01021d6998023759b2d887b7bc7775374b8a2043313f580d25b445a10c24c
ERC-223 swap via SwapRouter:
#### Call Transfer (with _data) of WUSDC223 token to SwapRouter address. Data contains call to exactInputSingle1 function with parameters of SwapRouter. https://sepolia.etherscan.io/tx/0x5d421813355f2f510779bfe5eaf5d30cca631344b2f3782b447e73fa5f860e6b

