# Daily resource curation, 2026-06-11

This log records the public-source checks behind the 2026-06-11 Awesome OpenClaw maintenance update.

## Summary

- Open contributor PRs reviewed: 2.
- Verified resources added to `README.md`: 34.
- Verified resources also added to `docs/website/directory.html`: 9.
- Primary source type: npm registry package metadata, npm package README content, and linked public GitHub repositories where available.
- Stopping reason: the run stopped below the daily 50-60 target because remaining search results included duplicates already in the README or website, wallet/payment/on-chain items needing separate risk review, social/account automation items needing stricter platform-policy wording, deprecated shims, or packages with insufficient OpenClaw-specific README evidence.

## Accepted candidates

| Candidate | Type | Public evidence | Placement |
|-----------|------|-----------------|-----------|
| `@openclaw-vk/vk` | plugin | npm metadata and README document a VKontakte channel plugin for OpenClaw using VK Bots Long Poll API and OpenClaw version requirements. | README |
| `@srinathh/openclaw-channel-twilio-whatsapp` | plugin | npm metadata and README document a Twilio WhatsApp channel plugin for OpenClaw with HTTPS webhook deployment notes. | README |
| `@lansenger-pm/openclaw-lansenger-channel` | plugin | npm metadata documents a Lansenger enterprise messaging channel plugin for OpenClaw with WebSocket inbound and HTTP outbound delivery. | README |
| `@largezhou/ddingtalk` | plugin | npm metadata and README document a DingTalk Stream-mode channel plugin for OpenClaw. | README |
| `@soimy/dingtalk` | plugin | npm metadata and README document a DingTalk channel plugin with OpenClaw compatibility badges and setup notes. | README |
| `@transplane/openclaw-bridgex` | plugin | npm metadata and README document a BridgeX channel plugin for OpenClaw agent-to-agent and human-to-agent messaging. | README, directory |
| `@zf-tech/openclaw-websocket` | plugin | npm metadata and README document a JSON-over-WebSocket OpenClaw channel plugin for custom apps. | README, directory |
| `@meepa/meepachat-openclaw` | plugin | npm metadata and README document a self-hosted MeepaChat channel plugin for OpenClaw using WebSocket inbound and REST outbound paths. | README, directory |
| `@nimsuite/openclaw-nim-channel` | plugin | npm metadata and README document a NetEase IM channel plugin for OpenClaw P2P, group, and QChat conversations. | README |
| `@helloagentai/openclaw` | plugin | npm metadata and README document a relay-backed HelloAgent channel plugin for OpenClaw assistants. | README |
| `@syengup/friday-channel-next` | plugin | npm metadata documents an Apple-channel plugin for OpenClaw. | README |
| `@hywkp/test-openclaw-sider` | plugin | npm metadata documents a Chrome channel plugin for connecting OpenClaw through Sider Chrome extension. | README |
| `@workclaw/openclaw-workclaw` | plugin | npm metadata documents an enterprise communications channel plugin for OpenClaw. | README |
| `@chat4000/openclaw-plugin` | plugin | npm metadata documents an E2E relay channel plugin for routing Chat4000 messages through OpenClaw. | README |
| `@fateinabox/aephix-openclaw` | plugin | npm metadata documents an Aephix chat channel provider for OpenClaw. | README |
| `@ynhcj/xiaoyi-channel` | plugin | npm metadata documents a Xiaoyi A2A protocol channel plugin for OpenClaw. | README |
| `@persistio/openclaw-plugin` | memory plugin | npm metadata and README document an OpenClaw-native Persistio long-term memory plugin with recall and store tools. | README, directory |
| `@posthog/openclaw` | monitoring dashboard | npm metadata and README document PostHog LLM Analytics for OpenClaw telemetry. | README, directory |
| `@paleo/openclaw-slack-mock` | developer tool | npm metadata and README document a synthetic Slack-shaped OpenClaw channel plugin for tests without live Slack sends. | README, directory |
| `openclaw-tavily` | plugin | npm metadata and README document Tavily search, extract, crawl, map, and research tools for OpenClaw. | README, directory |
| `@korveo/openclaw` | monitoring dashboard | npm metadata and README document a local-first span exporter for OpenClaw OpenTelemetry diagnostics. | README, directory |
| `@agentlas/openclaw` | plugin | npm metadata documents an OpenClaw plugin for Agentlas notes and knowledge-extraction workflows. | README |
| `@nextclaw/openclaw-compat` | developer tool | npm metadata documents an OpenClaw plugin compatibility layer for NextClaw. | README |
| `@scholai/openclaw-scholai` | plugin | npm metadata documents a Scholai courseware plugin for OpenClaw article-generation workflows. | README |
| `@scholai/openclaw-scholai-tools` | developer tool | npm metadata documents an onboarding CLI for Scholai OpenClaw plugin install, info, doctor, and update workflows. | README |
| `@listenai/openclaw-xiaoling` | plugin | npm metadata documents a Xiaoling AI plugin for OpenClaw. | README |
| `@a5c-ai/hooks-mux-adapter-openclaw` | developer tool | npm metadata documents a hooks-mux harness adapter for OpenClaw. | README |
| `@agent-vm/openclaw-gateway` | deployment template | npm metadata documents OpenClaw gateway lifecycle management inside an Agent VM. | README |
| `@alfe.ai/openclaw-sync` | backup/restore tool | npm metadata documents a workspace backup and sync skill for OpenClaw. | README, directory |
| `openclaw-webchat-server` | companion app | npm metadata documents a browser WebSocket relay server between webchat users and OpenClaw agents. | README |
| `@riddledc/openclaw-riddledc` | workflow automation | npm metadata documents an OpenClaw integration package for RiddleDC with no-secrets setup notes. | README |
| `@onequery/openclaw-plugin` | plugin | npm metadata documents a OneQuery OpenClaw plugin package. | README |
| `@parall/openclaw-agent` | companion app | npm metadata documents a bootstrap wrapper for preparing per-agent OpenClaw state before launching Parall agents. | README |
| `@watchline/openclaw-plugin` | workflow automation | npm metadata documents a delivery adapter for matched Watchline events in OpenClaw workflows. | README |

## Contributor PR triage

| PR | Classification | Decision | Reason |
|----|----------------|----------|--------|
| #182, TWZRD Agent Intel | resource-submission | deferred | Solana wallet, trust scoring, and x402 payment orientation needs stronger OpenClaw-specific evidence and more conservative safety wording before inclusion. |
| #99, XVARY Stock Research | resource-submission | deferred | Claude Code-specific skill, no clear OpenClaw integration evidence, and the PR adds a new top-level README section rather than using the existing taxonomy. |

## Deferred or rejected candidate classes

- Wallet, identity, payment, and on-chain packages were deferred for separate security and policy review.
- Risky social/account automation packages were deferred unless they had official API-compliant setup and conservative wording.
- Deprecated compatibility shims were skipped when the maintained package was already listed or a better current package existed.
- Generic adapter packages without enough OpenClaw-specific README evidence were not added.
