# DApps for TokenPocket
### Overview
This repo is to add and update the DApps and DApp logos on TokenPocket according to the community requirements. Once the PR is merged, your DApp or logo will be updated on TokenPocket. Please read the following tutorials.

### Donation for DApp listing
According to the DAO, the donation amount for a DApp listing or update has been voted to be 200,000 TPT. Click [here](https://snapshot.org/#/tptdao.eth/proposal/0x3f6f81046588af5a89062de6bea4dc92de67fa380cb1823babcf8dde3415f1ad) for details

### How to submit
TBD, similar to [token logo](https://tphelp.gitbook.io/en/wallet-operation/how-to-submit-a-token-logo)

### About Chains that DApps supported

1.Appoint EVM Chain. When need to appoint DApp is support Ethereum, Binance Smart Chain, the field as follow

```
[{
		"network": "ethereum",
		"chain_id": "1"
	},
	{
		"network": "ethereum",
		"chain_id": "56"
	}
]
```
differentiate through chain_id，it applies to all EVM chain

2.Appoint network like Tron, Solana, ect. Differentiate chain through the symbol of native token

```
[{
	"network": "SOL"
}, {
	"network": "TRX"
}]
```

3.Appoint Polkadot series chain. Differentiate chain through ss58

```
[{
	"network": "polkadot",
	"ss58": "0"
}, {
	"network": "polkadot",
	"ss58": "2"
}, {
	"network": "polkadot",
	"ss58": "27"
}]
```



# TokenPocket DApps提交指南
### Overview
本仓库是根据社区需求在 TokenPocket 上添加和更新 DApp 和 DApp 图标。 PR 合并后，您的 DApp 或 logo 将在 TokenPocket 上更新。请阅读以下教程。

### 捐赠更新DApp 
根据 DAO 的投票，DApp 上线或更新的捐赠金额已被投票确定为 200,000 TPT。点击[这里](https://snapshot.org/#/tptdao.eth/proposal/0x3f6f81046588af5a89062de6bea4dc92de67fa380cb1823babcf8dde3415f1ad)了解详情

### 关于DApp支持的链
1.指定EVM网络，当需要指定DApp支持ETH,BSC，HECO时，如下
```
[{
		"network": "ethereum",
		"chain_id": "1"
	},
	{
		"network": "ethereum",
		"chain_id": "56"
	},
	{
		"network": "ethereum",
		"chain_id": "128"
	}
]
```
通过chain_id区分，适用于所有EVM网络

2.指定波场,solana等网络,通过原生币符号区分网络.
```
[{
	"network": "SOL"
}, {
	"network": "TRX"
}]
```

3.指定波卡系列的网络,通过ss58区分网络
```
[{
	"network": "polkadot",
	"ss58": "0"
}, {
	"network": "polkadot",
	"ss58": "2"
}, {
	"network": "polkadot",
	"ss58": "27"
}]
```