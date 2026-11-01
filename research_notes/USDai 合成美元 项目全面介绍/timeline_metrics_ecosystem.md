# USD.AI (Permian Labs): Development Timeline, Growth Metrics, Ecosystem Integrations and Partnerships

Research date: 2026-11-01. All figures carry a date and URL. Where sources conflict, every version is recorded. Primary sources used: USD.AI official blog (usd.ai/blog, 80 posts from 2025-03-25 to 2026-10-29), docs.usd.ai, DefiLlama API (protocol + stablecoin endpoints, pulled 2026-11-01), CoinGecko, Stablewatch, Aave governance forum risk reports (Chaos Labs, LlamaRisk), Binance Research, press releases (Newswire, BusinessWire, PRNewswire), and Chinese-language media (Foresight News, ChainCatcher, PANews via Bitget/Tencent reposts).

Note on naming: the protocol is "USD.AI"; the non-yielding stablecoin is "USDai"; the yield-bearing staked token is "sUSDai"; the governance token is "CHIP" (launched 2026-04-21); the developer is Permian Labs, Inc.; the issuer entity named by CoinGecko is Genesys Protocol Holdings Ltd.; the off-chain DAO steward is the USD.AI Foundation / CHIP Foundation.

---

## Key Question 1: Dated chronology of USD.AI's development (announcement through November 2026)

### Takeaway
USD.AI went from first blog post (2025-03-25) and first on-chain deposits (2025-05-19) through a private beta (2025-06-10), public Arbitrum launch (2025-08-21), a rapid series of deposit-cap raises that took TVL from ~$100M to ~$500M in September 2025, a $700M TVL peak (Nov 2025 – Jan 2026), a large redemption wave and TVL drawdown in Q1–Q2 2026, a CHIP TGE on 2026-04-21, and then a second growth phase in H2 2026 driven by large GPU loans, the GLX loan exchange (2026-10-01), new chains (Arc, Solana) and sUSDai supply ATHs. There has never been a formal "testnet" announcement; the first phase was a partner-only private beta on Arbitrum.

### Cited Findings

**Pre-history and founding**
- Permian Labs was "established in 2021" by David Choi (CEO) with co-founders Conor Moore (COO) and Ivan Sergeev; Choi also oversees "Tactical Compute, a hardware infrastructure business" — [IQ.wiki David Choi](https://iq.wiki/wiki/david-choi)
- Core primitives (Automatic Tranche Maker, Liquid Credit Token, Yield Pass) were "developed and launched iteratively" in 2023–2024 on the MetaStreet protocol — [docs.usd.ai via IQ.wiki](https://docs.usd.ai/solution-overview/stackable-defi-primitives); [IQ.wiki USD.AI](https://iq.wiki/wiki/usdai)
- Audits listed by LlamaRisk: Cantina (2025-05-12: 1 medium, 8 low), Kais Tlili (2025-05-14: 1 medium, 1 low), plus M0 protocol audits (Quantstamp/Three Sigma/OpenZeppelin/Sherlock/Certora/ChainSecurity 2024) and EVM M0 Extensions audits (Certora July 2025, ChainSecurity 2025-07-21, Guardian 2025-08-05). Bug bounties: Cantina (max $100,000) and MetaStreet on Immunefi (max $50,000) — [Aave ARFC thread, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)

**2025: announcement, beta, public launch, cap raises**
- 2025-03-25: first official blog post, "USD.AI is Powered By M^0" (USDai backed by M0's tokenized T-bill dollar wM) — [USD.AI blog index](https://usd.ai/blog); [M0 research](https://research.m0.org/research/usdai-uses-m0s-stablecoin-platform-to-launch-composable-synthetic-dollar)
- 2025-05-04: "CALIBER Deep Dive" (the original hardware tokenization framework). An October 2026 note on several posts states "CALIBER is no longer part of USD.AI's loan structure" — [USD.AI blog index](https://usd.ai/blog); [Coinbase Ventures post with Oct 2026 update](https://usd.ai/blog/usdai-secures-coinbase-ventures-investment)
- 2025-05-19: first DefiLlama TVL datapoint ($912,367); DefiLlama `listedAt` = 2025-05-19 — [DefiLlama API /protocol/usd-ai](https://api.llama.fi/protocol/usd-ai)
- 2025-06-10: "Private Beta Is Live" — "first phase of USD.AI's rollout" for "a small group of partners"; mint USDai/sUSDai on Arbitrum; "preparing support for Mainnet, Berachain, and other DeFi ecosystems"; points program then called "Cores" — [USD.AI blog](https://usd.ai/blog/private-beta-is-live)
- 2025-06-11: DefiLlama TVL first exceeds $10M ($10.63M) — [DefiLlama API](https://api.llama.fi/protocol/usd-ai)
- July 2025: first loan, $620K (largest loan "grew from $620K in July 2025 to $98.1M in June 2026") — [Lighthouse YTD report](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse); borrower identified as Tactical Compute Holding Ltd (ADGM, UAE), $620,243.86 USDC — [Aave ARFC, Chaos Labs](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2025-08-13/14: $13M Series A led by Framework Ventures (CoinDesk dated 2025-08-13; IQ.wiki cites 2025-08-14) — [CoinDesk](https://www.coindesk.com/business/2025/08/13/usd-ai-raises-usd13m-to-expand-gpu-backed-stablecoin-lending); [IQ.wiki](https://iq.wiki/wiki/usdai). The official blog post of 2025-08-20 is titled "USD.AI Raises $13.4M" — [USD.AI blog](https://permian-labs.ghost.io/usdai-raises-13m-to-scale-ai-infra/). Participants: Dragonfly, Bullish, Arbitrum Foundation, DCG (Tekedia); Delphi, Fintech Collective (Cryptonews/Yahoo) — [Tekedia](https://www.tekedia.com/usd-ais-500m-deposit-cap-raise-is-a-bold-step-toward-scaling-ai-defi-integration/); [Yahoo/Cryptonews](https://finance.yahoo.com/news/yzi-labs-backs-usd-ai-185621852.html)
- 2025-08-19: DefiLlama TVL crosses $50M ($52.4M) — [DefiLlama API](https://api.llama.fi/protocol/usd-ai)
- 2025-08-20: "The Allo Game" points program announced — [USD.AI blog](https://usd.ai/blog/the-allo-game)
- 2025-08-21: "USD.AI has launched publicly on Arbitrum" with AutoVaults (Euler, K3 Capital, Concrete, Pendle); "over $50 million in deposits during its private beta" — [USD.AI blog](https://usd.ai/blog/usdai-launches-on-arbitrum-autovaults)
- 2025-08-26: YZi Labs (ex-Binance Labs) strategic investment (amount undisclosed); TVL "above $62.7M" — [Yahoo/Cryptonews](https://finance.yahoo.com/news/yzi-labs-backs-usd-ai-185621852.html)
- 2025-08-29: "deposits have reached the initial cap of 100 million USD"; USD.AI to be a Plasma mainnet launch partner allowing USDT deposits (Foresight News) — [Bitget repost](https://www.bitget.com/news/detail/12560604937954); DefiLlama TVL crossed $100M the same day ($106.1M) — [DefiLlama API](https://api.llama.fi/protocol/usd-ai)
- Early Sep 2025 (undated): The Defiant: TVL hits $110M, "nearly doubled since YZi Labs' strategic investment last week" — [The Defiant](https://thedefiant.io/news/defi/framework-ventures-backed-stablecoin-usdai-hits-usd110m-in-tvl)
- 2025-09-04: cap raised from $110M to $160M (+$50M); "next cap increase will coincide with Plasma mainnet launch" (ChainCatcher) — [Bitget repost](https://www.bitget.com/zh-CN/news/detail/12560604950001)
- 2025-09-11 (contested): IQ.wiki states "two $250 million deposit caps were filled, bringing total deposits to $500 million" on Sep 11 and that on 2025-09-19 "a new round raised the total deposit limit by another $500 million, with a portion reserved for Plasma" — [IQ.wiki](https://iq.wiki/wiki/usdai). This conflicts with the ChainCatcher ($160M cap on Sep 4) and Tekedia accounts (below) and with DefiLlama TVL ($110M on Sep 1; $501M first reached 2025-09-26).
- 2025-09-22: Bullish $4M investment (first since its August IPO); "USD.AI has $250M in private beta deposits" — [Bullish](https://www.bullish.com/us/news-insights/bullish-makes-4-million-investment-into-usd-ai-its-first-since-ipo)
- 2025-09-23: $500M cap deposit window opened 12 PM EST on Ethereum Mainnet accepting USDC; previous cap $160M; "$250M of the $500M cap is allocated to the Plasma Foundation" — [Tekedia, 2025-09-24](https://www.tekedia.com/usd-ais-500m-deposit-cap-raise-is-a-bold-step-toward-scaling-ai-defi-integration/)
- 2025-09-25: Plasma mainnet beta and XPL launched (USD.AI a launch partner) — [Blockworks](https://blockworks.co/news/plasma-announces-mainnet-beta); [The Block](https://www.theblock.co/post/372300/stablecoin-layer-1-plasma-goes-live-introducing-xpl-token-and-defi-integrations)
- 2025-09-26: DefiLlama TVL jumps to $501.2M (first day ≥$250M and ≥$500M) — [DefiLlama API](https://api.llama.fi/protocol/usd-ai)
- 2025-09-28: DefiLlama stablecoin tracking begins; Plasma USDai $67.6M on Sep 28; Arbitrum USDai $445.2M on Sep 30; Ethereum negligible — [DefiLlama stablecoin API id 309](https://stablecoins.llama.fi/stablecoin/309)
- 2025-10-06: "USDai $100m Cap Raise for Euler Unwind" — cap raised by $100M "exclusively for the autoUSDai vault" to fund "orderly unwind of borrowing for the Euler Frontier USDai vault"; effective Wed 2025-10-08 12 EST; 25x points for 30 days; non-aligned pool multiplier cut 10x → 3x — [USD.AI blog](https://usd.ai/blog/usdai-cap-euler-autousdai); PANews reported effective Beijing time 2025-10-09 00:00 to support "orderly liquidation of USDT0 positions in the Euler Frontier USDai market" — [MEXC news repost](https://www.mexc.com/news/121365)
- 2025-10-09: "$75 million quota ... filled within 52 seconds" by 2,631 addresses (ChainCatcher) — [Bitget repost](https://www.bitget.com/news/detail/12560605006310). (The AutoVault sunset post also says the Auto vaults "accepted $75 million in new deposits during the last USDai cap raise" — the $100M raise vs $75M filled discrepancy is unexplained.)
- 2025-10-09: QumulusAI $500M non-recourse facility announced — [Newswire](https://www.newswire.com/news/qumulusai-secures-500m-non-recourse-financing-facility-through-usd-ai-to); "USDAI Adopts Chainlink As Its Official Oracle" — [USD.AI blog index](https://usd.ai/blog)
- 2025-10-15: Aave ARFC to onboard USDai/sUSDai on Aave V3 Arbitrum posted by ACI; Chaos Labs (Oct 19) and LlamaRisk (Oct 20) both declined to support at that time — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- Oct 2025: LlamaRisk cites "a $581.2M deposit cap which has been filled" and that USD.AI said "the cap would be lifted post the expiry of the 20Nov2025 Pendle pool"; Chaos Labs cites a 500M cap — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2025-10-29: "Sunsetting the Auto Strategy Vaults" — autoUSDai held 17,711,046 USDC and autoSUSDai 3,119,485 USDC (as of 2025-10-24); withdrawals Nov 3–6; 15x boost ends Nov 7; full sunset and airdrop of USDai/sUSDai on Nov 24; "risks associated with the Euler Frontier market have diminished due to K3 Capital taking over risk curation" — [USD.AI blog](https://usd.ai/blog/sunsetting-auto-strategy-vaults)
- 2025-11-17: Coinbase Ventures investment in Permian Labs (amount undisclosed; body datelined "October 2025") — [USD.AI blog](https://usd.ai/blog/usdai-secures-coinbase-ventures-investment)
- 2025-11-20: "USD.AI Integrates with Coinbase Prime" — [USD.AI blog index](https://usd.ai/blog)
- 2025-11-22: DefiLlama protocol TVL all-time high $701.98M — [DefiLlama API](https://api.llama.fi/protocol/usd-ai)
- 2025-12-09: Quantum Solutions (TSE: 2338, Japan) up-to-$200M guidance facility; "Upgrade for Loan Router and Timelock" — [USD.AI blog](https://usd.ai/blog/quantum-solutions-usdai-financing); [blog index](https://usd.ai/blog)
- 2025-12-18: PYUSD integration: PayPal + USD.AI Foundation incentive of 4.5% on up to $1B deposits, one year, "expected early January"; "over $650 million in on-chain compute-backed assets" — [USD.AI blog](https://usd.ai/blog/pyusd-paypal-usdai-integration); [CoinDesk 2025-12-18 (mirror)](https://irishnews.pages.dev/crypto-news-coindesk.com/business/2025/12/18/paypal-s-pyusd-stablecoin-tapped-for-ai-infrastructure-financing)
- 2025-12-20: Entropy Advisors Dune dashboards (Arbitrum, Plasma, Base): total supply >650M, ~40% staked as sUSDai, Arbitrum >70% of supply — [KuCoin insight repost](https://www.kucoin.com/news/insight/ARB/6946341ded5e0100073836a3); dashboard: [dune.com/entropy_advisors/usdai-usdai](https://dune.com/entropy_advisors/usdai-usdai)

**2026 H1: facilities, Foundation, CHIP ICO/TGE, redemption wave, PYUSD migration**
- 2026-01-13: Arbitrum USDai supply ATH $523.9M; 2026-01-20: total USDai supply ATH $663.2M — [DefiLlama stablecoin API](https://stablecoins.llama.fi/stablecoin/309)
- 2026-01-14: Evan Meagher joins as Senior Advisor — [blog index](https://usd.ai/blog)
- 2026-01-22: Sharon AI (Australia) up to $500M facility; initial $65M draw in Q1 2026; USD.AI's approved facilities now "more than $1.2 billion" (QumulusAI, Quantum Solutions, Sharon AI) — [The Block](https://www.theblock.co/post/386759/onchain-lending-protocol-usdai-approves-500-million-loan-australian-ai-startup); [BusinessWire](https://www.businesswire.com/news/home/20260122439371/en/)
- 2026-01-27: "Announcing the USD.AI Foundation and $CHIP" — ICO and TGE "in Q1 2026"; "$1.5B+ pipeline, with the first $100M in GPU-backed loans originating Q1 2026"; "$7.7B+ in sUSDai traded in 2025"; "$1.2B in approved facilities to QumulusAI, Sharon AI, and Quantum SKK" (sic; presumably Quantum Solutions) — [USD.AI blog](https://usd.ai/blog/usdai-foundation-chip)
- 2026-02-06: Barkr (formerly Barker) residual-value protection added to GPU loans, backed by an "A-rated institutional reinsurer" with "over 140 years of operating history" — [USD.AI blog](https://usd.ai/blog/usdai-barker-insured-gpu-loan-coverage). ACI's 2026-02-17 Aave post describes it as a "Munich Re-backed coverage partnership" — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-02-09: CHIP ICO details: CoinList, KYC Feb 10–27, sale 2026-02-22 23:00 UTC to 2026-02-27 23:00 UTC, $0.03/CHIP, $300M FDV, 700,000,000 CHIP (7%), 100% unlocked at TGE; airdrop auto-distributed at TGE; Allo Season 1 ends 2026-02-18 — [USD.AI blog](https://usd.ai/blog/chip-ico-airdrop); [Tekedia 2026-02-13](https://www.tekedia.com/usd-ai-releases-ico-and-airdrop-details/)
- 2026-02-12: "Season 1 Finale: Level Up" — Boost Own (4-month lock) $270M FDV; Max Own (8-month lock) $190M FDV; Airdrop Boost/Max Earn buyouts at $350M/$420M implied FDV; "CHIP TGE is in March" — [USD.AI blog](https://usd.ai/blog/level-up-finale)
- 2026-02-19: QumulusAI first drawdown: 1,144 NVIDIA Blackwell GPUs (760 Blackwell + 384-GPU B300 cluster) — [Newswire](https://www.newswire.com/news/qumulusai-deploys-1-144-nvidia-blackwell-gpus-through-drawdown-under-500m-usd)
- 2026-02-19: Allo Season 2 "Flatiron" begins (runs to 2026-10-14) — [USD.AI blog](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- 2026-02-26: "Migration from wM to PYUSD was finalized" (LlamaRisk) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- Feb 2026: sUSDai supply peak ~320M (LlamaRisk) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-03-02: Messari-authored CHIP valuation report (commissioned by USD.AI; CN repost 2026-03-24) — [USD.AI blog](https://usd.ai/blog/usdai-chip-valuation-report-cn)
- 2026-03-06: peak sUSDai redemption queue "about $127M queued against about $330M unallocated USDai"; the March 2026 redemption window "processed about $130M against $342M TVL" (LlamaRisk) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-03-19: Pendle USDai and sUSDai pools launched on Plasma — [crypto.news](https://crypto.news/pendle-expands-defi-offerings-to-plasma-with-5-yield-markets/); [Bitget](https://www.bitget.com/news/detail/12560605636875)
- 2026-03-26: "[Updated] USDai Mint and Redeem Upgrade": from April 6 direct mint/redeem limited to KYC'd market makers (Paxos-approved) and institutions, 10 bps redemption fee, "every unit is fully backed 1:1 by PYUSD", $5M from Permian Labs seeds a USDC-USDai pool on Arbitrum; an "Update 10/01/2026" banner states these restrictions "are no longer in place" (minting/redemption permissionless again) — [USD.AI blog](https://usd.ai/blog/usdai-mint-redeem-upgrade)
- 2026-03-31: ~299M USDai on Arbitrum (down from 524M peak in Jan), ~160M sUSDai (down from 320M peak in Feb), staking ratio ~59%; 27 loans worth $18.1M (6.4% of reserves), 16 more in pipeline; max LTV raised 70% → 80%; supply cap removed (LlamaRisk, 2026-04-03) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-04-01: Chaos Labs reverses to support Aave listing, citing mint-cap removal, Barker valuation partnership, committed sUSDai liquidity buffer, PYUSD backing, planned 80% utilization cap, and "an ICO that raised about $8.8M" — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-04-06: Crucible Capital $26.8M loan (NVIDIA B300), then largest in book — [USD.AI blog](https://usd.ai/blog/crucible-capital-26m-gpu-backed-loan); [April recap](https://usd.ai/blog/usdai-april-recap)
- 2026-04-16: Flatiron Referral Boost program — [blog index](https://usd.ai/blog)
- 2026-04-17: QumulusAI $16.4M (H200) — [April recap](https://usd.ai/blog/usdai-april-recap)
- 2026-04-20: USDC sent to eligible Level Up airdrop (buyout) wallets — [USD.AI blog](https://usd.ai/blog/chip-is-live)
- 2026-04-21: CHIP TGE. Spot: Upbit (KRW), Binance (USDT/USDC, Seed Tag; also CHIP/TRY), Bybit, Bithumb, Robinhood, Coinbase (USD), Bitvavo (EUR), KuCoin, MEXC, HTX, Gate; perps: Binance, OKX, Bitget, Hyperliquid, Lighter; DEX: Aerodrome (Base); contract 0x0c1c1c109fe34733fca54b82d7b46b75cfb71f6e (OFT on Arbitrum, Base, Ethereum); total supply 10,000,000,000; airdrop claim deadline 2026-05-30; "$225 million in loans" executed since 2025 launch; "over $1.2 billion in approved facilities" — [USD.AI blog, 2026-04-22](https://usd.ai/blog/chip-is-live); [Binance listing coverage](https://www.mexc.com/news/1043058); [CoinGabbar on Seed Tag](https://www.coingabbar.com/en/crypto-currency-news/why-binance-applied-seed-tag-to-chip-coin-listing)
- 2026-04-29: Wilmington Trust (M&T Bank subsidiary) joins as escrow agent — [blog index](https://usd.ai/blog); [April recap](https://usd.ai/blog/usdai-april-recap)
- 2026-04-30: "USDAI has crossed $100M in active loans"; $34M Sweden loan (B200) is new largest; $11M Texas; sUSDai APY 7.26% — [April recap](https://usd.ai/blog/usdai-april-recap)
- 2026-05-22: Binance Research report (pre-spot): TVL $247M, >$100M deployed loans, ~70,000 depositors, 70 borrowers in pipeline, $1.6B pipeline; 2B CHIP circulating at listing; Binance HODLer allocation 25,000,000 CHIP — [Binance Research](https://www.binance.com/research/analysis/USD.AI)
- May 2026: Permian Labs bought back 338,806,273 CHIP from investor allocations; with prior airdrop buyback of 31,731,287 CHIP, cumulative buybacks = 3.71% of supply — [May 2026 recap](https://usd.ai/blog/usdai-may-2026-recap)
- 2026-06-03: "Allo Points API and Audit" — [blog index](https://usd.ai/blog)
- 2026-06-05: Duos Edge AI $98.1M three-year facility, 2,304 NVIDIA B300 GPUs, operated with Hydra Host — [USD.AI blog](https://usd.ai/blog/usdai-98m-duos-edge-ai-hydra-host-gpu-financing)
- 2026-06-08: "Lighthouse: USD.AI 2026 YTD Report" — [USD.AI blog](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse)
- 2026-06-25: NexGen Cloud $34M facility, 768 NVIDIA B200 GPUs, Sweden — [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [blog index](https://usd.ai/blog)
- 2026-06-29: Fluid $100M DEX Liquidity Facility for sUSDai (Fluid's own capital; LaaS) — [USD.AI blog](https://usd.ai/blog/usdai-fluid-100m-liquidity-facility)
- 2026-06-30: BSQ Capital Partners $300M APAC JV (path to $1B) — [USD.AI blog](https://usd.ai/blog/usdai-bsq-300m-apac-gpu-financing-jv)
- June 2026: DISH (EchoStar subsidiary) strategic investment in Permian Labs (amount undisclosed) — [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [Blockmedia (KR)](https://www.blockmedia.co.kr/archives/1104009)

**2026 H2: Aave approval, loan growth, Bullish/K3 facilities, Arc/Solana, GLX, governance**
- 2026-07-01: Morpho PT-USDai-15OCT borrow markets launched (curated by Steakhouse Financial) — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- 2026-07-06 / 07-13 / 07-20: $11.3M Texas (256 B200, 11.5%) executed; QumulusAI $15.3M into escrow; Hydra Host $54.4M into escrow (1,040 B300) — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- 2026-07-15: Proof of Loans attestation snapshot date (The Network Firm LLP; report published 2026-09-01) — [USD.AI blog](https://usd.ai/blog/proof-of-loans-independent-attestation-report)
- 2026-07-17: LlamaRisk: $205M cash reserves vs $203M deployed; 12 active loans $184M; 20 planned $508M; staking ratio 60%; recommended Aave caps 55M USDai / 55M sUSDai supply, 45M USDai borrow — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-07-20: ARFC raised to Snapshot; 2026-07-24: "Aave governance passed the ARFC for USDai and sUSDai on Aave V3 Arbitrum" — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260); [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- 2026-08-04: sUSDai ATH $349.5M; TVL $436.8M; Pendle added PT-USDai and PT-sUSDD looping markets on Morpho (maturity 2026-10-14) — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans); [Bitget](https://www.bitget.com/news/detail/12560605636875)
- August 2026: sUSDai supply passed $400M (+93% since March); TVL $492.1M at month-end; lifetime deployed $281.8M; 16 financings across 13 borrowers at one-year mark — [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath)
- 2026-08-28: Bullish $100M stablecoin-based debt facility; Bullish to list sUSDai with market-making — [USD.AI blog / PRNewswire](https://usd.ai/blog/usdai-100m-bullish-gpu-financing-facility)
- 2026-09-01: Proof of Loans independent attestation (The Network Firm LLP) — [USD.AI blog](https://usd.ai/blog/proof-of-loans-independent-attestation-report)
- 2026-09-15: USDai/sUSDai live on Arc as "Day 1 launch partner" (Bitwise Premium RWA USDC Vault on Morpho) — [USD.AI blog](https://usd.ai/blog/usdai-is-live-on-arc)
- 2026-09-16: K3 Capital $40M stablecoin-based revolving debt facility to Permian Labs, collateralized by sUSDai — [FinSMEs](https://www.finsmes.com/2026/09/permian-labs-receives-40m-stablecoin-based-revolving-debt-facility-from-k3-capital.html); [Sep recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- 2026-09-18: Robinhood Learn & Earn ($3 in CHIP) — [Sep recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- 2026-09-23: $128.9M facility, 32 NVIDIA GB200 NVL72 systems, British Columbia, Canada; "largest loan originated through the platform to date" — [USD.AI blog](https://usd.ai/blog/usdai-128m-gpu-financing-facility)
- 2026-09-24: USDai and sUSDai live on Solana (Jupiter Lend, Kamino/Allez vault, Exponent, Orca, Loopscale, Mezzanine); eight weeks of incentives — [USD.AI blog](https://usd.ai/blog/usdai-expands-on-solana)
- 2026-09-28: Binance Wallet PYUSD/sUSDai strategy live, $300K CHIP rewards for first 30 days — [Sep recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution); [blog 2026-09-30](https://usd.ai/blog/susdai-now-accessible-on-binance-wallet)
- 2026-09-30: LayerZero omnichain post: chains = Arbitrum (home), Ethereum, Plasma, Base, Solana; "approximately $2.05 billion in aggregate cross-chain transfer volume" — [USD.AI blog](https://usd.ai/blog/usdai-expands-omnichain-infrastructure-with-layerzero)
- Late Sep 2026: GPU loans on books peaked at $401M — [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- 2026-10-01: GLX (GPU Loan Exchange) launched with a $98.1M "season-and-sell" sale of the Duos Edge AI loan (sold at par); utilization ATH 78%; ">$400M in GPU financing processed in the past year"; ">$25B in inbound loan demand" — [USD.AI blog](https://usd.ai/blog/glx-connecting-institutional-capital-to-compute); [CHIP economics post](https://usd.ai/blog/compounding-economics-of-chip)
- 2026-10-02: September recap: TVL $659M+, lifetime deployed $420M+, net APY 6.9% — [USD.AI blog](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- 2026-10-14: Flatiron (S2) ends; Flatiron airdrop 225M CHIP (2.25%), claim 2026-10-20 to 2027-01-31; Metropolitan (S3) runs 2026-10-15 00:00 UTC to 2027-04-14 — [USD.AI blog](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- 2026-10-19: "CHIP Governance Is Live" — CRFC → Snapshot → on-chain vote → timelock; first proposal sets 80% max blended LTV, 1.15x min quarterly DSCR, 90% max sUSDai utilization, min Compute IQ score 60 — [USD.AI blog](https://usd.ai/blog/chip-governance-is-live)
- 2026-10-28: "The Compounding Economics of CHIP" — proposed fee switch: 100% of sUSDai NIM (net of Foundation costs) to programmatic CHIP purchases; gain-on-sale 60% GLX reinvestment / 40% Yield Reserve; USDai NIM switched off until $20B USDai outstanding — [USD.AI blog](https://usd.ai/blog/compounding-economics-of-chip)
- 2026-10-29: NexGen Cloud $106M senior secured term loan via GLX (Silver Point Capital, Victory Park Capital as lenders), 216 HGX B300 servers / 1,728 GPUs, Tier III data center in Finland, 4-year amortizing; ">$200 million of USD.AI's GPU financing has gone through GLX"; "USD.AI has originated more than $500 million in GPU financing in 2026" — [USD.AI blog](https://usd.ai/blog/usdai-106m-nexgen-cloud-finland-gpu-financing)

**Chain deployment summary (dated where possible)**
- Arbitrum: private beta 2025-06-10; public 2025-08-21 (home chain; minting/staking Arbitrum-only as of Oct 2025) — [blog](https://usd.ai/blog/private-beta-is-live); [Aave ARFC](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- Ethereum: deposits accepted via Ethereum mainnet from 2025-09-23; DefiLlama Ethereum USDai balance first appears 2025-09-30 (peak only $291K on 2026-07-17); USDT minting via LiFi on Ethereum by April 2026; Fluid governance listed sUSDai on Ethereum mainnet (June 2026) — [Tekedia](https://www.tekedia.com/usd-ais-500m-deposit-cap-raise-is-a-bold-step-toward-scaling-ai-defi-integration/); [DefiLlama stablecoin API](https://stablecoins.llama.fi/stablecoin/309); [April recap](https://usd.ai/blog/usdai-april-recap); [Fluid post](https://usd.ai/blog/usdai-fluid-100m-liquidity-facility)
- Plasma: launch partner at Plasma mainnet beta 2025-09-25; first DefiLlama balance 2025-09-28 ($67.6M); peak $176.1M on 2025-11-26; $0.78M on 2026-11-01 — [DefiLlama stablecoin API](https://stablecoins.llama.fi/stablecoin/309)
- Base: no official launch post found; covered by Entropy Dune dashboards by 2025-12-20; USDai contract listed on Base by CoinGecko; Aerodrome USDai/USDC pool (~$36K TVL) — [KuCoin insight](https://www.kucoin.com/news/insight/ARB/6946341ded5e0100073836a3); [CoinGecko USDai](https://www.coingecko.com/en/coins/usdai)
- Arc: 2026-09-15 — [blog](https://usd.ai/blog/usdai-is-live-on-arc)
- Solana: 2026-09-24 (CHIP Solana mint chipCAT7vi5CZtbZsn9z7iMPXvFwyAnKz3QFu8XVuHm) — [blog](https://usd.ai/blog/usdai-expands-on-solana); [CoinGecko CHIP](https://www.coingecko.com/en/coins/usd-ai)
- Berachain: mentioned as planned in June 2025; no deployment found — [blog](https://usd.ai/blog/private-beta-is-live)

### Inferences
- The "initial cap" of $100M (filled 2025-08-29) → $110M → $160M (2025-09-04) → $500M window (2025-09-23) → ~$581M (Oct 2025, incl. the $75–100M autoUSDai raise) → cap removed (between 2025-11-20 Pendle expiry and 2026-03-31) is the most internally consistent cap sequence; the IQ.wiki "two $250M caps filled by Sep 11" claim appears to be a mis-dated paraphrase of the Sep 23–26 $500M fill.
- The DefiLlama protocol-TVL ATH (2025-11-22, $702M) and USDai-supply ATH (2026-01-20, $663M) bracket the peak; the Q1 2026 decline (USDai supply $617M on Feb 1 → $309M on Apr 1) coincides with the end of Allo Season 1 (Feb 18), the ICO (Feb 22–27), the PYUSD migration (Feb 26) and the ~$130M March redemption window — i.e., a points-farming unwind rather than a credit event (no defaults reported by LlamaRisk as of July 2026).
- The "Update 10/01/2026" banner on the mint/redeem post, together with the 2026-10-01 GLX launch and record 78% utilization, suggests mint/redeem restrictions were lifted on 2026-10-01 (US date format), not 2026-01-10.

### Gaps
- No testnet date exists; the team never announced a testnet (private beta was the first phase).
- Exact dates for Base deployment, Coinbase Prime go-live, and the cap-removal date are not published.
- No Berachain/Monad/HyperEVM/Hyperliquid-EVM deployments were found (Hyperliquid lists CHIP perps only).
- The official "USD.AI Foundation" legal jurisdiction is not disclosed in the sources reviewed.

---

## Key Question 2: Metrics over time and current snapshot (TVL, supply, depositors, loan book, APY, redemptions)

### Takeaway
DefiLlama protocol TVL (which counts reserve assets, excluding deployed loans) rose from $0.9M (2025-05-19) to a $702M ATH (2025-11-22), fell to $160M (2026-08-01), and recovered to $274M on 2026-11-01 with a further $306M recorded as "borrowed" (deployed GPU loans). The protocol's own "TVL" (USDai + sUSDai) was $660M on 2026-10-14 and sUSDai alone was $549–559M (Oct–Nov 2026). The loan book grew from $1.27M (Oct 2025) to a $401M peak (late Sep 2026), with cumulative originations >$500M in 2026. sUSDai net APY has hovered at 6.9–7.5% in 2026 (7.78% 30-day per Stablewatch on 2026-11-01), against a 7.00% "CHIP Hurdle Rate" target.

### Cited Findings

**DefiLlama protocol TVL time series (USD, reserve assets; "borrowed" = deployed loans), pulled 2026-11-01** — [DefiLlama API /protocol/usd-ai](https://api.llama.fi/protocol/usd-ai) (web page: [defillama.com/protocol/usd-ai](https://defillama.com/protocol/usd-ai))
- 2025-05-19: $912,367 (first datapoint) | 2025-06-01: $1.11M | 2025-06-11: $10.63M (first ≥$10M) | 2025-07-01: $29.49M | 2025-08-01: $48.76M | 2025-08-19: $52.39M (first ≥$50M) | 2025-08-29: $106.12M (first ≥$100M) | 2025-09-01: $110.19M | 2025-09-26: $501.19M (first ≥$250M and ≥$500M) | 2025-10-01: $504.97M | 2025-11-01: $580.04M | 2025-11-22: $701.98M (ATH) | 2025-12-01: $659.19M | 2026-01-01: $684.39M | 2026-02-01: $640.83M | 2026-03-01: $466.96M | 2026-04-01: $310.86M | 2026-05-01: $249.79M | 2026-06-01: $292.98M | 2026-07-01: $196.29M | 2026-08-01: $159.63M | 2026-09-01: $228.10M | 2026-10-01: $248.13M | 2026-11-01: $274.30M (Arbitrum only) + borrowed $306.23M.
- DefiLlama category: RWA; symbol CHIP; chains: Arbitrum only (the protocol adapter tracks Arbitrum).
- $1B TVL was never reached on DefiLlama.

**DefiLlama USDai stablecoin supply (id 309), pulled 2026-11-01** — [stablecoins.llama.fi/stablecoin/309](https://stablecoins.llama.fi/stablecoin/309)
- 2025-09-28: $67.6M (Plasma only, first datapoint) | 2025-10-01: $503.4M | 2025-11-01: $579.0M | 2025-12-01: $622.5M | 2026-01-01: $653.5M | 2026-01-20: $663.2M (ATH) | 2026-02-01: $616.8M | 2026-03-01: $460.5M | 2026-04-01: $308.7M | 2026-05-01: $247.5M | 2026-06-01: $288.0M | 2026-07-01: $192.8M | 2026-08-01: $158.7M | 2026-09-01: $227.7M | 2026-10-01: $247.9M | 2026-11-01: $273.8M.
- By chain on 2026-11-01: Arbitrum $273.04M (ATH $523.9M on 2026-01-13); Plasma $0.78M (ATH $176.1M on 2025-11-26); Ethereum $5.6K (ATH $291K on 2026-07-17). Peg mechanism "crypto-backed"; price $0.9994.

**Protocol-reported and third-party TVL/supply at key dates**
- 2025-06 early: TVL "near zero"; deposits passed $10M mid-June; $30–40M in July; private beta ~$50M — [Yahoo/Cryptonews 2025-08-26](https://finance.yahoo.com/news/yzi-labs-backs-usd-ai-185621852.html)
- 2025-08-26: TVL >$62.7M; borrowing $1.25M — [Yahoo/Cryptonews](https://finance.yahoo.com/news/yzi-labs-backs-usd-ai-185621852.html)
- Early Sep 2025: TVL $110M — [The Defiant](https://thedefiant.io/news/defi/framework-ventures-backed-stablecoin-usdai-hits-usd110m-in-tvl)
- 2025-09-22: "$250M in private beta deposits" — [Bullish](https://www.bullish.com/us/news-insights/bullish-makes-4-million-investment-into-usd-ai-its-first-since-ipo)
- 2025-10-19/20: USDai ~500M (Chaos Labs) vs 418.7M Arbitrum + 159.2M Plasma = 577.9M (LlamaRisk); sUSDai >160M (Chaos) vs 136.5M + 30.4M = 166.9M (LlamaRisk); staking ratio ~29–30%; holders: USDai 2,688 (Arbitrum) / 1,373 (Plasma); sUSDai 2,462 / 996 — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2025-12-18: "over $650 million in on-chain compute-backed assets" — [USD.AI blog](https://usd.ai/blog/pyusd-paypal-usdai-integration)
- 2025-12-20: total supply >650M, ~40% staked (Entropy Dune) — [KuCoin insight](https://www.kucoin.com/news/insight/ARB/6946341ded5e0100073836a3)
- 2026-02-13: TVL "around $658M" — [Tekedia](https://www.tekedia.com/usd-ai-releases-ico-and-airdrop-details/)
- March 2026: $342M TVL at the redemption window; 2026-03-31: ~299M USDai (Arbitrum) and ~160M sUSDai, staking ~59% — [Aave governance, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-05-22: TVL $247M; ~70,000 depositors — [Binance Research](https://www.binance.com/research/analysis/USD.AI)
- 2026-06-08 (Lighthouse YTD): TVL $398M, $202M deployed — [USD.AI blog](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse)
- 2026-06-13: USDai ~306.5M across chains (~298M Arbitrum); "about 6.88 million USDai staked into sUSDai" (as reported; appears inconsistent with other sUSDai figures); USDai DEX pools ~$1.43M; lifetime secondary volume ~$436.5M — [CoinGape](https://coingape.com/usdai-crosses-20m-in-yield-paid-as-gpu-backed-loans-grow/)
- 2026-06-29: >$200M sUSDai TVL on Fluid; Fluid holds 60% of all sUSDai TVL — [USD.AI blog](https://usd.ai/blog/usdai-fluid-100m-liquidity-facility)
- 2026-07-17: $205M cash reserves vs $203M deployed loans; staking ratio 60% — [Aave governance, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-08-04: sUSDai ATH $349.5M; TVL $436.8M — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- 2026-08 month-end: TVL $492.1M; sUSDai supply >$400M (+93% since March) — [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath)
- 2026-10-02: TVL $659M+ — [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- 2026-10-14: sUSDai TVL $549M (from $336M at start of Flatiron, +64%); total TVL $660M (from $522M); GPU loans $311M (from $6.7M; peak $401M late Sep) — [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- Undated (page captured 2026-11-01): Stablewatch sUSDai TVL/market cap $558.69M, price $1.12, 30-day APY 7.78%, yield paid out 7d $741.72K / 30d $3.38M / 90d $8.09M / all-time $25.72M; chains Arbitrum, Plasma, Ethereum — [Stablewatch](https://www.stablewatch.io/analytics/assets/sUSDai-USD.AI)
- Search-snippet variants: Stablewatch "$555.3M TVL for sUSDai"; DefiLlama "$249.15m" (Arbitrum-only) — [Stablewatch](https://www.stablewatch.io/analytics/assets/sUSDai-USD.AI); [DefiLlama](https://defillama.com/protocol/usd-ai)

**Loan book over time**
- Oct 2025: two active loans ~$1.27M (Tactical Compute Holding $620,243.86; Compute Labs, Inc. $649,600); 36-month, 30-day payments, ~15% APR; GPU-backed share of reserves 0.2–0.9%; five more loans expected, first on 2025-10-29 — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-01-27: "first $100M in GPU-backed loans originating Q1 2026"; $1.5B+ pipeline — [USD.AI blog](https://usd.ai/blog/usdai-foundation-chip)
- 2026-03-02 (Messari model): pipeline loan principal ~$105.7M; $1.5B reserve pipeline — [USD.AI blog CN](https://usd.ai/blog/usdai-chip-valuation-report-cn)
- 2026-03-31: 27 loans, $18.1M (6.4% of reserves) — [Aave governance, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260). (Note: "27 loans / $18.1M" vs "$225M in loans executed" claimed by USD.AI on 2026-04-22 — the latter likely includes escrowed/committed amounts.)
- 2026-04-22: "$225 million in loans" since launch; ">$1.2 billion in approved facilities" — [USD.AI blog](https://usd.ai/blog/chip-is-live)
- 2026-04-30: >$100M active loans — [April recap](https://usd.ai/blog/usdai-april-recap)
- 2026-06-08: 13 active loans, avg $15.8M, $283M collateral; 26 term sheets ($817M); $205M closed; 394 leads ($13.0B) — [Lighthouse](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse)
- 2026-06-13: GPU loans "close to half" of reserves; 8 pipeline loans $370M (Entropy Dune) — [CoinGape](https://coingape.com/usdai-crosses-20m-in-yield-paid-as-gpu-backed-loans-grow/)
- 2026-07-17: 12 active loans $184M; 20 planned $508M; "no liquidations, defaults, or missed payments" — [Aave governance, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- July 2026: $81M (3 loans: $69.7M escrow + $11.3M funded) — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- Aug 2026: +$22.8M (2 financings); lifetime deployed $281.8M; 16 financings / 13 borrowers / 4 publicly listed neoclouds; one early repayment — [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath)
- 2026-10-01: >$400M processed in past year; utilization ATH 78% — [GLX post](https://usd.ai/blog/glx-connecting-institutional-capital-to-compute)
- 2026-10-02: lifetime deployed $420M+ — [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- 2026-10-14: GPU loans on books $311M (peak $401M late Sep; drop reflects the $98.1M Duos loan sold via GLX) — [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- 2026-10-29: >$500M originated in 2026; >$200M through GLX — [NexGen post](https://usd.ai/blog/usdai-106m-nexgen-cloud-finland-gpu-financing)
- 2026-11-01: DefiLlama "borrowed" $306.2M — [DefiLlama API](https://api.llama.fi/protocol/usd-ai)

**GPU counts / hardware financed (disclosed deal-by-deal)**
- 1,144 Blackwell (QumulusAI, Feb 2026); 2,304 B300 (Duos, Jun 2026); 768 B200 (NexGen Sweden, Jun 2026); 256 B200 (Texas, Jul 2026); 1,040 B300 (Hydra Host, Jul–Sep 2026); 192 B300 ($10M loan, Sep 2026); 32 GB200 NVL72 systems = 2,304 GPUs at 72/rack (BC Canada, Sep 2026); 1,728 B300 (NexGen Finland, Oct 2026). Hardware types attested: H200, B200, B300, RTX PRO 6000 in US, Canada, Sweden (as of 2026-07-15) — [Proof of Loans](https://usd.ai/blog/proof-of-loans-independent-attestation-report) and deal posts cited in Key Question 3.

**sUSDai APY history**
- Docs target "15% to 25% APR" (2025) — [docs via IQ.wiki](https://docs.usd.ai/technical-overview/technical-protocol-overview#susdai); Binance Research: target 10–15% APR — [Binance Research](https://www.binance.com/research/analysis/USD.AI); stablewatch/ChainCatcher analysis projected 13–17%+ at full hardware backing (2025-10-27) — [Tencent News repost](https://news.qq.com/rain/a/20251027A06K7B00)
- Feb 2026: "yields of about 9% in some periods"; Level Up: "6-10% with sUSDai, including 4.5% $PYUSD incentives" — [Tekedia](https://www.tekedia.com/usd-ai-releases-ico-and-airdrop-details/); [Level Up](https://usd.ai/blog/level-up-finale)
- 2026-04-30: 7.26% — [April recap](https://usd.ai/blog/usdai-april-recap)
- May 2026: Pendle PT-sUSDai fixed >9%; 2026-06-02: June maturity 9.7%, Oct maturity 9.51% — [May recap](https://usd.ai/blog/usdai-may-2026-recap)
- H1 2026 YTD average 7.0% (~$10M paid); projected 12.4% at full deployment; premium ~370 bps over 3-month T-bills, ~285 bps over sDAI — [Lighthouse](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse); [May recap](https://usd.ai/blog/usdai-may-2026-recap)
- June 2026: ~8% (CoinGape), 8% YTD average (Fluid post) — [CoinGape](https://coingape.com/usdai-crosses-20m-in-yield-paid-as-gpu-backed-loans-grow/); [Fluid post](https://usd.ai/blog/usdai-fluid-100m-liquidity-facility)
- 2026-07-17: projected ~11% (LlamaRisk) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-08-05: 8.61% gross / 7.46% net — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- 2026-08 month-end: 7.20% net; cumulative yield $22.4M — [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath)
- 2026-10-02: 6.9% net — [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- 2026-10-14: 6.89% net / 8.07% gross; Flatiron-period holder earnings $15.2M ($8.5M GPU loans + $6.7M PYUSD reserve yield) — [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- 2026-11-01 capture: 30-day APY 7.78%; all-time yield paid $25.72M — [Stablewatch](https://www.stablewatch.io/analytics/assets/sUSDai-USD.AI)
- Cumulative yield milestones: >$10M (April 2026), $15M+ (May 2026), $20M+ (June 2026), $22.4M (Aug 2026), $25.72M (Nov 2026) — [April recap](https://usd.ai/blog/usdai-april-recap); [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath); [Stablewatch](https://www.stablewatch.io/analytics/assets/sUSDai-USD.AI)
- Yield target: "CHIP Hurdle Rate (CHR)": Foundation "intends to support net APY toward 7.00%, subject to available capital"; not a guaranteed minimum; top-ups from a Yield Reserve funded by GLX gain-on-sale — [CHIP governance post](https://usd.ai/blog/chip-governance-is-live)
- Borrower rates: ~15% APR (2025 loans); 7–15% APR per docs; 2026 examples: 12% (NexGen Sweden), 11.5% (Texas), 10% (Hydra Host; Corvex 10% fixed 3y), 15% fixed (QumulusAI Aug 2026), 13% (192-B300 loan), 6.5% escrow / 9% funded ($128.9M IG-offtaker deal) — [docs](https://docs.usd.ai/llms-full.txt); [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans); [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath); [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- Fees: lending admin fee 13.73% of loan interest; sUSDai admin fee 10% of yield (Oct 2025, LlamaRisk); 10 bps USDai redemption fee (Mar 2026); origination fee ~2–3% per loan; sUSDai NIM = 10% of sUSDai yield (Oct 2026) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260); [mint/redeem post](https://usd.ai/blog/usdai-mint-redeem-upgrade); [CHIP economics](https://usd.ai/blog/compounding-economics-of-chip)

**Revenue**
- ARR $1.1M (2025), $4.0M (Q1 2026), $14.3M YTD and $30M Q2-2026 annualized DAO ARR (Lighthouse page) vs "$44.6M protocol ARR" (June recap summarizing the same report) — [Lighthouse](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse); [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets)
- May 2026: #2 on Arbitrum by 30-day revenue; 30-day fees $1.19M; 365-day revenue $3.6M — [May recap](https://usd.ai/blog/usdai-may-2026-recap)

**Redemption mechanics and queue data**
- sUSDai redemptions: 30-day global epoch, FIFO, queue days 1–29, processed day 30, unfilled requests roll over; max sUSDai utilization for new loans 90%; QEV "planned but not yet implemented" (docs) — [docs.usd.ai](https://docs.usd.ai/llms-full.txt); a QEV concept post was published 2025-09-19 — [USD.AI blog](https://usd.ai/blog/queue-extractable-value)
- Oct 2025: "30-day timelock on sUSDai redemptions"; USDai traded at $1.03–1.06 premium in early October 2025 (premium fell from ~6% to ~3%); sUSDai premium peaked ~4.2% — [Aave governance, Chaos Labs](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-03-06: peak queue ~$127M vs ~$330M unallocated USDai; March window processed ~$130M vs $342M TVL — [Aave governance, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- 2026-06-29: Fluid $100M liquidity facility as "exit rails" for sUSDai — [USD.AI blog](https://usd.ai/blog/usdai-fluid-100m-liquidity-facility)
- 2026-07-17: up to 13.9M USDai and ~12.6M sUSDai swappable to USDC within 7.5% price impact; Fluid sUSDai/USDC TVL $18.1M — [Aave governance, LlamaRisk](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)

**CHIP token snapshot (CoinGecko, captured 2026-11-01)** — [CoinGecko CHIP](https://www.coingecko.com/en/coins/usd-ai)
- Price $0.04261; market cap ~$85.2M; FDV ~$426M; circulating 2B; total/max 10B; 24h volume ~$4.56M; ATH $0.1402; ATL $0.02162; 39 spot markets (Binance, Coinbase, Kraken, Bybit, KuCoin, Gate, Toobit, Ourbit, BingX...), 45 derivatives markets (Binance Futures, Hyperliquid, Bybit, OKX, Bitget, MEXC...); contracts: EVM 0x0c1c1c109fe34733fca54b82d7b46b75cfb71f6e (Ethereum/Arbitrum/Base), Solana chipCAT7vi5CZtbZsn9z7iMPXvFwyAnKz3QFu8XVuHm.
- Peak 24h CHIP volume $1.3B in the first week after TGE — [April recap](https://usd.ai/blog/usdai-april-recap)
- ICO proceeds: "about $8.8M" (Chaos Labs, 2026-04-01) vs "approximately $19.4 million" (Atomic Wallet Academy) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260); [Atomic Wallet](https://academy.atomicwallet.io/articles/what-is-usd-ai)
- Tokenomics (Messari report): investors 29.6%, ecosystem 27.5%, core contributors 23.5%, reserve 19.5%; investors/contributors: 12-month lock, 33% unlock, then 67% linear over 24 months — [USD.AI blog CN](https://usd.ai/blog/usdai-chip-valuation-report-cn). Binance Research: airdrop 3%, ICO 7%, ecosystem bootstrapping 10%, 20% circulating at listing — [Binance Research](https://www.binance.com/research/analysis/USD.AI)

**USDai token snapshot (CoinGecko, captured 2026-11-01)** — [CoinGecko USDai](https://www.coingecko.com/en/coins/usdai)
- Price $0.9993; market cap $273.8M (rank #144); supply 273.957M; 24h volume $16.8K; ATH $1.19; ATL $0.7698; contract 0x0a1a1a107e45b7ced86833863f482bc5f4ed82ef on Arbitrum, Ethereum, Plasma, Base; pools: Uniswap V4 (Arbitrum) 73% of volume, Fluid, Curve, Balancer V2 (Arbitrum), Aerodrome Slipstream (Base), Balancer V3 (Plasma).

### Inferences
- DefiLlama's protocol "TVL" ($274M) plus "borrowed" ($306M) ≈ $580M on 2026-11-01, which reconciles with the protocol's own "$660M total TVL" (Oct 14) less the Duos loan sold via GLX and mark-to-market; the team's TVL = USDai + sUSDai, DefiLlama's TVL = undeployed reserves. The report writer should present both, labelled.
- Yield-paid-out figures from Stablewatch ($25.72M all-time) are lower than USD.AI dashboard figures, which the team says include origination fees — [April recap](https://usd.ai/blog/usdai-april-recap).
- Depositor count ~70,000 (Binance Research, May 2026) is far higher than the Oct 2025 on-chain holder counts (~2.7K USDai / ~2.5K sUSDai on Arbitrum), consistent with the Allo Game broadening participation in Q4 2025–Q1 2026; the Oct 2026 points distribution (top 100 wallets = 73% of points) shows capital remains concentrated.

### Gaps
- No continuous sUSDai supply time series was obtainable (DefiLlama tracks USDai only; Stablewatch shows a single undated figure). Entropy Advisors' Dune dashboard (dune.com/entropy_advisors/usdai-usdai) likely has it but could not be fetched.
- No published count of current sUSDai holders/depositors beyond Binance Research's ~70,000 (May 2026).
- No official total GPU count financed; only deal-level counts.
- The ICO raise amount is contested ($8.8M vs $19.4M) and USD.AI never published it.
- Current redemption queue length/wait time is not published; only the March 2026 peak is documented.

---

## Key Question 3: Borrowers and deals (named operators, facility sizes, hardware, locations)

### Takeaway
USD.AI has announced four large "guidance" facilities totalling up to $1.5B (QumulusAI $500M, Sharon AI $500M, Quantum Solutions $200M, plus the BSQ $300M JV) and roughly a dozen funded loans ranging from $620K (July 2025) to $128.9M (Sep 2026), concentrated in NVIDIA B200/B300/GB200 hardware in the US, Canada, Sweden and Finland; as of August 2026 the book held 16 financings across 13 borrowers with no reported defaults.

### Cited Findings
- **Tactical Compute Holding Ltd** (ADGM, UAE): $620,243.86 USDC, 36 months, ~15% APR (first loan, July 2025). Note: Tactical Compute is described as a hardware business overseen by Permian Labs CEO David Choi — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260); [IQ.wiki David Choi](https://iq.wiki/wiki/david-choi)
- **Compute Labs, Inc.** (Delaware, US): $649,600 USDC, 36 months, ~15% APR (2025) — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- Early borrowers listed on usd.ai (per IQ.wiki): Lyceum, Hydra Host, Compute Labs, TACOM — [IQ.wiki](https://iq.wiki/wiki/usdai)
- **QumulusAI** (Atlanta-datelined; "vertically integrated AI infrastructure company"): $500M non-recourse facility (2025-10-09) covering up to 70% of approved GPU deployments, GWRT collateral; first drawdown 2026-02-19 for 1,144 Blackwell GPUs (760 + 384-GPU B300 cluster); 2026 target >20,000–23,000 GPUs; draws of $4.3M, $16.4M (H200, 2026-04-17), $15.3M (escrow 2026-07-13); August 2026 loan at 15% fixed — [Newswire Oct 2025](https://www.newswire.com/news/qumulusai-secures-500m-non-recourse-financing-facility-through-usd-ai-to); [Newswire Feb 2026](https://www.newswire.com/news/qumulusai-deploys-1-144-nvidia-blackwell-gpus-through-drawdown-under-500m-usd); [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans); [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath); [DCD](https://www.datacenterdynamics.com/en/news/qumulusai-raises-500m-to-expand-ai-compute-infrastructure/)
- **Quantum Solutions Co., Ltd.** (TSE: 2338, Japan): up to $200M guidance facility (2025-12-09), board-authorized, non-recourse, GPU types undisclosed; holds ETH/BTC treasury — [USD.AI blog](https://usd.ai/blog/quantum-solutions-usdai-financing)
- **Sharon AI** (SharonAI Holdings, Australia): up to $500M debt facility (2026-01-22), initial $65M draw in Q1 2026, Australia and APAC; followed a $100M convertible note in Dec 2025 — [The Block](https://www.theblock.co/post/386759/onchain-lending-protocol-usdai-approves-500-million-loan-australian-ai-startup); [BusinessWire](https://www.businesswire.com/news/home/20260122439371/en/); [Pulse2](https://pulse2.com/sharon-ai-lines-up-to-500-million-usd-ai-debt-facility-for-gpu-financed-compute-expansion-across-australia-and-asia-pacific)
- **Crucible Capital**: $26.8M loan, NVIDIA B300 (2026-04-06) — [USD.AI blog](https://usd.ai/blog/crucible-capital-26m-gpu-backed-loan); [April recap](https://usd.ai/blog/usdai-april-recap)
- **Unnamed Texas borrower**: $11M (2026-04-30) and $11.3M for 32 B200 servers / 256 GPUs at 11.5% APY (executed 2026-07-06) — [April recap](https://usd.ai/blog/usdai-april-recap); [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- **NexGen Cloud** (European AI cloud; Hyperstack brand logo on homepage): $34M facility for 768 NVIDIA B200 GPUs in Sweden (announced 2026-06-25, funded June, 12% APY post-deployment; first reported as "$34M in Sweden" on 2026-04-30); second facility $106M senior secured term loan via GLX for 216 HGX B300 servers / 1,728 GPUs in a Tier III data center in Finland, 4-year amortizing, take-or-pay offtake with "a leading AI inference platform", lenders Silver Point Capital and Victory Park Capital (2026-10-29); combined $140M — [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [NexGen Finland post](https://usd.ai/blog/usdai-106m-nexgen-cloud-finland-gpu-financing); [usd.ai homepage logos](https://usd.ai/)
- **Duos Edge AI, Inc.** (subsidiary of Duos Technologies Group, Nasdaq: DUOT), operated with **Hydra Host** (Brokkr AI Factory OS): $98.1M three-year non-recourse facility, 2,304 NVIDIA B300 GPUs in modular Edge Data Centers (2026-06-05); homepage lists the site as Columbus, Georgia, USA; loan sold at par via GLX on 2026-10-01 — [USD.AI blog](https://usd.ai/blog/usdai-98m-duos-edge-ai-hydra-host-gpu-financing); [GLX post](https://usd.ai/blog/glx-connecting-institutional-capital-to-compute); [usd.ai homepage](https://usd.ai/)
- **Hydra Host** (Boulder, CO; 40+ data center partners, 30K+ GPUs): $54.4M loan for 1,040 NVIDIA B300 GPUs, escrow 2026-07-20, funded Sep 2026 at 10% — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans); [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- **Corvex**: 10% fixed three-year financing (August 2026; size undisclosed; part of $22.8M August total with QumulusAI) — [August recap](https://usd.ai/blog/august-recap-100m-facility-susdai-ath)
- **Unnamed**: $10M backed by 192 B300s at 13% (September 2026) — [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- **Unnamed publicly listed GPU cloud provider**: $128.9M facility, 32 NVIDIA GB200 NVL72 systems, British Columbia, Canada, multi-year agreement with "blue-chip, investment-grade counterparty"; 6.5% in escrow / 9% once funded (2026-09-23) — [USD.AI blog](https://usd.ai/blog/usdai-128m-gpu-financing-facility); [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- **Axos** appears as a partner/borrower logo on the homepage (no deal post found) — [usd.ai homepage](https://usd.ai/)
- **BSQ Capital Partners** (Singapore, founded 2022): $300M APAC JV (Australia, Japan, South Korea, Southeast Asia, India), senior secured term loans, path to $1B; BSQ as investment manager (2026-06-30) — [USD.AI blog](https://usd.ai/blog/usdai-bsq-300m-apac-gpu-financing-jv)
- Attested hardware/locations as of 2026-07-15: NVIDIA H200, B200, B300, RTX PRO 6000 in the United States, Canada and Sweden; attestation by The Network Firm LLP (agreed-upon procedures, not an audit) — [Proof of Loans](https://usd.ai/blog/proof-of-loans-independent-attestation-report)
- Loan structure (docs): per-loan LTV 70–80%, blended portfolio cap 80%, min quarterly DSCR 1.15x, 3-year amortization with 30-day payments, DSRA ~10% of gross loan, min Compute IQ score 60; Compute IQ "built on more than $25 billion of GPU financing data" — [docs.usd.ai](https://docs.usd.ai/llms-full.txt); [CHIP governance post](https://usd.ai/blog/chip-governance-is-live)
- Pipeline: 394 leads / $13.0B (Jun 2026); ">$25B in inbound loan demand since launch" from "a couple hundred borrowers" (Oct 2026); "$13 billion in prospective financings over eight months across 200+ neoclouds" (Aug 2026) — [Lighthouse](https://usd.ai/blog/usdai-2026-ytd-report-lighthouse); [GLX post](https://usd.ai/blog/glx-connecting-institutional-capital-to-compute); [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)

### Inferences
- Deal sizes stepped up roughly 10x per quarter in 2026 ($26.8M → $34M → $98.1M → $128.9M), and the mix shifted from on-demand neocloud rentals toward investment-grade take-or-pay offtakes (lower 6.5–9% rates), which the GLX season-and-sell model depends on.
- Announced "facility" ceilings ($1.5B+) far exceed funded principal (~$300–400M on books), so facility headlines should not be read as deployed capital.

### Gaps
- Borrower identity for the $128.9M BC facility, the Texas loans, the $10M 192-B300 loan, and the Corvex loan size were not disclosed.
- Actual drawn amounts under Sharon AI and Quantum Solutions facilities were not found.
- No per-loan LTV, DSCR or valuation figures beyond the attestation description.

---

## Key Question 4: Ecosystem integrations and partnerships (DeFi venues, chains, custodians, exchanges, treasury issuers, insurers, vendors)

### Takeaway
USDai/sUSDai are integrated across Arbitrum-centric DeFi (Fluid, Curve, Uniswap, Balancer, Pendle, Morpho, Euler, Aave V3 Arbitrum approved July 2026), Plasma, Base (Aerodrome), Arc (Morpho/Bitwise), and Solana (Jupiter Lend, Kamino, Exponent, Orca, Loopscale, Mezzanine), with LayerZero OFT as the bridge layer; institutional rails include Coinbase Prime, Anchorage (CHIP custody), Wilmington Trust (escrow), Bullish (facility + sUSDai listing), K3 Capital, Silver Point/Victory Park (GLX buyers), and PayPal/Paxos PYUSD as the reserve asset (replacing M0's wM in Feb 2026).

### Cited Findings

**Reserve/backing partners**
- M0 (wM tokenized T-bill dollar): backing from 2025-03-25 until migration to PYUSD finalized 2026-02-26 — [USD.AI blog index](https://usd.ai/blog); [M0 research](https://research.m0.org/research/usdai-uses-m0s-stablecoin-platform-to-launch-composable-synthetic-dollar); [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- PayPal PYUSD (issued by Paxos): announced 2025-12-18; 4.5% on up to $1B for one year from early January 2026; "nearly all of PYUSD's supply on Arbitrum is deployed within USDai" (Feb 2026); docs now say USDai "collateralized by PYUSD" — [USD.AI blog](https://usd.ai/blog/pyusd-paypal-usdai-integration); [The Defiant](https://thedefiant.io/news/tradfi-and-fintech/paypal-pyusd-supply-crosses-usd4-billion); [docs.usd.ai](https://docs.usd.ai)
- "Wrapped US T-Bills" remain in reserves alongside PYUSD and GPU loans (Dune, June 2026) — [CoinGape](https://coingape.com/usdai-crosses-20m-in-yield-paid-as-gpu-backed-loans-grow/)

**Oracles, bridges, infrastructure**
- Chainlink official oracle (2025-10-09); LayerZero OFT for USDai/sUSDai/CHIP; Uniswap V3 for internal swaps; MetaStreet lending pools — [blog index](https://usd.ai/blog); [LayerZero post](https://usd.ai/blog/usdai-expands-omnichain-infrastructure-with-layerzero); [IQ.wiki](https://iq.wiki/wiki/usdai)
- LiFi for USDT → USDai/sUSDai minting on Arbitrum and Ethereum; Sunrise for Solana expansion (April 2026) — [April recap](https://usd.ai/blog/usdai-april-recap)

**DEX and lending venues (with dated liquidity where available)**
- Arbitrum, Oct 2025: Fluid USDai/USDC ~$20.5–20.9M; Curve USDai/USDC ~$5.15–7.5M; Uniswap v3 ~$0.77–5.34M; PancakeSwap ~$270K; Curve sUSDai/USDC ~$12.8M; Fluid sUSDai ~$2.79M; Uniswap sUSDai ~$1.66M. Plasma: Balancer USDai/USDT0 ~$41.7M (Chaos cites ~$182M across pairs), Balancer sUSDai ~$2.44–4M — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- Euler: AutoVaults (Aug 2025) and Euler Frontier USDai market on Plasma (unwound Oct–Nov 2025; K3 Capital took over curation) — [Arbitrum launch post](https://usd.ai/blog/usdai-launches-on-arbitrum-autovaults); [AutoVault sunset](https://usd.ai/blog/sunsetting-auto-strategy-vaults)
- K3 Capital and Concrete: AutoVault curators (Aug–Nov 2025); K3 $40M revolving facility (Sep 2026) — [Arbitrum launch post](https://usd.ai/blog/usdai-launches-on-arbitrum-autovaults); [FinSMEs](https://www.finsmes.com/2026/09/permian-labs-receives-40m-stablecoin-based-revolving-debt-facility-from-k3-capital.html)
- Pendle: Allo rewards tokenization partner (Aug 2025); Arbitrum pools incl. a 20Nov2025 maturity; Plasma USDai/sUSDai pools (2026-03-19); PT-sUSDai-15OCT2026 and USDai 15OCT2026 markets on Arbitrum (~$50.4M TVL on 2026-07-29 per Portals; ~$59.6M Pendle TVL per DefiLlama RWA page); PT-USDai/PT-sUSDD markets on Morpho (2026-08-04); Season 3 lists Pendle YTs with 2027-02-25 expiry — [Arbitrum launch post](https://usd.ai/blog/usdai-launches-on-arbitrum-autovaults); [crypto.news](https://crypto.news/pendle-expands-defi-offerings-to-plasma-with-5-yield-markets/); [Portals](https://explorer.portals.fi/yield/arbitrum:0xcbf629c8d396b1261f81f55175afa010e94787d8.md); [DefiLlama RWA USDai](https://defillama.com/rwa/asset/usdai); [Bitget](https://www.bitget.com/news/detail/12560605636875); [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- Morpho: PT-USDai-15OCT borrow markets curated by Steakhouse Financial (2026-07-01); Bitwise Premium RWA vault (Ethereum and Arc); Re7 "Frax-USD.AI Ecosystem" vault — [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans); [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution); [Arc post](https://usd.ai/blog/usdai-is-live-on-arc)
- Fluid: $100M committed DEX Liquidity Facility (2026-06-29); >$200M sUSDai TVL and 60% of all sUSDai on Fluid; sUSDai listed on Ethereum mainnet via Fluid governance; smart collateral (T2/T4) in Season 3 — [Fluid post](https://usd.ai/blog/usdai-fluid-100m-liquidity-facility); [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- Aave V3 Arbitrum: ARFC (2025-10-15) initially opposed; reopened 2026-02-17; supported by Chaos Labs (2026-04-01) and LlamaRisk (2026-04-03, 2026-07-17); Snapshot 2026-07-20; passed 2026-07-24; recommended caps 55M USDai / 55M sUSDai supply, 45M USDai borrow, CAPO 15–16% max yearly growth — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260); [July recap](https://usd.ai/blog/usdai-july-recap-81m-deployed-loans)
- Base: Aerodrome Slipstream USDai/USDC pool (~$36K TVL) and CHIP/Aerodrome pools — [CoinGecko USDai](https://www.coingecko.com/en/coins/usdai); [CHIP is live](https://usd.ai/blog/chip-is-live)
- Solana (2026-09-24): Jupiter Lend, Kamino (Allez Labs-managed vault), Exponent, Orca, Loopscale, Mezzanine — [Solana post](https://usd.ai/blog/usdai-expands-on-solana)
- Arc (2026-09-15): Day-1 launch partner; Morpho Bitwise Premium RWA USDC Vault — [Arc post](https://usd.ai/blog/usdai-is-live-on-arc)
- Other venues named in Season 3 eligibility: Curve, Balancer, Exponent LP, Uniswap (CHIP LP) — [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- Season 3 mentions DefiLlama RWA page listing sUSDai positions on Plasma, Pendle V2, Morpho Blue, Euler V2 and Kamino Lend — [DefiLlama RWA sUSDai](https://defillama.com/rwa/asset/sUSDai)

**Custody, escrow, exchanges, distribution**
- Coinbase Prime integration (2025-11-20) — [blog index](https://usd.ai/blog)
- Anchorage Digital institutional custody for CHIP (April 2026) — [April recap](https://usd.ai/blog/usdai-april-recap)
- Wilmington Trust (M&T Bank) escrow agent (2026-04-29) — [April recap](https://usd.ai/blog/usdai-april-recap)
- Bullish: $4M equity (2025-09-22), $100M debt facility and planned sUSDai listing with market making (2026-08-28) — [Bullish](https://www.bullish.com/us/news-insights/bullish-makes-4-million-investment-into-usd-ai-its-first-since-ipo); [Bullish facility post](https://usd.ai/blog/usdai-100m-bullish-gpu-financing-facility)
- Binance Wallet DeFi: PYUSD/sUSDai strategy (2026-09-28) — [blog](https://usd.ai/blog/susdai-now-accessible-on-binance-wallet)
- Robinhood: CHIP spot listing (2026-04-21) and Learn & Earn (2026-09-18) — [CHIP is live](https://usd.ai/blog/chip-is-live); [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- CHIP exchange coverage: 39 spot / 45 derivatives markets (CoinGecko, Nov 2026) — [CoinGecko CHIP](https://www.coingecko.com/en/coins/usd-ai)

**Insurance, valuation, attestation**
- Barkr (formerly Barker): residual-value warranty backed by an A-rated reinsurer (described as Munich Re by ACI); Barkr facilitated ~$2B in collateral valuations; max LTV raised 70% → 80% with ~80% Barker coverage — [Barkr post](https://usd.ai/blog/usdai-barker-insured-gpu-loan-coverage); [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- The Network Firm LLP: Proof of Loans attestation (2026-09-01) — [Proof of Loans](https://usd.ai/blog/proof-of-loans-independent-attestation-report)

**Institutional capital / GLX**
- GLX buyers: unnamed institutional buyer for the Duos loan (2026-10-01); Silver Point Capital and Victory Park Capital (NexGen Finland, 2026-10-29) — [GLX post](https://usd.ai/blog/glx-connecting-institutional-capital-to-compute); [NexGen Finland](https://usd.ai/blog/usdai-106m-nexgen-cloud-finland-gpu-financing)

**Investors (equity)**
- Framework Ventures (lead), Dragonfly, Bullish, Arbitrum Foundation, DCG, Delphi, Fintech Collective (Series A, Aug 2025); YZi Labs (2025-08-26); Bullish Capital $4M (2025-09-22); Coinbase Ventures (2025-11-17); DISH/EchoStar (June 2026). A BuiltIn profile lists total raised $38M incl. Ethereal, Nascent, Alliance — [CoinDesk](https://www.coindesk.com/business/2025/08/13/usd-ai-raises-usd13m-to-expand-gpu-backed-stablecoin-lending); [Tekedia](https://www.tekedia.com/usd-ais-500m-deposit-cap-raise-is-a-bold-step-toward-scaling-ai-defi-integration/); [Yahoo/Cryptonews](https://finance.yahoo.com/news/yzi-labs-backs-usd-ai-185621852.html); [Coinbase Ventures post](https://usd.ai/blog/usdai-secures-coinbase-ventures-investment); [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [BuiltIn Colorado](https://www.builtincolorado.com/company/permian-labs)
- Plasma Foundation: strategic partner; $250M of the Sep 2025 cap allocated to Plasma — [Tekedia](https://www.tekedia.com/usd-ais-500m-deposit-cap-raise-is-a-bold-step-toward-scaling-ai-defi-integration/)

### Inferences
- Liquidity has migrated from Plasma (Balancer USDT0 pools, $176M USDai peak Nov 2025) back to Arbitrum/Ethereum (Fluid) — Plasma USDai supply is now <$1M; the Plasma "launch partner" phase was incentive-driven.
- Tokenized-treasury partnerships are limited to M0 (ended) and the unnamed "wrapped T-bill" holdings; no evidence of Franklin Templeton, Superstate, BUIDL or Sky/USDS partnerships.

### Gaps
- No Franklin Templeton / Superstate / BlackRock BUIDL / Sky partnerships found.
- No hardware-vendor (NVIDIA/Supermicro/Dell) partnership announcements found; NVIDIA/Rockchip are named only as collateral types.
- Aave V3 Arbitrum go-live date after the July 2026 vote is not confirmed in sources.
- Exact Pendle Arbitrum market launch date (likely Sep 2025 given the "20Nov2025" maturity) was not located in an official post.

---

## Key Question 5: Community and marketing (Allo points program, referrals, Kaito, KOLs, social metrics)

### Takeaway
The points program is officially called the "Allo Game" (an earlier June 2025 post called it "Cores"): Season 1 (2025-08-20 to 2026-02-18) split users into ICO (KYC, 5x) vs Airdrop (2x) alignment and funded a 10% token allocation (7% ICO at $300M FDV + 3% airdrop); Season 2 "Flatiron" (2026-02-19 to 2026-10-14) paid 225M CHIP (2.25%) with multipliers of 1x–40x and a referral boost; Season 3 "Metropolitan" (2026-10-15 to 2027-04-14) uses a published multiplier table (1x–15x). No Kaito/Yaps campaign was found.

### Cited Findings
- Private beta (2025-06-10) referenced a rewards program "Cores" with beta participants as "early recipients" — [USD.AI blog](https://usd.ai/blog/private-beta-is-live)
- Allo Game (2025-08-20): points daily per dollar; ICO Alignment (brown) via holding USDai, Airdrop Alignment (teal) via staking sUSDai; 10% of supply to the game (70% ICO / 30% airdrop); ICO = 7% at $300M FDV, KYC required; airdrop = 3%; game ends after $20M yield paid or 6 months — [USD.AI blog](https://usd.ai/blog/the-allo-game)
- Multipliers reported: USDai holders 5x, sUSDai stakers 2x (Chinese media); 25x for autoUSDai (Oct 2025); 15x AutoUSDai boost ending 2025-11-07; non-aligned pool 10x → 3x (2025-10-06); 10x for depositors taking the airdrop after AutoVault sunset; Pendle YT example "100x leverage" — [Tencent/ChainCatcher](https://news.qq.com/rain/a/20251027A06K7B00); [cap/Euler post](https://usd.ai/blog/usdai-cap-euler-autousdai); [AutoVault sunset](https://usd.ai/blog/sunsetting-auto-strategy-vaults); [Allo Game](https://usd.ai/blog/the-allo-game)
- Season 1 ended 2026-02-18; unaligned points "will be burned" — [CHIP ICO post](https://usd.ai/blog/chip-ico-airdrop)
- Level Up (2026-02-12): lock Pendle YTs for discounted ICO ($270M/$190M FDV) or airdrop buyouts ($350M/$420M implied FDV); YT maturities 2026-06-17 and 2026-10-14 — [Level Up](https://usd.ai/blog/level-up-finale); [CHIP is live](https://usd.ai/blog/chip-is-live)
- Flatiron (S2): 2026-02-19 to 2026-10-14; multipliers 1x–40x; "all rewards distributed through $CHIP airdrops"; Flatiron Referral Boost for creators (2026-04-16); sCHIP staking earned 10x points; 225M CHIP (2.25%) pool incl. integration partners; claim 2026-10-20 to 2027-01-31; ~904B points from deposits / ~955B incl. referrals; top 100 wallets = 699B (~73%) — [CHIP is live](https://usd.ai/blog/chip-is-live); [blog index](https://usd.ai/blog); [April recap](https://usd.ai/blog/usdai-april-recap); [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- Metropolitan (S3): 2026-10-15 to 2027-04-14; multipliers per $1/day: USDai wallet 2x; sUSDai wallet 1x; sUSDai single-asset collateral (Morpho, Fluid, Euler, Jupiter Lend, Kamino) 3x; Fluid smart collateral 4x; sUSDai LP 4x; sUSDai YT 6x; locked YT sUSDai (2027-02-25) 10x; USDai/USDC DEX LP 8x; USDai Pendle LP 8x; USDai Pendle YT 10x; locked YT USDai 15x; CHIP LPs 12x; locked CHIP/sCHIP earn none; referral boosts ended with S2; no minimum, no cap — [Metropolitan post](https://usd.ai/blog/allo-game-flatiron-ends-metropolitan-begins)
- "Allo Points API and Audit" published 2026-06-03 — [blog index](https://usd.ai/blog)
- Third-party points calculator at gpu.credit — [gpu.credit](https://gpu.credit/)
- CHIP emissions fell from 3% of supply (S1 airdrop) to 2.25% (S2) — [CHIP economics](https://usd.ai/blog/compounding-economics-of-chip)
- Binance HODLer Airdrop allocation 25,000,000 CHIP; Binance applied a Seed Tag at listing — [Binance Research](https://www.binance.com/research/analysis/USD.AI); [CoinGabbar](https://www.coingabbar.com/en/crypto-currency-news/why-binance-applied-seed-tag-to-chip-coin-listing)
- Events/media: PTC 26 Hawaii (2026-01-09), Digital Asset Yield Summit (2026-05-04), CoinDesk Live at Consensus Miami (2026-05-07), The DCo Podcast and Shoal Signal (2026-05-27), Robinhood Learn & Earn (2026-09-18) — [May recap](https://usd.ai/blog/usdai-may-2026-recap); [September recap](https://usd.ai/blog/usdai-september-recap-capital-compute-distribution)
- Recognition: RootData List 2025 Top 100 — [Tencent/ChainCatcher](https://news.qq.com/rain/a/20251027A06K7B00)
- Prediction-market signal: Polymarket ~60% odds of day-one FDV >$300M (Feb 2026) — [Tekedia](https://www.tekedia.com/usd-ai-releases-ico-and-airdrop-details/)
- Official channels: X @USDai_Official, Telegram t.me/usdaiofficial — [docs.usd.ai](https://docs.usd.ai)

### Inferences
- The point multipliers and emergency boosts (25x/15x) were used as a liquidity-management tool (e.g., to fund the Euler unwind), which explains the extreme short-term inflows (e.g., $75M in 52 seconds) and the later outflows after Season 1 ended.

### Gaps
- No Kaito/Yaps campaign or leaderboard for USD.AI was found in any source.
- No follower counts, Discord/Telegram member counts, or named KOL coverage with reach metrics were found.
- Season 3 CHIP pool size is not disclosed.

---

## Key Question 6: 2026 developments (products, expansion, regulatory/legal, statements)

### Takeaway
2026 brought the token (CHIP TGE 2026-04-21, governance live 2026-10-19, fee switch proposed 2026-10-28), the PYUSD reserve migration, Barkr insurance, Wilmington Trust escrow, the GLX loan exchange (2026-10-01) with Silver Point/Victory Park as buyers, Bullish ($100M) and K3 ($40M) credit lines, APAC expansion via BSQ, new chains (Arc, Solana), and a stated 2026 goal of $1B–$1.5B in loans against >$500M actually originated by late October.

### Cited Findings
- Product: USD.AI Foundation announced (2026-01-27) as "off-chain steward of the USD.AI DAO" — [blog](https://usd.ai/blog/usdai-foundation-chip)
- Product: mint/redeem routed through KYC'd market makers from 2026-04-06 with 10 bps fee, later reverted to permissionless (banner "Update 10/01/2026") — [blog](https://usd.ai/blog/usdai-mint-redeem-upgrade)
- Product: Allo Points API & audit (2026-06-03); rebuilt dashboard showing yield, price history and loans (May 2026) — [blog index](https://usd.ai/blog); [May recap](https://usd.ai/blog/usdai-may-2026-recap)
- Product: Proof of Loans attestation (2026-09-01) — [blog](https://usd.ai/blog/proof-of-loans-independent-attestation-report)
- Product: GLX "season-and-sell" (2026-10-01); roadmap targets cost per loan <$1M and time-to-loan of 7 days vs ~6 months today; gain-on-sale spread ~1–2% today, 5–6% target "once ABS markets open" — [GLX post](https://usd.ai/blog/glx-connecting-institutional-capital-to-compute); [CHIP economics](https://usd.ai/blog/compounding-economics-of-chip)
- Governance: first CRFC "Origination Parameters for New sUSDai Financings" (2026-10-19) — [blog](https://usd.ai/blog/chip-governance-is-live)
- Token economics: proposed 100% of sUSDai NIM to CHIP purchases; cumulative buybacks 3.71% of supply by May 2026; CHIP price $0.0426 / FDV $426M on 2026-11-01 (vs $300M ICO FDV, $0.1402 ATH) — [CHIP economics](https://usd.ai/blog/compounding-economics-of-chip); [May recap](https://usd.ai/blog/usdai-may-2026-recap); [CoinGecko](https://www.coingecko.com/en/coins/usd-ai)
- Expansion: BSQ APAC JV ($300M → $1B), Sharon AI (Australia), Quantum Solutions (Japan), NexGen (Sweden, Finland), BC Canada deal; Arc and Solana deployments — see Key Questions 3–4
- Roadmap statements: "on track for $1.5 Bn in loans in 2026" (2026-02-12); Binance Research roadmap: Q2 2026 $100M deployed, Q4 2026 $1B deployed; "10,000 Neoclouds" thesis post (2026-10-16); "$2T compute financing middle market" (2026-07-09) — [Level Up](https://usd.ai/blog/level-up-finale); [Binance Research](https://www.binance.com/research/analysis/USD.AI); [blog index](https://usd.ai/blog)
- Strategic investors in 2026: DISH/EchoStar (June; exploring EchoStar energy-linked sites for data centers) — [June recap](https://usd.ai/blog/usdai-june-recap-new-highs-across-markets); [Blockmedia](https://www.blockmedia.co.kr/archives/1104009)
- Team: Evan Meagher joined as Senior Advisor (2026-01-14) — [blog index](https://usd.ai/blog)
- Legal/regulatory context: analysts expect sUSDai "likely to be classified as a security in major jurisdictions"; UCC Article 7 warehouse-receipt framework "has not been tested in court" (stablewatch analysis, Oct 2025); ICO required KYC via CoinList; Binance Seed Tag — [Tencent/ChainCatcher](https://news.qq.com/rain/a/20251027A06K7B00); [CHIP ICO post](https://usd.ai/blog/chip-ico-airdrop); [CoinGabbar](https://www.coingabbar.com/en/crypto-currency-news/why-binance-applied-seed-tag-to-chip-coin-listing)
- Incidents/pauses: none involving loan defaults ("no liquidations, defaults, or missed payments" as of 2026-07-17); stress events were the Oct 2025 Euler Frontier unwind, the Oct 2025 USDai premium ($1.03–1.06), and the March 2026 ~$127–130M redemption queue — [Aave governance](https://governance.aave.com/t/arfc-onboard-usdai-susdai-to-aave-v3-arbitrum-instance/23260)
- Notable quotes: Conor Moore: "NexGen Cloud came back to us for a facility three times the size of the first" (2026-10-29); David Choi: Bullish "recognizes that compute is becoming a credit market in its own right" (2026-08-28) — [NexGen Finland](https://usd.ai/blog/usdai-106m-nexgen-cloud-finland-gpu-financing); [Bullish facility](https://usd.ai/blog/usdai-100m-bullish-gpu-financing-facility)

### Inferences
- The 2026 strategy pivoted from "deposit growth via points" (2025) to "originate-to-distribute via GLX" with institutional buyers, which is why deployed loans on the books fell from $401M to $311M in October even as cumulative originations passed $500M.
- The $1B-deployed Q4 2026 target (Binance Research) appears unlikely to be met by year-end given $420M+ lifetime deployed on 2026-10-02 and >$500M originated by 2026-10-29.

### Gaps
- No regulatory filings (SEC, MAS, etc.) or acquisitions by Permian Labs were found.
- No October 2026 third-party news coverage was found beyond official posts; the latest independent item is the K3 facility (FinSMEs, 2026-09-16).
- The USD.AI homepage loan-book stats did not render (showed "—"), so no official live dashboard numbers could be captured on 2026-11-01.
