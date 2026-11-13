# InTheta

I build tools for AI agents and market data. My public work focuses on how agents access data, use tools, and fit into developer workflows.

## AI and developer tools

- [Agent Capability Middleware](https://github.com/InTheta/agent-capability-middleware) provides an open SDK and reference profiles for user-controlled agent permissions, private context, and x402 policy flows.
- [Omni Universe SDKs](https://github.com/InTheta/omni-universe-sdks) provides public SDKs, data examples, and guarded trading agent examples.
- [Prime Agent with T3 Code](https://github.com/InTheta/t3code/pull/1) documents how to connect Prime Agent to local Ollama over ACP. The Windows test used Qwen to read a disposable file and verified that its checksum stayed the same. The guide is in an open draft on my T3 fork.

## Selected upstream contributions

- [DefiLlama dimension adapters](https://github.com/DefiLlama/dimension-adapters/pull/7627) added the Omni Terminal Hyperliquid builder adapter.
- [rust-ibapi](https://github.com/wboayue/rust-ibapi/pull/625) fixed protobuf date decoding for historical daily bars.
