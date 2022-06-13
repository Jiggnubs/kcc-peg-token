# kcc-peg-token
KuCoin Community Chain Peg Token Factory

## Install dependency
```shell
npm install
```

## Compile
```shell
npm run compile
```

## Run unittest
```shell
npm run test
```


# Mainnet
```javascript
╔═══════════════════════════════╤════════╤══════════╤════════════════════════════════════════════╗
║ name                          │ symbol │ decimals │ address                                    ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ Wrapped KCS                   │ WKCS   │ 18       │ 0x4446Fc4eb47f2f6586f9fAAb68B3498F86C07521 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ Factory                       │        │          │ 0x6B3BbB4075c562C0786F289Fc52d7c85be2318FA ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Tether USD            │ USDT   │ 18       │ 0x0039f574eE5cC39bdD162E9A88e3EB1f111bAF48 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg USD Coin              │ USDC   │ 18       │ 0x980a5AfEf3D17aD98635F6C5aebCBAedEd3c3430 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg BTCK Token            │ BTCK   │ 18       │ 0xfA93C12Cd345c658bc4644D1D4E1B9615952258C ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Ether                 │ ETH    │ 18       │ 0xf55aF137A98607F7ED2eFEfA4cd2DfE70E4253b1 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Uniswap               │ UNI    │ 18       │ 0xEe58E4D62b10A92dB1089d4D040B759C28aE16Cd ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Chainlink             │ LINK   │ 18       │ 0x47841910329aaa6b88D5e9DcdE9000195151dc72 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Crypto.com Coin       │ CRO    │ 18       │ 0x652D253b7Ca91810A4a05ACFc39729387c5090C0 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg The Graph             │ GRT    │ 18       │ 0xb49dd3eDB98FBe82A01DFcb556Cd016964baf5A3 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Maker                 │ MKR    │ 18       │ 0xdE81028C743f5304fe2cdEfac588f572d629a687 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Quant                 │ QNT    │ 18       │ 0x791630C11c7159A748d8c2267a66780B3DDC40a7 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Compound              │ COMP   │ 18       │ 0x16c4106966cE30e06E806A7c40eEFb46d84cE7e5 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Synthetix             │ SNX    │ 18       │ 0x31965b5c9c55f5579eb49F4b3AcC59aA10a7B98E ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Chiliz                │ CHZ    │ 18       │ 0x6E8ce0519B7e4d691BaCE464099547E5fC17679c ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Enjin Coin            │ ENJ    │ 18       │ 0x6e2D990C8e718E7b6D86ed08eBf0FF2dEc05253B ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg TrueUSD               │ TUSD   │ 18       │ 0xD17027b85Abf02721F953EE528721A980fa58941 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg yearn.finance         │ YFI    │ 18       │ 0xdfa3Ef49d357c6b0B2DfBB88701af2b7A053fD0A ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Telcoin               │ TEL    │ 18       │ 0x621C1E8610e4B9b7fc9F043203C008EDe52E92F5 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Nexo                  │ NEXO   │ 18       │ 0xb7A18bd55e8E3E2262d7c8Ee7b4DD9B216Df0Faf ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Basic Attention Token │ BAT    │ 18       │ 0x0bF46C86Ce3B904660aE85677EaA20B0C1b24064 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Paxos Standard        │ PAX    │ 18       │ 0x69a7169F9Da9BBa04b982e49Ffd8d6a16c70c590 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg HUSD                  │ HUSD   │ 18       │ 0xBEc1e1009CE00ECf7F16372451Ac849b39C32897 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg 1INCH Token           │ 1INCH  │ 18       │ 0x79f3244F3FFd7500A31a90Bb83C7D56649c2C7C5 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg SHIBA INU             │ SHIB   │ 18       │ 0x73b6086955c820370A18002F60E9b51FB67d7e1A ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Curve DAO Token       │ CRV    │ 18       │ 0x4500E16dA66b99e0C55D7B46EBBD59bc413BA171 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg SushiSwap             │ SUSHI  │ 18       │ 0xE0a60890BB7F9250089455620063fb6fe4DC159a ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Aave Token            │ AAVE   │ 18       │ 0xE76e97C157658004eE22e01C03a5e21A4655A2Fd ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg DODO                  │ DODO   │ 18       │ 0x8724F9FB7B3f1bb6f2c90B3Ad3Fd6B3c20A06429 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Polygon               │ MATIC  │ 18       │ 0x1B8e27ABA297466fc6765Ce55BD12A8E216759da ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Balancer              │ BAL    │ 18       │ 0xFC31366Be1795c1Ff444b9fBF55759733aD4d26D ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Decentraland          │ MANA   │ 18       │ 0xC19a5caCC2bb68Ff09f2Fcc695F31493A039Fa5e ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Spice                 │ SFI    │ 18       │ 0xd55D9DF77B23A7455613f2244Ee4B6a45b6e2D00 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Umbrella              │ UMB    │ 18       │ 0xD61BAbA0E2646544c1ef59acab081529467cE918 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Waves                 │ WAVES  │ 18       │ 0xD46bA0A3547a6b9C2040eD8b259c5F6830278141 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Gala                  │ GALA   │ 18       │ 0xdfB59EE64A97C9E12c588cF3ca5FeE814FE0680c ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Terra                 │ LUNA   │ 18       │ 0xF429E1B220C35Df18598a65424bEC377f2A82fAe ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Optimism              │ OP     │ 18       │ 0xB166BCd58a01317e4969F2376F430b0890f91e1c ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Dogecoin              │ DOGE   │ 18       │ 0x0b3604f103BF53D85A4b581caA7b264272156A3f ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg XRP                   │ XRP    │ 18       │ 0x0ad7D767fD4aF9F42DDa46130ddC46CF413720d2 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg TRON                  │ TRX    │ 18       │ 0xeA0E1820bd127355a17be53A50f81267af50f7e4 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg NEAR Protocol         │ NEAR   │ 18       │ 0x46BD632c3A2aCAAdDb3c0a31D1abEdA7fFFc58C1 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Cosmos Hub            │ ATOM   │ 18       │ 0xc38578e395160f728121e0C2f3C7805Ac238aa3b ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Solana                │ SOL    │ 18       │ 0x390296f96B1bdEe35A91cD82372BF9363d802678 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Kava                  │ KAVA   │ 18       │ 0xFeEdf5F9127e806B025707D9A410140F5D1442C5 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Cardano               │ ADA    │ 18       │ 0xfDc1B1E6B6207B8638e638AbE2E02dcA77D6E1CC ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Stellar               │ XLM    │ 18       │ 0x041D249278ed659A96E62061a6ea5DaF6753Aab2 ║
╟───────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Origin Protocol       │ OGN    │ 18       │ 0x00C6D1D43483aa7Cbeae886eC4E802fC296CD749 ║
╚═══════════════════════════════╧════════╧══════════╧════════════════════════════════════════════╝
```


# Testnet
```javascript
╔════════════════════════════╤════════╤══════════╤════════════════════════════════════════════╗
║ name                       │ symbol │ decimals │ address                                    ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ Wrapped KCS                │ WKCS   │ 18       │ 0x6551358EDC7fee9ADAB1E2E49560E68a12E82d9e ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ Factory                    │        │          │ 0x8f763FF0e3d9D551De95527E46dF3876D9f4918a ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Wrapped BTC        │ WBTC   │ 18       │ 0xf57a7eE19a628e4d475b72d6c9DD847c50636e01 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Wrapped Ether      │ WETH   │ 18       │ 0xF8Cb9f1D136Ff4c883320b5B4fa80048b888F459 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Tether USD         │ USDT   │ 18       │ 0x67f6a7BbE0da067A747C6b2bEdF8aBBF7D6f60dc ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg USD Coin           │ USDC   │ 18       │ 0xD6c7E27a598714c2226404Eb054e0c074C906Fc9 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Uniswap            │ UNI    │ 18       │ 0xA4d35720Fe0B62c0eea9D272F5ea73189093ec82 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg ChainLink Token    │ LINK   │ 18       │ 0x040fBFd760C3dCA12F3f67D54A09dcB13877eaA5 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Aave Token         │ AAVE   │ 18       │ 0x4e5839b4E651da7071Fbd617bF1dDefb5f33A9DB ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Dai Stablecoin     │ DAI    │ 18       │ 0x07d169F52fCB96a9f56325f510528E0D65ca4952 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Maker              │ MKR    │ 18       │ 0x9Afb5acd8288F30047cb59c3acEff4c85602B069 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg SHIBA INU          │ SHIB   │ 18       │ 0x38825EaF53ac2ECC01Ecae28Fc3c1e5220dEAD7C ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg FTX Token          │ FTT    │ 18       │ 0xB20A491fC1d9689c2A3d6766502F8796B7A016D1 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Crypto.com Coin    │ CRO    │ 18       │ 0x376eDaADb16cF8De8D373113017fa62DBFeDD6Ad ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg HuobiToken         │ HT     │ 18       │ 0x3EC5b948F0cB8869fcE80A840Ae9d23C242CA658 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Compound           │ COMP   │ 18       │ 0x92dB35c063DD7b8D6cC0CF373130Ff83e8A08617 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Bitfinex LEO Token │ LEO    │ 18       │ 0xBb740Aca24CAD73A2742B654426f660B45C62d1D ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Wrapped UST Token  │ UST    │ 18       │ 0x662BCf8BCbAE918528Cb0E3c855D899A245f9D6E ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg Telcoin            │ TEL    │ 18       │ 0x69F436180BDE67A5C7e1893B74b942d6aD24b8B3 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg chiliZ             │ CHZ    │ 18       │ 0x8eBc9Dec6239355a7ABebDFf31Eaff650e229A43 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg yearn.finance      │ YFI    │ 18       │ 0x299814b885ecC391Ec5962ca159a7d09ad078ca6 ║
╟────────────────────────────┼────────┼──────────┼────────────────────────────────────────────╢
║ KCC-Peg HoloToken          │ HOT    │ 18       │ 0x2a876f31124397400CBeE0bF1865c9Af8d9aAb78 ║
╚════════════════════════════╧════════╧══════════╧════════════════════════════════════════════╝
```