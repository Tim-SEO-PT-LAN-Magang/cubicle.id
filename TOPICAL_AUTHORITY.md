# Topical Authority — cubicle.id

## Role and boundary

`cubicle.id` is planned as an Indonesian decision and project-support hub for buyers, designers, facility teams, contractors, and operators who must specify, procure, install, accept, clean, maintain, repair, or replace cubicle systems. Repository and live-site evidence audited on 2026-07-23 show an umbrella commercial offer spanning office workstations, toilet partitions, and electrical cubicles, plus custom fabrication and installation.

The domain may cover the same subjects as other owned cubicle, kubikel, phenolic, toilet-partition, office, or electrical properties. Those are separate publishers; cross-domain overlap is allowed. Cannibalization controls in this plan apply only within `cubicle.id`.

Within this domain:

- `/` owns the supplier/installer proposition, project qualification, proof, contact, and quote path.
- Planned knowledge pages own neutral definitions, decisions, calculations, diagnosis, maintenance, and safety education.
- `CUB-03`, `CUB-04`, and `CUB-05` own office, toilet, and electrical-system intents respectively. A page must not use the generic word *cubicle* without identifying which system it means.
- Electrical-cubicle content is educational project support, not authorization for unqualified readers to design, energize, open, test, modify, or service switchgear.
- No city, province, or region swap pages are planned. A local case or climate page is permitted only when it contains site-specific evidence that materially changes the decision.
- Prices, warranties, nationwide coverage, performance, fire, water, hygiene, electrical, acoustic, environmental, and accessibility claims remain unverified until supported by current primary evidence.

Primary geography is Indonesia. The audience includes owner representatives, procurement staff, architects/interior designers, MEP and electrical professionals, facility managers, installers, and informed commercial buyers. Home use is secondary and must never blur professional safety or public-building obligations.

## Evidence audited

Repository: `Tim-SEO-PT-LAN-Magang/cubicle.id`, local canonical candidate `C:\tmp\portfolio-authority\cubicle.id`, branch `main`, clean before this documentation change, with `origin/main` at `4655562`.

Audit completed 2026-07-23:

- 101 tracked files: one exported homepage, two feeds, two WordPress/API documents, one WordPress manifest, theme/plugin assets, and media.
- One substantive public route: `/`. The WordPress API snapshot identifies it as page ID 308, slug `home`.
- Zero article routes, zero separate product/service pages, zero geographic pages, and zero useful category/tag/archive/pagination routes in the repository.
- `/feed` contains no items; `/comments/feed` is infrastructure rather than editorial coverage.
- `/wp-json/` and `/wp-json/wp/v2/pages/308` are exported WordPress data surfaces, not reader-facing coverage.
- No sitemap file exists in the repository. Live checks of `/sitemap.xml` and `/wp-sitemap.xml` returned HTTP 200 HTML copies of the homepage rather than XML sitemaps. Live `/robots.txt` also returned the homepage fallback.
- Sample checks of four planned slugs also returned the homepage title/body with HTTP 200. Proposed slugs therefore have no substantive content collision, but deployment routing currently creates soft-200 fallback URLs that must be fixed before publication.
- Homepage navigation is five same-page anchors: Beranda, Produk, Tentang Kami, Material, and Testimonial.
- Homepage product cards name office cubicles, toilet cubicles, and electrical cubicles.
- Homepage material cards name glass, wood/multiplex, phenolic, and PVC.
- Homepage commercial claims include product quality, affordable price, professional labor, broad reach, “100% guarantee,” and service throughout Indonesia.
- Product links point to `officecubicle.test`, `toilet.cubicle.id`, and `electriccubicle.test`; the two `.test` links are non-production placeholders.
- The quote form posts to an exported WordPress API path and needs an end-to-end delivery test.
- Footer email uses `contact@cubicle.co.id`, creating a domain-identity ambiguity that needs intentional confirmation.
- Testimonials use generic English names and no project evidence; authenticity, consent, and attribution need manual verification before continued use.

Evidence counts treat the homepage as one commercial URL, not as complete editorial coverage. Assets, API surfaces, feeds, and anchors do not count as articles.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Only substantive page; mixes umbrella definition, three product systems, materials, proof, FAQ, and quote intent | expand | `/` remains commercial umbrella; planned hubs own educational depth | Confirm current offer, responsible business entity, service scope, contact ownership, and conversion tracking |
| `/#service` and product cards | Three product families are presented only as short cards | expand | `CUB-03`, `CUB-04`, and `CUB-05` hubs; `/` retains concise routing cards | Confirm whether all three offers are currently sold and installed |
| `http://officecubicle.test/` | Non-production placeholder link | remove | Planned `office-cubicle` hub or a verified production destination | Confirm intended owner route before changing the live site |
| `https://toilet.cubicle.id/` | Separate subdomain linked from the toilet card | manual review | Keep only if live, owned, useful, and intentionally cross-linked; `CUB-04` still owns this domain’s knowledge intent | Audit subdomain availability, canonical purpose, and reciprocal/link-label clarity |
| `http://electriccubicle.test/` | Non-production placeholder link on a safety-critical product | remove | Planned `cubicle-listrik` hub or verified specialist destination | Confirm actual electrical competence, products, certifications, and responsible reviewer |
| `/#material` | Four materials described with broad, unsupported durability/suitability claims | expand | `CUB-06` owns neutral material selection; `/` keeps short verified options | Obtain technical data sheets, finish systems, substrate details, fire/moisture evidence, and warranty conditions |
| `/#testimonial` | Generic names, stock-like presentation, no identifiable project proof | manual review | Verified case-study/proof module under `/` or removal | Confirm identity, consent, project, dates, claims, and image licenses |
| `/#footer` and quote form | Commercial contact path; static WordPress form action may not deliver | keep | `/` | Submit controlled tests, verify receipt/consent/privacy handling, and document response owner |
| `contact@cubicle.co.id` | Contact identity points to another owned domain | manual review | `/` footer/contact | Confirm whether shared identity is intentional and disclose it clearly |
| `/feed`, `/comments/feed` | Empty or infrastructure feeds | noindex | No editorial owner | Verify crawler headers and whether feeds are needed |
| `/wp-json/**`, `/wp-includes/**`, `/wp-content/**` | Exported CMS/API/assets; some URLs may be crawlable | noindex | Static infrastructure | Verify headers, remove unused surfaces only after dependency review |
| `/sitemap.xml`, `/wp-sitemap.xml`, `/robots.txt` | Live SPA/static fallback serves homepage HTML with HTTP 200 | manual review | Real XML sitemap and text robots route | Verify deployment routing, content type, and crawler retrieval after implementation |
| Unknown paths and all proposed article slugs | Live deployment returns the homepage with HTTP 200 instead of a real 404 | manual review | Each published slug gets distinct content/canonical; all other unknown paths return a real 404 | Recheck status, title, canonical, body, and sitemap membership after routing changes |
| `xmlrpc.php?rsd` and oEmbed discovery links | WordPress discovery links point to absent/static endpoints | remove | None | Confirm nothing in the static deployment depends on them |

Principal risks:

1. The word *cubicle* currently conflates interior partitions and electrical switchgear. Every route needs an explicit entity and audience.
2. Electrical work, accessibility, fire behavior, moisture resistance, hygiene, and public-building use can create life-safety consequences. Thin generic advice is prohibited.
3. Product claims are not yet tied to test reports, declarations, approved samples, installation records, or warranty terms.
4. The current site has no functional sitemap/robots route and no article architecture.
5. Placeholder product links, an unverified form, cross-domain contact identity, and unverifiable testimonials weaken trust and lead attribution.

## Coverage matrix

| Completeness lens | Topic owner(s) | Coverage decision |
|---|---|---|
| Definition, vocabulary, history, and measurement | CUB-01 | Distinguish office, toilet, and electrical meanings; maintain a hub glossary rather than synonym pages |
| Types, configurations, anatomy, and interfaces | CUB-01, CUB-03, CUB-04, CUB-05, CUB-07 | Each system owns its variants and parts; shared hardware concepts live in CUB-07 |
| Materials, finishes, properties, and mechanisms | CUB-06, CUB-09 | Selection requires verified substrate/finish, moisture, cleaning, fire, emissions, and compatibility evidence |
| Need recognition and no-action decision | CUB-01, CUB-02, CUB-13 | Readers learn when reconfiguration, repair, or replacement is justified and when observation is enough |
| Survey and diagnosis | CUB-02, CUB-13 | Site/use surveys precede specification; symptoms route to cause isolation rather than instant product choice |
| Requirements and design | CUB-02, CUB-03, CUB-04, CUB-05, CUB-08 | Translate users, traffic, privacy, loads, services, safety, cleaning, and access into a brief |
| Comparison and selection | CUB-03, CUB-04, CUB-05, CUB-06 | Compare only substitutable systems; never treat office, toilet, and electrical cubicles as alternatives |
| Budget, quantity, tender, and procurement | CUB-10 | Cost components, takeoff, bid normalization, samples, contracts, lead times, and supplier evidence |
| Preparation and sequencing | CUB-11 | Substrates, utilities, access, protection, isolation, permits, and coordination before installation |
| Installation and quality control | CUB-11 | Trade-specific methods, hold points, tolerances, records, and stop conditions |
| Commissioning and handover | CUB-11, CUB-15 | Snagging, functional checks, labels, as-builts, training, warranty baseline, and acceptance |
| Normal use and operations | CUB-03, CUB-04, CUB-05, CUB-12 | Occupant, cleaner, facility, and electrical operator paths remain separate |
| Inspection, cleaning, and maintenance | CUB-09, CUB-12 | Cleaning chemistry and moisture controls are evidence-gated; electrical servicing is specialist-only |
| Troubleshooting and repair | CUB-13 | Symptoms, likely causes, safe isolation, repair feasibility, recurrence control, and escalation |
| Upgrade, reuse, replacement, and decommissioning | CUB-13, CUB-14 | Whole-life decisions cover disruption, salvage, waste, documentation, and occupied retrofits |
| Stakeholders and building types | CUB-02, CUB-03, CUB-04, CUB-05, CUB-14 | Owner, designer, procurement, installer, operator, cleaner, and user outcomes are explicit |
| Indonesian climate and supply | CUB-06, CUB-09, CUB-10, CUB-14 | Humidity, wet cleaning, corrosion, transport, replacement availability, and coastal exposure are material; no location swaps |
| Scale, performance, and quality level | CUB-02, CUB-03, CUB-04, CUB-05, CUB-08 | Traffic, duty cycle, user diversity, planned life, and serviceability define quality—not price labels alone |
| New build versus occupied retrofit | CUB-11, CUB-14 | Access, dust/noise, shutdown, temporary facilities, protection, and reinstatement are separate decisions |
| DIY versus professional | CUB-11, CUB-12, CUB-13 | Minor non-hazardous checks may be described; structural anchoring, glazing, fire-critical, accessibility, and electrical work require competence |
| Safety and health | CUB-05, CUB-08, CUB-09 | Electrical hazards, entrapment, sharp edges, glass, pinch points, fire/smoke, chemicals, hygiene, and accessible egress receive gates |
| Failure modes | CUB-13 | Progressive and sudden failures connect symptoms, consequences, diagnosis, prevention, repair, and replacement |
| Standards and regulation | CUB-05, CUB-08, CUB-09, CUB-11 | Cite only current official sources/applicable editions after project-specific review; no invented clauses |
| Environmental impact | CUB-06, CUB-09, CUB-14 | Durability, repairability, emissions, cleaning burden, packaging, salvage, and end-of-life evidence |
| Evidence quality, myths, and unsafe advice | CUB-05, CUB-06, CUB-09, CUB-15 | Primary documents and named reviewers outrank marketing language; unsafe shortcuts are corrected |
| Calculators, diagrams, checklists, and cases | CUB-02, CUB-07, CUB-08, CUB-10, CUB-11, CUB-15 | Tools expose inputs and assumptions; cases require real project records and consent |
| News/trends | N/A | No maintainable news operation is evidenced; material regulatory/product changes belong in maintained evergreen pages |
| Geographic doorway content | N/A | City/province swaps are prohibited; substantiated climate or project evidence is integrated into owner topics |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| CUB-01 | Fundamentals and system taxonomy | Identify the correct cubicle system, vocabulary, components, and appropriate next decision | Cubicle/kubikel/cubical usage; office vs toilet vs electrical entities; partition vs enclosure; anatomy; common units; lifecycle; when not to replace; glossary governance | Entity diagram, annotated photos, terminology table, sourced explanation | Does not select a material (CUB-06), create a project brief (CUB-02), or sell installation (`/`) | 6 |
| CUB-02 | Survey, requirements, and design brief | Convert users, space, risk, operations, and constraints into a reviewable brief | Stakeholders; occupancy/traffic; dimensions; services; substrate; privacy; acoustics; cleaning; moisture; fire; electrical duties; access; aesthetics; budget; schedule; survey records | Survey checklist, requirements matrix, decision tree, measurement sheet, expert review | Does not design each product family (CUB-03/04/05), calculate tender quantities (CUB-10), or prescribe installation (CUB-11) | 6 |
| CUB-03 | Office cubicle and workstation systems | Choose and operate an office partition/workstation system that supports work, change, privacy, and services | Panel types/heights; bench vs individual workstations; layout; ergonomics interfaces; power/data routing; acoustics; visual privacy; daylight; reconfiguration; cleaning; defects | Layout diagrams, comparison table, mock-up checklist, acoustic evidence plan, original project photos | Office systems only; toilet partitions belong to CUB-04, electrical enclosures to CUB-05, generic materials to CUB-06 | 6 |
| CUB-04 | Toilet cubicle systems | Specify toilet partitions for privacy, wet service, traffic, cleaning, accessibility, and maintainability | Layouts; privacy; door swing; hardware; floor-/ceiling-supported arrangements; wet/dry zones; humidity; corrosion; vandal resistance; accessible compartments; child/family use; cleaning; renewal | Annotated layouts, hardware schedule, wet-area decision table, accessibility review, inspection photos | Toilet partitions only; office workstations belong to CUB-03, electrical enclosures to CUB-05, material properties to CUB-06 | 6 |
| CUB-05 | Electrical cubicles and switchgear enclosures | Ask competent questions, verify evidence, and recognize work that requires qualified electrical professionals | Terminology; LV/MV/project classification; enclosure and internal separation concepts; environment/duty; arc/fire/shock risk; ingress; earthing; interlocks; labels; access; testing; operation; maintenance; retrofit; emergency boundaries | Current official standard/manufacturer documents, single-line and enclosure diagrams, licensed electrical expert review, test/certificate checklist | Educational buyer/operator support only; no DIY design, energization, opening, switching, testing, modification, or repair instructions; interior partitions belong to CUB-03/04 | 6 |
| CUB-06 | Materials, substrates, and finishes | Compare materials by verified use conditions and whole-system performance rather than labels | Compact laminate/phenolic; PVC and composites; wood-based boards; glass; metal; cores/skins; coatings; edges; fasteners; moisture; fire/smoke; corrosion; impact; cleaning chemicals; emissions; repairability; sample approval | Technical-data comparison, sample-test protocol, cutaway diagram, manufacturer declaration review, expert review | Owns material selection and properties; system layout remains CUB-03/04/05, fire/accessibility risk decisions CUB-08/09 | 6 |
| CUB-07 | Components, hardware, and interfaces | Specify compatible parts and inspect interfaces that determine function and durability | Hinges; locks/latches; indicators; handles; feet/pilasters; channels; headrails; brackets; seals; edge details; fasteners; anchors; glass fittings; cable interfaces; replaceability; corrosion couples | Exploded diagrams, hardware schedule, compatibility matrix, inspection photos, pull-out/load evidence where applicable | Components and interfaces only; complete system selection belongs to CUB-03/04/05 and site installation to CUB-11 | 6 |
| CUB-08 | Dimensions, ergonomics, accessibility, and inclusive use | Validate dimensions and user journeys without copying generic numbers into the wrong project | Measurement conventions; clearances; reach/operation; door and circulation logic; wheelchair and ambulant use; children/family needs; visual/tactile cues; pinch/entrapment; dignity/privacy; mock-ups; current Indonesian requirements | Dimension diagrams, user-journey review, full-scale mock-up, current official accessibility sources, accessibility specialist review | No universal dimensions are promised; system-specific layout remains CUB-03/04 and project survey CUB-02 | 6 |
| CUB-09 | Moisture, hygiene, cleaning, fire, and occupant health | Select safe evidence and operating controls for wet, cleaned, occupied, or fire-sensitive environments | Water exposure vs “waterproof” claims; edges/joints; mold conditions; corrosion; cleaning agents; disinfection; slip and residue transfer; indoor emissions; dust; fire reaction/smoke claims; combustible contents; evacuation interfaces; PPE/chemical handling | Manufacturer compatibility data, current safety data sheets, hygiene plan, moisture map, fire-document checklist, competent fire review | Does not give electrical hazard procedures (CUB-05), routine schedule ownership (CUB-12), or generic material comparison (CUB-06) | 6 |
| CUB-10 | Budget, quantity, tender, and procurement | Produce a comparable scope, takeoff, bid review, sample approval, and contract evidence pack | Cost structure; units; wastage; preliminaries; logistics; demolition; MEP coordination; alternates; approved equals; bid normalization; exclusions; lead time; spares; warranty; supplier verification; change control | Transparent calculator, bill-of-quantity template, bid matrix, sample/submittal register, contract checklist | Owns commercial comparison and procurement records; product suitability remains CUB-03/04/05/06 and service conversion remains `/` | 6 |
| CUB-11 | Preparation, installation, quality control, and handover | Coordinate a safe installation and accept work through documented hold points | Approved drawings/samples; setting out; substrate survey; deliveries/storage; occupied-area controls; utilities/isolation; anchors; frames/panels/hardware; alignment; protection; cleaning; snagging; tests; as-builts; training; warranties | Method-statement template, inspection/test plan, hold-point checklist, photo records, handover dossier | Does not teach unqualified electrical work (CUB-05), choose materials (CUB-06), or diagnose in-service failures (CUB-13) | 6 |
| CUB-12 | Operation, inspection, cleaning, and preventive maintenance | Establish role-specific routines that preserve safety, hygiene, appearance, and warranty evidence | User behavior; opening/closing; loading; visual checks; fastener/hardware adjustment; cleaning matrix; moisture control; service logs; spares; escalation; shutdown; electrical operator boundaries | Role matrix, cleaning chart, inspection checklist, service log, manufacturer instructions, competent-person review | Planned routines only; symptom-led diagnosis belongs to CUB-13 and hazardous electrical service to qualified personnel under CUB-05 | 6 |
| CUB-13 | Defects, troubleshooting, repair, and replacement | Diagnose symptoms methodically and choose safe repair, partial renewal, or replacement | Misalignment; loose hardware; swelling/delamination; stains/odor/mold; corrosion; cracks/chips; broken glass; privacy gaps; unstable panels; water ingress; repeated faults; electrical warning signs; recurrence controls; salvage | Symptom-cause matrix, stop-condition box, inspection photos, repairability decision tree, specialist review | Does not replace the maintenance schedule (CUB-12), provide live electrical procedures (CUB-05), or sell a repair service (`/`) | 6 |
| CUB-14 | Building context, retrofit, resilience, and end of life | Adapt decisions to occupancy, climate, site constraints, future change, and responsible decommissioning | Office, school, healthcare, hospitality, retail, industrial, public and transport contexts; humid/coastal exposure; occupied retrofit; temporary facilities; future reconfiguration; design life; reuse; recycling; waste; documentation | Context matrix, retrofit phasing diagram, climate exposure checklist, lifecycle assessment evidence, decommissioning plan | Context modifies owner topics but does not create city pages; product/system fundamentals remain CUB-03/04/05 | 6 |
| CUB-15 | Commercial scope, proof, handover, and project evaluation | Qualify a supplier/installer and evaluate delivery using verifiable scope, evidence, and outcomes | Service boundaries; capability; survey-to-quote flow; portfolio proof; references/consent; licenses; insurance; submittals; schedule; quality records; change orders; warranties; complaints; case methodology; post-occupancy review | Supplier questionnaire, evidence register, anonymized real case template, handover checklist, lead-quality measurement plan | Neutral selection criteria live here; current offer, contact, and quote conversion remain on `/`; no fabricated projects or testimonials | 6 |

All 15 parent topics have six distinct catalog briefs. No exception to the minimum is used.

## Related-domain opportunities

Related owned domains may independently publish complete coverage. Links or collaborations are optional and must be useful to readers, transparently labeled, and editorially justified:

- `cubicle.co.id`, `kubikel.co.id`, and `kubikel.id`: terminology, systems, and procurement viewpoints.
- `toiletcubicle.co.id`, `toiletphenolic.co.id`, `toilet.cubicle.id`, and `phenolic.id`: toilet-partition and phenolic specialist depth.
- Appropriate office/interior properties: workspace planning, acoustics, furniture, and fit-out context.
- Appropriate electrical/safety properties: qualified switchgear, fire, electrical-safety, or facility-operations review.
- Material specialists such as glass, wood, aluminium, or flooring properties: verified substrate-specific evidence.

Matching subjects on those domains are not a reason to suppress useful `cubicle.id` pages. Within this site, one owner page still controls each intent.

## Consolidation plan

1. Preserve `/` as the commercial umbrella, but replace broad superlatives and “100% guarantee” with precise, evidenced scope and terms.
2. Route each product card to a real, same-domain hub or a verified specialist destination. Remove `.test` links immediately when implementation begins.
3. Keep the homepage material section as a concise selector linking to `CUB-06`; remove absolute durability/suitability claims that lack system evidence.
4. Verify or remove testimonials. Real case content needs client consent, scope, dates, constraints, evidence, and outcomes.
5. Test the quote form from browser submission through receipt, consent/storage, response ownership, and analytics. Use a working static-compatible endpoint.
6. Confirm the intentional relationship with `cubicle.co.id` before retaining its email identity.
7. Implement real `robots.txt` and XML sitemap responses with correct content types; do not let the homepage fallback mask missing crawler files.
8. Remove unused WordPress discovery/API/feed surfaces only after dependency review; otherwise noindex non-editorial routes and keep them out of the sitemap.
9. Preserve `/` history. No redirect is proposed merely to fit the new taxonomy.

## Internal-link architecture

- `/` links to the three system hubs (`CUB-03`, `CUB-04`, `CUB-05`), the material selector (`CUB-06`), procurement support (`CUB-10`), proof/qualification (`CUB-15`), and a working quote/contact path.
- `CUB-01` is the vocabulary router. It links readers to the correct system and never acts as a second product-sales page.
- `CUB-02` sends requirements to the relevant system hub, accessibility (`CUB-08`), safety/health (`CUB-09`), procurement (`CUB-10`), and installation planning (`CUB-11`).
- Each system hub links to its six children and contextually to materials, components, dimensions/accessibility, risk, procurement, installation, maintenance, and defects.
- Material pages link to the systems in which the material is actually applicable; they do not claim universal suitability.
- Diagnostic pages link to the relevant preventive routine, safe repair/replacement decision, installation root cause, and commercial qualification route.
- Procurement pages link to the applicable system/material evidence and to CUB-15 supplier proof, not indiscriminately to every service page.
- Every article links upward to its topic hub. Related-ID links in the catalog provide lateral and lifecycle paths; no fixed generic link set is copied across all rows.
- No article is orphaned: each belongs to one topic hub, each hub is reachable from `/` or `CUB-01`, and every topic appears in at least one cross-topic path.

## Evidence and editorial standards

These are publication gates, not optional style notes:

1. **Entity gate:** every title, introduction, diagram, and claim must identify office, toilet, or electrical cubicles when ambiguity is possible.
2. **Safety gate:** mark hazards, prerequisites, PPE/area controls where relevant, stop conditions, and tasks requiring competent professionals. Electrical content requires qualified electrical expert review and must not expose live-work or bypass procedures.
3. **Accessibility gate:** verify the current applicable Indonesian legal/technical sources and project/building obligations before publishing dimensions. Include user journeys, operability, dignity, egress interfaces, and mock-up/field verification; do not import foreign numbers as universal rules.
4. **Fire gate:** distinguish material marketing labels from assembly/system evidence. Identify applicable test method, specimen/configuration, report issuer, result scope, penetrations/interfaces, smoke considerations, and competent fire-review need. Never infer whole-system compliance from one component.
5. **Moisture gate:** define exposure (humidity, splash, wet cleaning, leakage, immersion), substrate, edges/joints, penetrations, fasteners, sealants, ventilation, and cleaning chemistry. “Waterproof” requires system-level evidence and stated limits.
6. **Material gate:** identify exact product/substrate/core/finish/thickness/configuration, technical data source, sample approval, compatibility, emissions/chemical evidence where relevant, repairability, and replacement availability. Do not generalize from a material family name.
7. **Installation gate:** require approved drawings/submittals, competent installers, substrate and utility checks, isolation/permit controls, manufacturer instructions, hold points, tolerances from verified sources, inspection records, protection, testing, snagging, and as-builts.
8. **Cleaning gate:** verify manufacturer compatibility and current safety data before naming chemicals or methods. State dilution/contact/rinsing/ventilation/PPE only from primary instructions; test inconspicuously where appropriate; never mix chemicals; define escalation for mold, contamination, damage, or electrical proximity.
9. **Procurement gate:** state assumptions, units, inclusions/exclusions, alternates, taxes/logistics only when current and verified, sample/submittal status, lead times, responsible parties, warranty conditions, spares, and change control. Prices require a date, geography, scope, and source.
10. **Evidence gate:** standards and regulations require current official sources and edition/applicability review; technical claims require primary manufacturer/test data; cases require real records and consent; calculations expose inputs and limitations; reviews identify reviewer role and date.
11. **Commercial-integrity gate:** neutral education must not disguise sales copy. Claims about reach, price, guarantees, credentials, speed, and performance require substantiation and clear conditions.
12. **Maintenance gate:** assign an owner, interval basis, record, acceptance/escalation rule, and warranty relationship. Never invent service intervals.

## First bounded publication cluster

Wave A contains 12 assets:

1. CUB-01-A — definition and taxonomy hub.
2. CUB-02-A — project-brief checklist.
3. CUB-03-A — office-cubicle selection guide.
4. CUB-04-A — toilet-cubicle selection guide.
5. CUB-05-A — electrical-cubicle buyer vocabulary and safety boundary.
6. CUB-06-A — material decision matrix.
7. CUB-07-A — components and hardware anatomy.
8. CUB-08-A — measurement/accessibility workflow.
9. CUB-09-A — moisture claim verification.
10. CUB-10-A — quotation comparison matrix.
11. CUB-11-A — installation hold-point checklist.
12. CUB-15-A — supplier evidence checklist.

The cluster is coherent because it begins with entity selection, translates needs into a brief, provides one safe entry page for each product family, then supplies the cross-system evidence needed to compare a quotation and installation. The homepage routes to the three hubs and the supplier-evidence path; each system hub links back through requirements, materials, risk, procurement, and installation.

Before publication, complete all applicable safety, accessibility, fire, moisture, material, installation, cleaning, procurement, and expert-review gates. Electrical content cannot publish until a qualified electrical reviewer is identified.

Monitor:

- sitemap validity, crawl retrieval, indexation, and canonical selection;
- impressions and clicks separated by office, toilet, electrical, material, procurement, and installation intent;
- navigation from hub to task completion (checklist use, quote-matrix use, form start/completion);
- qualified inquiries by product family, project stage, and evidence completeness;
- form delivery and response time;
- repeated-query and landing-page pairs that indicate same-domain cannibalization;
- assisted conversions, not rankings alone;
- corrections, reviewer sign-off currency, and content aging.

Scale only after the first cluster is indexed, useful, evidence-complete, operationally maintained, and producing interpretable intent or lead signals.

## Definition of done

Planning is complete when:

- all 15 topic IDs have exactly six distinct briefs and the coverage ledger matches;
- every lifecycle stage, major stakeholder, product family, material/risk decision, and applicable completeness lens has an owner;
- every brief has a unique ID, title, slug, primary intent, reader, promise, explicit owner boundary, evidence format, valid related IDs, priority, and bounded wave;
- proposed slugs do not collide with repository/live routes;
- same-domain overlap groups have one intent owner and clear distinction rules;
- no city/province swaps, synonym-only pages, invented standards, prices, tests, reviews, or cases exist;
- every planned page has a route from a hub and at least one meaningful next link;
- the first cluster passes all applicable evidence gates;
- `/sitemap.xml`, `/wp-sitemap.xml`, and `/robots.txt` return intended crawler files rather than the homepage fallback;
- placeholder product links, form delivery, contact identity, claims, and testimonials are resolved;
- the skill validator passes and the repository diff contains only intended authority documents.
