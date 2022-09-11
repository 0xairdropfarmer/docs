# NuLink Testnet

## NuLink Testnet

The NuLink Testnet includes four parts: the NuLink Staking Dapp, the NuLink Worker Node, the NuLink Agent and the NuLink File Sharing Dapp. The NuLink Staking Dappand the  NuLink Worker Node are used by those who want to provide cryptographic service in the NuLink test network; while the NuLink Agent and the NuLink File Sharing Dapp are used by those who want to use the privacy-preserving service in the NuLink test network. The token in the NuLink testnet is NLK(test). Please be aware it is only used for testing purpose and has no trading value. 

* [**NuLink Worker Node:**](nulink_worker.md) The node to provide cryptographic service in the NuLink network. 

* [**NuLink Staking Dapp:**](staking_Dapp.md) The platform for managing the staker/worker account 

* [**NuLink Agent:**](nulink_agent.md) The plug in to handle the local cryptographic operation of the file sharing users.

* [**NuLink File Sharing Dapp:**](file_sharing_Dapp.md) The entrypoint for data sharing users to manage the private file and handle the authorization  request.

The NuLink testnet is launched on BNB Smart Chain Testnet. The smart contract address is:

* **NuLink Token**: []
* **NuLink Staking Pool**: []
* **Simple PRE Application**: []
* **Subscription Manager**: []

## Characters

* **Staker/Workers:** Staker/workers refer to those  who stake their NLK token and provide the cryptographic service in the NuLink network. They need to deposit  their NLK token from his staking account using the NuLink staking Dapp first. And then they need to start a worker node by using the NuLink worker Installer. After the NuLink worker node is successfully started, they need to bond the NuLink worker node to his staking account by using the NuLink staking Dapp again. Remember, the staker must bond with an active worker to be eligible for staking reward.

* **File Sharing Users:** File sharing users refer to those who pay service fee to use the cryptographic service in the NuLink network. They need to install the NuLink Agent to access the NuLink file sharing Dapp. The file owner needs to pay the service fee in terms of NLK to grant access to any file request applicant. The file request applicants do not need to pay fees in the NuLink network. (Why do we charge fees for file owners instead of the file request applicants? Think about the commodity tax: the seller need to pay the tax, and they can charge this to the consumer by increasing the sell price. ) 

## Work Flow

![image](../miscellaneous/img/workflow.png)