# Chronicle 다이제스트 — 2026-11-02

> 최근 30일(2026-10-03~) 관측. 시간해자 아카이브의 축적물 요약.

## 한눈에
- 소스 **12개** · 추적 엔티티 **109,063** · 원장 총 이벤트 **198,638** · 체인 총 길이 **198,638**
- 이번 기간: 소멸 **1596** · 수정 **29780** · 신규 **23,125**
- **3중 공증**: 해시체인 12/12 소스 봉인 · git 히스토리 · TSA 외부앵커 **12/12** 머리 고정

## 사라진 것 — 소멸 (지금 찍은 자만 소유)
- `mcp-census` **server:ai.inxy/seo-audit** — 1.4.0 _(2026-11-01)_
- `mcp-census` **server:app.floot.shadowgraph-live/shadowgraph** — 1.0.0 _(2026-11-01)_
- `mcp-census` **server:com.ai-agents-make-money-here/mcp** — 1.0.0 _(2026-11-01)_
- `mcp-census` **server:com.ai-erd/ai-erd** — 1.0.0 _(2026-11-01)_
- `mcp-census` **server:com.booklint/desk** — 0.4.0 _(2026-11-01)_
- `mcp-census` **server:com.booklint/stamp** — 0.1.0 _(2026-11-01)_
- `mcp-census` **server:com.boosthis/boosthis** — 1.0.0-alpha.82 _(2026-11-01)_
- `mcp-census` **server:com.botrotation/discovery** — 1.5.0 _(2026-11-01)_
- `mcp-census` **server:com.clauxel.equiblesagent/equiblesagent-mcp** — 1.0.0 _(2026-11-01)_
- `mcp-census` **server:com.drillable/gateway** — 0.3.0 _(2026-11-01)_
- `mcp-census` **server:com.kriptonianlabs/xrpl** — 0.10.2 _(2026-11-01)_
- `mcp-census` **server:com.mintverdict/mintverdict** — 0.1.2 _(2026-11-01)_
- `mcp-census` **server:com.moodlemcp/moodle** — 1.0.0 _(2026-11-01)_
- `mcp-census` **server:com.openwants/openwants** — 3.3.0 _(2026-11-01)_
- `mcp-census` **server:com.runmirrors/mirrors** — 1.0.0 _(2026-11-01)_
- `mcp-census` **server:dev.fruitstand/fund-returns** — 1.0.1 _(2026-11-01)_
- `mcp-census` **server:dev.kaneky/jobpost** — 0.1.1 _(2026-11-01)_
- `mcp-census` **server:dev.kaneky/kimage** — 0.18.4 _(2026-11-01)_
- `mcp-census` **server:dev.stackscope/stackscope** — 1.0.1 _(2026-11-01)_
- `mcp-census` **server:dev.workers.jeffmarcilliat.proofrun-closed/proofrun** — 0.1.0 _(2026-11-01)_
- `mcp-census` **server:io.ahel/ahel** — 2.0.0 _(2026-11-01)_
- `mcp-census` **server:io.github.402signal/402signal** — 0.3.0 _(2026-11-01)_
- `mcp-census` **server:io.github.402signalhq/402signal** — 0.3.2 _(2026-11-01)_
- `mcp-census` **server:io.github.ASEM-BATAWY/vicatoo** — 0.9.0 _(2026-11-01)_
- `mcp-census` **server:io.github.AnthonE/scry** — 1.2.0 _(2026-11-01)_
- …외 1571건 더 (원장 changes.jsonl에 전량 보존)

## 바뀐 것 — 조용한 수정
- `mcp-census` **server:ad.getle/leads** · version: 1.0.0 → 1.0.1 _(2026-11-01)_
- `mcp-census` **server:ai.2kw/mcp-server** · version: 6.3.0 → 8.0.3 _(2026-11-01)_
- `mcp-census` **server:ai.agentlookups/greenlight** · status: active → deprecated _(2026-11-01)_
- `mcp-census` **server:ai.agentplaybooks/agentplaybooks** · description_sha256: 0544d209b8080eb2efc261b39612ce9dc6b24e7dc593cd2f82859a85812e6f4a → 9f8190dbc355f8631a6d920aaf41abecd0dd2554049b91998a3028d84b3050c4 _(2026-11-01)_
- `mcp-census` **server:ai.agentplaybooks/agentplaybooks** · status: deprecated → active _(2026-11-01)_
- `mcp-census` **server:ai.agentplaybooks/agentplaybooks** · version: 1.0.0 → 0.10.0 _(2026-11-01)_
- `mcp-census` **server:ai.aginera/preconstruction** · description_sha256: 28478ff98d6825f0fa4fdf739c93394f5240cda3e7bac4f106d47a1bd5328141 → 1f51e369b68ad46b58215b5e8820ba66a7b53cad91bfbd64927b83267702c9c8 _(2026-11-01)_
- `mcp-census` **server:ai.aginera/preconstruction** · version: 1.1.0 → 1.2.0 _(2026-11-01)_
- `mcp-census` **server:ai.aimentiontracker/mcp** · status: active → deprecated _(2026-11-01)_
- `mcp-census` **server:ai.aivikings/registrar** · repository_url: ∅ → https://github.com/AIvikings/aivikings-mcp _(2026-11-01)_
- `mcp-census` **server:ai.aivikings/registrar** · version: 1.0.2 → 1.0.3 _(2026-11-01)_
- `mcp-census` **server:ai.alphaquantlabs/propertycheck** · description_sha256: 9ee16c2d88e2d51b4c01b6a8d2c843eb233da8747a0ed86086074c97a0537be9 → ca2773ce393fc4588b4974a8a439605b29edc0e5e84900d6a0209d028386c07f _(2026-11-01)_
- `mcp-census` **server:ai.alphaquantlabs/propertycheck** · version: 1.12.1 → 1.15.3 _(2026-11-01)_
- `mcp-census` **server:ai.analyticslegends/sap-analytics** · description_sha256: e6c1184ad95973451fd64b757b8019bf61f343f2f0399f30f6582adccec1dd85 → 1774951093795ca1d2264fa416e12d6b943724066381b1f55278d8165b345d63 _(2026-11-01)_
- `mcp-census` **server:ai.analyticslegends/sap-analytics** · version: 1.0.8 → 1.1.1 _(2026-11-01)_
- `mcp-census` **server:ai.atlaso/mcp** · description_sha256: 15c9c44ae06acefa0867f40ba6878c7bceb382f08e565cc33f3fb7668100e3ec → b995e30c15207d0c9ec4b028e03cb44d161a66d7ada474f3f31b254a4f15ff04 _(2026-11-01)_
- `mcp-census` **server:ai.atlaso/mcp** · version: 1.0.1 → 1.0.2 _(2026-11-01)_
- `mcp-census` **server:ai.attestari/attestari** · version: 0.2.1 → 2.10.0 _(2026-11-01)_
- `mcp-census` **server:ai.audiopod/audiopod** · description_sha256: bf0c83a94103b1238c43aae3253d769f73e563c1af513df7a27e39ed9f3007f2 → 0244de5ec2e1e0c4cd5a04a03675da75365ffb121ccbd729df0b6dbefd3c76db _(2026-11-01)_
- `mcp-census` **server:ai.audiopod/audiopod** · version: 2026.9.19 → 2026.10.14 _(2026-11-01)_
- `mcp-census` **server:ai.audo/audo** · version: 1.0.0 → 1.0.1 _(2026-11-01)_
- `mcp-census` **server:ai.augmentev/paseo** · description_sha256: 8e4c8e071b12c396d232cdac07b035e8080beadc9ee071e4833f8c46ce57127d → d345c9ab231f0d49b636ab92aa4ed21f60d947e55e6c3aebc78995690332850a _(2026-11-01)_
- `mcp-census` **server:ai.augmentev/paseo** · version: 0.1.1 → 0.1.2 _(2026-11-01)_
- `mcp-census` **server:ai.auten/mcp** · version: 0.1.4 → 0.1.5 _(2026-11-01)_
- `mcp-census` **server:ai.auxen/auxen** · description_sha256: c216391cf95f37241437924f84778c65db13757684d8123eb2366c0048cd822c → c5256d5d5334b5680163c389dabd6dcb8b5effe1ae0cd6347cebf2b2a5ff4a6f _(2026-11-01)_
- …외 29755건 더 (원장 changes.jsonl에 전량 보존)

## 소스별 현황
| 소스 | 엔티티 | 체인 | 최신 | 앵커 | 신규 | 소멸 | 수정 |
| --- | ---: | ---: | --- | :---: | ---: | ---: | ---: |
| agent-commerce-census | 96 | 96 | 2026-07-13 | ⚓ | 0 | 0 | 0 |
| ai-jobs-ledger | 2,907 | 10,667 | 2026-11-01 | ⚓ | 992 | 1014 | 264 |
| ai-vendor-ledger | 452 | 1,876 | 2026-10-31 | ⚓ | 48 | 54 | 349 |
| bunyang-capsule | 1,739 | 1,740 | 2026-10-17 | ⚓ | 146 | 0 | 0 |
| commitments-watch | 9 | 117 | 2026-10-26 | ⚓ | 0 | 0 | 30 |
| compute-price-index | 227 | 227 | 2026-07-10 | ⚓ | 0 | 0 | 0 |
| consent-census | 67 | 920 | 2026-11-01 | ⚓ | 0 | 0 | 281 |
| datago-watch | 1 | 1 | 2026-07-11 | ⚓ | 0 | 0 | 0 |
| deal-audit-ledger | 48,888 | 93,373 | 2026-11-01 | ⚓ | 3,729 | 185 | 11235 |
| forecast-graders | 6 | 69 | 2026-10-22 | ⚓ | 0 | 0 | 6 |
| llm-korea-capsule | 44 | 44 | 2026-07-13 | ⚓ | 0 | 0 | 0 |
| mcp-census | 54,627 | 89,508 | 2026-11-01 | ⚓ | 18,210 | 343 | 17615 |

_생성 2026-11-02T00:57:57.205Z · 무결성 검증은 `npm run verify`, 재현은 각 소스 snapshots/ 원본._
