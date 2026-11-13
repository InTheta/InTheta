<p align="center">
  <img src="https://avatars.githubusercontent.com/u/17220028?v=4" width="104" height="104" alt="Omni Redeemer">
</p>

<h1 align="center">Market data, trading systems &amp; AI agents</h1>

<p align="center">
  I build Omni Terminal and the tools around it, from decoding exchange data to defining what a trading agent is allowed to do.
</p>

<p align="center">
  <a href="https://omniterminal.app/">Explore Omni Terminal</a> &nbsp;·&nbsp;
  <a href="https://github.com/InTheta/omni-universe-sdks">Browse the SDKs</a> &nbsp;·&nbsp;
  <a href="https://github.com/wboayue/rust-ibapi/pull/625">Read a merged Rust fix</a>
</p>

---

### Explore the code

| If you're interested in… | Start here |
| --- | --- |
| **Market data and trading integrations** | [Omni Universe SDKs](https://github.com/InTheta/omni-universe-sdks) has public SDKs, market-data examples and guarded trading agent examples. |
| **Agent permissions and payments** | [Agent Capability Middleware](https://github.com/InTheta/agent-capability-middleware) includes an SDK and reference profiles for user-controlled tool permissions, private context and x402 payment policies. |
| **Onchain strategy vaults** | [HL Vault SDK](https://github.com/InTheta/hl-vault-sdk) is a TypeScript SDK for Hyperliquid, HIP-3 and HIP-4 strategy vaults. |

### A closer look at three changes

- **IBKR daily bars were landing in 1970.** The Rust protobuf decoder read an eight-digit trading date as Unix seconds. I added calendar-date handling and a regression test, then checked the result with live MU daily bars from IB Gateway. [Merged upstream · rust-ibapi #625](https://github.com/wboayue/rust-ibapi/pull/625)
- **Omni needed an adapter for DefiLlama's Hyperliquid builder data.** I contributed the Omni Terminal builder adapter to the public dimension-adapters repository. [Merged upstream · DefiLlama #7627](https://github.com/DefiLlama/dimension-adapters/pull/7627)
- **A local model needed a way into T3 Code.** I documented Prime Agent over ACP with Ollama and checked on Windows that Qwen could read a disposable file while its checksum stayed the same. [Merged on my integration branch · t3code #1](https://github.com/InTheta/t3code/pull/1)
