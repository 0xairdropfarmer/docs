# NuLink Agent SDK
The SDK for third-party integration with [NuLink Agent](../product/nulink_agent.md).

These APIs allow you to access NuLink Agent programmatically and perform various actions, such as connect, upload, apply, approve and download.

## Getting Started

The default address in the Nulink Web Agent Access SDK:

* NuLink Agent: https://agent.testnet.nulink.org
* Backend service address: https://agent-integration-demo.nulink.org/bk. 

If you need to change these two addresses, you will need to write the following configurations in the .env file of your project: REACT_APP_NULINK_AGENT_ADDRESS for the web agent address and REACT_APP_NULINK_BACKEND_ADDRESS for the backend service address.

The default network is Horus (BSC Testnet), default chain id is 97.
If you need to change these two addresses and network, you will need to write the following configurations in the .env file of your project:
- REACT_APP_NULINK_AGENT_URL:  the web agent address
- REACT_APP_CENTRALIZED_SERVER_URL: the centralized service address
- REACT_APP_DEFAULT_NETWORK_CHAIN_ID: the network chain id


```
// modify .env in your project
// the web agent address
REACT_APP_NULINK_AGENT_ADDRESS=xxxxxx
// the agent bcakend service address
REACT_APP_NULINK_BACKEND_ADDRESS=xxxxxx
// chain Id
REACT_APP_DEFAULT_NETWORK_CHAIN_ID=xx
```

## Install
```bash
npm i @nulink_network/nulink-web-agent-access-sdk
```
or
```bash
yarn add @nulink_network/nulink-web-agent-access-sdk
```

## How to use

See [nulink-web-agent-integration-demo](https://github.com/NuLink-network/nulink-web-agent-integration-demo.git)  to get how to use NuLink Agent SDK.

Here the [Agent SDK API reference](./agent_api.md).