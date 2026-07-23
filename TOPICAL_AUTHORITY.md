# Topical Authority — outdooradvertising.co.id

## Role and boundary

`outdooradvertising.co.id` should become an Indonesian, national-scope knowledge and decision hub for outdoor advertising as a **physical media system**: media choice, site and creative planning, structure, fabrication, foundations, electrical and digital systems, permits, public safety, installation, inspection, maintenance, and measurement. Its strongest defensible role is the junction between advertising practice and the built asset that carries the message.

The domain should not become a directory of city-swapped service pages. Geographic demand may be served by a genuinely local landing page only when there is local proof, a distinct operating area, local regulatory detail, and unique project evidence; geography is excluded from this editorial plan. The site also does not replace a licensed engineer, geotechnical investigation, electrical designer, tax adviser, road authority, building owner, or permit office. Articles explain decisions, evidence, interfaces, and questions to take to those parties.

## Evidence audited

- Git repository `cfpages-admfiresafety/OutdoorAdvertising.co.id`, branch `main`, audited at commit `03ea40dd06906e9cf2c91bda94a21fd0059440fe`.
- 13,207 tracked files, including 7,008 HTML files and a WordPress static export.
- Core product routes for baliho, billboard, branding mobil, huruf timbul, neon box, neon flex, papan nama, running text, totem or pole sign, videotron, and a combined perizinan-pajak page.
- Root homepage and service-page headings, which mostly define products, present choices, state generic advantages, and cross-promote the same product set.
- 5,379 root HTML pages made of exactly 489 geographic variants for each of 11 service families; geography was treated as duplication evidence and omitted from the roadmap.
- 538 author archive pages, 539 category archive pages, and 538 blog archive pages, indicating indexable archive multiplication.
- `sitemap-complete.xml` lists 7,008 URLs. `page-sitemap.xml` contains 15 URLs and `category-sitemap.xml` contains 11. `sitemap_index.xml` points to 27 absent post-sitemap files plus the page and category sitemaps, so sitemap-source parity requires repair.
- Portfolio documentation in the OneDrive MD knowledge base, including the ownership/category ledger and the separate topical-authority role already planned for `advert.id`.

Live deployment, analytics, Search Console queries, backlink profile, conversions, permit outcomes, engineering calculations, fabrication records, inspection records, and campaign measurement datasets were not available in this repository. Claims that depend on them remain evidence-gated.

## Existing coverage and risks

| Finding | Evidence | Risk | Required action |
|---|---|---|---|
| Eleven recognizable media/service families exist | Core routes and H1s cover baliho, billboard, vehicle branding, dimensional letters, neon systems, signs, digital displays, and permits | Useful product taxonomy exists, but each page is shallow and commercially repetitive | Preserve one canonical commercial route per service and link it to neutral educational clusters |
| Geographic templates dominate the export | 489 variants across each of 11 families, totaling 5,379 root pages | Near-duplicate copy, crawl waste, doorway-page signals, and internal cannibalization | Audit indexation and demand; consolidate, redirect, noindex, or remove unsupported variants |
| Archive multiplication is substantial | 538 author, 539 category, and 538 blog archive pages | Thin or duplicate archives consume crawl and create alternate intent owners | Keep only useful curated archives; noindex or remove pagination and empty/repetitive archives |
| Sitemap sources disagree | Complete sitemap has 7,008 URLs while the index names 27 absent post sitemaps | Crawlers receive incomplete or broken discovery signals | Generate sitemaps from the actual canonical build and validate every listed URL |
| Product explanations lack lifecycle depth | Core headings focus on “what it is,” choices, seller advantages, and related products | Site cannot yet answer structural, safety, electrical, inspection, or measurement questions | Build the 14-topic lifecycle map below |
| Videotron heading contains a content error | Videotron page includes “Apa Itu Baliho?” | Weak quality signal and possible template leakage | Correct the heading and inspect every product template for swapped entities |
| Permits and tax are merged into one seller page | `perizinan-pajak/` | Legal, property, structural, road, tax, and content approvals can be falsely flattened | Split educational intents while retaining one commercial service owner |
| Structural and public-safety evidence is absent | No calculations, drawings, geotechnical records, inspection criteria, or licensed review found | Unsafe specificity or unsubstantiated engineering claims | Apply mandatory engineering and public-safety evidence gates |
| Campaign claims are not substantiated | No viewability, traffic, lift, conversion, or attribution dataset found | Invented reach or ROI numbers would damage trust | Use measurement plans, formulas, worked examples marked as examples, and sourced datasets only |
| Canonical/live role is uncertain | Repository is a static export and portfolio ledger flags deployed-source parity | Editing an export may not update the deployed source | Confirm Cloudflare project, production branch, build source, and canonical repository before implementation |

## Coverage matrix

| Decision stage | Media and message | Physical asset | Governance and safety | Operations and evidence |
|---|---|---|---|---|
| Understand | OAD-01 | OAD-07, OAD-08 | OAD-11 | OAD-13 |
| Compare and plan | OAD-02, OAD-03, OAD-04, OAD-05, OAD-06 | OAD-07, OAD-09, OAD-10 | OAD-11 | OAD-14 |
| Specify and procure | OAD-04, OAD-05, OAD-06 | OAD-08, OAD-09, OAD-10 | OAD-11, OAD-12 | OAD-14 |
| Build and commission | OAD-05, OAD-06 | OAD-08, OAD-09, OAD-10 | OAD-12 | OAD-13, OAD-14 |
| Operate and improve | OAD-02, OAD-03, OAD-04 | OAD-07, OAD-10 | OAD-11 | OAD-13 |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| OAD-01 | Outdoor-media systems and terminology | Distinguish media families and choose the next decision path | OOH taxonomy; owned signs versus rented inventory; static versus digital; freestanding versus attached; temporary versus permanent; roadside versus place-based; lifecycle and stakeholder map | Taxonomy table; system diagrams; decision tree; glossary with source notes | Definitions and selection logic only; product engineering belongs to later topics | 6 |
| OAD-02 | Campaign planning and measurement | Translate a communication goal into a measurable outdoor-media plan | Objective; audience and journey; reach and frequency concepts; opportunity to see; exposure versus attention; QR, short URL, call, visit, and lift measurement; attribution limits | Measurement plan; metric dictionary; formula sheet; worked examples clearly labeled hypothetical | Does not promise reach, conversion, or ROI without audited campaign data | 6 |
| OAD-03 | Site survey, visibility, and public context | Evaluate whether a location can deliver legibility without creating hazards | Approach path; viewing angle; distance and dwell time; obstructions; ambient light; traffic context; pedestrian context; mapping; photography; property and utility constraints | Survey checklist; annotated sightline sketches; photo protocol; site-comparison matrix | No universal distance, luminance, setback, or traffic-safety value without local standard and competent review | 6 |
| OAD-04 | Creative, typography, graphics, and display faces | Produce a legible, manufacturable message and durable display face | Information hierarchy; type; contrast; image crop; copy length; day/night behavior; print files; color management; vinyl, banner, rigid face, paint, and protective finishes | Creative checklist; mockup set; preflight sheet; sample-board protocol; before/after examples | Does not prescribe a universal creative formula or material life; campaign and material claims need evidence | 6 |
| OAD-05 | Static signs and mobile display systems | Match a static or vehicle-based format to its use and physical context | Baliho versus billboard; papan nama and dimensional letters; neon box and neon flex; totem or pole sign; vehicle branding; mounting and service access | Comparison matrix; system cutaways; use-case decision tree; maintenance-access sketches | Structural sizes, supports, attachment, and electrical details require topics OAD-07 to OAD-10 | 6 |
| OAD-06 | Digital outdoor displays and controls | Specify the functional questions for videotron and running-text systems | Pixel pitch; viewing geometry; brightness and dimming; content scheduling; controller and network; weather protection; ventilation; redundancy; fail-safe behavior; content operations | Block diagrams; specification checklist; commissioning test plan; content workflow | No vendor performance, luminance limit, ingress rating, or cyber-security guarantee without product and regulatory evidence | 6 |
| OAD-07 | Structural behavior, loads, and design review | Understand how an outdoor structure carries load and what evidence an engineer needs | Load path; dead, wind, seismic, maintenance, and accidental actions; geometry; serviceability; fatigue and vibration; temporary states; existing structures; design documentation | Concept diagrams; load-path worksheet; red-flag checklist; licensed-engineer evidence gate | Educational only; no member size, capacity, wind speed, or structural adequacy claim without site-specific licensed design | 6 |
| OAD-08 | Materials, fabrication, welding, and corrosion control | Define a traceable fabrication and quality-control package | Steel and aluminum selection; material certificates; cutting and forming; weld procedure and welder qualification; bolting; galvanizing and paint; dissimilar metals; dimensional control; nonconformance | Fabrication flow; ITP template; weld map; coating checklist; sample traceability record | No grade, weld acceptance, coating thickness, or service-life prescription without governing specification and verified records | 6 |
| OAD-09 | Connections, anchors, foundations, and supporting substrates | Identify site and interface evidence needed before fixing a sign | Soil investigation; foundation concepts; overturning and uplift; baseplates and anchors; concrete and grout; wall and roof attachments; waterproofing; utility conflicts; proof testing | Interface matrix; foundation decision tree; anchor schedule template; hold-point checklist | No foundation dimension, anchor capacity, substrate adequacy, or test load without geotechnical and structural design | 6 |
| OAD-10 | Electrical power, lighting, data, and weather protection | Plan a maintainable and testable electrical or illuminated system | Load schedule; supply and isolation; protection and earthing; cable routing; enclosures; LED drivers; thermal management; lightning and surge; controls and data; safe access | Single-line concept; load schedule template; commissioning checklist; fault tree | Not a wiring instruction; installation and test values require licensed electrical work, product data, and applicable rules | 6 |
| OAD-11 | Permits, tax, property rights, content, and public safety | Build an approval matrix before committing money or construction | Landowner consent; building and road authority; advertising permit; local tax; zoning and heritage; content restrictions; traffic distraction; neighbor impact; accessibility; emergency contact and records | Stakeholder matrix; permit dossier checklist; question list for authorities; decision log | Requirements vary by place and asset; no universal permit, tax, setback, content, or approval claim | 6 |
| OAD-12 | Logistics, lifting, installation, and work-zone safety | Sequence installation around verified lifting, access, and public-protection controls | Transport envelope; route survey; crane and lifting plan; temporary stability; work at height; exclusion zone; traffic or pedestrian management; weather stop; energization; rescue and handover | Method-statement outline; lift information checklist; hold-point map; public-protection plan | No lift capacity, rigging selection, exclusion distance, or weather limit without competent site-specific plan | 6 |
| OAD-13 | Inspection, maintenance, repair, and end of life | Operate the asset with risk-based inspections and documented interventions | Baseline inspection; corrosion; cracks and welds; bolts and anchors; foundations; electrical and display faults; cleaning; storm or impact response; repair versus replacement; dismantling and waste | Asset register; inspection forms; defect severity matrix; trend log; decommissioning checklist | Inspection intervals and disposition are risk- and jurisdiction-dependent; structural/electrical defects require competent assessment | 6 |
| OAD-14 | Procurement, submittals, QA, commissioning, and handover | Buy and accept a complete, evidence-backed outdoor-media asset | Employer requirements; scope interfaces; drawings and calculations; samples; submittals; ITP and hold points; factory and site acceptance; punch list; as-builts; warranties; lifecycle cost | Responsibility matrix; submittal register; acceptance checklist; handover index; lifecycle-cost worksheet | Does not endorse a vendor or declare compliance; acceptance criteria come from the agreed design and applicable requirements | 6 |

## Related-domain opportunities

| Domain | Distinct role | Safe relationship |
|---|---|---|
| `advert.id` | Advertising strategy, channel, inventory, and campaign-performance education | `outdooradvertising.co.id` owns the physical-asset lifecycle; link to `advert.id` when a reader needs broader advertising strategy |
| `reklame.id` or another verified portfolio domain | If active, may own the Indonesian commercial/legal term “reklame” | Do not mirror this catalog; assign one domain as canonical for each same-intent query and use cross-domain links only where reader value is clear |
| `pabrikasi.id` and fabrication subdomains | Cross-industry fabrication processes and supplier capability | Link for deep generic fabrication knowledge; retain sign-specific interfaces, inspection, and acceptance here |
| `tiang.pabrikasi.id` | Pole fabrication as a specialist structural product | Link for pole-production detail; retain outdoor-media selection, sign loads, public context, and whole-asset lifecycle here |
| Electrical, lighting, or construction portfolio sites | Deep trade-specific education | Use contextual links for discipline depth; never copy their pages or imply that cross-domain overlap is same-domain cannibalization |

Cross-domain overlap is permitted because separate domains can present distinct owner perspectives. The anti-cannibalization rule in this plan applies only within `outdooradvertising.co.id`.

## Consolidation plan

1. Confirm which repository and branch build the live Cloudflare deployment before changing production content.
2. Export the canonical URL inventory from the deployed site, Search Console, analytics, backlinks, leads, and this repository; map redirects before removal.
3. Preserve one canonical commercial page for each proven service family. Educational articles must not compete for “jasa” intent.
4. Cluster the 5,379 geographic pages by service and content fingerprint. Retain a local page only with unique local proof, regulatory information, staff/service capability, and demand; otherwise consolidate to the service owner with permanent redirects or remove/noindex according to evidence.
5. Select one useful author archive and a small number of curated category hubs if they help navigation. Noindex or remove empty, duplicated, paginated, and feed-like archives.
6. Correct entity/template defects, beginning with the videotron page’s “Apa Itu Baliho?” heading.
7. Generate one canonical sitemap set from the deployed build, remove references to absent post sitemaps, and test status, canonical, indexability, and final destination for every URL.
8. Publish new articles only after collision review against retained URLs, redirects, titles, H1s, and Search Console queries.

## Internal-link architecture

- Homepage → the 14 topic hubs, with commercial service routes presented separately from the learning center.
- Every topic hub → its six article briefs, the relevant canonical service page, and adjacent lifecycle hubs.
- OAD-01 routes readers to OAD-02 through OAD-06 for media decisions and OAD-07 through OAD-14 for delivery.
- OAD-02 campaign plan → OAD-03 site survey → OAD-04 creative → selected OAD-05 or OAD-06 system.
- OAD-07 structure → OAD-08 fabrication → OAD-09 foundations/interfaces → OAD-12 installation → OAD-13 inspection.
- OAD-10 electrical links bidirectionally with OAD-05 illuminated signs, OAD-06 digital displays, OAD-12 commissioning, and OAD-13 fault diagnosis.
- OAD-11 approvals links to OAD-03 site constraints, OAD-07 engineering evidence, OAD-12 public protection, and OAD-14 submittals.
- OAD-14 procurement and handover is the convergence hub for the complete evidence chain.
- Article-to-article links should follow the `Related IDs` field and use descriptive anchors tied to the next decision, not repeated exact-match commercial anchors.
- Geographic pages, if any survive evidence review, link to the canonical service owner and relevant technical hubs; they do not spawn city-specific educational copies.

## Evidence and editorial standards

1. Label statements as observed repository fact, sourced fact, calculation, worked example, professional judgment, or hypothesis.
2. Use primary sources first: applicable laws and authority pages, adopted standards where legally accessible, manufacturer datasheets, licensed design records, material certificates, test reports, and campaign platform exports. Record jurisdiction, edition, date, and access date.
3. Never invent wind speeds, member sizes, foundation dimensions, anchor capacities, electrical ratings, brightness, sight distances, permit requirements, tax rates, costs, reach, impressions, conversion rates, or ROI.
4. Structural articles require a visible **engineering evidence gate**: site and geometry, load basis, governing rules, material and connection assumptions, supporting substrate or geotechnical evidence, temporary states, and review by a competent licensed engineer.
5. Materials/fabrication articles require traceable specifications, certificates where applicable, welding/bolting/coating procedures, inspection and test records, and nonconformance disposition.
6. Foundation and anchor articles require site-specific ground/substrate evidence, verified interfaces, concealed-utility review, installation records, and competent design; generic dimensions are prohibited.
7. Electrical/lighting/digital articles require product datasheets, load and protection design, enclosure/environment evidence, installation by competent parties, and recorded commissioning tests.
8. Permit/public-safety articles must identify the exact jurisdiction and authority; distinguish landowner consent, planning/building approval, road control, advertising permit, tax, content, and operating obligations.
9. Installation articles require an approved site-specific method, lifting information, temporary stability, work-at-height and rescue controls, weather criteria, and protection for workers and the public.
10. Inspection articles distinguish observation from diagnosis. Safety-critical defects trigger isolation or escalation according to the competent person’s plan; the article does not declare an asset safe.
11. Measurement articles publish the metric definition, source, date window, denominator, exclusions, attribution rule, uncertainty, and whether the example is hypothetical or observed.
12. Indonesian copy should be plain, concrete, and decision-led. Include diagrams, checklists, tables, photographs, or templates only when they materially help verification.
13. Each brief owns one primary intent and states what it excludes. Review title, slug, H1, outline, and Search Console query overlap before publishing.
14. Show author, reviewer, last technical review date, references, and correction route on safety-, law-, engineering-, and measurement-sensitive pages.

## First bounded publication cluster

Publish 12 P0 articles as a single decision-and-safety spine:

1. OAD-01-A01 — Peta Sistem Media Luar Ruang
2. OAD-01-A02 — Media Milik Sendiri atau Sewa Inventori OOH
3. OAD-02-A01 — Menyusun Tujuan Kampanye OOH yang Bisa Diukur
4. OAD-03-A01 — Checklist Survei Lokasi Media Luar Ruang
5. OAD-03-A02 — Menilai Sightline, Sudut Pandang, dan Halangan
6. OAD-04-A01 — Hierarki Pesan untuk Media Luar Ruang
7. OAD-05-A01 — Baliho dan Billboard: Bedanya di Sistem, Bukan Nama
8. OAD-06-A01 — Cara Membaca Spesifikasi Videotron
9. OAD-07-A01 — Memahami Load Path Struktur Media Luar Ruang
10. OAD-09-A01 — Data yang Wajib Ada Sebelum Merancang Fondasi Signage
11. OAD-11-A01 — Matriks Izin Media Luar Ruang
12. OAD-13-A01 — Baseline Inspection Sebelum Media Dioperasikan

This wave supplies the taxonomy, decision path, site/creative fundamentals, structural and foundation evidence gates, approvals, digital specification literacy, and an operational baseline. Commercial product pages should link into it only after their duplication and canonical status are settled.

## Definition of done

- All 14 topics have one hub and six published, materially distinct briefs: 84 articles total.
- Every retained service, article, hub, archive, and geographic URL has a single canonical intent owner.
- Geographic templates are consolidated; no city/province/region editorial brief exists in this roadmap.
- Broken sitemap references are removed and all submitted URLs resolve to canonical, indexable pages.
- All structural, foundation, fabrication, electrical, digital, permit, public-safety, installation, inspection, and measurement claims pass the evidence gates above.
- Every article has title, slug, primary intent, explicit boundary, evidence format, related links, author/reviewer, sources, and review date.
- The first 12-article cluster is published and internally linked before later waves expand.
- Search Console and analytics are reviewed after indexing; outlines are merged or adjusted when real query overlap reveals same-domain cannibalization.
- Repository-to-production parity is documented, and a clean build plus route/canonical/link checks pass before deployment.
