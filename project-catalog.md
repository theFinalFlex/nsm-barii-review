# Project catalog

Review date: 2026-09-06. This is an evidence-based progress edition, not a certification of tool reliability. Repository creation and last-push dates below come from GitHub metadata; a push is not necessarily a code change or release. All software remained unexecuted.


“Barii-published” identifies where the work was published; it does not assert exclusive authorship. Forks, credited integrations, third-party products and unresolved provenance are distinguished below. Status descriptions refer to the cited version and review date.

## NetVuln

**Type:** Barii-published software; legacy scanner.

Combines port scanning with domain, geographic, subdomain, and external vulnerability information. The README calls it NSM Port Scanner / NetVuln v1.8.

**Chronology and latest evidenced status:** Repository created 2024-11-21; latest push recorded 2025-02-06. The dedicated video describes iterations, saved results and external API integration. It also acknowledges unreliable NVD responses (8:01–8:23), Shodan limits (6:12–6:32), and logging shortcomings (9:52–10:23). Its “better than Nmap” title is not supported by a controlled accuracy/performance comparison.

**Connections:** NetVuln-2.0 is the documented successor. Earlier unnamed port-scanner clips belong to this development line.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetVuln), [history](https://github.com/NSM-Barii/NetVuln/commits). Related content: [YouTube DNEvb71kFA4](https://www.youtube.com/watch?v=DNEvb71kFA4), [YouTube EnbQ0B-m_9g](https://www.youtube.com/watch?v=EnbQ0B-m_9g), [YouTube -hPAT72vwHQ](https://www.youtube.com/watch?v=-hPAT72vwHQ).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetAlert-2.0

**Type:** Barii-published software; explicitly retired.

LAN device inventory, whitelist comparison, notifications, logging, and an optional disruptive response.

**Chronology and latest evidenced status:** Repository created 2025-02-06; latest push recorded 2025-07-01. Commit 1ffa8fd (2025-07-01) explicitly ends development and fixes background-thread shutdown. Earlier videos show notification and response experiments, including duplicate actions and an incomplete stop path. “Unauthorized” means absent from the configured list, not a verified intrusion.

**Connections:** Successive NetAlert experiments lead to NetAlert-3.0, later renamed Yoda. NetSniffer describes itself as a related counterpart.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetAlert-2.0), [history](https://github.com/NSM-Barii/NetAlert-2.0/commits). Related content: [YouTube KmQQo4xG-LU](https://www.youtube.com/watch?v=KmQQo4xG-LU), [YouTube wudeiKIpcOI](https://www.youtube.com/watch?v=wudeiKIpcOI), [YouTube ph6newsu3xo](https://www.youtube.com/watch?v=ph6newsu3xo), [YouTube 7EjrsKzI81o](https://www.youtube.com/watch?v=7EjrsKzI81o).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetBruter

**Type:** Barii-published software; acknowledged legacy experiment.

Combines discovery of reachable services with credential-testing experiments.

**Chronology and latest evidenced status:** Repository created 2025-02-07; latest push recorded 2025-03-12. README and the 100-day video acknowledge high false-positive rates. At 10:17–10:20 in the latter he says all the reviewed apparent successes were false positives. The IP-scanner video (6:40–7:01) says updates will be limited because a rewrite is planned. Neither visible login pages nor an HTTP success status establish successful authentication.

**Connections:** A proposed 2.0 rewrite appears in the 150-day video, but no public repository with that exact name is in this inventory. Do not assume Vader is its formal successor.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetBruter), [history](https://github.com/NSM-Barii/NetBruter/commits). Related content: [YouTube KmQQo4xG-LU](https://www.youtube.com/watch?v=KmQQo4xG-LU), [YouTube kg-EOdJet-8](https://www.youtube.com/watch?v=kg-EOdJet-8), [YouTube wudeiKIpcOI](https://www.youtube.com/watch?v=wudeiKIpcOI), [YouTube iOAstEBq8zA](https://www.youtube.com/watch?v=iOAstEBq8zA).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetSniffer

**Type:** Barii-published software; older experiment.

Combines local device discovery, availability tracking, per-device traffic summaries, and port inventories.

**Chronology and latest evidenced status:** Repository created 2025-03-11; latest push recorded 2025-03-11. README warns of high thread/resource use. The 150-day video explicitly says the script began as Camera Scanner, then changed purpose (6:37–6:46), and that a desired GUI is unfinished (7:15–7:21). Claims about seeing all traffic require capture-position and network-topology qualifications.

**Connections:** Related to NetAlert; a confirmed pivot from a camera-scanner idea, rather than evidence of a completed camera compromise product.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetSniffer), [history](https://github.com/NSM-Barii/NetSniffer/commits). Related content: [YouTube wudeiKIpcOI](https://www.youtube.com/watch?v=wudeiKIpcOI), [YouTube KmQQo4xG-LU](https://www.youtube.com/watch?v=KmQQo4xG-LU).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetSpeed

**Type:** Barii-published software; legacy learning project.

Schedules internet speed measurements, stores results, and identifies previously observed favorable times.

**Chronology and latest evidenced status:** Repository created 2025-03-11; latest push recorded 2025-03-11. The title “Speed Up My Internet” overstates the mechanism. The full video explains measurement and filtering of historical results; it does not demonstrate an increase in available bandwidth. README identifies it as early work.

**Connections:** An early example of the same recurring pattern: timed collection, stored results, configurable output. A proposed NetSpeed 2.0 is mentioned in the 60-day video but is not a separate current repository here.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetSpeed), [history](https://github.com/NSM-Barii/NetSpeed/commits). Related content: [YouTube 2eHa2hSzy6M](https://www.youtube.com/watch?v=2eHa2hSzy6M), [YouTube lh7_GZ6W6Jo](https://www.youtube.com/watch?v=lh7_GZ6W6Jo), [YouTube bm49D7GdI1w](https://www.youtube.com/watch?v=bm49D7GdI1w).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetBooter-2.0

**Type:** Barii-published software; sparsely documented experiment.

Packet-generation and network-disruption experiment with a terminal interface and logging.

**Chronology and latest evidenced status:** Repository created 2025-05-09; latest push recorded 2025-05-09. No root README was present. The 200-day video distinguishes a working portion from unfinished options and reports disappointing throughput. A May 9, 2025 commit describes work after an extended stream. No runtime verification was performed.

**Connections:** Successor to the early NetBooter / connection-stressor demonstrations. Those early prototypes are not all represented by separate current repositories.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetBooter-2.0), [history](https://github.com/NSM-Barii/NetBooter-2.0/commits). Related content: [YouTube SPyDKpf3YkQ](https://www.youtube.com/watch?v=SPyDKpf3YkQ), [YouTube lh7_GZ6W6Jo](https://www.youtube.com/watch?v=lh7_GZ6W6Jo), [YouTube ph6newsu3xo](https://www.youtube.com/watch?v=ph6newsu3xo).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetVuln-2.0

**Type:** Barii-published software; documented successor with unfinished features.

Aggregates network/web reconnaissance and external data, with LLM-generated interpretation.

**Chronology and latest evidenced status:** Repository created 2025-05-26; latest push recorded 2025-08-11. At the 200-day demonstration, he explicitly says vulnerability checks were not yet integrated (12:37–12:56), directory results were not yet sent to AI (13:15–13:21), and directory discovery produced false positives (11:23–11:48). Later README features and plans must be versioned separately. AI interpretation is not independent validation of a finding.

**Connections:** Successor to NetVuln according to README, despite the erroneous word “predecessor” in some descriptions. Ten vulnerability-scanner streams and later website/AI stream series are inventoried, not fully reviewed.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetVuln-2.0), [history](https://github.com/NSM-Barii/NetVuln-2.0/commits). Related content: [YouTube ph6newsu3xo](https://www.youtube.com/watch?v=ph6newsu3xo), [YouTube gD5j6zYpKzg](https://www.youtube.com/watch?v=gD5j6zYpKzg), [YouTube SAcSwnRha8I](https://www.youtube.com/watch?v=SAcSwnRha8I).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## NetCracker

**Type:** Barii-published software; evolving wireless toolkit.

Wi-Fi discovery and frame-analysis toolkit with experimental active-testing features.

**Chronology and latest evidenced status:** Repository created 2025-04-16; latest push recorded 2026-05-29. The 200-day clip explicitly retracts a staged claim that it is disconnecting networks (3:57–4:03). The one-year video calls several features incomplete. A January 13, 2026 commit and Short subsequently claim an evil-twin feature. Chocapikk PR #1 was merged March 19, 2026. Later additions do not retroactively make earlier demonstrations complete.

**Connections:** One branch of the move from LAN tools to Wi-Fi; helps contextualize framework and later monitoring builds.

**Sources:** [Repository and README](https://github.com/NSM-Barii/NetCracker), [history](https://github.com/NSM-Barii/NetCracker/commits). Related content: [YouTube ph6newsu3xo](https://www.youtube.com/watch?v=ph6newsu3xo), [YouTube w5rLJsXncmw](https://www.youtube.com/watch?v=w5rLJsXncmw), [YouTube 6h998y0YHyM](https://www.youtube.com/watch?v=6h998y0YHyM), [YouTube OSmh4S1Vv0o](https://www.youtube.com/watch?v=OSmh4S1Vv0o).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Yoda

**Type:** Barii-published software; renamed and substantially redesigned.

Current passive Wi-Fi/BLE monitoring with terminal visualization and anomaly alerts; an archived generation used LAN discovery, a web GUI, and voice control.

**Chronology and latest evidenced status:** Repository created 2025-08-02; latest push recorded 2026-08-08. The archived README explicitly says formerly NetAlert-3.0. Release v3.0.0 (2025-08-16) describes the older LAN generation. July 2026 history documents notification-default and CLI fixes. Selective current source inspection confirms opt-in notification fields and applied CLI overrides, and identifies a Wi-Fi tshark wrapper and Bluetooth code marked as remastered from Bluehound. Recent jamming-detection video acknowledges latency and produces contradictory time announcements. No calibrated detection accuracy is established.

**Connections:** NetAlert → NetAlert-3.0/Yoda; current Yoda also reuses the Bluehound line. Yoda-Jr is a separate fork and should not be conflated with this repository.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Yoda), [history](https://github.com/NSM-Barii/Yoda/commits). Related content: [YouTube w5rLJsXncmw](https://www.youtube.com/watch?v=w5rLJsXncmw), [YouTube 7OyHeHakheE](https://www.youtube.com/watch?v=7OyHeHakheE), [YouTube uNs9aeZixB4](https://www.youtube.com/watch?v=uNs9aeZixB4), [YouTube MndfSrY2Jbk](https://www.youtube.com/watch?v=MndfSrY2Jbk), [YouTube QNtxPcRgi5Y](https://www.youtube.com/watch?v=QNtxPcRgi5Y).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## flock-back

**Type:** Integration using credited community research.

Looks for radio signatures associated with Flock cameras; developed from BLE detection to include Wi-Fi observations.

**Chronology and latest evidenced status:** Repository created 2025-11-28; latest push recorded 2026-07-20. README credits jakeswiz and colonel_panic_hacks. Firmware-change explanations are presented as hypotheses, not vendor-confirmed facts. GPS remains described as unimplemented. Release v3.0 exists although README branding says v2.0. The creator thanks an issue reporter for Wi-Fi observations and says he will investigate; that is not validation of every submitted signature.

**Connections:** Feeds into Dooku. Distinct from flock-down, which alerts on mapped locations rather than sensing radio traffic.

**Sources:** [Repository and README](https://github.com/NSM-Barii/flock-back), [history](https://github.com/NSM-Barii/flock-back/commits). Related content: [YouTube Xp9W37A9DZw](https://www.youtube.com/watch?v=Xp9W37A9DZw), [YouTube PHzBr-plKGA](https://www.youtube.com/watch?v=PHzBr-plKGA), [YouTube w5rLJsXncmw](https://www.youtube.com/watch?v=w5rLJsXncmw).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## framework

**Type:** Barii-published software; under development.

A modular IoT/wireless research toolkit whose documentation lists BLE and Wi-Fi work and prospective UART support.

**Chronology and latest evidenced status:** Repository created 2025-12-16; latest push recorded 2026-05-28. README explicitly marks UART as coming soon and leaves a license placeholder. A video says he began the project in December 2025 to investigate IoT issues and later slowed that work while juggling projects. Its broad title does not establish comprehensive coverage or reliable automated discovery.

**Connections:** Associated with the BLE research repositories and CVE; the May Wi-Fi demonstration links this repository directly.

**Sources:** [Repository and README](https://github.com/NSM-Barii/framework), [history](https://github.com/NSM-Barii/framework/commits). Related content: [YouTube PpAucZ52NSw](https://www.youtube.com/watch?v=PpAucZ52NSw), [YouTube wnDFeErO2nc](https://www.youtube.com/watch?v=wnDFeErO2nc), [YouTube HOf1A88ozNo](https://www.youtube.com/watch?v=HOf1A88ozNo).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## CVE-2025-15474

**Type:** Research disclosure and proof-of-concept repository.

Documents availability loss in an AuntyFey smart combination lock over BLE.

**Chronology and latest evidenced status:** Repository created 2025-12-24; latest push recorded 2025-12-25. Official CVE record credits Jabari Lucien (nsm_barii), names VulnCheck as assigner, and was published January 7, 2026. CVSS v4.0 is 5.3, Medium; the issue is resource exhaustion/denial of service, not a demonstrated unlock bypass. The repository documents a physical advertising trigger and contains an inconsistent secondary CVE number. Assignment validates formal credit, not independent lab reproduction.

**Connections:** Related to framework, the smart-lock Short, and separate BLE experiments. Do not merge all these reports into one CVE.

**Sources:** [Repository and README](https://github.com/NSM-Barii/CVE-2025-15474), [history](https://github.com/NSM-Barii/CVE-2025-15474/commits). Related content: [YouTube bzBYiiq93Eo](https://www.youtube.com/watch?v=bzBYiiq93Eo), [YouTube PpAucZ52NSw](https://www.youtube.com/watch?v=PpAucZ52NSw).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## ble-smartlock-bypass-dos

**Type:** Code-only research experiment.

A separate BLE smart-lock experiment.

**Chronology and latest evidenced status:** Repository created 2025-12-25; latest push recorded 2025-12-25. The repository contains LICENSE and poc.py without a root explanatory README. Its name is not enough to establish affected models, verified bypass, disclosure status, or a second assigned CVE. No attack was executed.

**Connections:** Related research area to CVE-2025-15474, but identity and scope are unresolved.

**Sources:** [Repository and README](https://github.com/NSM-Barii/ble-smartlock-bypass-dos), [history](https://github.com/NSM-Barii/ble-smartlock-bypass-dos/commits).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## ble-smartplug-improper-access-control

**Type:** Code-only research experiment.

BLE smart-plug access-control experiment.

**Chronology and latest evidenced status:** Repository created 2025-12-29; latest push recorded 2025-12-31. Sparse source and requirements were inventoried; no root README, formal advisory, or independent corroboration was established in this pass. Treat the repository name as an author claim requiring clarification.

**Connections:** Part of the late-2025 IoT/BLE research cluster.

**Sources:** [Repository and README](https://github.com/NSM-Barii/ble-smartplug-improper-access-control), [history](https://github.com/NSM-Barii/ble-smartplug-improper-access-control/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## ip-camera-exposed-telnet

**Type:** Documentation-only research write-up.

Describes an exposed Telnet service on an Adorcam camera, firmware 1.00.11.

**Chronology and latest evidenced status:** Repository created 2026-01-20; latest push recorded 2026-01-20. The README explicitly says authentication is required and identifies cleartext communication. This supports a service-exposure concern; it does not establish authentication bypass, remote code execution, or assigned CVE credit. The write-up is limited.

**Connections:** Part of the IoT research cluster; separate from Flock camera detection.

**Sources:** [Repository and README](https://github.com/NSM-Barii/ip-camera-exposed-telnet), [history](https://github.com/NSM-Barii/ip-camera-exposed-telnet/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Bluehound

**Type:** Barii-published software with embedded subprojects.

BLE discovery, manufacturer-data interpretation, RSSI visualization, and heuristic interference monitoring.

**Chronology and latest evidenced status:** Repository created 2026-01-30; latest push recorded 2026-07-26. Current README focuses on Python/BlueZ while embedded C++ subdirectories also exist. A radar display is explicitly described in the long video (2:54–3:22) as a visualization of signal-strength distance, not direction. Demonstrated count drops do not establish reliable jammer classification. Vendored dependencies and build files require separate attribution.

**Connections:** Bluetooth monitoring informs current Yoda; includes M5 experiments.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Bluehound), [history](https://github.com/NSM-Barii/Bluehound/commits). Related content: [YouTube HOf1A88ozNo](https://www.youtube.com/watch?v=HOf1A88ozNo), [YouTube ekBHVfAHydU](https://www.youtube.com/watch?v=ekBHVfAHydU), [YouTube Ozs8drNSG8s](https://www.youtube.com/watch?v=Ozs8drNSG8s), [YouTube WaD0YHizoz4](https://www.youtube.com/watch?v=WaD0YHizoz4).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## wicon

**Type:** Sparsely documented experiment.

Wi-Fi/GUI and server-related experimental source.

**Chronology and latest evidenced status:** Repository created 2026-02-08; latest push recorded 2026-02-21. No root README or license was identified. File names and commit subjects show exploratory work; they do not establish a finished product or its reliability. Do not infer capabilities solely from suggestive filenames.

**Connections:** Adjacent to wireless and embedded experiments; formal relationship to named main projects unresolved.

**Sources:** [Repository and README](https://github.com/NSM-Barii/wicon), [history](https://github.com/NSM-Barii/wicon/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Vader

**Type:** Barii-published software with merged external contributions.

Network-service inventory organized around address blocks and allocation data.

**Chronology and latest evidenced status:** Repository created 2026-02-22; latest push recorded 2026-05-02. README describes memory-conscious processing and Bloom-filter deduplication. Chocapikk PR #1 was merged March 19, 2026; PR #2 remains open. Geographic allocation labels are not precise physical locations. Scale claims remain unbenchmarked in this review.

**Connections:** Explicitly paired with Maul; conceptual data-discovery stage of that pair.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Vader), [history](https://github.com/NSM-Barii/Vader/commits). Related content: [YouTube 5sK11pxU6u0](https://www.youtube.com/watch?v=5sK11pxU6u0).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Maul

**Type:** Barii-published software with collaboration history.

Maps infrastructure relationships using DNS and certificate metadata, with related enumeration functions.

**Chronology and latest evidenced status:** Repository created 2026-03-06; latest push recorded 2026-07-24. README explicitly accepts Vader output. PR #2 merged March 19, 2026 and credits the preceding Chocapikk work; Chocapikk PR #1 itself was not merged. Later history reports memory/concurrency and persistence improvements. PR #3 remains open. Descriptions and proposed fixes are not executed tests.

**Connections:** Explicit companion to Vader.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Maul), [history](https://github.com/NSM-Barii/Maul/commits). Related content: [YouTube BsEma9GjHFA](https://www.youtube.com/watch?v=BsEma9GjHFA).

**License:** MIT. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Yoda-Jr

**Type:** Fork of third-party voice-agent demonstration.

A voice assistant/tool-integration demo built on an upstream Friday/Tony Stark project.

**Chronology and latest evidenced status:** Repository created 2026-04-08; latest push recorded 2026-04-29. GitHub API confirms parent and source are SAGAR-TAMANG/friday-tony-stark-demo. README identifies a stack including FastMCP, LiveKit, and external speech/LLM services. Barii-specific changes have not been separated from upstream code; full authorship cannot be attributed to him.

**Connections:** Separate from Yoda. The voice-control Short is relevant, but its exact repository/version needs confirmation.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Yoda-Jr), [history](https://github.com/NSM-Barii/Yoda-Jr/commits). Related content: [YouTube QNtxPcRgi5Y](https://www.youtube.com/watch?v=QNtxPcRgi5Y).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## flock-down

**Type:** Barii-published Android app; experimental release.

Offline map and proximity alerts for known ALPR camera locations on an Android car head unit.

**Chronology and latest evidenced status:** Repository created 2026-04-30; latest push recorded 2026-06-22. v1.0 was released June 22, 2026. README reports 110,924 ALPR locations, including 83,203 Flock locations, for a May 7 dataset; release wording compresses this into an overbroad Flock count. Cached maps, Google Play Services, and data freshness matter. The June 18 caption explicitly warns that the app is under heavy testing.

**Connections:** Complements Dooku/flock-back but uses existing map data rather than RF detection. Credits upstream OpenStreetMap/Overpass/DeFlock data.

**Sources:** [Repository and README](https://github.com/NSM-Barii/flock-down), [history](https://github.com/NSM-Barii/flock-down/commits). Related content: [YouTube y6M_DLEE-Ug](https://www.youtube.com/watch?v=y6M_DLEE-Ug).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## black_america

**Type:** Creative/informational repository.

A history/knowledge-base project outside the main wireless-security toolset.

**Chronology and latest evidenced status:** Repository created 2026-05-17; latest push recorded 2026-06-15. Included for inventory completeness. The existence of this public creative project does not support inferences about private characteristics. Detailed content review remains pending.

**Connections:** No demonstrated code-level relationship to the security tools.

**Sources:** [Repository and README](https://github.com/NSM-Barii/black_america), [history](https://github.com/NSM-Barii/black_america/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Dooku

**Type:** Barii-published hardware/software integration.

A portable Raspberry Pi-based radio collection and wardriving rig with a custom dashboard.

**Chronology and latest evidenced status:** Repository created 2026-05-22; latest push recorded 2026-06-21. The former war-rig URL redirects here. Documentation identifies Pi 5, multiple ALFA adapters, GPS, BLE/SDR hardware, portable power, cooling and a case. Materials README totals $516.58, a historical self-reported bill rather than a current quote. Kismet performs core capture; custom scripts and dashboard integrate collection and uploads. Documentation disagrees on automatic versus manual scan start, likely reflecting revisions.

**Connections:** Integrates flock-back and Kismet; shown alongside flock-down.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Dooku), [history](https://github.com/NSM-Barii/Dooku/commits). Related content: [YouTube wyTOf20fJB0](https://www.youtube.com/watch?v=wyTOf20fJB0), [YouTube y6M_DLEE-Ug](https://www.youtube.com/watch?v=y6M_DLEE-Ug), [YouTube 8QZFc6pEEiE](https://www.youtube.com/watch?v=8QZFc6pEEiE).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## nsm-barii

**Type:** Portfolio website repository.

Presents and links his public work.

**Chronology and latest evidenced status:** Repository created 2026-06-03; latest push recorded 2026-06-23. Useful for identity and project discovery, but some summaries lag repository state: website count 26 versus 28 inventoried repositories; UART and camera-count wording require qualification. Marketing text is not an independent source.

**Connections:** Connects the public website, GitHub, video/social profiles, and Discord invite.

**Sources:** [Repository and README](https://github.com/NSM-Barii/nsm-barii), [history](https://github.com/NSM-Barii/nsm-barii/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## router_tp_link

**Type:** Research assets and scripts.

Router-focused investigation containing images, videos and experimental scripts.

**Chronology and latest evidenced status:** Repository created 2026-06-04; latest push recorded 2026-06-05. No root README was identified. Its presence establishes an investigation, not a verified flaw, finished exploit, assigned CVE, or completed disclosure. Operational files were not executed.

**Connections:** Related to the broader IoT research cluster.

**Sources:** [Repository and README](https://github.com/NSM-Barii/router_tp_link), [history](https://github.com/NSM-Barii/router_tp_link/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Ezra

**Type:** Barii-published software; partially documented development.

Local discovery/fingerprinting using mDNS and SSDP.

**Chronology and latest evidenced status:** Repository created 2026-06-08; latest push recorded 2026-06-10. README distinguishes planned CVE lookup and exports from current discovery. It also claims an mDNS spoofing component whose named file is absent from the inventoried tree, a documentation discrepancy. No inference of successful exploitation is warranted.

**Connections:** Extends the local-network visibility theme into service-discovery metadata.

**Sources:** [Repository and README](https://github.com/NSM-Barii/Ezra), [history](https://github.com/NSM-Barii/Ezra/commits). Related content: [YouTube -zz9vHWfxRk](https://www.youtube.com/watch?v=-zz9vHWfxRk).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## ble_shark

**Type:** Third-party product customization.

Custom portal assets associated with a BLE Shark showcase.

**Chronology and latest evidenced status:** Repository created 2026-07-24; latest push recorded 2026-07-24. The repository has a portal README and four HTML templates rather than the original hardware/firmware. The July 26 video description explicitly thanks BLE Shark for sponsorship and the supplied device and provides a discount code. Credit the vendor for the product and Barii for the published customizations/showcase.

**Connections:** Embedded-device/product content, distinct from original Bluehound/Yoda code.

**Sources:** [Repository and README](https://github.com/NSM-Barii/ble_shark), [history](https://github.com/NSM-Barii/ble_shark/commits). Related content: [YouTube 5t947AOnK5g](https://www.youtube.com/watch?v=5t947AOnK5g).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## c5-wardriver

**Type:** Empty repository.

An empty repository; its name suggests wardriving, but its intended scope is unconfirmed.

**Chronology and latest evidenced status:** Repository created 2026-07-24; latest push recorded 2026-07-24. The repository has no advertised Git references or files. It is not evidence of a completed build. Do not equate it with the newer drone-detection clip without a direct source.

**Connections:** Relationship to Dooku and the unnamed drone project remains unresolved.

**Sources:** [Repository and README](https://github.com/NSM-Barii/c5-wardriver), [history](https://github.com/NSM-Barii/c5-wardriver/commits).

**License:** No root license detected in GitHub metadata. A missing root detection is not a legal conclusion; archived/subdirectory and README license statements may differ.

## Additional projects visible in content but not matched to a current repository

**Early NetAlert, NetBooter/connection stressor, and unnamed scanner prototypes:** documented in the first-week, 30-day, and 60-day videos. These are development stages, not automatically additional independent products. [First week](https://www.youtube.com/watch?v=SPyDKpf3YkQ), [30 days](https://www.youtube.com/watch?v=lh7_GZ6W6Jo).

**Shared IP-information project with Lucas:** the 150-day video (9:52–11:52) describes a private shared repository with location, weather and AbuseIPDB information, including a live debugging interruption. He distinguishes a submitted abuse report from proven maliciousness. Repository identity and current publication status remain unresolved; geographic precision is not validated. [Video](https://www.youtube.com/watch?v=wudeiKIpcOI&t=592s).

**Unnamed drone-detection build:** September 5, 2026 Short says the program is closed source and withholds hardware details. Limited transcript and frame samples do not establish detection range, error rate, protocol classification, or a connection to c5-wardriver. [Short](https://www.youtube.com/shorts/7vSG9y8i2-w).

**Unnamed vision program and IR privacy demonstration:** the August 30 caption describes software under live development and plans for a later facial-recognition discussion. The clip also compares Face ID behavior and near-infrared appearance using third-party glasses tagged @vaydrsunglasses. Instagram lists nsm_sev.7 as a coauthor; contribution roles are not specified. No explicit sponsorship disclosure was observed in this caption. Software identity, repository, protection claims and validation remain unresolved. [Short](https://www.youtube.com/shorts/dAo3I5m98eI), [creator caption](https://www.instagram.com/nsm_barii/reel/DcqkeCDhWU2/).

**Unnamed RF monitoring case:** July 12 caption describes a case being engineered over days/weeks to study radio signals. Its exact relationship to Dooku or the later drone detector is unresolved; shared hardware appearance alone is insufficient to merge projects. [Caption](https://www.instagram.com/nsm_barii/reel/Das31lvtT3Q/).

**Third-party embedded demonstrations:** the Nmap-on-phone Short explicitly starts with a third-party Bus Pirate repository and an M5 device. The “Marauder in progress” Short remains a visual-review gap. Do not list these as original products. [Nmap clip](https://www.youtube.com/shorts/NtaGQZGe0k0), [Marauder clip](https://www.youtube.com/shorts/EHgLC6-bnp8).
