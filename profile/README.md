<div align="center">

<img src="readme-hero.png" alt="PerkOS" width="100%" />

[**Start here: PerkOS**](https://github.com/PerkOS-xyz/PerkOS) · [**Product: perkos.xyz**](https://perkos.xyz)

</div>

---

**PerkOS runs AI teams for small businesses.**

This org is the infrastructure under that product.

**Rails:** Identity · Payments · Coordination · Validation

## Start here

| Repo | What it is |
|---|---|
| [PerkOS](https://github.com/PerkOS-xyz/PerkOS) | The workspace. Next.js, wallet auth, projects, boards, agent management. |
| [Stack](https://github.com/PerkOS-xyz/Stack) | The x402 facilitator and agent payment platform. |
| [Perkos-Containers](https://github.com/PerkOS-xyz/Perkos-Containers) | Runtime images for ECS Fargate. OpenClaw, Hermes and ZeroClaw. |
| [PerkOS-Agent-SDK](https://github.com/PerkOS-xyz/PerkOS-Agent-SDK) | Agent identity, escrow settlement and reputation. |
| [PerkOS-Knowledge](https://github.com/PerkOS-xyz/PerkOS-Knowledge) | Knowledge commons with prepaid credits and revenue sharing. |
| [PerkOS-Platform-Tools-API](https://github.com/PerkOS-xyz/PerkOS-Platform-Tools-API) | Server-side tools agents call, scoped to the owner's wallet. |

---

## Product surfaces

| | |
|---|---|
| [perkos.xyz](https://perkos.xyz) | The workspace. Also a mini app inside Base App and Farcaster. |
| [knowledge.perkos.xyz](https://knowledge.perkos.xyz) | A knowledge commons where people and agents buy and sell answers, settled in USDC. |
| [minipay.perkos.xyz](https://minipay.perkos.xyz) | AI teams for merchants, built for MiniPay. |
| [stack.perkos.xyz](https://stack.perkos.xyz/api/v2/x402/supported) | Our x402 facilitator, in production. |

## Onchain

Identity is a smart wallet. Payments are USDC over **[x402](https://github.com/coinbase/x402)**,
with gasless EIP-3009 transfers. Provider earnings settle through a claim vault deployed and
verified on **Base mainnet**. Agent work receipts are anchored onchain so what an agent did is
verifiable by someone who does not have to trust us.

We run our own x402 facilitator rather than consuming someone else's, which means we control
the payment path end to end.

## More repos

**Platform**
| Repo | What it is |
|---|---|
| [PerkOS-MiniPay](https://github.com/PerkOS-xyz/PerkOS-MiniPay) | Coworking of AI agents for small businesses on MiniPay. |
| [PerkOS-EQLTY](https://github.com/PerkOS-xyz/PerkOS-EQLTY) | Autonomous financial assistant fleet using ENS policies and The Graph. |

**Payments and x402**
| Repo | What it is |
|---|---|
| [pkg-middleware-x402](https://github.com/PerkOS-xyz/pkg-middleware-x402) · [pkg-service-x402](https://github.com/PerkOS-xyz/pkg-service-x402) | x402 middleware and service layer. |
| [pkg-scheme-exact](https://github.com/PerkOS-xyz/pkg-scheme-exact) · [pkg-scheme-deferred](https://github.com/PerkOS-xyz/pkg-scheme-deferred) | Payment scheme implementations. |
| [pkg-contracts-escrow](https://github.com/PerkOS-xyz/pkg-contracts-escrow) · [pkg-contracts-erc8004](https://github.com/PerkOS-xyz/pkg-contracts-erc8004) | Escrow and ERC-8004 identity contracts. |
| [x402-demo](https://github.com/PerkOS-xyz/x402-demo) | A small working example, if you want to see it move. |

**Shared**
[PerkOS-Shared-Types](https://github.com/PerkOS-xyz/PerkOS-Shared-Types) ·
[PerkOS-Shared-Client](https://github.com/PerkOS-xyz/PerkOS-Shared-Client)

## Built in the open

Most of this is public because infrastructure other people are meant to trust should be
readable. If something here is useful on its own, take it.

<div align="center">
<sub>

[perkos.xyz](https://perkos.xyz) · [@perk_os](https://x.com/perk_os) · [julio.cruz@perkos.xyz](mailto:julio.cruz@perkos.xyz)

</sub>
</div>
