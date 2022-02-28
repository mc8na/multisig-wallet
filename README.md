# multisig-wallet
Multi-signature Wallet

This decentralized application performs the function of a multi-signature wallet.

A multisig is a cryptocurrency wallet that requires two or more private keys to sign and approve the transfer.

This dapp connects to the user's Metamask wallet and allows them to submit or approve transfers of tokens.

The frontend of this dapp shows the wallet addresses that are considered approvers and the quorum, the number of approvals needed in order to send a transfer. For this dapp there are three approvers and the quorum is 2.

After the user connects their Metamask wallet, they can create a new transfer or approve an existing transfer. Only wallets that are considered approvers can approve a transfer.

When a user submits or approves a transfer, Metamask will pop up prompting them to pay the required gas fee.

When a transfer is submitted, it will not be sent until a quorum of approvers have approved the transfer.

Before_Submit.png shows the state of the dapp before a transfer of 5 ETH another wallet is submitted. The Transfers list shows prior transfers with the transfer id, the amount to be transferred, the receiving address, the number of approvals, and whether the transfer has been sent. The other images show the Metamask prompts to pay the gas fee when creating or approving a transfer.
