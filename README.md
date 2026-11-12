# Awesome Electric Vehicle with stars

A carefully curated list of specifications, tools, and resources for electric vehicle (EV) charging protocols — a central point of information for developers and enthusiasts working in the e-mobility space.

## Contents

<!-- BEGIN GENERATED TOC -->

* [Specifications](#specifications)
  * [OCPP (Open Charge Point Protocol)](#ocpp-open-charge-point-protocol)
  * [ISO 15118](#iso-15118)
  * [OCPI (Open Charge Point Interface)](#ocpi-open-charge-point-interface)
  * [OICP (Open InterCharge Protocol)](#oicp-open-intercharge-protocol)
  * [eMIP (eMobility Protocol Inter-Operation)](#emip-emobility-protocol-inter-operation)
  * [eMI³ (eMobility ICT Interoperability)](#emi-emobility-ict-interoperability)
  * [NeMo (Hyper-Network for electroMobility)](#nemo-hyper-network-for-electromobility)
  * [Eichrecht](#eichrecht)
  * [OIOI (discontinued)](#oioi-discontinued)
* [Tools and Resources](#tools-and-resources)
  * [OCPP](#ocpp)
  * [OCPI](#ocpi)
  * [iso15118](#iso15118)
  * [Eichrecht](#eichrecht-1)
  * [Other](#other-1)
  * [Uncategorized](#uncategorized)

<!-- END GENERATED TOC -->

[![ev roaming protocols](img/ev-roaming-protocols.jpg)](https://www.emobilitysimplified.com/2020/08/ev-roaming-protocol-differences-OCPI-OICP-OCHP-eMIP.html)

## Specifications

### OCPP (Open Charge Point Protocol)

The **Open Charge Point Protocol (OCPP)** is a communication protocol between electric vehicle charging stations and a central management system.

* [Wikipedia](https://en.wikipedia.org/wiki/Open_Charge_Point_Protocol)
* [Open Charge Aliance](https://www.openchargealliance.org/)
* Specifications
  * [2.1](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-2.1) (2025-01)
  * [2.0.1](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-2.0.1) (2020-04)
  * [2.0 (deprecated)](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-2.0) (2018)
  * [1.6](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-1.6-Documentation_2019_12) (2015)
  * [1.6 - Security Whitepaper Ed3](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/Whitepapers/OCPP-1.6-security-whitepaper-edition-3-2)
  * [1.x - Multiple Connectors per EVSE](https://github.com/juherr/awesome-ev-charging/blob/main/ocpp/Whitepapers/ocpp_1_x_multiple_connectors_per_evse.pdf)
  * [1.5 (deprecated)](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-1.5) (2012)
  * [1.2 (deprecated)](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-1.2) (2010)
* [Configuration Keys (1.6)](https://github.com/juherr/awesome-ev-charging/blob/main/ocpp/OCPP-1.6-configuration-keys.md) - Reference table of OCPP 1.6 configuration keys.

### ISO 15118

**ISO 15118** is an international standard for communication between electric vehicles and the charging station.

* [Wikipedia](https://en.wikipedia.org/wiki/ISO_15118)
* [iso.org](https://www.iso.org/search.html?PROD_isoorg_en%5Bquery%5D=15118\&PROD_isoorg_en%5Bmenu%5D%5Bfacet%5D=standard)

### OCPI (Open Charge Point Interface)

The **Open Charge Point Interface (OCPI)** is a protocol for roaming between charging station networks.

* [Specifications on GitHub](https://github.com/ocpi/ocpi) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07
  * [2.3.0-d2](https://github.com/ocpi/ocpi/releases/download/v2.3.0-ed2/OCPI-2.3.0-ed2.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06)
  * [2.2.1](https://github.com/ocpi/ocpi/releases/download/2.2.1/OCPI-2.2.1.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2021-10)
  * [2.2.0-d2](https://github.com/ocpi/ocpi/releases/download/2.2-d2/OCPI-2.2-d2.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 - Deprecated, use 2.2.1 instead (2020-06)
  * [2.2.0](https://github.com/ocpi/ocpi/releases/download/2.2/OCPI-2.2.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 - Deprecated, use 2.2.0-d2 instead (2019-09)
  * [2.1.1-d2](https://github.com/ocpi/ocpi/releases/download/2.1.1-d2/OCPI_2.1.1-d2.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2019-06)
  * [2.1.1](https://github.com/ocpi/ocpi/releases/download/2.1.1/OCPI_2.1.1.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 - Deprecated, use 2.1.1-d2 instead (2017-06)
  * [2.0](https://github.com/ocpi/ocpi/files/135934/OCPI_2.0-d2.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2016-02)
  * [2.3.0](https://evroaming.org/wp-content/uploads/2025/02/OCPI-2.3.0.pdf) (2025-02)
  * 2.1.0 - Deprecated, contains some bugs, use 2.1.1 instead (2016-04)

* [EVRoaming Fundation](https://evroaming.org/)

* [ocpi.github.io](https://ocpi.github.io/) - OCPI feature-development hub: proposals and processes for upcoming spec versions.

* Official OpenAPI/Swagger definitions and migration guides (rendered from the [openapi-specification](#api-specification) project).
  * [2.3.0 Swagger UI](https://ocpi.github.io/openapi-specification/ocpi/2.3.0/)
  * [2.2.1 → 2.3.0 migration guide](https://ocpi.github.io/openapi-specification/migrations/2.2.1-2.3.0/migration-guide.html)
  * [2.2.1 Swagger UI](https://ocpi.github.io/openapi-specification/ocpi/2.2.1/)

* [ocpi.fyi](https://ocpi.fyi/) - A browsable rendering of the OCPI specification with an API reference and version comparison. 🏅
  * [2.3.0 Swagger](https://ocpi.fyi/api/2.3.0/swagger/) (unofficial)
  * [2.2.1 Swagger](https://ocpi.fyi/api/2.2.1/swagger/) (unofficial)
  * [2.1.1 Swagger](https://ocpi.fyi/api/2.1.1/swagger/) (unofficial)

#### Modules

OCPI 2.3.0 is published as a [core specification](https://github.com/ocpi/ocpi/tree/2.3.0/release/core) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 plus optional modules packaged separately.

Core functional modules:

| Module                 | Specification per version                                           |
| ---------------------- | ------------------------------------------------------------------- |
| Locations              | [2.1.1][ocpi-loc-211], [2.2.1][ocpi-loc-221], [2.3.0][ocpi-loc-230] |
| Sessions               | [2.1.1][ocpi-ses-211], [2.2.1][ocpi-ses-221], [2.3.0][ocpi-ses-230] |
| CDRs                   | [2.1.1][ocpi-cdr-211], [2.2.1][ocpi-cdr-221], [2.3.0][ocpi-cdr-230] |
| Tariffs                | [2.1.1][ocpi-tar-211], [2.2.1][ocpi-tar-221], [2.3.0][ocpi-tar-230] |
| Tokens                 | [2.1.1][ocpi-tok-211], [2.2.1][ocpi-tok-221], [2.3.0][ocpi-tok-230] |
| Commands               | [2.1.1][ocpi-cmd-211], [2.2.1][ocpi-cmd-221], [2.3.0][ocpi-cmd-230] |
| Charging Profiles      | [2.2.1][ocpi-cp-221], [2.3.0][ocpi-cp-230]                          |
| Hub Client Info        | [2.2.1][ocpi-hci-221], [2.3.0][ocpi-hci-230]                        |
| Invoice Reconciliation | [2.3.0 (ed2)][ocpi-ir-230]                                          |

Additional modules (packaged separately). Payments and Bookings are optional, evolve independently of the core, and are published as standalone PDFs bundling a core edition with the module. They are independent from each other and from Invoice Reconciliation — an implementation may support any of them on its own.

* Booking (2.3.0) — exact version labels are still being settled; the OCPI editors deferred on this in [ocpi/ocpi#572](https://github.com/ocpi/ocpi/issues/572) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07
  * [ed1](https://github.com/ocpi/ocpi/releases/download/v2.3.0-bookings/OCPI-2.3.0-bookings.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06, tag `v2.3.0-bookings`)
  * ed2 — not yet released
  * [1.1](https://evroaming.org/wp-content/uploads/2026/01/OCPI-2.3.0-booking-1.1.pdf) (2025-06, no GitHub tag)
* Payments (2.3.0)
  * [ed2](https://github.com/ocpi/ocpi/releases/download/v2.3.0-ed2-payments/OCPI-2.3.0-ed2-payments.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06, core edition 2 + Payments)
  * [ed1](https://github.com/ocpi/ocpi/releases/download/v2.3.0-payments/OCPI-2.3.0-payments.pdf) ⭐ 601 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06, core edition 1 + Payments)

Extensions (vendor / community):

| Extension                          | OCPI version | Source    | Date    |
| ---------------------------------- | ------------ | --------- | ------- |
| [Direct Payment][ext-dp]           | 2.2.1        | EVRoaming | 2024-03 |
| [e-PoI service][ext-epoi]          | 2.2.1        | Gireve    | 2025-10 |
| [Accessibility extension][ext-acc] | 2.3.0, 3.0   | EVRoaming | 2025-12 |
| [Autocharge][ext-ac]               | 2.3.0        | Community | —       |

[ocpi-loc-211]: https://github.com/ocpi/ocpi/blob/release-2.1.1-bugfixes/mod_locations.md

[ocpi-loc-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_locations.asciidoc

[ocpi-loc-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_locations.asciidoc

[ocpi-ses-211]: https://github.com/ocpi/ocpi/blob/release-2.1.1-bugfixes/mod_sessions.md

[ocpi-ses-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_sessions.asciidoc

[ocpi-ses-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_sessions.asciidoc

[ocpi-cdr-211]: https://github.com/ocpi/ocpi/blob/release-2.1.1-bugfixes/mod_cdrs.md

[ocpi-cdr-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_cdrs.asciidoc

[ocpi-cdr-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_cdrs.asciidoc

[ocpi-tar-211]: https://github.com/ocpi/ocpi/blob/release-2.1.1-bugfixes/mod_tariffs.md

[ocpi-tar-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_tariffs.asciidoc

[ocpi-tar-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_tariffs.asciidoc

[ocpi-tok-211]: https://github.com/ocpi/ocpi/blob/release-2.1.1-bugfixes/mod_tokens.md

[ocpi-tok-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_tokens.asciidoc

[ocpi-tok-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_tokens.asciidoc

[ocpi-cmd-211]: https://github.com/ocpi/ocpi/blob/release-2.1.1-bugfixes/mod_commands.md

[ocpi-cmd-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_commands.asciidoc

[ocpi-cmd-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_commands.asciidoc

[ocpi-cp-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_charging_profiles.asciidoc

[ocpi-cp-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_charging_profiles.asciidoc

[ocpi-hci-221]: https://github.com/ocpi/ocpi/blob/release-2.2.1-bugfixes/mod_hub_client_info.asciidoc

[ocpi-hci-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_hub_client_info.asciidoc

[ocpi-ir-230]: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/mod_invoice_reconciliation.asciidoc

[ext-dp]: https://evroaming.org/wp-content/uploads/2024/10/DirectPayment_2_2_1___EVRF_version.pdf

[ext-epoi]: https://www.gireve.com/wp-content/uploads/2025/10/Gireve_Tech_ePoI-OCPI-2.2.1_ImplementationGuide_V1.1-_en.pdf

[ext-acc]: https://evroaming.org/wp-content/uploads/2026/01/e_accessibility_extension-1.0.0.pdf

[ext-ac]: https://ocpi.fyi/ocpi/2.3.0/extensions/mod_autocharge_roaming.html

#### Roaming

Roaming relies on ID Registration Offices (IDRO) that assign and publish the operator (CPO) and provider (eMSP) identifiers exchanged over OCPI.

* [Identification Registration Repository](https://alternative-fuels-observatory.ec.europa.eu/markets-and-policy/policy-insights/identification-registration-repository) - The European reference, maintained by the European Alternative Fuels Observatory.
* [IDRO Directory](https://idro.juherr.dev/) - A global directory aggregating e-mobility identifiers from national and regional IDRO registries.

Roaming platforms (hubs) that interconnect CPOs and eMSPs, by founding year:

* 🇩🇪 [Hubject](https://hubject.com/) (2012)
* 🇫🇷 [Gireve](https://gireve.com/) (2013)
* 🇩🇪 [e-clearing.net](https://www.e-clearing.net/) (2014)
* 🇩🇪 [eNAPI](https://enapi.com/) (2024)
* 🇫🇷 [CO-OP ev](https://www.co-opev.com/) (2026)

### OICP (Open InterCharge Protocol)

The **Open InterCharge Protocol (OICP)** is another protocol for roaming, developed by Hubject.

* [Specifications on GitHub](https://github.com/hubject/oicp) ⭐ 82 | 🐛 23 | 📅 2026-06-17
  * [2.3](https://github.com/hubject/oicp/tree/master/OICP-2.3) ⭐ 82 | 🐛 23 | 📅 2026-06-17 (2020-10)
  * 2.2: [CPO](https://github.com/hubject/oicp/releases/download/v2.2/OICP-CPO-2.2.pdf) ⭐ 82 | 🐛 23 | 📅 2026-06-17, [EMP](https://github.com/hubject/oicp/releases/download/v2.2/OICP-EMP-2.2.pdf) ⭐ 82 | 🐛 23 | 📅 2026-06-17 (2017-10)
  * 2.1: [CPO](https://github.com/hubject/oicp/releases/download/v2.1/OICP-CPO-2.1.pdf) ⭐ 82 | 🐛 23 | 📅 2026-06-17, [EMP](https://github.com/hubject/oicp/releases/download/v2.1/OICP-EMP-2.1.pdf) ⭐ 82 | 🐛 23 | 📅 2026-06-17 (2016-10, retired 2023-04-13)

### eMIP (eMobility Protocol Inter-Operation)

The **eMobility Protocol Inter-Operation (eMIP)** is a roaming protocol developed by Gireve.

* [Protocol description v1.0.17](https://www.gireve.com/wp-content/uploads/2025/02/Gireve_Tech_eMIP-V0.7.4_ProtocolDescription_1.0.17-en.pdf) (2025-02)
* [Implementation guide v1.0.7](https://www.gireve.com/wp-content/uploads/2022/09/Gireve_Tech_eMIP-V0.7.4_ImplementationGuide_1.0.7_en.pdf) (2022-09)

### eMI³ (eMobility ICT Interoperability)

**eMI³ (eMobility ICT Interoperability)** was a European initiative for e-mobility interoperability.

* [Website (archived)](https://web.archive.org/web/20230925033629/http://emi3group.com/)
* [Document index](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/README.md) - Every PDF the website published, with a verified archived copy where one survives.
* [Statement on quality of e-mobility service](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/eMI3-statement-on-QoS-2020-final.pdf) - Using publicly accessible charging infrastructures (2020-06).
* Specifications
  * eMi³ standard version V1.1 electric vehicle ICT interface specifications (2019-10)
    * [Part 1 v1.1](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.1/eMI3-standard-v1.1-Part-1.pdf)
    * [Terms and definitions v1.4](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.1/eMI3-standard-TermsAndDefinitions-v1.4.pdf)
  * eMi³ standard version V1.0 electric vehicle ICT interface specifications (2019-10)
    * [Part 1 v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-v1.0-Part-1.pdf)
    * [Part 2 v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-v1.0-Part-2.pdf)
    * [Terms and definitions v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-TermsAndDefinitions-v1.0.pdf)

### NeMo (Hyper-Network for electroMobility)

**NeMo (Hyper-Network for electroMobility)** was a European Horizon 2020 project (2016–2019) that defined a common information model and an open inter-roaming protocol to connect e-mobility platforms.

* [Website (archived)](https://web.archive.org/web/20230205021136/https://nemo-emobility.eu/)
* [Deliverables (archived)](https://web.archive.org/web/20230205021136/https://nemo-emobility.eu/deliverables/)
* [Document index](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/README.md) - Every PDF the website published, with its original and archived links.
* Specifications
  * [D3.2 Open European Inter-Roaming Protocol](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D3.2-Open-European-InterRoaming-Protocol_Final.pdf) - Draft (2017-12).
  * Common Information Models v1.0 (2017-09)
    * [D3.3 deliverable](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D3.3-Common-Information-Models_Final.pdf)
    * [Standalone edition](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-Common-Information-Models-1.pdf) - Model chapters only, without the deliverable front matter.
  * [D2.3 Standards and protocols](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D2.3-Standards-and-protocols_Final-subject-to-EC-approval.pdf) - Subject to EC approval (2019-10).
* Requirements and methodology
  * [D1.1 Use cases and actors' requirements](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D1.1-Use-Cases-and-Actors_Final.pdf) (2017-06)
  * [D1.3 Interoperability and regulatory requirements](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D1.3-Interoperability-and-Regulation-Requirements_Final.pdf) (2017-10)
  * [D7.1 Global adoption and self-certification methodology for CPOs and EMPs](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D7.1-Global-adoption-and-self-cert-methodology_Final-subject-to-EC-approval.pdf) - Subject to EC approval (2019-02).
* Validation and tooling
  * [D6.3 Hyper-Network validation](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo-D6.3-Hyper-Network-Validation_Final.pdf) (2019-11)
  * [Service Creation Tools manual](https://github.com/juherr/awesome-ev-charging/blob/main/nemo/NeMo_ServiceCreation_Manual_05_2018-1.pdf) (2018-05)

### Eichrecht

**Eichrecht** is a German law for calibration and verification of measuring instruments, which applies to EV charging.

* [Whitepaper](https://openchargealliance.org/wp-content/uploads/2024/03/Presentation_Eichrecht_Plugfest.pdf)
* [Signed Meter Values in OCPP](https://openchargealliance.org/wp-content/uploads/2025/02/signed_meter_values-v10.pdf)

### OIOI (discontinued)

* [Latest specifications](https://juherr.dev/oioi-documentation/)

## Tools and Resources

This list features actively maintained, curated projects. Dormant, archived, or not-yet-reviewed projects are collected separately in [legacy-projects.md](legacy-projects.md). Charging Station Management Systems — source-available and commercial, with their OCA certificates, OCPP versions and API availability — are catalogued in [csms.md](csms.md).

<!-- BEGIN GENERATED PROJECTS -->

### OCPP

#### Server

* [steve-community/steve](https://github.com/steve-community/steve) ⭐ 1,150 | 🐛 96 | 🌐 Java | 📅 2026-11-11 - SteVe is a Java-based charging station management system that administers charge points, users, and RFID authentication through OCPP (OCPP 1.2, 1.5, 1.6 · Java · ⭐ 1148).
* [citrineos/citrineos-core](https://github.com/citrineos/citrineos-core) ⭐ 309 | 🐛 15 | 🌐 TypeScript | 📅 2026-11-12 - CitrineOS is a TypeScript-based modular server runtime and operator interface for managing EV charging infrastructure via OCPP 1.6 and 2.0.1 (OCPP 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 308).
* [dallmann-consulting/OCPP.Core](https://github.com/dallmann-consulting/OCPP.Core) ⭐ 305 | 🐛 11 | 🌐 C# | 📅 2026-10-28 - OCPP.Core is a .NET-based OCPP server with a web interface for managing charge points, connectors, transactions, and charging tokens (OCPP 1.6, 2.0, 2.1 · C# · ⭐ 309).
* [citrineos/citrineos](https://github.com/citrineos/citrineos) ⭐ 159 | 🐛 8 | 📅 2026-09-21 - CitrineOS is an open-source charging station management system implementing OCPP 1.6 and 2.x for communication between charging stations and charge management software (OCPP 1.6, 2.0.1 · ⭐ 158).
* [apostoldevel/ocpp-cs](https://github.com/apostoldevel/ocpp-cs) ⭐ 80 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - A C++20 central system and charge point emulator supporting OCPP 1.5, 1.6, and 2.0.1 (OCPP 1.5, 1.6, 2.0.1 · C++ · ⭐ 80).
* [EVtivity/evtivity-csms](https://github.com/EVtivity/evtivity-csms) ⭐ 35 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-12 - EVtivity is a charging station management system implementing OCPP, OCPI roaming, ISO 15118 Plug and Charge, operator APIs, and web interfaces for operators and drivers (OCPP 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 34).
* [yuncitys/charging-cloud-web](https://github.com/yuncitys/charging-cloud-web) ⭐ 27 | 🐛 0 | 🌐 Vue | 📅 2026-11-07 - Open-source enterprise-level charging station management system (CSMS) supporting OCPP 1.5, 1.6J, and 2.0J protocols for electric vehicles and e-bikes, built with Spring Cloud microservices and Vue.js frontend (OCPP 1.6, 2.0 · Vue · ⭐ 27).
* [srcfl/ftw](https://github.com/srcfl/ftw) ⭐ 24 | 🐛 93 | 🌐 Go | 📅 2026-11-12 - FTW is a local-first home energy management system that coordinates solar generation, batteries, grid power, EV charging, and thermal assets on Raspberry Pi or Linux (OCPP 1.6, 2.0.1 · Go · ⭐ 23).
* [gertjana/ocpp-backend](https://github.com/gertjana/ocpp-backend) ⭐ 23 | 🐛 0 | 🌐 Elixir | 📅 2025-11-11 - An Elixir backend implementing OCPP 1.6 and limited OCPP 2.0 support for connecting to and managing EV chargers (OCPP 1.6, 2.0 · Elixir · ⭐ 23).
* [vampirebyte/rabbitmq-web-ocpp](https://github.com/vampirebyte/rabbitmq-web-ocpp) ⭐ 19 | 🐛 1 | 🌐 Erlang | 📅 2026-08-26 - A RabbitMQ plugin that accepts OCPP 1.6J and 2.x messages over WebSockets and translates them into AMQP messages (Erlang · ⭐ 19).
* [savekar-ev/OCPP-1.6-Charging-Point-Management-System](https://github.com/savekar-ev/OCPP-1.6-Charging-Point-Management-System) ⭐ 17 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-10 - An open-source full-stack Charge Point Management System that manages EV chargers using OCPP 1.6 JSON (OCPP 1.6 · TypeScript · ⭐ 17).
* [joulo-nl/joulo-ocpp-proxy](https://github.com/joulo-nl/joulo-ocpp-proxy) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-10 - Joulo-ocpp-proxy is a Node.js/TypeScript WebSocket proxy that forwards OCPP traffic between EV chargers and a primary CSMS while optionally mirroring charger messages to secondary CSMS backends (OCPP 1.6, 2.0, 2.0.1 · TypeScript · ⭐ 15).
* [gyzod/ocpp2mqtt](https://github.com/gyzod/ocpp2mqtt) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-09-19 - A Python gateway that converts OCPP 1.6 messages to MQTT and MQTT messages to OCPP for integrating EV charging stations with automation systems (OCPP 1.6 · Python · ⭐ 11).
* [OpenChargingCloud/CSMSCLI](https://github.com/OpenChargingCloud/CSMSCLI) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2026-11-12 - A C#/.NET Charging Station Management System that manages charging stations and operates as an OCPI charge point operator (OCPP 1.6, 2.1 · C# · ⭐ 9).
* [davbauer/ocpp-manager](https://github.com/davbauer/ocpp-manager) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-05 - OCPP Manager is an open-source platform for monitoring and managing EV charging stations, RFID authorizations, and charging transactions through a web interface (TypeScript · ⭐ 8).
* [SolarNetwork/solarnetwork-central](https://github.com/SolarNetwork/solarnetwork-central) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2026-11-11 - SolarNet is a cloud platform that manages SolarNetwork accounts and nodes, accepts SolarNode data, and exposes REST APIs for accessing it (Java · ⭐ 7).
* [unified-error-codes/csds](https://github.com/unified-error-codes/csds) ⭐ 7 | 🐛 15 | 🌐 Python | 📅 2026-04-30 - UEC Software Stack provides charging-station diagnostics through unified error codes and telemetry, with a backend, web dashboard, and EVSE agent communicating via OCPP (Python · ⭐ 7).
* [Beep-Technologies/esteban-ocpp](https://github.com/Beep-Technologies/esteban-ocpp) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-05-15 - Esteban-OCPP is a Golang OCPP server providing charge-point, user, transaction, and REST administration functions (OCPP 2.0 · Go · ⭐ 5).
* [parklapp/steve-pluggable](https://github.com/parklapp/steve-pluggable) ⭐ 4 | 🐛 11 | 🌐 Java | 📅 2026-11-02 - SteVe is a Java-based OCPP server for managing electric vehicle charging stations, users, RFID cards, and related operations (OCPP 1.2, 1.5, 1.6 · Java · ⭐ 4).
* [juherr/evolve](https://github.com/juherr/evolve) ⭐ 4 | 🐛 18 | 🌐 Java | 📅 2026-09-07 - EVolve is a Java implementation of an OCPP server for electric vehicle charging systems (Java · ⭐ 4).
* [evlinked/ocpp-rs](https://github.com/evlinked/ocpp-rs) ⭐ 4 | 🐛 11 | 🌐 Rust | 📅 2026-10-27 - A Rust implementation of OCPP 1.6J and partially OCPP 2.0.1 providing a CSMS server, charge point simulator, conformance tests, and observability (OCPP 1.6, 2.0.1 · Rust · ⭐ 4).
* [erik73/app-steve](https://github.com/erik73/app-steve) ⭐ 3 | 🐛 2 | 🌐 Dockerfile | 📅 2026-11-11 - A Home Assistant add-on that runs the SteVe OCPP server to communicate with charge points (Dockerfile · ⭐ 3).
* [eliodecolli/Medinilla](https://github.com/eliodecolli/Medinilla) ⭐ 3 | 🐛 7 | 🌐 C# | 📅 2026-10-22 - Medinilla is an ASP.NET Core backend implementing OCPP functionality for managing electric vehicle charging stations (OCPP 2.0.1 · C# · ⭐ 3).
* [eveys-mobility/OCPP](https://github.com/eveys-mobility/OCPP) ⭐ 3 | 🐛 6 | 🌐 Python | 📅 2026-11-11 - A Python-based OCPP 1.6/2.0.1 gateway that manages EV charger WebSocket connections and exposes REST, gRPC, Kafka, and webhook interfaces (OCPP 1.6, 2.0.1 · Python · ⭐ 3).
* [elton-saraci/ocpp-central-system](https://github.com/elton-saraci/ocpp-central-system) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-09-20 - An open-source Java backend that manages EV charging stations through OCPP 1.6 over WebSockets and provides REST APIs for monitoring and control (OCPP 1.6 · Java · ⭐ 3).
* [mohsinali33226/ocpp-charging-operations-lab](https://github.com/mohsinali33226/ocpp-charging-operations-lab) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-09-09 - An OCPP 1.6 system that simulates charging stations and provides a CSMS for monitoring, remote operations, smart charging, and failure recovery (OCPP 1.6, 2.0.1 · HTML · ⭐ 2).
* [wimhaanstra/virtual-ocpp](https://github.com/wimhaanstra/virtual-ocpp) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-28 - Virtual OCPP is a self-hosted OCPP 1.6J service that connects Smart EVSE chargers to a local CSMS, records charging activity, proxies selected traffic, and provides monitoring dashboards (OCPP 1.6 · TypeScript · ⭐ 2).
* [zeloscloud/zelos-extension-ocpp](https://github.com/zeloscloud/zelos-extension-ocpp) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2026-11-02 - An OCPP server extension for the Zelos App that collects real-time meter data from charge points and monitors fleet health (OCPP 1.6, 2.0.1 · Python · ⭐ 1).
* [LastProject-ESIEE/OCPPConfigurationServer](https://github.com/LastProject-ESIEE/OCPPConfigurationServer) ⭐ 1 | 🐛 12 | 🌐 Java | 📅 2026-11-09 - A Spring Boot web application implementing an OCPP websocket server for configuring and managing charge points (Java · ⭐ 1).
* [alexeimoisseev/ocpp-server-typescript](https://github.com/alexeimoisseev/ocpp-server-typescript) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-12 - A TypeScript WebSocket server that supports core OCPP 1.6J and 2.0.1 charging operations for testing and learning (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 1).
* [amolsurjuse/ocpp-service](https://github.com/amolsurjuse/ocpp-service) ⭐ 1 | 🐛 12 | 🌐 Java | 📅 2026-10-05 - A Spring Boot microservice that manages OCPP WebSocket connections to electric vehicle charging stations and routes charging commands and messages (OCPP 2.0.1 · Java · ⭐ 1).
* [codetics-software/ev-server-lite](https://github.com/codetics-software/ev-server-lite) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-12 - A Spring Boot-based EV charging supervision server implementing OCPP 1.6 and OCPI 2.1.1 with a Next.js dashboard for charging management, sessions, and payment (OCPP 1.6 · Kotlin · ⭐ 1).
* [juherr/steve-ocpp-csms-image](https://github.com/juherr/steve-ocpp-csms-image) ⭐ 1 | 🐛 1 | 🌐 Shell | 📅 2026-11-10 - A community-maintained project that builds ready-to-run Docker images for the SteVe open-source OCPP Central System (Shell · ⭐ 1).

#### Simulator

* [SAP/e-mobility-charging-stations-simulator](https://github.com/SAP/e-mobility-charging-stations-simulator) ⭐ 231 | 🐛 17 | 🌐 TypeScript | 📅 2026-11-12 - A Node.js application that simulates and scales charging stations using the OCPP-J protocol (OCPP 1.6, 2.0, 2.0.1 · TypeScript · ⭐ 232).
* [monta-app/ocpp-emulator](https://github.com/monta-app/ocpp-emulator) ⭐ 182 | 🐛 9 | 🌐 Kotlin | 📅 2026-11-12 - An open-source Kotlin Multiplatform desktop application that emulates OCPP 1.6 and 2.0.1 charge points for testing and local development (OCPP 1.6, 2.0.1 · Kotlin · ⭐ 182).
* [solidstudiosh/ocpp-virtual-charge-point](https://github.com/solidstudiosh/ocpp-virtual-charge-point) ⭐ 122 | 🐛 22 | 🌐 TypeScript | 📅 2026-11-06 - A configurable, terminal-based OCPP charging station simulator written in Node.js with support for OCPP versions 1.2, 1.6, 2.0.1, and 2.1, featuring schema validation and multi-connector configuration (OCPP 1.2, 1.6, 2.0.1 · TypeScript · ⭐ 122).
* [shiv3/ocpp-cp-simulator](https://github.com/shiv3/ocpp-cp-simulator) ⭐ 48 | 🐛 49 | 🌐 TypeScript | 📅 2026-11-12 - An OCPP charge point simulator with browser, CLI, and control APIs for testing AI agents, CI workflows, and CSMS implementations (OCPP 1.2, 1.5, 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 47).
* [OpenChargingCloud/ChargingStationApp](https://github.com/OpenChargingCloud/ChargingStationApp) ⭐ 42 | 🐛 12 | 🌐 TypeScript | 📅 2026-04-03 - An Electron-based virtual charging station that implements OCPP versions 1.6, 2.0.1, and 2.1 for testing and certification (OCPP 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 42).
* [ozgurbayram/OCPPSimulator](https://github.com/ozgurbayram/OCPPSimulator) ⭐ 35 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-12 - A web-based simulator that emulates OCPP charge points to test communication with charge station management systems (OCPP 1.6 · TypeScript · ⭐ 35).
* [virta-ltd/charge-device-simulator](https://github.com/virta-ltd/charge-device-simulator) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - A Python-based collection of EV charging device simulators supporting protocols such as OCPP and Ensto (Python · ⭐ 21).
* [road-labs/chargestation-one](https://github.com/road-labs/chargestation-one) ⭐ 18 | 🐛 1 | 🌐 Less | 📅 2026-11-10 - A browser-based charging station simulator supporting OCPP 1.6 and OCPP 2.0.1, including OCMF meter-data signing (OCPP 1.6, 2.0.1, 2.1 · Less · ⭐ 18).
* [c-jimenez/open-ocpp-simu](https://github.com/c-jimenez/open-ocpp-simu) ⭐ 16 | 🐛 4 | 🌐 C++ | 📅 2026-04-15 - A charge point simulation environment that uses Open OCPP to simulate charge points communicating with an OCPP central system and MQTT to coordinate its components (C++ · ⭐ 16).
* [tzi-app/tzi-OCTT](https://github.com/tzi-app/tzi-OCTT) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-03-05 - A Python pytest test suite implementing OCTT scenarios to verify CSMS implementations against OCPP 2.0.1 and OCPP 1.6J using mock charge points and a minimal CSMS (OCPP 1.6, 2.0.1 · Python · ⭐ 11).
* [kwtycoon/kilowatt-tycoon](https://github.com/kwtycoon/kilowatt-tycoon) ⭐ 7 | 🐛 8 | 🌐 Rust | 📅 2026-07-10 - Kilowatt Tycoon is a Rust/Bevy tycoon game and full-stack EV charging network simulator that models grid operations, charger faults, and OCPP, OCPI, and OpenADR data flows (OCPP 1.6 · Rust · ⭐ 7).
* [PlugSecure-Inc/ocpp-simulator-lab](https://github.com/PlugSecure-Inc/ocpp-simulator-lab) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-17 - An end-to-end testing tool that simulates OCPP charge points and charge point management systems through a web interface (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 6).
* [ZhongRuoyu/ocppsim](https://github.com/ZhongRuoyu/ocppsim) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2026-11-12 - A terminal-based OCPP-J charge point simulator written in Rust that connects to a CSMS over WebSocket for protocol testing and development (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 5).
* [elton-saraci/ocpp-charge-point-simulator](https://github.com/elton-saraci/ocpp-charge-point-simulator) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2026-09-21 - A Java-based OCPP 1.6 charge point simulator that manages multiple charge points through a REST API and web console (OCPP 1.6 · Java · ⭐ 5).
* [vfg27/EmuOCPP](https://github.com/vfg27/EmuOCPP) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2026-03-22 - EmuOCPP is a Mininet/IPMininet-based emulator for testing OCPP 1.6, 2.0, and 2.0.1 communications between charging stations and central management systems (OCPP 1.6, 2.0, 2.0.1 · Python · ⭐ 5).
* [flowionab/charge-point-simulator](https://github.com/flowionab/charge-point-simulator) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - Flowion Charge Point Simulator emulates EV charge points using OCPP for testing and validating charging infrastructure and CSMS software (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 4).
* [ReliON-Charging/everest-dcfc](https://github.com/ReliON-Charging/everest-dcfc) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-02-24 - A multi-architecture container that simulates an EVerest-based DC fast charger with configurable connectors and OCPP versions for testing (OCPP 1.6, 2.0.1, 2.1 · C++ · ⭐ 4).
* [road-labs/ocpp-trace-replayer](https://github.com/road-labs/ocpp-trace-replayer) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-09-11 - A command-line tool that replays Open OCPP Trace files against OCPP backends, with support for multiple OCPP versions and message rewrites (OCPP 1.5, 1.6, 2.0.1, 2.1 · Go · ⭐ 3).
* [wirelane/ocpp-client-simulator](https://github.com/wirelane/ocpp-client-simulator) ⭐ 3 | 🐛 2 | 🌐 JavaScript | 📅 2026-09-17 - A Node.js command-line simulator of an OCPP 1.6 charging station that connects to OCPP servers and supports configurable charging scenarios and signed meter values (OCPP 1.6 · JavaScript · ⭐ 3).
* [hlsxx/ocpp-charge-point-simulator](https://github.com/hlsxx/ocpp-charge-point-simulator) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-11-07 - A Rust CLI that simulates OCPP 1.6 charge points for testing and load-testing OCPP backends (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 2).
* [I-Love-OCPP/Charge-Point-Simulator](https://github.com/I-Love-OCPP/Charge-Point-Simulator) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-03 - A React and TypeScript web application for simulating an electric vehicle charge point (TypeScript · ⭐ 1).

#### Libraries

##### C

* [tux-evse/afb-ocpp-ext](https://github.com/tux-evse/afb-ocpp-ext) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-11-25 - An AFB microservice extension that provides OCPP 1.6 and 2.0.1 client connectivity (OCPP 1.6, 2.0.1 · ⭐ 2).

##### C\#

* [OpenChargingCloud/WWCP\_OCPP](https://github.com/OpenChargingCloud/WWCP_OCPP) ⭐ 70 | 🐛 9 | 🌐 C# | 📅 2026-11-12 - A software library for building OCPP v1.6, v2.0.1, and v2.1 services and gateways connecting OCPP systems with WWCP (OCPP 1.5, 1.6, 2.0.1, 2.1 · ⭐ 71).

##### C++

* [matth-x/MicroOcpp](https://github.com/matth-x/MicroOcpp) ⭐ 547 | 🐛 134 | 🌐 C++ | 📅 2025-12-04 - C/C++ OCPP 1.6 / 2.0.1 client library for microcontroller-based EV charging equipment, supporting Espressif, Arduino, NXP, STM, Linux and other platforms (OCPP 1.6, 2.0.1 · ⭐ 547).
* [c-jimenez/open-ocpp](https://github.com/c-jimenez/open-ocpp) ⭐ 174 | 🐛 10 | 🌐 C++ | 📅 2026-04-13 - Open-source C++ library implementing the WebSocket/JSON versions of OCPP 1.6 and 2.0.1 (OCPP 1.6, 2.0.1 · ⭐ 174).
* [Tinkerforge/tfocpp](https://github.com/Tinkerforge/tfocpp) ⭐ 4 | 🐛 3 | 🌐 C++ | 📅 2026-09-26 - A C++ library implementing OCPP 1.6J Core and Smart Charging profiles for integration into EV charger firmware (OCPP 1.6 · ⭐ 4).

##### Go

* [aliml92/ocpp](https://github.com/aliml92/ocpp) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2026-08-12 - A Go library implementing the JSON-based Open Charge Point Protocol (OCPP) versions 1.6 and 2.0.1 for charge point clients and central systems (OCPP 1.6, 2.0.1 · ⭐ 27).
* [ChargePi/ocpp-manager](https://github.com/ChargePi/ocpp-manager) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2026-04-19 - A Go library for managing and validating OCPP charging-station configuration variables, including versioned and mandatory keys (OCPP 1.6, 2.0.1 · ⭐ 6).
* [shiv3/gocpp](https://github.com/shiv3/gocpp) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-06-18 - Gocpp is a Go library implementing OCPP 1.6, 2.0.1, and 2.1 for typed CSMS and charge-point communication with JSON-schema validation (OCPP 1.6, 2.0.1, 2.1 · ⭐ 5).
* [road-labs/ocppj-go](https://github.com/road-labs/ocppj-go) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2026-11-12 - A Go library implementing OCPP-J communication over WebSockets for client and server applications (OCPP 1.6, 2.0.1 · ⭐ 4).
* [road-labs/ocpp-types-go](https://github.com/road-labs/ocpp-types-go) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-09-04 - A Go library providing strongly typed message definitions and routing helpers for OCPP versions 1.5, 1.6, 2.0.1, and 2.1 (OCPP 1.5, 1.6, 2.0.1, 2.1 · ⭐ 3).
* [aasanchez/ocpp16messages](https://github.com/aasanchez/ocpp16messages) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2026-10-17 - A Go library that defines and validates OCPP 1.6 request and response message types for EV charging systems (OCPP 1.6 · ⭐ 2).

##### Java

* [ChargeTimeEU/Java-OCA-OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP) ⭐ 381 | 🐛 17 | 🌐 Java | 📅 2026-06-19 - Java library implementing OCPP client and server functionality for OCPP 1.6, 2.0.1, and 2.1 using JSON and SOAP transports (OCPP 1.6, 2.0.1, 2.1 · ⭐ 380).

##### JavaScript

* [mikuso/ocpp-rpc](https://github.com/mikuso/ocpp-rpc) ⭐ 134 | 🐛 14 | 🌐 JavaScript | 📅 2026-08-21 - A Node.js client and server library implementing OCPP-J RPC over WebSockets for OCPP 1.6J, 2.0.1J, and 2.1 (OCPP 1.6, 2.0.1, 2.1 · ⭐ 136).
* [argonne-vci/node-red-contrib-ocpp](https://github.com/argonne-vci/node-red-contrib-ocpp) ⭐ 37 | 🐛 27 | 🌐 JavaScript | 📅 2026-06-05 - Node-RED nodes for communicating with EVSE charge points and central systems using OCPP 1.5 and 1.6 over SOAP and JSON (OCPP 1.5, 1.6 · ⭐ 37).
* [ampeco/cpd-ocpp](https://github.com/ampeco/cpd-ocpp) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-22 - A JavaScript library implementing and validating OCPP 1.6 JSON communication between charging stations and central systems (OCPP 2.0 · ⭐ 3).
* [BSVKey/ocmf-kit](https://github.com/BSVKey/ocmf-kit) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-29 - A zero-dependency toolkit that generates and verifies OCMF-signed EV-charging meter readings, tests invalid sessions, and maps them to OCPP signed-meter-value formats (OCPP 2.0.1 · ⭐ 1).

##### Kotlin

* [IZIVIA/ocpp-toolkit](https://github.com/IZIVIA/ocpp-toolkit) ⭐ 46 | 🐛 38 | 🌐 Kotlin | 📅 2026-11-07 - A Kotlin library implementing the OCPP charging protocol for both charging stations and management systems across versions 1.2–2.0.1 (SOAP and JSON/WebSocket) (OCPP 1.2, 1.5, 1.6, 2.0 · ⭐ 46).
* [monta-app/library-ocpp](https://github.com/monta-app/library-ocpp) ⭐ 6 | 🐛 3 | 🌐 Kotlin | 📅 2026-11-12 - A Kotlin library for implementing OCPP 1.6 and OCPP 2.0.1 communication between charge points and servers (OCPP 1.6 · ⭐ 6).
* [I-Love-OCPP/sdk-1.6j](https://github.com/I-Love-OCPP/sdk-1.6j) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-02 - A Kotlin SDK for implementing an OCPP 1.6 JSON Central System (OCPP 1.6 · ⭐ 1).

##### Python

* [mobilityhouse/ocpp](https://github.com/mobilityhouse/ocpp) ⭐ 1,051 | 🐛 15 | 🌐 Python | 📅 2026-11-12 - Python library implementing the Open Charge Point Protocol (OCPP) in JSON format, supporting versions 1.6, 2.0.1, and 2.1 (OCPP 1.6, 2.0.1, 2.1 · ⭐ 1050).

##### Rust

* [tommymalmqvist/rust-ocpp](https://github.com/tommymalmqvist/rust-ocpp) ⭐ 106 | 🐛 10 | 🌐 Rust | 📅 2026-11-03 - A Rust library implementing and validating OCPP versions 1.6, 2.0.1, and work-in-progress 2.1 for EV charging stations (OCPP 1.6, 2.0.1, 2.1 · ⭐ 106).
* [flowionab/ocpp-client](https://github.com/flowionab/ocpp-client) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2026-09-17 - A Rust library implementing the communication layer for OCPP-enabled charge points and CSMS integrations, supporting OCPP 1.6J, 2.0.1, and 2.1 over WebSocket (OCPP 1.6, 2.0.1, 2.1 · ⭐ 8).
* [flowionab/ocpp-charge-point](https://github.com/flowionab/ocpp-charge-point) ⭐ 7 | 🐛 2 | 🌐 Rust | 📅 2026-09-24 - A Rust framework for developing EV charger firmware with OCPP 1.6J and 2.0.1 support (OCPP 1.6, 2.0.1, 2.1 · ⭐ 7).
* [hupe1980/ocpp-kit](https://github.com/hupe1980/ocpp-kit) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2026-11-08 - A Rust library providing typed, layered abstractions for OCPP 1.6J, 2.0.1, and 2.1 over JSON/WebSocket, with protocol framing, a sans-I/O engine, transport layer, and optional higher-level domains for charging stations and CSMS backends (OCPP 1.6, 2.0.1, 2.1 · ⭐ 4).

##### TypeScript

* [voltbras/ts-ocpp](https://github.com/voltbras/ts-ocpp) ⭐ 48 | 🐛 6 | 🌐 TypeScript | 📅 2026-01-20 - A TypeScript library implementing OCPP central system and charge point communication for OCPP-JSON 1.6 and OCPP-SOAP 1.5 (⭐ 48).
* [jacoscaz/typed-ocpp](https://github.com/jacoscaz/typed-ocpp) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-14 - A TypeScript library for type-aware validation of OCPP 1.6, 2.0.1, and 2.1 messages using the Open Charge Alliance’s JSON Schemas (OCPP 1.6, 2.0, 2.1 · ⭐ 11).
* [connected-hil/ocpp-tools](https://github.com/connected-hil/ocpp-tools) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-08 - A TypeScript library providing OCPP 1.6 and 2.0.1 message types, parsers, schemas, and validation utilities (OCPP 1.6, 2.0.1, 2.1 · ⭐ 8).
* [ocpp-debugkit/toolkit](https://github.com/ocpp-debugkit/toolkit) ⭐ 7 | 🐛 12 | 🌐 TypeScript | 📅 2026-10-11 - OCPP DebugKit is an open-source developer toolkit for inspecting, analyzing, replaying, testing, and reporting OCPP charging-session traces locally (⭐ 7).
* [ocpptools/ocpptools](https://github.com/ocpptools/ocpptools) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-11 - Open-source TypeScript monorepo providing OCPP 1.6J and 2.0.1 libraries for frame parsing, validation, schema-driven simulation, and message construction (OCPP 1.6, 2.0.1 · ⭐ 1).

#### Misc

* [evcc-io/evcc](https://github.com/evcc-io/evcc) ⭐ 7,604 | 🐛 207 | 🌐 Go | 📅 2026-11-12 - Evcc is a local EV charge controller and home energy management system that coordinates charging with chargers, meters, solar, batteries, and other energy devices (Go · ⭐ 7539).
* [lbbrhzn/ocpp](https://github.com/lbbrhzn/ocpp) ⭐ 414 | 🐛 47 | 🌐 Python | 📅 2026-11-12 - A Home Assistant integration for controlling and monitoring electric vehicle chargers using OCPP 1.6J, 2.0.1, and experimental 2.1 (Python · ⭐ 413).
* [EVerest/EVerest](https://github.com/EVerest/EVerest) ⭐ 295 | 🐛 258 | 🌐 C++ | 📅 2026-11-12 - EVerest is a modular open-source full-stack framework for building EV charging systems with support for OCPP 1.6/2.0/2.1 and ISO 15118-2/3/20 protocols (OCPP 1.6, 2.0.1, 2.1 · C++ · ⭐ 293).
* [OpenEVSE/openevse\_esp32\_firmware](https://github.com/OpenEVSE/openevse_esp32_firmware) ⭐ 283 | 🐛 62 | 🌐 C | 📅 2026-11-10 - OpenEVSE ESP32 firmware that provides a WiFi gateway, web interface, energy-management features, and integrations for an OpenEVSE charger (OCPP 1.6 · C · ⭐ 283).
* [SmartEVSE/SmartEVSE-3](https://github.com/SmartEVSE/SmartEVSE-3) ⭐ 239 | 🐛 14 | 🌐 C | 📅 2026-08-30 - Open source EVSE (Electric Vehicle Supply Equipment) controller with OCPP 1.6j support, smart charging capabilities, and multi-module power sharing (OCPP 1.6 · C · ⭐ 238).
* [ChargeLab/OpenOCPP](https://github.com/ChargeLab/OpenOCPP) ⭐ 92 | 🐛 2 | 🌐 C++ | 📅 2026-11-06 - Multi-platform OCPP 1.6/2.0.1 embedded firmware for electric vehicle charging stations (OCPP 1.6, 2.0.1 · C++ · ⭐ 91).
* [ChargePi/ChargePi-go](https://github.com/ChargePi/ChargePi-go) ⭐ 55 | 🐛 15 | 🌐 Go | 📅 2026-11-02 - ChargePi is a Linux-based framework for building and managing EV charging stations, with hardware abstraction, OCPP 1.6 support, a management UI, and an API (OCPP 1.6, 2.0.1, 2.1 · Go · ⭐ 54).
* [nader0913/ocpp-rag](https://github.com/nader0913/ocpp-rag) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2026-06-09 - MCP server providing semantic search and retrieval of OCPP 1.6, OCPP 2.0.1, and ISO 15118 Plug & Charge specifications, use cases, and documentation (OCPP 1.6, 2.0.1 · Python · ⭐ 53).
* [alexeimoisseev/ocpp.md](https://github.com/alexeimoisseev/ocpp.md) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2026-07-12 - A structured reference and documentation repository for developing with OCPP 2.1, 2.0.1, and 1.6J (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 31).
* [ocpp-balanz/ocpp-2w-proxy](https://github.com/ocpp-balanz/ocpp-2w-proxy) ⭐ 18 | 🐛 9 | 🌐 Python | 📅 2026-02-22 - An OCPP proxy that forwards charger messages between the charger and primary and secondary central systems (Python · ⭐ 18).
* [appspace/kwwhat](https://github.com/appspace/kwwhat) ⭐ 15 | 🐛 53 | 📅 2026-11-12 - Kwwhat is a dbt-based open-source data pipeline that transforms raw OCPP charging logs into structured analytics models for charger reliability and utilization metrics (OCPP 1.6, 2.0.1, 2.1 · ⭐ 15).
* [vfg27/CheckOCPP](https://github.com/vfg27/CheckOCPP) ⭐ 13 | 🐛 1 | 🌐 Lua | 📅 2026-03-22 - CheckOCPP is a Wireshark dissector that detects OCPP versions, validates message structures, and flags non-compliant unencrypted packets (OCPP 1.6, 2.0, 2.0.1 · Lua · ⭐ 13).
* [chargex-consortium/ev-charge-seq-state](https://github.com/chargex-consortium/ev-charge-seq-state) ⭐ 8 | 🐛 0 | 📅 2026-06-02 - A collection of UML sequence diagrams and finite-state-machine models describing SAE J1772 PWM, ISO 15118 HLC, and OCPP charging workflows (OCPP 1.6, 2.0.1, 2.1 · ⭐ 8).
* [michael-adler/ha-ocpp-relay](https://github.com/michael-adler/ha-ocpp-relay) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-08-05 - Home Assistant integration that relays OCPP communication between EV chargers and remote management servers while exposing OCPP traffic as Home Assistant sensors (Python · ⭐ 7).
* [juherr/open-ocpp-tck](https://github.com/juherr/open-ocpp-tck) ⭐ 6 | 🐛 52 | 🌐 TypeScript | 📅 2026-11-12 - Open-ocpp-tck is an open-source test harness for OCPP 1.6 and 2.0.1 CSMS conformance testing that drives a charge-point simulator and verifies OCPP wire messages (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 6).
* [ChargePi/chargeflow](https://github.com/ChargePi/chargeflow) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-09-18 - ChargeFlow is a CLI tool that validates OCPP 1.6, 2.0.1, and 2.1 JSON messages against schemas and checks OCMF-compatible meter values (OCPP 1.6, 2.0.1, 2.1 · Go · ⭐ 4).
* [ocpp-debugkit/studio](https://github.com/ocpp-debugkit/studio) ⭐ 4 | 🐛 4 | 🌐 Zig | 📅 2026-07-30 - A native Zig desktop application and CLI for capturing, decoding, analyzing, and replaying OCPP 1.6J charging-session traces, including live WebSocket proxying between charge points and CSMS backends (OCPP 1.6 · Zig · ⭐ 4).
* [open-ocpp-trace/specification](https://github.com/open-ocpp-trace/specification) ⭐ 4 | 🐛 11 | 🌐 JavaScript | 📅 2026-07-22 - An implementation-independent JSON/JSONL specification for recording, validating, and exchanging OCPP message traces (JavaScript · ⭐ 4).
* [sepehr-safari/ocpp-handbook](https://github.com/sepehr-safari/ocpp-handbook) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-15 - A vendor-neutral, comprehensive course on EV charging protocols (OCPP, OCPI, ISO 15118), industry context, hardware, and practical debugging techniques for software engineers (OCPP 1.6, 2.0.1 · JavaScript · ⭐ 3).
* [eliodecolli/ocpp-test-cases](https://github.com/eliodecolli/ocpp-test-cases) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-03-20 - A repository of AI-generated test cases for the base implementation of OCPP 2.0.1 (OCPP 2.0.1 · Python · ⭐ 1).
* [OpenChargingTechnology/OCPP-SBOM](https://github.com/OpenChargingTechnology/OCPP-SBOM) ⭐ 1 | 🐛 0 | 📅 2025-12-05 - Formal SBOM (CycloneDX and SPDX) representations of OCPP specification bundles for supply-chain transparency and reproducibility (OCPP 2.1 · ⭐ 1).

### OCPI

#### Server

* [citrineos/citrineos-ocpi](https://github.com/citrineos/citrineos-ocpi) ⭐ 23 | 🐛 9 | 🌐 TypeScript | 📅 2026-11-11 - A set of modules that adds OCPI 2.2.1 CPO functionality to CitrineOS Core (OCPI 2.2.1 · TypeScript · ⭐ 23).
* [olisystems/ocn-node-v2](https://github.com/olisystems/ocn-node-v2) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-11-05 - A Kotlin and Spring Boot service that brokers OCPI traffic between parties and integrates with the Open Charging Network Registry (OCPI 2.2 · Kotlin · ⭐ 1).

#### Simulator

* [savekar-ev/OCPI-2.2.1-EMSP-Simulator](https://github.com/savekar-ev/OCPI-2.2.1-EMSP-Simulator) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2026-05-07 - A Python simulator of an OCPI 2.2.1 EMSP used to validate CPO implementations, credentials exchanges, and schema compliance (OCPI 2.2.1 · Python · ⭐ 10).
* [rally-finance/ocpi-mock-hub](https://github.com/rally-finance/ocpi-mock-hub) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-04-22 - A Go-based mock OCPI 2.2.1 hub server that simulates charging-network interactions for integration development and testing (OCPI 2.2.1 · Go · ⭐ 5).

#### Libraries

##### C\#

* [OpenChargingCloud/WWCP\_OCPI](https://github.com/OpenChargingCloud/WWCP_OCPI) ⭐ 29 | 🐛 1 | 🌐 C# | 📅 2026-11-11 - A software implementation that enables communication between WWCP entities and OCPI-compliant entities across OCPI versions 2.1.1, 2.2.1, 2.3.0, and 3.0 (OCPI 2.0, 2.1, 2.1.1, 2.2, 2.2.1, 2.3.0 · ⭐ 29).
* [BitzArt/OCPI.Net](https://github.com/BitzArt/OCPI.Net) ⭐ 27 | 🐛 6 | 🌐 C# | 📅 2026-08-01 - OCPI.Net is a C#/.NET implementation of the OCPI protocol for EV charging and roaming (⭐ 27).

##### Java

* [steve-community/ocpi-models](https://github.com/steve-community/ocpi-models) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-11-04 - A Java library providing OCPI 2.2.1 data models, Spring MVC API mappings, and REST clients (OCPI 2.2.1 · ⭐ 3).

##### Kotlin

* [IZIVIA/ocpi-toolkit](https://github.com/IZIVIA/ocpi-toolkit) ⭐ 39 | 🐛 15 | 🌐 Kotlin | 📅 2026-10-29 - A Kotlin library that implements OCPI 2.2.1 business logic, validation, data models, and transport interfaces for CPO and eMSP integrations (OCPI 2.2.1 · ⭐ 38).

##### PHP

* [mrbig/ocpi-protocol](https://github.com/mrbig/ocpi-protocol) ⭐ 2 | 🐛 2 | 🌐 PHP | 📅 2026-06-09 - A PHP library for handling OCPI v2.2.1 requests, responses, models, validation, and client/server interfaces (OCPI 2.2.1 · ⭐ 2).

##### Python

* [TECHS-Technological-Solutions/ocpi](https://github.com/TECHS-Technological-Solutions/ocpi) ⭐ 64 | 🐛 12 | 🌐 Python | 📅 2025-12-26 - A Python library that implements the Open Charge Point Interface (OCPI) for communicating with central systems (⭐ 64).
* [elumobility/ocpi-python](https://github.com/elumobility/ocpi-python) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-10-29 - A Python library implementing the OCPI protocol with FastAPI and Pydantic, supporting versions 2.3.0, 2.2.1, and 2.1.1 (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 8).
* [evorada/ocpi-types](https://github.com/evorada/ocpi-types) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - Auto-generated type definitions for the OCPI protocol in Go, Python, Rust, and TypeScript (OCPI 2.3.0 · ⭐ 5).

##### Rust

* [evlinked/ocpi-rs](https://github.com/evlinked/ocpi-rs) ⭐ 4 | 🐛 20 | 🌐 Rust | 📅 2026-10-26 - A Rust implementation of the OCPI protocol providing typed models, an asynchronous client, server handlers, and a validation CLI (OCPI 2.0, 2.1.1, 2.2.1, 2.3.0 · ⭐ 4).
* [hupe1980/ocpi-kit](https://github.com/hupe1980/ocpi-kit) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - A Rust toolkit that implements OCPI versions 2.1.1–2.3.0 with data models, protocol translation, client and server components, roaming-hub support, tariff auditing, and a CLI (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 1).

##### TypeScript

* [ocpi/ocpi-tool](https://github.com/ocpi/ocpi-tool) ⭐ 33 | 🐛 7 | 🌐 TypeScript | 📅 2026-09-17 - A command-line tool that exports filtered charging data from OCPI platforms for use in external data-processing pipelines (OCPI 2.2.1 · ⭐ 33).
* [solidstudiosh/ocpi-schema](https://github.com/solidstudiosh/ocpi-schema) ⭐ 20 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-23 - A Node.js tool that generates JSON Schemas for OCPI 2.1.1 and later (⭐ 20).
* [shiv3/gocpi](https://github.com/shiv3/gocpi) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-30 - Gocpi is a Go library implementing OCPI versions 2.1.1, 2.2.1, and 2.3.0 with typed clients, server handlers, generated models, validation, and pricing utilities for EV-charging roaming (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 2).

##### Other

* [tandemdrive/ocpi-tariffs](https://codeberg.org/tandemdrive/ocpi-tariffs) - A project for calculating tariffs defined by the Open Charge Point Interface (OCPI) (⭐ 40).

#### Misc

* [OpenChargingCloud/OCPIExplorerDesktopApp](https://github.com/OpenChargingCloud/OCPIExplorerDesktopApp) ⭐ 5 | 🐛 13 | 🌐 TypeScript | 📅 2026-04-23 - An Electron desktop application for testing and certifying OCPI implementations and vendor extensions across multiple OCPI versions (OCPI 2.1, 2.1.1, 2.2, 2.2.1, 2.3.0 · TypeScript · ⭐ 5).
* [Quentin-BACQUET/GIREVE\_Tech\_OCPI\_V2.1.1](https://github.com/Quentin-BACQUET/GIREVE_Tech_OCPI_V2.1.1) ⭐ 5 | 🐛 1 | 📅 2026-05-13 - An implementation guide documenting GIREVE’s OCPI 2.1.1 interface, including CPO/eMSP integration rules and Eichrecht signed-data handling (OCPI 2.1.1 · ⭐ 5).
* [Quentin-BACQUET/GIREVE\_Tech\_OCPI\_V2.2.1](https://github.com/Quentin-BACQUET/GIREVE_Tech_OCPI_V2.2.1) ⭐ 2 | 🐛 1 | 📅 2026-05-12 - A GIREVE implementation guide for integrating with the OCPI 2.2.1 interface (OCPI 2.2.1 · ⭐ 2).
* [OpenChargingCloud/OCPIExplorerWebApp](https://github.com/OpenChargingCloud/OCPIExplorerWebApp) ⭐ 2 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-14 - A web application for exploring, testing, and certifying OCPI implementations and vendor extensions across multiple OCPI versions (OCPI 2.1, 2.1.1, 2.2.1, 2.3.0 · TypeScript · ⭐ 2).
* [juherr/ocpi-fyi](https://github.com/juherr/ocpi-fyi) ⭐ 2 | 🐛 9 | 🌐 JavaScript | 📅 2026-10-21 - A versioned documentation site for OCPI specifications and related API reference material (OCPI 2.1.1, 2.2.1, 2.3.0 · JavaScript · ⭐ 2).
* [olisystems/ocn-registry-v2.0](https://github.com/olisystems/ocn-registry-v2.0) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-29 - OCN Registry 2.0 provides Ethereum-based smart contracts and a CLI for registering Open Charging Network nodes, OCPI parties, and service providers (TypeScript · ⭐ 1).

### iso15118

#### Plug\&Charge

* [hubject/opcp](https://github.com/hubject/opcp) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2026-04-02 - Open Plug\&Charge Protocol (OPCP) provides specifications and documentation for exchanging, signing, and managing ISO 15118-related Plug\&Charge certificates and services (JavaScript · ⭐ 73).
* [securityinmobility/dc-charging-station](https://github.com/securityinmobility/dc-charging-station) ⭐ 10 | 🐛 6 | 🌐 Python | 📅 2026-11-08 - Software stack for a bidirectional DC charging station implementing ISO 15118 V2G communication and Plug\&Charge support with hardware abstraction for power delivery control (Python · ⭐ 10).

#### Libraries

##### C++

* [dspace-group/dsV2Gshark](https://github.com/dspace-group/dsV2Gshark) ⭐ 114 | 🐛 2 | 🌐 C++ | 📅 2026-10-28 - A Wireshark plugin that decodes and analyzes ISO 15118, DIN 70121, and related electric vehicle charging communication packets (⭐ 113).

##### Java

* [SwitchEV/RISE-V2G](https://github.com/SwitchEV/RISE-V2G) ⭐ 261 | 🐛 22 | 🌐 Java | 📅 2025-12-19 - RISE V2G is an open-source reference implementation of the ISO 15118 communication interface between electric vehicles and charging stations (⭐ 261).

##### Python

* [ecog-io/iso15118](https://github.com/ecog-io/iso15118) ⭐ 250 | 🐛 69 | 🌐 Python | 📅 2026-11-12 - A Python implementation of the ISO 15118-2 and ISO 15118-20 communication protocols (⭐ 248).
* [uhi22/pyPLC](https://github.com/uhi22/pyPLC) ⭐ 238 | 🐛 8 | 🌐 Python | 📅 2026-11-10 - A Python project for sniffing and implementing CCS powerline communication between electric vehicles and charging equipment (⭐ 238).
* [Sevenstax/FreeV2G](https://github.com/Sevenstax/FreeV2G) ⭐ 71 | 🐛 19 | 🌐 Python | 📅 2026-09-23 - FreeV2G is a Python host application that controls 8devices WHITE-beet modules for ISO 15118 and DIN 70121 communication between electric vehicles and charging equipment (⭐ 71).
* [ecog-io/pyslac](https://github.com/ecog-io/pyslac) ⭐ 56 | 🐛 10 | 🌐 Python | 📅 2026-11-12 - A Python implementation of the SLAC protocol specified in ISO 15118-3 for managing EVSE matching sessions over a network interface (⭐ 56).
* [zeloscloud/zelos-extension-v2g](https://github.com/zeloscloud/zelos-extension-v2g) ⭐ 1 | 🐛 6 | 🌐 Python | 📅 2026-11-02 - A Zelos extension that decodes ISO 15118, DIN 70121, and SocketCAN traffic from captures or live traffic into queryable traces (⭐ 1).

##### Rust

* [hupe1980/iso15118](https://github.com/hupe1980/iso15118) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-11-10 - A pure Rust implementation of the ISO 15118 vehicle-to-grid communication protocol providing EXI codecs, session engines, message handling, SLAC discovery, and Plug & Charge profiles for both charging station and vehicle roles (⭐ 2).

#### Misc

* [uhi22/ccs32clara](https://github.com/uhi22/ccs32clara) ⭐ 117 | 🐛 14 | 🌐 C | 📅 2026-11-05 - Ccs32clara is STM32 software using a QCA7005 modem to control CCS charging communication and related vehicle charging hardware (C · ⭐ 115).
* [SukritJaAIproject/EV\_Charger\_Fault\_Detection\_AI](https://github.com/SukritJaAIproject/EV_Charger_Fault_Detection_AI) - Windows application for AI-based fault detection in DC EV charger sessions from ISO 15118-2 / DIN 70121 packet captures, benchmarked on a 212-station fleet (Python · ⭐ 2).

### Eichrecht

#### Libraries

##### TypeScript

* [road-labs/ocmf-js](https://github.com/road-labs/ocmf-js) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-22 - TypeScript/JavaScript library that implements signing and verification of OCMF (Open Charge Metering Format) signed meter data (⭐ 3).
* [OpenChargingCloud/ChargyCore.TS](https://github.com/OpenChargingCloud/ChargyCore.TS) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-03 - A TypeScript library that validates transparent, cryptographically-signed EV charging meter data according to German Eichrecht calibration law (⭐ 2).

#### Misc

* [SAFE-eV/OCMF-Open-Charge-Metering-Format](https://github.com/SAFE-eV/OCMF-Open-Charge-Metering-Format) ⭐ 33 | 🐛 12 | 📅 2026-10-15 - A markdown repository containing the Open Charge Metering Format (OCMF) specification for development and review (⭐ 33).

### Other

#### Analytics & data

* [openchargemap/ocm-system](https://github.com/openchargemap/ocm-system) ⭐ 152 | 🐛 49 | 🌐 C# | 📅 2026-11-06 - Open Charge Map is an open registry and API for crowdsourced electric vehicle charging-location data, supporting websites, apps, research, and analysis (C# · ⭐ 151).
* [openchargemap/ocm-export](https://github.com/openchargemap/ocm-export) ⭐ 47 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-23 - A tool that exports Open Charge Map point-of-interest data into separate JSON files for each charging location (JavaScript · ⭐ 47).
* [open-ev-data/open-ev-data-dataset](https://github.com/open-ev-data/open-ev-data-dataset) ⭐ 32 | 🐛 3 | 🌐 JavaScript | 📅 2025-12-30 - OpenEV Data is a versioned, community-maintained dataset of electric vehicle specifications compiled from layered JSON fragments into canonical records (JavaScript · ⭐ 32).
* [vbalagovic/cars-dataset](https://github.com/vbalagovic/cars-dataset) ⭐ 29 | 🐛 0 | 📅 2026-07-08 - A dataset and API providing specifications for cars, trucks, motorcycles, and market price listings (⭐ 28).
* [robeertm/ev-charge-tracker](https://github.com/robeertm/ev-charge-tracker) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-11-11 - Self-hosted web dashboard for tracking electric vehicle charges, costs, CO2 emissions, and battery health across multiple vehicle manufacturer APIs (Python · ⭐ 13).
* [gaia-charge/evdb](https://github.com/gaia-charge/evdb) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2026-08-14 - An open database of electric vehicles containing specifications, market availability, and related data with query and visualization tools (Python · ⭐ 11).
* [MTES-MCT/qualicharge](https://github.com/MTES-MCT/qualicharge) ⭐ 10 | 🐛 37 | 🌐 Python | 📅 2026-11-10 - QualiCharge provides an API, dashboard, and analysis tools for evaluating electric vehicle charging service quality from supervision data (Python · ⭐ 10).
* [Jungle-Bus/ref-EU-EVSE](https://github.com/Jungle-Bus/ref-EU-EVSE) ⭐ 4 | 🐛 10 | 🌐 Python | 📅 2026-11-05 - A data-processing project that consolidates and validates French open data on EV charging stations for integration into OpenStreetMap (Python · ⭐ 4).
* [juherr/open-idro-directory](https://github.com/juherr/open-idro-directory) ⭐ 3 | 🐛 38 | 🌐 TypeScript | 📅 2026-11-09 - Open directory that aggregates, validates, and publishes e-mobility identifiers from official national and regional registries with provenance and API access (TypeScript · ⭐ 3).
* [chaser-d/Green\_Smart\_Grid\_Simulator](https://github.com/chaser-d/Green_Smart_Grid_Simulator) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2026-08-06 - A DuckDB and dbt pipeline that ingests, validates, transforms, and aggregates telemetry from solar, wind, and hydroelectric assets into financial reporting marts (HTML · ⭐ 3).
* [rajvvv/EV-Infra-Planner](https://github.com/rajvvv/EV-Infra-Planner) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-30 - A geospatial dashboard forecasts EV adoption and identifies charger deployment gaps across major Indian cities (JavaScript · ⭐ 3).
* [scroodge/VoltFlow](https://github.com/scroodge/VoltFlow) ⭐ 3 | 🐛 40 | 🌐 TypeScript | 📅 2026-11-05 - VoltFlow is a mobile-first PWA for tracking EV charging sessions, vehicle telemetry, trips, maintenance records, and related analytics (TypeScript · ⭐ 3).
* [GuillaumeBraillon/EV-Charge-Tracker](https://github.com/GuillaumeBraillon/EV-Charge-Tracker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-29 - A personal web PWA that records, analyzes, and estimates EV charging costs using real charging data, tariffs, subscriptions, and Home Assistant/N8N imports (TypeScript · ⭐ 1).
* [roy429-hub/buima-tracker](https://github.com/roy429-hub/buima-tracker) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-01 - Buima Tracker is a web dashboard that parses EV-charging site reports and displays installation data, revenue, profit, KPIs, and charging sessions (JavaScript · ⭐ 1).

#### Battery

* [dalathegreat/Battery-Emulator](https://github.com/dalathegreat/Battery-Emulator) ⭐ 3,024 | 🐛 174 | 🌐 C++ | 📅 2026-11-09 - Battery-Emulator translates between supported EV battery packs and home or solar inverters so the packs can be used as stationary energy storage (C++ · ⭐ 3016).
* [mnh-jansson/open-battery-information](https://github.com/mnh-jansson/open-battery-information) ⭐ 1,832 | 🐛 99 | 🌐 C++ | 📅 2026-09-30 - Open Battery Information provides Arduino firmware and a web-based tool for reading battery-management-system data to support battery repair (C++ · ⭐ 1829).
* [remontsuri/EV-QA-Framework](https://github.com/remontsuri/EV-QA-Framework) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - A Python framework for validating EV battery telemetry, detecting anomalies, predicting state of health, simulating CAN networks and battery behavior, and exposing monitoring metrics (Python · ⭐ 9).

#### Charging management system

* [flobz/psa\_car\_controller](https://github.com/flobz/psa_car_controller) ⭐ 610 | 🐛 169 | 🌐 Python | 📅 2026-11-07 - A Python application that remotely monitors and controls PSA electric vehicles through the connected\_car v4 API, including charging, climate, and trip data (Python · ⭐ 607).
* [artmakerzbr/ev-tracker](https://github.com/artmakerzbr/ev-tracker) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-15 - A web app for recording EV charging sessions and calculating charges owed to a condominium (JavaScript · ⭐ 1).

#### Developer tools & libraries

* [tillsteinbach/CarConnectivity](https://github.com/tillsteinbach/CarConnectivity) ⭐ 216 | 🐛 28 | 🌐 Python | 📅 2026-10-14 - CarConnectivity is a Python API for retrieving telemetry and other data from vehicle services across multiple car brands (Python · ⭐ 216).
* [juherr/mobilityid](https://github.com/juherr/mobilityid) ⭐ 2 | 🐛 24 | 🌐 PHP | 📅 2026-11-09 - A multi-language monorepo providing implementations for parsing and handling mobility and EVSE identifiers (PHP · ⭐ 2).
* [ChargePi/openev-data-mcp](https://github.com/ChargePi/openev-data-mcp) ⭐ 1 | 🐛 0 | 🌐 PLpgSQL | 📅 2026-10-15 - An MCP server that provides AI assistants with query and semantic-search access to electric vehicle specifications from the open-ev-data dataset (PLpgSQL · ⭐ 1).
* [ducminhquan/datex2-ts](https://github.com/ducminhquan/datex2-ts) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20 - A TypeScript data model and runtime conversion/validation library for DATEX II v3 JSON (TypeScript · ⭐ 1).
* [xBlaz3kx/evcc-helm-chart](https://github.com/xBlaz3kx/evcc-helm-chart) ⭐ 0 | 🐛 1 | 🌐 Go Template | 📅 2026-11-01 - Helm chart for deploying EVCC, an open-source EV charging controller, on Kubernetes with SQLite database backup support (Go Template · ⭐ 0).

#### EVSE firmware

* [dzurikmiroslav/esp32-evse](https://github.com/dzurikmiroslav/esp32-evse) ⭐ 151 | 🐛 22 | 🌐 C | 📅 2026-10-31 - ESP32-based J1772 EVSE firmware with configurable hardware support, web management, energy metering, scheduling, and OTA updates (C · ⭐ 151).
* [bastoon577-lang/Viridian\_SmartCharger](https://github.com/bastoon577-lang/Viridian_SmartCharger) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-07-09 - Custom firmware for ESP01/Viridian-based EV charger that adapts charging power in real-time based on Linky smart meter data to manage grid load (C++ · ⭐ 1).

#### Energy management

* [OpenEMS/openems](https://github.com/OpenEMS/openems) ⭐ 1,623 | 🐛 70 | 🌐 Java | 📅 2026-11-10 - OpenEMS is a modular platform for monitoring and controlling energy storage, renewable generation, electric vehicle charging stations, heat pumps, and other energy devices (Java · ⭐ 1617).

#### Home automation

* [marq24/ha-evcc](https://github.com/marq24/ha-evcc) ⭐ 502 | 🐛 1 | 🌐 Python | 📅 2026-11-08 - An unofficial Home Assistant integration that connects to evcc to monitor and control EV charging and photovoltaic-based charging settings (Python · ⭐ 501).
* [andreadegiovine/homeassistant-stellantis-vehicles](https://github.com/andreadegiovine/homeassistant-stellantis-vehicles) ⭐ 299 | 🐛 18 | 🌐 Python | 📅 2026-11-09 - A Home Assistant integration that connects to Stellantis vehicle APIs to monitor vehicle status and control supported remote functions (Python · ⭐ 297).
* [leeyuentuen/alfen\_wallbox](https://github.com/leeyuentuen/alfen_wallbox) ⭐ 104 | 🐛 17 | 🌐 Python | 📅 2026-11-09 - A custom Home Assistant component for monitoring and controlling Alfen wallboxes (Python · ⭐ 104).
* [Pulpyyyy/carconnectivity-addon](https://github.com/Pulpyyyy/carconnectivity-addon) ⭐ 80 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-09 - A Home Assistant add-on that packages CarConnectivity to retrieve vehicle data from compatible manufacturers’ online services (JavaScript · ⭐ 80).
* [lachand/EV\_charger](https://github.com/lachand/EV_charger) ⭐ 42 | 🐛 11 | 🌐 Python | 📅 2026-11-09 - A Home Assistant integration that locally monitors and controls Tuya EV chargers over a LAN connection (Python · ⭐ 42).
* [tamcore/stelloauth](https://github.com/tamcore/stelloauth) ⭐ 16 | 🐛 3 | 🌐 Go | 📅 2026-11-11 - Stelloauth is a self-hosted web service that automates Stellantis vehicle OAuth authentication for the Home Assistant integration (Go · ⭐ 16).
* [SCiunczyk/wallbox-diy](https://github.com/SCiunczyk/wallbox-diy) ⭐ 5 | 🐛 1 | 📅 2026-09-16 - An ESP32-based Wi-Fi Modbus proxy and Home Assistant configuration for monitoring and controlling a DIY electric vehicle wallbox (⭐ 5).
* [wimhaanstra/com.sortedbits.smartevse](https://github.com/wimhaanstra/com.sortedbits.smartevse) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - A Homey app that connects to Smart EVSE-3 chargers through MQTT to monitor and control charging locally (TypeScript · ⭐ 1).

#### Maps & route planning

* [GeiserX/Pumperly](https://github.com/GeiserX/Pumperly) ⭐ 47 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-09 - An open-source route planner combining live fuel prices from 22 countries and EV charging station data with detour-aware corridor filtering (TypeScript · ⭐ 45).

#### Mobile app

* [ev-map/EVMap](https://github.com/ev-map/EVMap) ⭐ 283 | 🐛 52 | 🌐 Kotlin | 📅 2026-11-02 - EVMap is an open-source Android app that displays electric vehicle charging stations, availability, search, filtering, and navigation-map data from community databases (Kotlin · ⭐ 283).
* [powerly-ev/open-ev-charge-android-app](https://github.com/powerly-ev/open-ev-charge-android-app) ⭐ 9 | 🐛 0 | 🌐 Kotlin | 📅 2026-10-23 - White-label Android application template for discovering and managing EV charging sessions with peer-to-peer charger sharing and OCPP/OCPI backend integration (Kotlin · ⭐ 9).
* [EVtivity/evtivity-mobile-app](https://github.com/EVtivity/evtivity-mobile-app) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-12 - A white-label iOS and Android mobile app for EV drivers using the EVtivity charging platform (TypeScript · ⭐ 6).

#### Other protocols

* [enbility/eebus-go](https://github.com/enbility/eebus-go) ⭐ 123 | 🐛 45 | 🌐 Go | 📅 2026-11-06 - A Go library for implementing EEBUS use cases, including SHIP and SPINE communication, certificate handling, device discovery, connections, and pairing (Go · ⭐ 123).
* [enbility/ship-go](https://github.com/enbility/ship-go) ⭐ 19 | 🐛 34 | 🌐 Go | 📅 2026-11-02 - A Go library implementing the EEBUS SHIP 1.0.1 protocol (Go · ⭐ 19).
* [enbility/spine-go](https://github.com/enbility/spine-go) ⭐ 10 | 🐛 33 | 🌐 Go | 📅 2026-11-06 - Spine-go is a Go library implementing the EEBUS SPINE 1.3 protocol (Go · ⭐ 10).
* [hupe1980/openadr](https://github.com/hupe1980/openadr) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - A Rust crate implementing OpenADR 3.1 with VTN and VEN runtimes, a typed client, and conformance-testing tools (Rust · ⭐ 1).
* [juherr/datex4j](https://github.com/juherr/datex4j) ⭐ 0 | 🐛 35 | 🌐 Java | 📅 2026-10-23 - Datex4j is a modular Java SDK for parsing, serializing, validating, and converting DATEX II publications across multiple standard versions (Java · ⭐ 0).

#### Simulators

* [EVtivity/evtivity-ev-tester](https://github.com/EVtivity/evtivity-ev-tester) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-09-27 - An open-source EV-side simulator that emulates AC charging over SAE J1772 to test EVSEs and charging-system backends (C++ · ⭐ 3).

#### Specifications & documentation

* [chargeprice/chargeprice-api-docs](https://github.com/chargeprice/chargeprice-api-docs) ⭐ 43 | 🐛 3 | 📅 2026-11-11 - Documentation for accessing the Chargeprice API, which provides electric-vehicle charging tariffs, stations, companies, and vehicle data (⭐ 43).
* [etalab/schema-irve](https://github.com/etalab/schema-irve) ⭐ 13 | 🐛 15 | 🌐 Elixir | 📅 2026-10-26 - A set of data schemas for static, operational, and pricing information about public electric vehicle charging infrastructure (Elixir · ⭐ 13).
* [charinev/unified-error-codes](https://github.com/charinev/unified-error-codes) ⭐ 12 | 🐛 47 | 🌐 Python | 📅 2026-10-27 - A draft specification for standardized error codes and diagnostics across the EV charging ecosystem (Python · ⭐ 11).
* [OpenChargingTechnology/Whitepapers](https://github.com/OpenChargingTechnology/Whitepapers) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2026-11-12 - A collection of technical whitepapers and specifications for EV charging infrastructure covering OCPP, OCPI, OICP, ISO 15118, and related cybersecurity and interoperability standards (Python · ⭐ 5).
* [ocpi/openapi-specification](https://github.com/ocpi/openapi-specification) ⭐ 4 | 🐛 13 | 🌐 JavaScript | 📅 2026-05-13 - A repository containing an OpenAPI specification (JavaScript · ⭐ 4).
* [unified-error-codes/specification](https://github.com/unified-error-codes/specification) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-10-27 - A CharIN repository containing a draft specification for standardized error codes and diagnostics across the EV charging ecosystem (Python · ⭐ 4).
* [codetics-software/electric-mobility](https://github.com/codetics-software/electric-mobility) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-11-05 - A guidance and reference collection for AI agents building EV charging infrastructure, with protocol-specific field cards, architecture patterns, security gates, and engineering practices for OCPI, OCPP, and CSMS platforms (Python · ⭐ 1).
* [ChargePi/oecs](https://github.com/ChargePi/oecs) ⭐ 1 | 🐛 1 | 🌐 Go | 📅 2026-10-07 - OECS is a JSON Schema for describing the hardware, software, payment, pricing, and compliance details of EV charger models (Go · ⭐ 1).

### Uncategorized

* [vampirebyte/ocpp-gatling-test](https://github.com/vampirebyte/ocpp-gatling-test) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-08-28 (Java · ⭐ 1)

<!-- END GENERATED PROJECTS -->

## Contributing

Contributions are welcome! If you know of a tool or resource that is not on the list, please feel free to add it.

The easiest way to contribute is to [open an issue](https://github.com/juherr/awesome-ev-charging/issues/new/choose) using the "Add a link" template.

You can also submit a pull request. Note that the project listing above is **generated** — descriptions and categories are edited in `classifications.csv`, not by hand in this file. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full workflow.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-12._
