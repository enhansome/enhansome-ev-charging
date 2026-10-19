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

* [Specifications on GitHub](https://github.com/ocpi/ocpi) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07
  * [2.3.0-d2](https://github.com/ocpi/ocpi/releases/download/v2.3.0-ed2/OCPI-2.3.0-ed2.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06)
  * [2.2.1](https://github.com/ocpi/ocpi/releases/download/2.2.1/OCPI-2.2.1.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2021-10)
  * [2.2.0-d2](https://github.com/ocpi/ocpi/releases/download/2.2-d2/OCPI-2.2-d2.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 - Deprecated, use 2.2.1 instead (2020-06)
  * [2.2.0](https://github.com/ocpi/ocpi/releases/download/2.2/OCPI-2.2.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 - Deprecated, use 2.2.0-d2 instead (2019-09)
  * [2.1.1-d2](https://github.com/ocpi/ocpi/releases/download/2.1.1-d2/OCPI_2.1.1-d2.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2019-06)
  * [2.1.1](https://github.com/ocpi/ocpi/releases/download/2.1.1/OCPI_2.1.1.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 - Deprecated, use 2.1.1-d2 instead (2017-06)
  * [2.0](https://github.com/ocpi/ocpi/files/135934/OCPI_2.0-d2.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2016-02)
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

OCPI 2.3.0 is published as a [core specification](https://github.com/ocpi/ocpi/tree/2.3.0/release/core) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 plus optional modules packaged separately.

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

* Booking (2.3.0) — exact version labels are still being settled; the OCPI editors deferred on this in [ocpi/ocpi#572](https://github.com/ocpi/ocpi/issues/572) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07
  * [ed1](https://github.com/ocpi/ocpi/releases/download/v2.3.0-bookings/OCPI-2.3.0-bookings.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06, tag `v2.3.0-bookings`)
  * ed2 — not yet released
  * [1.1](https://evroaming.org/wp-content/uploads/2026/01/OCPI-2.3.0-booking-1.1.pdf) (2025-06, no GitHub tag)
* Payments (2.3.0)
  * [ed2](https://github.com/ocpi/ocpi/releases/download/v2.3.0-ed2-payments/OCPI-2.3.0-ed2-payments.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06, core edition 2 + Payments)
  * [ed1](https://github.com/ocpi/ocpi/releases/download/v2.3.0-payments/OCPI-2.3.0-payments.pdf) ⭐ 597 | 🐛 148 | 🌐 Perl | 📅 2026-09-07 (2026-06, core edition 1 + Payments)

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
* Specifications
  * eMi³ standard version V1.1 electric vehicle ICT interface specifications (2019-10)
    * [Part 1 v1.1](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.1/eMI3-standard-v1.1-Part-1.pdf)
    * [Terms and definitions v1.4](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.1/eMI3-standard-TermsAndDefinitions-v1.4.pdf)
  * eMi³ standard version V1.0 electric vehicle ICT interface specifications (2019-10)
    * [Part 1 v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-v1.0-Part-1.pdf)
    * [Part 2 v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-v1.0-Part-2.pdf)
    * [Terms and definitions v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-TermsAndDefinitions-v1.0.pdf)

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

* [steve-community/steve](https://github.com/steve-community/steve) ⭐ 1,140 | 🐛 97 | 🌐 Java | 📅 2026-10-17 - An open-source OCPP charging station management system server implementation in Java supporting OCPP protocol versions 1.2 through 1.6 (OCPP 1.2, 1.5, 1.6 · Java · ⭐ 1134).
* [dallmann-consulting/OCPP.Core](https://github.com/dallmann-consulting/OCPP.Core) ⭐ 306 | 🐛 9 | 🌐 C# | 📅 2026-10-04 - OCPP 1.6J/2.0/2.1 server written in .NET 10 with web-based management UI for charge points and tokens (OCPP 1.6, 2.0, 2.1 · C# · ⭐ 306).
* [citrineos/citrineos-core](https://github.com/citrineos/citrineos-core) ⭐ 299 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-19 - Open-source OCPP 1.6 and 2.0.1 charging station management server written in TypeScript with modular components, message routing, and operator web UI (OCPP 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 298).
* [citrineos/citrineos](https://github.com/citrineos/citrineos) ⭐ 156 | 🐛 10 | 📅 2026-09-21 - Open-source OCPP 1.6/2.0.1 Charging Station Management System server with ISO 15118 Plug\&Charge support (OCPP 1.6, 2.0.1 · ⭐ 154).
* [apostoldevel/ocpp-cs](https://github.com/apostoldevel/ocpp-cs) ⭐ 80 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - OCPP 1.5 (SOAP), 1.6, and 2.0.1 (JSON/WebSocket) Central System server with integrated charge point emulator in C++20 (OCPP 1.5, 1.6, 2.0.1 · C++ · ⭐ 80).
* [EVtivity/evtivity-csms](https://github.com/EVtivity/evtivity-csms) ⭐ 32 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-16 - An OCPP 1.6/2.1 and OCPI 2.2.1/2.3.0 compliant charging station management system with ISO 15118 Plug and Charge support, REST API, and AI-powered operator and driver frontends (OCPP 1.6, 2.1 · TypeScript · ⭐ 33).
* [yuncitys/charging-cloud-web](https://github.com/yuncitys/charging-cloud-web) ⭐ 27 | 🐛 0 | 🌐 Vue | 📅 2026-10-19 - Open-source charging station management and billing platform supporting OCPP 1.5, 1.6, and 2.0 protocols for electric vehicles and e-bikes (OCPP 1.6, 2.0 · Vue · ⭐ 26).
* [openchargehub/ocpp-proxy](https://github.com/openchargehub/ocpp-proxy) ⭐ 24 | 🐛 11 | 🌐 Python | 📅 2025-10-27 - A secure OCPP 1.6/2.0.1 proxy server that shares a single EV charger among multiple backend services with automatic protocol detection and intelligent arbitration (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 24).
* [gertjana/ocpp-backend](https://github.com/gertjana/ocpp-backend) ⭐ 23 | 🐛 0 | 🌐 Elixir | 📅 2025-11-11 - An OCPP 1.6/2.0 compliant charging station management backend written in Elixir using Cowboy with WebSocket support and a dashboard for command control (OCPP 1.6, 2.0 · Elixir · ⭐ 23).
* [srcfl/ftw](https://github.com/srcfl/ftw) ⭐ 21 | 🐛 95 | 🌐 Go | 📅 2026-10-19 - Home energy management system with built-in OCPP 1.6J + 2.0.1 server for coordinating solar, batteries, grid, and EV charging (OCPP 1.6, 2.0.1 · Go · ⭐ 20).
* [savekar-ev/OCPP-1.6-Charging-Point-Management-System](https://github.com/savekar-ev/OCPP-1.6-Charging-Point-Management-System) ⭐ 17 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-10 - A production-ready full-stack OCPP 1.6 Charge Point Management System (CPMS) with a WebSocket server, REST API, and admin UI for managing EV charging stations (OCPP 1.6 · TypeScript · ⭐ 17).
* [OpenChargingCloud/CSMSCLI](https://github.com/OpenChargingCloud/CSMSCLI) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2026-10-19 - A .NET Charging Station Management System implementing OCPP and OCPI protocols for managing EV charging stations and roaming services (OCPP 1.6, 2.1 · C# · ⭐ 9).
* [davbauer/ocpp-manager](https://github.com/davbauer/ocpp-manager) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-05 - An OCPP-based open-source charging station management platform with web interface for monitoring, RFID authorization, and transaction tracking (TypeScript · ⭐ 8).
* [unified-error-codes/csds](https://github.com/unified-error-codes/csds) ⭐ 7 | 🐛 16 | 🌐 Python | 📅 2026-04-30 - An OCPP-based backend service that collects unified error codes and telemetry from charging stations for diagnostic analysis (Python · ⭐ 7).
* [Beep-Technologies/esteban-ocpp](https://github.com/Beep-Technologies/esteban-ocpp) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-05-15 - An open-source OCPP server implementation in Golang providing charging station management with REST APIs and supporting cloud and edge deployment (OCPP 2.0 · Go · ⭐ 5).
* [parklapp/steve-pluggable](https://github.com/parklapp/steve-pluggable) ⭐ 4 | 🐛 11 | 🌐 Java | 📅 2026-04-09 - Java implementation of an OCPP server for managing electric charge points, supporting OCPP 1.2 through 1.6 in both SOAP and JSON variants (OCPP 1.2, 1.5, 1.6 · Java · ⭐ 4).
* [juherr/evolve](https://github.com/juherr/evolve) ⭐ 4 | 🐛 18 | 🌐 Java | 📅 2026-09-07 - EVolve is an OCPP server implementation written in Java (Java · ⭐ 4).
* [eliodecolli/Medinilla](https://github.com/eliodecolli/Medinilla) ⭐ 3 | 🐛 7 | 🌐 C# | 📅 2026-09-07 - An OCPP-compliant charging station management system backend written in ASP.NET Core (OCPP 2.0.1 · C# · ⭐ 3).
* [eveys-mobility/OCPP](https://github.com/eveys-mobility/OCPP) ⭐ 3 | 🐛 4 | 🌐 Python | 📅 2026-10-19 - OCPP-J 1.6 CSMS gateway for the Eveys EV-charging platform that manages charger WebSocket connections and exposes REST, gRPC, and Kafka event interfaces (OCPP 1.6, 2.0.1 · Python · ⭐ 3).
* [erik73/app-steve](https://github.com/erik73/app-steve) ⭐ 3 | 🐛 1 | 🌐 Dockerfile | 📅 2026-10-15 - OCPP server for electric vehicle charging point management, packaged as a Home Assistant add-on (Dockerfile · ⭐ 3).
* [FlipSoftware/moovolt-csms](https://github.com/FlipSoftware/moovolt-csms) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-11-04 - An OCPP-compliant Charging Station Management System (CSMS) built in Rust with a distributed architecture (SPR and SG components) for managing EV charging stations via WebSocket and AMQP messaging (Rust · ⭐ 3).
* [elton-saraci/ocpp-central-system](https://github.com/elton-saraci/ocpp-central-system) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-09-20 - A Spring Boot OCPP 1.6 Central System that manages EV charging stations over WebSocket with support for transactions, remote operations, smart charging, and a REST API (OCPP 1.6 · Java · ⭐ 3).
* [wimhaanstra/virtual-ocpp](https://github.com/wimhaanstra/virtual-ocpp) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-28 - Self-hosted OCPP 1.6j charging station management server with integrated charger simulator, local CSMS functionality, and optional proxying to external OCPP backends (OCPP 1.6 · TypeScript · ⭐ 2).
* [zeloscloud/zelos-extension-ocpp](https://github.com/zeloscloud/zelos-extension-ocpp) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2026-09-01 - An OCPP 1.6/2.0.1 CSMS server extension for the Zelos App that manages EV charging point connections with real-time monitoring and remote control (OCPP 1.6, 2.0.1 · Python · ⭐ 1).
* [alexeimoisseev/ocpp-server-typescript](https://github.com/alexeimoisseev/ocpp-server-typescript) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-12 - A minimal OCPP server in TypeScript supporting OCPP 1.6J and 2.0.1 over WebSocket for learning the protocol, testing chargers, and running simulators (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 1).
* [amolsurjuse/ocpp-service](https://github.com/amolsurjuse/ocpp-service) ⭐ 1 | 🐛 12 | 🌐 Java | 📅 2026-10-05 - Spring Boot microservice providing an OCPP server for managing EV charging station WebSocket connections, message routing, and remote command execution (OCPP 2.0.1 · Java · ⭐ 1).
* [juherr/steve-ocpp-csms-image](https://github.com/juherr/steve-ocpp-csms-image) ⭐ 1 | 🐛 4 | 🌐 Shell | 📅 2026-10-16 - Docker images for SteVe, an open-source OCPP Central System management server, pre-compiled at build time for ready-to-run deployment (Shell · ⭐ 1).

#### Simulator

* [SAP/e-mobility-charging-stations-simulator](https://github.com/SAP/e-mobility-charging-stations-simulator) ⭐ 229 | 🐛 20 | 🌐 TypeScript | 📅 2026-10-19 - A Node.js simulator for OCPP-J charging stations that enables load testing and scaled simulation of multiple charging infrastructure endpoints (OCPP 1.6, 2.0, 2.0.1 · TypeScript · ⭐ 227).
* [monta-app/ocpp-emulator](https://github.com/monta-app/ocpp-emulator) ⭐ 180 | 🐛 8 | 🌐 Kotlin | 📅 2026-10-19 - An open-source OCPP 1.6 and 2.0.1 charge point emulator for testing and local development (OCPP 1.6, 2.0.1 · Kotlin · ⭐ 180).
* [solidstudiosh/ocpp-virtual-charge-point](https://github.com/solidstudiosh/ocpp-virtual-charge-point) ⭐ 120 | 🐛 21 | 🌐 TypeScript | 📅 2026-09-22 - A configurable, terminal-based OCPP charging station simulator supporting versions 1.6 and 2.0.1 with multi-connector and EVSE support (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 119).
* [shiv3/ocpp-cp-simulator](https://github.com/shiv3/ocpp-cp-simulator) ⭐ 44 | 🐛 64 | 🌐 TypeScript | 📅 2026-10-14 - OCPP charge point simulator with browser UI, CLI, daemon, and Socket.IO control API for AI agent testing and CSMS development (OCPP 1.2, 1.5, 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 43).
* [OpenChargingCloud/ChargingStationApp](https://github.com/OpenChargingCloud/ChargingStationApp) ⭐ 41 | 🐛 12 | 🌐 TypeScript | 📅 2026-04-03 - An Electron-based OCPP charging station simulator for testing and certification of OCPP v1.6, v2.0.1, and v2.1 protocols (OCPP 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 41).
* [ozgurbayram/OCPPSimulator](https://github.com/ozgurbayram/OCPPSimulator) ⭐ 35 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-12 - A web-based OCPP simulator for testing EV charging station management systems by emulating multiple charge points and simulating OCPP 1.6 protocol communication (OCPP 1.6 · TypeScript · ⭐ 34).
* [virta-ltd/charge-device-simulator](https://github.com/virta-ltd/charge-device-simulator) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - Python-based device simulators for EV charging protocols including OCPP, deployable as Docker containers (Python · ⭐ 21).
* [road-labs/chargestation-one](https://github.com/road-labs/chargestation-one) ⭐ 18 | 🐛 2 | 🌐 Less | 📅 2026-09-28 - A browser-based charging station simulator supporting OCPP 1.6 and OCPP 2.0.1 protocols with transaction control and OCMF meter signing (OCPP 1.6, 2.0.1, 2.1 · Less · ⭐ 18).
* [c-jimenez/open-ocpp-simu](https://github.com/c-jimenez/open-ocpp-simu) ⭐ 16 | 🐛 4 | 🌐 C++ | 📅 2026-04-15 - A charge point simulator environment built on the Open OCPP library with simulated charge points, launcher daemon, and HMI supervisor communicating via MQTT and OCPP protocols (C++ · ⭐ 16).
* [kwtycoon/kilowatt-tycoon](https://github.com/kwtycoon/kilowatt-tycoon) ⭐ 7 | 🐛 8 | 🌐 Rust | 📅 2026-07-10 - A Rust/Bevy-based EV charging network simulator game implementing OCPP 1.6J, OCPI 2.3.0, and OpenADR 3.0 protocols (OCPP 1.6 · Rust · ⭐ 7).
* [PlugSecure-Inc/ocpp-simulator-lab](https://github.com/PlugSecure-Inc/ocpp-simulator-lab) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-17 - A web-based OCPP simulator and testing tool that simulates both Charge Points and Charge Point Management Systems with support for OCPP 1.6J, 2.0.1, and 2.1 (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 6).
* [elton-saraci/ocpp-charge-point-simulator](https://github.com/elton-saraci/ocpp-charge-point-simulator) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2026-09-21 - OCPP 1.6 charge point simulator supporting multiple simultaneous charge points managed via REST API with an included web console (OCPP 1.6 · Java · ⭐ 6).
* [ZhongRuoyu/ocppsim](https://github.com/ZhongRuoyu/ocppsim) ⭐ 5 | 🐛 2 | 🌐 Rust | 📅 2026-10-18 - A terminal-based OCPP-J charge point simulator written in Rust for testing and developing CSMS servers (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 5).
* [vfg27/EmuOCPP](https://github.com/vfg27/EmuOCPP) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2026-03-22 - OCPP 1.6, 2.0, and 2.0.1 emulator with security profiles 1-3 that simulates charging stations and management systems using mininet for network topology simulation and includes Wireshark packet inspection tools (OCPP 1.6, 2.0, 2.0.1 · Python · ⭐ 5).
* [ReliON-Charging/everest-dcfc](https://github.com/ReliON-Charging/everest-dcfc) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-02-24 - A containerized DCFC simulator supporting OCPP 1.6, 2.0.1, and 2.1 with configurable multi-connector capability and Node-RED dashboard for testing (OCPP 1.6, 2.0.1, 2.1 · C++ · ⭐ 4).
* [flowionab/charge-point-simulator](https://github.com/flowionab/charge-point-simulator) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-19 - An OCPP 1.6J/2.0.1/2.1 charge point simulator built in Rust for testing Charge Station Management Systems and developing EV charging infrastructure (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 3).
* [wirelane/ocpp-client-simulator](https://github.com/wirelane/ocpp-client-simulator) ⭐ 3 | 🐛 2 | 🌐 JavaScript | 📅 2026-09-17 - A command-line simulator of an OCPP 1.6 compatible charging station that connects to OCPP servers for testing scenarios such as RFID authorization and remote start/stop commands (OCPP 1.6 · JavaScript · ⭐ 3).
* [hlsxx/ocpp-charge-point-simulator](https://github.com/hlsxx/ocpp-charge-point-simulator) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-05-22 - A Rust CLI tool that simulates OCPP 1.6 charge points for testing OCPP backends without physical hardware (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 2).
* [mohsinali33226/ocpp-charging-operations-lab](https://github.com/mohsinali33226/ocpp-charging-operations-lab) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-09-09 - A Python-based OCPP 1.6 simulator with virtual charging stations and an integrated CSMS backend for operations monitoring, remote control, and scenario testing (OCPP 1.6, 2.0.1 · HTML · ⭐ 1).
* [I-Love-OCPP/Charge-Point-Simulator](https://github.com/I-Love-OCPP/Charge-Point-Simulator) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-03 - A React and TypeScript web application frontend for simulating EV charging stations (TypeScript · ⭐ 1).

#### Libraries

##### C

* [pazzk-labs/ocpp](https://github.com/pazzk-labs/ocpp) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2025-11-06 - A C language OCPP client library implementation with configurable protocol support for charging applications (⭐ 10).
* [tux-evse/afb-ocpp-ext](https://github.com/tux-evse/afb-ocpp-ext) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-11-25 - An AFB micro-service framework extension library providing OCPP 1.6 and 2.0.1 transport protocol support for CSMS client connections (OCPP 1.6, 2.0.1 · ⭐ 2).

##### C\#

* [OpenChargingCloud/WWCP\_OCPP](https://github.com/OpenChargingCloud/WWCP_OCPP) ⭐ 71 | 🐛 9 | 🌐 C# | 📅 2026-10-19 - Software library for building OCPP services and WWCP gateways supporting OCPP v1.6, v2.0.1, and v2.1 (OCPP 1.5, 1.6, 2.0.1, 2.1 · ⭐ 71).

##### C++

* [matth-x/MicroOcpp](https://github.com/matth-x/MicroOcpp) ⭐ 548 | 🐛 132 | 🌐 C++ | 📅 2025-12-04 - C/C++ OCPP 1.6 / 2.0.1 client library for microcontroller-based EV charging equipment, supporting Espressif, Arduino, NXP, STM, Linux and other platforms (OCPP 1.6, 2.0.1 · ⭐ 545).
* [c-jimenez/open-ocpp](https://github.com/c-jimenez/open-ocpp) ⭐ 174 | 🐛 10 | 🌐 C++ | 📅 2026-04-13 - C++ library implementation of the OCPP 1.6 and 2.0.1 WebSocket/JSON protocols (OCPP 1.6, 2.0.1 · ⭐ 175).
* [Tinkerforge/tfocpp](https://github.com/Tinkerforge/tfocpp) ⭐ 4 | 🐛 3 | 🌐 C++ | 📅 2026-09-26 - C++ library implementing OCPP 1.6J protocol with Core and Smart Charging profiles for EV charger firmware integration (OCPP 1.6 · ⭐ 4).

##### Go

* [aliml92/ocpp](https://github.com/aliml92/ocpp) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2026-08-12 - Go library implementing OCPP 1.6 and 2.0.1 in JSON format, supporting both server and client functionality (OCPP 1.6, 2.0.1 · ⭐ 27).
* [ChargePi/ocpp-manager](https://github.com/ChargePi/ocpp-manager) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2026-04-19 - Go library for managing and validating OCPP configuration variables with versioning and mandatory key enforcement (OCPP 1.6, 2.0.1 · ⭐ 6).
* [shiv3/gocpp](https://github.com/shiv3/gocpp) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-06-18 - A Go library implementing OCPP 1.6, 2.0.1, and 2.1 with generics-first typed APIs for CSMS and charge-point applications, including JSON-Schema validation and pluggable storage and observability components (OCPP 1.6, 2.0.1, 2.1 · ⭐ 5).
* [road-labs/ocppj-go](https://github.com/road-labs/ocppj-go) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-08-17 - Go library implementing the OCPP-J (JSON over WebSockets) protocol with client and server support (OCPP 1.6, 2.0.1 · ⭐ 4).
* [road-labs/ocpp-types-go](https://github.com/road-labs/ocpp-types-go) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-09-04 - A Go library providing strongly-typed struct definitions and helpers for OCPP protocol messages across versions 1.5, 1.6, 2.0.1, and 2.1 (OCPP 1.5, 1.6, 2.0.1, 2.1 · ⭐ 3).
* [aasanchez/ocpp16messages](https://github.com/aasanchez/ocpp16messages) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2026-10-17 - A type-safe Go library implementing OCPP 1.6 message structures with validation for EV charging station and CSMS applications (OCPP 1.6 · ⭐ 2).

##### Java

* [ChargeTimeEU/Java-OCA-OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP) ⭐ 380 | 🐛 16 | 🌐 Java | 📅 2026-06-19 - Java library for implementing OCPP-compliant client and server applications, supporting OCPP 1.6 (JSON/SOAP) and OCPP 2.0.1/2.1 (OCPP 1.6, 2.0.1, 2.1 · ⭐ 378).

##### JavaScript

* [mikuso/ocpp-rpc](https://github.com/mikuso/ocpp-rpc) ⭐ 136 | 🐛 14 | 🌐 JavaScript | 📅 2026-08-21 - A Node.js library implementing client and server for the OCPP-J JSON-RPC-over-WebSocket transport protocol (versions 1.6, 2.0.1, 2.1) (OCPP 1.6, 2.0.1, 2.1 · ⭐ 135).
* [argonne-vci/node-red-contrib-ocpp](https://github.com/argonne-vci/node-red-contrib-ocpp) ⭐ 37 | 🐛 27 | 🌐 JavaScript | 📅 2026-06-05 - Node-Red nodes for OCPP 1.5/1.6 communication with EVSE charge points and central systems via SOAP and JSON protocols (OCPP 1.5, 1.6 · ⭐ 37).
* [ampeco/cpd-ocpp](https://github.com/ampeco/cpd-ocpp) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-22 - Node.js library implementing OCPP 1.6 JSON protocol with abstraction layers for building charging station and central management system interfaces (OCPP 2.0 · ⭐ 3).

##### Kotlin

* [IZIVIA/ocpp-toolkit](https://github.com/IZIVIA/ocpp-toolkit) ⭐ 46 | 🐛 13 | 🌐 Kotlin | 📅 2026-10-02 - A Kotlin library implementing OCPP 1.2, 1.5, 1.6, and 2.0.1 protocols for both charging stations and CSMS over OCPP-J and OCPP-S transports (OCPP 1.2, 1.5, 1.6, 2.0 · ⭐ 46).
* [monta-app/library-ocpp](https://github.com/monta-app/library-ocpp) ⭐ 6 | 🐛 1 | 🌐 Kotlin | 📅 2026-10-19 - Kotlin library for OCPP 1.6 and 2.0.1 implementation supporting both synchronous and asynchronous message handling patterns (OCPP 1.6 · ⭐ 6).
* [I-Love-OCPP/sdk-1.6j](https://github.com/I-Love-OCPP/sdk-1.6j) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-02 - Kotlin SDK for implementing OCPP 1.6 JSON-based central systems (OCPP 1.6 · ⭐ 1).

##### Python

* [mobilityhouse/ocpp](https://github.com/mobilityhouse/ocpp) ⭐ 1,047 | 🐛 18 | 🌐 Python | 📅 2026-10-04 - Python library implementing the Open Charge Point Protocol (OCPP) versions 1.6 and 2.0.1 in JSON format (OCPP 1.6, 2.0.1 · ⭐ 1047).

##### Rust

* [tommymalmqvist/rust-ocpp](https://github.com/tommymalmqvist/rust-ocpp) ⭐ 105 | 🐛 10 | 🌐 Rust | 📅 2026-10-19 - Rust library implementing OCPP versions 1.6, 2.0.1, and 2.1 with official schema validation (OCPP 1.6, 2.0.1, 2.1 · ⭐ 103).
* [flowionab/ocpp-charge-point](https://github.com/flowionab/ocpp-charge-point) ⭐ 7 | 🐛 2 | 🌐 Rust | 📅 2026-09-24 - A Rust library framework for implementing OCPP 1.6J and 2.0.1 compliant charge point firmware with embedded hardware abstraction support (OCPP 1.6, 2.0.1, 2.1 · ⭐ 7).
* [flowionab/ocpp-client](https://github.com/flowionab/ocpp-client) ⭐ 7 | 🐛 1 | 🌐 Rust | 📅 2026-09-17 - A Rust library providing OCPP client communication with support for OCPP 1.6J, 2.0.1, and 2.1, featuring WebSocket/WSS transport and embedded-friendly no\_std support (OCPP 1.6, 2.0.1, 2.1 · ⭐ 6).
* [evlinked/ocpp-rs](https://github.com/evlinked/ocpp-rs) ⭐ 4 | 🐛 10 | 🌐 Rust | 📅 2026-09-28 - A Rust library implementing OCPP 1.6J and OCPP 2.0.1 with CSMS server and Charge Point simulator (OCPP 1.6, 2.0.1 · ⭐ 4).
* [hupe1980/ocpp-kit](https://github.com/hupe1980/ocpp-kit) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - A Rust library providing OCPP 1.6J, 2.0.1 and 2.1 protocol support with typed payloads and multi-layer architecture for charging stations, CSMS backends and local controllers (OCPP 1.6, 2.0.1, 2.1 · ⭐ 3).

##### TypeScript

* [voltbras/ts-ocpp](https://github.com/voltbras/ts-ocpp) ⭐ 48 | 🐛 6 | 🌐 TypeScript | 📅 2026-01-20 - TypeScript library implementing OCPP v1.6-JSON and v1.5-SOAP with type-safe request/response handling for central systems and charge points (⭐ 48).
* [jacoscaz/typed-ocpp](https://github.com/jacoscaz/typed-ocpp) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-14 - A TypeScript library for type-aware validation of OCPP 1.6, OCPP 2.0.1, and OCPP 2.1 messages against official JSON Schemas from the Open Charge Alliance (OCPP 1.6, 2.0, 2.1 · ⭐ 11).
* [connected-hil/ocpp-tools](https://github.com/connected-hil/ocpp-tools) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-08 - Open-source TypeScript library providing type definitions, interfaces, and validation utilities for OCPP v1.6 and v2.0.1 protocol messages (OCPP 1.6, 2.0.1, 2.1 · ⭐ 8).

#### Misc

* [evcc-io/evcc](https://github.com/evcc-io/evcc) ⭐ 7,396 | 🐛 194 | 🌐 Go | 📅 2026-10-19 - Open-source EV charge controller and home energy management system with OCPP support and integrations for 100+ chargers, solar inverters, and heating systems (Go · ⭐ 7343).
* [lbbrhzn/ocpp](https://github.com/lbbrhzn/ocpp) ⭐ 407 | 🐛 46 | 🌐 Python | 📅 2026-10-16 - Home Assistant integration for OCPP 1.6j/2.0.1/2.1 compatible electric vehicle chargers (Python · ⭐ 402).
* [EVerest/EVerest](https://github.com/EVerest/EVerest) ⭐ 282 | 🐛 257 | 🌐 C++ | 📅 2026-10-19 - EVerest is a modular open-source full-stack framework for building EV charging systems with support for OCPP 1.6/2.0/2.1 and ISO 15118-2/3/20 protocols (OCPP 1.6, 2.0.1, 2.1 · C++ · ⭐ 277).
* [SmartEVSE/SmartEVSE-3](https://github.com/SmartEVSE/SmartEVSE-3) ⭐ 235 | 🐛 11 | 🌐 C | 📅 2026-08-30 - Open source EVSE (Electric Vehicle Supply Equipment) controller with OCPP 1.6j support, smart charging capabilities, and multi-module power sharing (OCPP 1.6 · C · ⭐ 234).
* [ChargeLab/OpenOCPP](https://github.com/ChargeLab/OpenOCPP) ⭐ 90 | 🐛 1 | 🌐 C++ | 📅 2026-10-08 - Multi-platform OCPP 1.6/2.0.1 embedded firmware for electric vehicle charging stations (OCPP 1.6, 2.0.1 · C++ · ⭐ 90).
* [nader0913/ocpp-rag](https://github.com/nader0913/ocpp-rag) ⭐ 61 | 🐛 0 | 🌐 Python | 📅 2026-06-09 - MCP server providing semantic search and retrieval of OCPP 1.6, OCPP 2.0.1, and ISO 15118 Plug & Charge specifications, use cases, and documentation (OCPP 1.6, 2.0.1 · Python · ⭐ 61).
* [ChargePi/ChargePi-go](https://github.com/ChargePi/ChargePi-go) ⭐ 53 | 🐛 15 | 🌐 Go | 📅 2026-10-01 - ChargePi is an open-source, modular Linux-based charge point framework implementing OCPP 1.6 with management UI and API (OCPP 1.6, 2.0.1, 2.1 · Go · ⭐ 52).
* [alexeimoisseev/ocpp.md](https://github.com/alexeimoisseev/ocpp.md) ⭐ 31 | 🐛 1 | 🌐 Python | 📅 2026-07-12 - A structured OCPP (2.1, 2.0.1, 1.6J) knowledge base with message schemas, data types, sequence diagrams, and smart-charging guides designed for AI agent integration in EV charging development (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 31).
* [vampirebyte/rabbitmq-web-ocpp](https://github.com/vampirebyte/rabbitmq-web-ocpp) ⭐ 19 | 🐛 1 | 🌐 Erlang | 📅 2026-08-26 - RabbitMQ 4.x plugin that terminates OCPP 1.6J and 2.x WebSocket connections from EV charging stations and translates each frame into AMQP messages, so backends can consume them as queue workers (Erlang · ⭐ 19).
* [ocpp-balanz/ocpp-2w-proxy](https://github.com/ocpp-balanz/ocpp-2w-proxy) ⭐ 17 | 🐛 7 | 🌐 Python | 📅 2026-02-22 - A two-way OCPP proxy that enables charging stations to establish simultaneous connections with multiple management systems (primary and secondary) using configurable message forwarding rules (Python · ⭐ 16).
* [joulo-nl/joulo-ocpp-proxy](https://github.com/joulo-nl/joulo-ocpp-proxy) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-19 - A lightweight OCPP WebSocket proxy that forwards charger traffic to a primary CSMS backend while optionally mirroring messages to secondary backends for monitoring and analytics (OCPP 1.6, 2.0, 2.0.1 · TypeScript · ⭐ 14).
* [vfg27/CheckOCPP](https://github.com/vfg27/CheckOCPP) ⭐ 13 | 🐛 1 | 🌐 Lua | 📅 2026-03-22 - Wireshark dissector for automatic OCPP version detection and protocol compliance validation of OCPP 1.6, 2.0, and 2.0.1 traffic (OCPP 1.6, 2.0, 2.0.1 · Lua · ⭐ 13).
* [tzi-app/tzi-OCTT](https://github.com/tzi-app/tzi-OCTT) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-03-05 - Python pytest implementation of OCPP Conformance Test Suite scenarios for validating CSMS systems against OCPP 2.0.1 and OCPP 1.6J specifications, including 327 test cases across 16 functional areas (OCPP 1.6, 2.0.1 · Python · ⭐ 11).
* [gyzod/ocpp2mqtt](https://github.com/gyzod/ocpp2mqtt) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-09-19 - A bidirectional gateway that converts OCPP 1.6 protocol messages to MQTT and vice versa for integrating EV charging stations with home automation systems (OCPP 1.6 · Python · ⭐ 11).
* [chargex-consortium/ev-charge-seq-state](https://github.com/chargex-consortium/ev-charge-seq-state) ⭐ 7 | 🐛 0 | 📅 2026-06-02 - Collection of UML sequence diagrams and finite-state machines modeling EV charging protocols including OCPP 1.6J/2.0/2.1 and ISO 15118-2/20 (OCPP 1.6, 2.0.1, 2.1 · ⭐ 6).
* [ocpp-debugkit/toolkit](https://github.com/ocpp-debugkit/toolkit) ⭐ 7 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-11 - Open-source debugging toolkit for analyzing OCPP charging session traces with failure detection, scenario evaluation, and report generation (TypeScript · ⭐ 5).
* [juherr/open-ocpp-tck](https://github.com/juherr/open-ocpp-tck) ⭐ 6 | 🐛 47 | 🌐 TypeScript | 📅 2026-10-02 - Open-source OCPP conformance test compatibility kit with pluggable drivers and wire-level assertions for testing charging station management systems (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 5).
* [OpenChargingTechnology/Whitepapers](https://github.com/OpenChargingTechnology/Whitepapers) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2026-10-19 - Open-source technical whitepapers on EV charging cybersecurity, regulations, protocol specifications, and secure implementation patterns for OCPP, OCPI, OICP, ISO 15118, and Eichrecht (OCPP 1.6, 2.1 · Python · ⭐ 5).
* [michael-adler/ha-ocpp-relay](https://github.com/michael-adler/ha-ocpp-relay) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2026-08-05 - Home Assistant integration that relays OCPP communication between EV chargers and remote management servers while exposing OCPP traffic as Home Assistant sensors (Python · ⭐ 4).
* [ChargePi/chargeflow](https://github.com/ChargePi/chargeflow) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-09-18 - A CLI tool for validating raw OCPP JSON messages against OCPP 1.6, 2.0.1, and 2.1 schemas (OCPP 1.6, 2.0.1, 2.1 · Go · ⭐ 4).
* [ocpp-debugkit/studio](https://github.com/ocpp-debugkit/studio) ⭐ 4 | 🐛 4 | 🌐 Zig | 📅 2026-07-30 - Native desktop debugger for OCPP charging sessions that provides live traffic inspection, protocol failure detection, and trace analysis (OCPP 1.6 · Zig · ⭐ 4).
* [open-ocpp-trace/specification](https://github.com/open-ocpp-trace/specification) ⭐ 4 | 🐛 3 | 🌐 JavaScript | 📅 2026-07-22 - A versioned JSON/JSONL trace format specification with schema and validation toolkit for recording and analyzing OCPP message exchanges (JavaScript · ⭐ 4).
* [sepehr-safari/ocpp-handbook](https://github.com/sepehr-safari/ocpp-handbook) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-15 - A vendor-neutral, comprehensive course on EV charging protocols (OCPP, OCPI, ISO 15118), industry context, hardware, and practical debugging techniques for software engineers (OCPP 1.6, 2.0.1 · JavaScript · ⭐ 3).
* [road-labs/ocpp-trace-replayer](https://github.com/road-labs/ocpp-trace-replayer) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-09-11 - Command-line tool for replaying OCPP trace files against OCPP backends to test server implementations (OCPP 1.5, 1.6, 2.0.1, 2.1 · Go · ⭐ 3).
* [eliodecolli/ocpp-test-cases](https://github.com/eliodecolli/ocpp-test-cases) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-03-20 - Test cases for OCPP 2.0.1 protocol implementation, AI-generated from the official specification documentation with coverage of Transactions, Authorization, and Provision modules (OCPP 2.0.1 · Python · ⭐ 1).
* [OpenChargingTechnology/OCPP-SBOM](https://github.com/OpenChargingTechnology/OCPP-SBOM) ⭐ 1 | 🐛 0 | 📅 2025-12-05 - Formal SBOM (CycloneDX and SPDX) representations of OCPP specification bundles for supply-chain transparency and reproducibility (OCPP 2.1 · ⭐ 1).
* [codetics-software/electric-mobility](https://github.com/codetics-software/electric-mobility) ⭐ 1 | 🐛 0 | 📅 2026-10-05 - A reference skill providing implementation guidance, protocol documentation, and engineering practices for electric mobility software across OCPI, OCPP, and platform architecture (OCPP 1.6, 2.0.1, 2.1 · ⭐ 1).

### OCPI

#### Server

* [citrineos/citrineos-ocpi](https://github.com/citrineos/citrineos-ocpi) ⭐ 23 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-13 - OCPI 2.2.1 CPO server modules built on CitrineOS Core for charging point operations and eMSP partner management (OCPI 2.2.1 · TypeScript · ⭐ 23).
* [olisystems/ocn-node-v2](https://github.com/olisystems/ocn-node-v2) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-10-15 - A Kotlin/Spring Boot service that brokers OCPI v2.2 traffic between charging network parties and integrates with the OCN Registry (OCPI 2.2 · Kotlin · ⭐ 1).

#### Simulator

* [savekar-ev/OCPI-2.2.1-EMSP-Simulator](https://github.com/savekar-ev/OCPI-2.2.1-EMSP-Simulator) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2026-05-07 - A Python-based OCPI 2.2.1 EMSP Simulator for validating CPO protocol correctness, credentials handshake, and schema compliance (OCPI 2.2.1 · Python · ⭐ 10).
* [rally-finance/ocpi-mock-hub](https://github.com/rally-finance/ocpi-mock-hub) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-04-22 - A mock OCPI 2.2.1 hub server in Go for development and testing of OCPI integrations without a live partner (OCPI 2.2.1 · Go · ⭐ 5).

#### Libraries

##### C\#

* [OpenChargingCloud/WWCP\_OCPI](https://github.com/OpenChargingCloud/WWCP_OCPI) ⭐ 29 | 🐛 1 | 🌐 C# | 📅 2026-10-18 - A protocol implementation library providing OCPI v2.1–v3.0 support with extensions for GDPR, Eichrecht, AFIR compliance, and bridges for communication between WWCP and OCPI systems (OCPI 2.0, 2.1, 2.1.1, 2.2, 2.2.1, 2.3.0 · ⭐ 29).
* [BitzArt/OCPI.Net](https://github.com/BitzArt/OCPI.Net) ⭐ 27 | 🐛 5 | 🌐 C# | 📅 2026-08-01 - A .NET C# library implementing the Open Charge Point Interface (OCPI) protocol, with full support for version 2.2.1 and partial support for version 2.2 (⭐ 27).

##### Java

* [steve-community/ocpi-models](https://github.com/steve-community/ocpi-models) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-10-11 - Java library providing OCPI 2.2.1 data models, Spring MVC API mappings, and RestTemplate clients for implementing OCPI endpoints (OCPI 2.2.1 · ⭐ 3).

##### Kotlin

* [IZIVIA/ocpi-toolkit](https://github.com/IZIVIA/ocpi-toolkit) ⭐ 37 | 🐛 14 | 🌐 Kotlin | 📅 2026-10-19 - A Kotlin library implementing OCPI 2.2.1 protocol business logic, validation rules, and data models (OCPI 2.2.1 · ⭐ 37).

##### PHP

* [mrbig/ocpi-protocol](https://github.com/mrbig/ocpi-protocol) ⭐ 2 | 🐛 2 | 🌐 PHP | 📅 2026-06-09 - A PHP library implementing OCPI v2.2.1 with request/response classes for eMSP and CPO server interfaces and a client SDK for CPO communication (OCPI 2.2.1 · ⭐ 2).

##### Python

* [TECHS-Technological-Solutions/ocpi](https://github.com/TECHS-Technological-Solutions/ocpi) ⭐ 64 | 🐛 12 | 🌐 Python | 📅 2025-12-26 - A Python library implementing the Open Charge Point Interface (OCPI) protocol with data validation and adapter functionality for integrating central system data with OCPI schemas (⭐ 64).
* [elumobility/ocpi-python](https://github.com/elumobility/ocpi-python) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-10-14 - A production-ready Python library implementing the OCPI protocol with FastAPI, supporting versions 2.3.0, 2.2.1, and 2.1.1 with comprehensive modules and Pydantic v2 validation (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 8).
* [evorada/ocpi-types](https://github.com/evorada/ocpi-types) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - Auto-generated OCPI protocol type definitions and language bindings for Go, Python, Rust, and TypeScript (OCPI 2.3.0 · ⭐ 5).

##### Rust

* [evlinked/ocpi-rs](https://github.com/evlinked/ocpi-rs) ⭐ 4 | 🐛 17 | 🌐 Rust | 📅 2026-09-07 - A typed Rust library, async client, and server handler traits for implementing OCPI (Open Charge Point Interface) protocol versions 2.0–2.3.0 with axum web framework integration and CLI tooling (OCPI 2.0, 2.1.1, 2.2.1, 2.3.0 · ⭐ 4).
* [hupe1980/ocpi-kit](https://github.com/hupe1980/ocpi-kit) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - A Rust library toolkit providing OCPI protocol support with wire models for versions 2.1.1–2.3.0, async client, axum server framework, and auditable tariff engine for EV roaming applications (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 1).

##### TypeScript

* [shiv3/gocpi](https://github.com/shiv3/gocpi) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-30 - A Go library implementing OCPI 2.1.1, 2.2.1, and 2.3.0 with typed client and server interfaces, generated from OpenAPI specifications (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 2).

##### Other

* [tandemdrive/ocpi-tariffs](https://codeberg.org/tandemdrive/ocpi-tariffs) - A library for calculating tariffs according to the OCPI (Open Charging Point Interface) specification (⭐ 41).

#### Misc

* [ocpi/ocpi-tool](https://github.com/ocpi/ocpi-tool) ⭐ 33 | 🐛 7 | 🌐 TypeScript | 📅 2026-09-17 - A command-line tool for exporting charging station data from OCPI platforms with privacy-preserving filters and ETL pipeline support (OCPI 2.2.1 · TypeScript · ⭐ 33).
* [solidstudiosh/ocpi-schema](https://github.com/solidstudiosh/ocpi-schema) ⭐ 20 | 🐛 7 | 🌐 TypeScript | 📅 2026-09-28 - A Node.js tool that generates JSON Schema files for OCPI protocol versions 2.1.1 onwards (TypeScript · ⭐ 20).
* [OpenChargingCloud/OCPIExplorerDesktopApp](https://github.com/OpenChargingCloud/OCPIExplorerDesktopApp) ⭐ 5 | 🐛 13 | 🌐 TypeScript | 📅 2026-04-23 - An Electron-based desktop application for testing and certification of OCPI protocol implementations across multiple versions (OCPI 2.1, 2.1.1, 2.2, 2.2.1, 2.3.0 · TypeScript · ⭐ 5).
* [Quentin-BACQUET/GIREVE\_Tech\_OCPI\_V2.1.1](https://github.com/Quentin-BACQUET/GIREVE_Tech_OCPI_V2.1.1) ⭐ 5 | 🐛 1 | 📅 2026-05-13 - OCPI 2.1.1 implementation guide by GIREVE with integration specifications for Charge Point Operators and e-Mobility Service Providers (OCPI 2.1.1 · ⭐ 5).
* [Quentin-BACQUET/GIREVE\_Tech\_OCPI\_V2.2.1](https://github.com/Quentin-BACQUET/GIREVE_Tech_OCPI_V2.2.1) ⭐ 2 | 🐛 1 | 📅 2026-05-12 - OCPI 2.2.1 implementation guide for GIREVE with integration specifications for charge point operators and e-mobility service providers (OCPI 2.2.1 · ⭐ 2).
* [OpenChargingCloud/OCPIExplorerWebApp](https://github.com/OpenChargingCloud/OCPIExplorerWebApp) ⭐ 2 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-14 - A web application for testing and certifying OCPI protocol implementations across multiple versions (OCPI 2.1, 2.1.1, 2.2.1, 2.3.0 · TypeScript · ⭐ 2).
* [juherr/ocpi-fyi](https://github.com/juherr/ocpi-fyi) ⭐ 2 | 🐛 8 | 🌐 JavaScript | 📅 2026-10-18 - Multi-version Antora documentation site for OCPI specifications that mirrors upstream release branches and publishes versioned documentation with search indexing (OCPI 2.1.1, 2.2.1, 2.3.0 · JavaScript · ⭐ 2).
* [olisystems/ocn-registry-v2.0](https://github.com/olisystems/ocn-registry-v2.0) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-29 - Decentralized Ethereum-based smart contracts and CLI for registering and discovering OCPI parties and OCN node operators (TypeScript · ⭐ 1).

### iso15118

#### Plug\&Charge

* [hubject/opcp](https://github.com/hubject/opcp) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2026-04-02 - Open Plug\&Charge Protocol specification for ISO 15118 defining certificate provisioning, authentication services, and PKI architecture for Plug\&Charge interoperability (JavaScript · ⭐ 73).
* [pazzk-labs/evse](https://github.com/pazzk-labs/evse) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2025-11-01 - EVSE firmware implementing ISO 15118 and IEC 61851 standards for electric vehicle charging (C · ⭐ 21).
* [securityinmobility/dc-charging-station](https://github.com/securityinmobility/dc-charging-station) ⭐ 10 | 🐛 5 | 🌐 Python | 📅 2026-09-18 - Software stack for a bidirectional DC charging station implementing ISO 15118 V2G communication and Plug\&Charge support with hardware abstraction for power delivery control (Python · ⭐ 10).

#### Libraries

##### Python

* [uhi22/pyPLC](https://github.com/uhi22/pyPLC) ⭐ 238 | 🐛 7 | 🌐 Python | 📅 2026-10-10 - Python library for ISO 15118 CCS V2G charging communication via powerline network adaptors, supporting charger emulation, vehicle simulation, and traffic sniffing (⭐ 237).

#### Misc

* [SwitchEV/RISE-V2G](https://github.com/SwitchEV/RISE-V2G) ⭐ 260 | 🐛 22 | 🌐 Java | 📅 2025-12-19 - Open source reference implementation of the ISO 15118 Vehicle-to-Grid communication interface standard (Java · ⭐ 260).
* [ecog-io/iso15118](https://github.com/ecog-io/iso15118) ⭐ 248 | 🐛 72 | 🌐 Python | 📅 2026-10-13 - A Python library implementing the ISO 15118-2 and -20 V2G communication protocols for charging stations and electric vehicles (Python · ⭐ 245).
* [uhi22/ccs32clara](https://github.com/uhi22/ccs32clara) ⭐ 115 | 🐛 10 | 🌐 C | 📅 2026-06-22 - STM32 firmware implementing ISO 15118 CCS charging protocol with QCA7005 modem for EV charging (C · ⭐ 113).
* [dspace-group/dsV2Gshark](https://github.com/dspace-group/dsV2Gshark) ⭐ 112 | 🐛 2 | 🌐 C++ | 📅 2026-08-18 - Wireshark plugin for analyzing and decoding ISO 15118 V2G (Vehicle-to-Grid) communication messages between electric vehicles and charging stations, including support for DIN 70121, ISO 15118-2, ISO 15118-20, and Battery Data Exchange protocols (C++ · ⭐ 110).
* [Sevenstax/FreeV2G](https://github.com/Sevenstax/FreeV2G) ⭐ 71 | 🐛 19 | 🌐 Python | 📅 2026-09-23 - Python host application for ISO 15118 charging communication with 8devices WHITE-BEET embedded modules (Python · ⭐ 71).
* [ecog-io/pyslac](https://github.com/ecog-io/pyslac) ⭐ 56 | 🐛 12 | 🌐 Python | 📅 2026-09-03 - Python implementation of the SLAC (Signal Level Attenuation Characterisation) protocol from ISO 15118-3 for EV charging station communication (Python · ⭐ 54).
* [hupe1980/iso15118](https://github.com/hupe1980/iso15118) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-09-13 - A sans-I/O Rust library implementing ISO 15118 vehicle-to-grid communication protocol with support for both vehicle and charging equipment sides (Rust · ⭐ 1).
* [zeloscloud/zelos-extension-v2g](https://github.com/zeloscloud/zelos-extension-v2g) ⭐ 1 | 🐛 6 | 🌐 Python | 📅 2026-10-06 - A Zelos extension that decodes ISO 15118 and DIN 70121 EV-charging protocol messages and SocketCAN frames from packet captures into aligned, queryable traces (Python · ⭐ 1).

### Eichrecht

#### Libraries

##### TypeScript

* [road-labs/ocmf-js](https://github.com/road-labs/ocmf-js) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-25 - TypeScript/JavaScript library that implements signing and verification of OCMF (Open Charge Metering Format) signed meter data (⭐ 3).

#### Misc

* [SAFE-eV/transparenzsoftware](https://github.com/SAFE-eV/transparenzsoftware) ⭐ 34 | 🐛 13 | 🌐 Java | 📅 2025-10-28 - A Java utility for verifying EV charging metering data against German Eichrecht (MID-compliant metrology) standards (Java · ⭐ 34).
* [OpenChargingCloud/ChargyCore.TS](https://github.com/OpenChargingCloud/ChargyCore.TS) ⭐ 2 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-18 - TypeScript library that validates cryptographic signatures and ensures transparency in e-mobility charging processes under German Calibration Law (Eichrecht) and European regulations (TypeScript · ⭐ 2).

### Other

#### Analytics & data

* [openchargemap/ocm-export](https://github.com/openchargemap/ocm-export) ⭐ 47 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-23 - An automated export of Open Charge Map's live charging station POI data, organized by country into individual JSON files with tooling for parsing and refreshing the dataset (JavaScript · ⭐ 47).
* [open-ev-data/open-ev-data-dataset](https://github.com/open-ev-data/open-ev-data-dataset) ⭐ 32 | 🐛 3 | 🌐 JavaScript | 📅 2025-12-30 - A structured, community-maintained dataset of electric vehicle specifications with layered JSON authoring and multi-format output for analysis, comparison, and integration (JavaScript · ⭐ 31).
* [vbalagovic/cars-dataset](https://github.com/vbalagovic/cars-dataset) ⭐ 28 | 🐛 0 | 📅 2026-07-08 - A vehicle specifications database and API covering 54,000+ variants of cars, trucks, and motorcycles with detailed performance, dimensional, and feature data (⭐ 28).
* [appspace/kwwhat](https://github.com/appspace/kwwhat) ⭐ 15 | 🐛 47 | 📅 2026-10-17 - A dbt data pipeline that transforms raw OCPP charging logs into structured models and metrics for EV charging reliability, utilization, and contextual intelligence (⭐ 14).
* [robeertm/ev-charge-tracker](https://github.com/robeertm/ev-charge-tracker) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-10-18 - Self-hosted web dashboard for tracking electric vehicle charging data, costs, emissions, and vehicle status via integration with 15 EV brand manufacturer APIs (Python · ⭐ 12).
* [gaia-charge/evdb](https://github.com/gaia-charge/evdb) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2026-08-14 - Open-source electric vehicle database with specifications, market availability, and manufacturer data, validated with JSON Schema and exposed via SQLite, Datasette, and Streamlit (Python · ⭐ 9).
* [MTES-MCT/qualicharge](https://github.com/MTES-MCT/qualicharge) ⭐ 10 | 🐛 39 | 🌐 Python | 📅 2026-10-16 - QualiCharge is a data analytics platform that collects and analyzes EV charging supervision data to improve service quality, providing APIs and dashboards for operators (Python · ⭐ 10).
* [Jungle-Bus/ref-EU-EVSE](https://github.com/Jungle-Bus/ref-EU-EVSE) ⭐ 4 | 🐛 10 | 🌐 Python | 📅 2026-10-05 - Tool that consolidates, validates, and cleans French EV charging station data from open data sources for OpenStreetMap integration (Python · ⭐ 4).
* [juherr/open-idro-directory](https://github.com/juherr/open-idro-directory) ⭐ 3 | 🐛 37 | 🌐 TypeScript | 📅 2026-10-19 - Open IDRO Directory aggregates, normalizes, validates, and publishes e-mobility identifiers from official national and regional IDRO registries with provenance tracking and API access (TypeScript · ⭐ 3).
* [chaser-d/Green\_Smart\_Grid\_Simulator](https://github.com/chaser-d/Green_Smart_Grid_Simulator) ⭐ 3 | 🐛 0 | 🌐 HTML | 📅 2026-08-06 - A DuckDB and dbt-based ELT data pipeline for ingesting, validating, and aggregating renewable energy telemetry from solar, wind, and hydroelectric grid assets (HTML · ⭐ 3).
* [rajvvv/EV-Infra-Planner](https://github.com/rajvvv/EV-Infra-Planner) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-30 - An interactive geospatial analytics dashboard that forecasts EV adoption and identifies charging infrastructure deployment gaps across Indian cities (JavaScript · ⭐ 2).
* [GuillaumeBraillon/EV-Charge-Tracker](https://github.com/GuillaumeBraillon/EV-Charge-Tracker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-03 - A PWA web application for tracking, analyzing, and estimating electric vehicle charging costs with flexible pricing simulation and subscription management (TypeScript · ⭐ 1).
* [roy429-hub/buima-tracker](https://github.com/roy429-hub/buima-tracker) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-01 - Dashboard for tracking EV charging operations and computing KPIs, revenue, and profit metrics from daily xlsx reports across multiple sites (JavaScript · ⭐ 1).

#### Battery

* [dalathegreat/Battery-Emulator](https://github.com/dalathegreat/Battery-Emulator) ⭐ 2,978 | 🐛 145 | 🌐 C++ | 📅 2026-10-19 - Embedded firmware that enables used EV battery packs to function as stationary energy storage by interfacing with home solar inverters (C++ · ⭐ 2959).
* [mnh-jansson/open-battery-information](https://github.com/mnh-jansson/open-battery-information) ⭐ 1,805 | 🐛 96 | 🌐 C++ | 📅 2026-09-30 - Arduino firmware and web interface for reading battery data and unlocking battery management systems (BMS) for repair purposes (C++ · ⭐ 1797).
* [remontsuri/EV-QA-Framework](https://github.com/remontsuri/EV-QA-Framework) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - Python QA framework for EV batteries with anomaly detection, SOH prediction, thermal runaway early warning, and international compliance testing (Python · ⭐ 9).

#### Charging management system

* [artmakerzbr/ev-tracker](https://github.com/artmakerzbr/ev-tracker) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-15 - A web application for tracking residential EV charging sessions and calculating electricity billing for condominium cost-sharing (JavaScript · ⭐ 1).

#### Developer tools & libraries

* [enbility/eebus-go](https://github.com/enbility/eebus-go) ⭐ 123 | 🐛 40 | 🌐 Go | 📅 2026-09-30 - A Go library implementing the EEBUS protocol (SHIP 1.0.1 and SPINE 1.3.0) for energy management and building automation use cases (Go · ⭐ 123).
* [juherr/mobilityid](https://github.com/juherr/mobilityid) ⭐ 2 | 🐛 21 | 🌐 PHP | 📅 2026-10-18 - Monorepo with the original Scala mobility ID library (contract identifiers) and Java, Go, PHP, and TypeScript ports, published to Maven Central, npm, and Packagist (PHP · ⭐ 2).
* [ChargePi/openev-data-mcp](https://github.com/ChargePi/openev-data-mcp) ⭐ 1 | 🐛 0 | 🌐 PLpgSQL | 📅 2026-10-15 - An MCP server for querying electric vehicle specifications including battery capacity, range, charging power, and drivetrain details from the open-ev-data dataset (PLpgSQL · ⭐ 1).
* [xBlaz3kx/evcc-helm-chart](https://github.com/xBlaz3kx/evcc-helm-chart) ⭐ 0 | 🐛 0 | 🌐 Go Template | 📅 2026-08-02 - Helm chart for deploying EVCC, an open-source EV charging controller, on Kubernetes with SQLite database backup support (Go Template · ⭐ 0).

#### EVSE firmware

* [OpenEVSE/openevse\_esp32\_firmware](https://github.com/OpenEVSE/openevse_esp32_firmware) ⭐ 279 | 🐛 64 | 🌐 C | 📅 2026-10-18 - WiFi gateway firmware for OpenEVSE v6 controllers using ESP32, providing a web UI for local network charging control, energy management, and integration with external systems including OCPP, MQTT, and Emoncms (C · ⭐ 277).
* [dzurikmiroslav/esp32-evse](https://github.com/dzurikmiroslav/esp32-evse) ⭐ 149 | 🐛 20 | 🌐 C | 📅 2026-08-05 - J1772-compliant EVSE firmware for ESP32 microcontrollers with REST API, Modbus support, and web-based management interface (C · ⭐ 148).
* [SCiunczyk/wallbox-diy](https://github.com/SCiunczyk/wallbox-diy) ⭐ 5 | 🐛 1 | 📅 2026-09-16 - DIY WiFi-to-ModBus proxy firmware for ESP32 that enables remote control of a home EV charging wallbox via Home Assistant (⭐ 5).

#### Energy management

* [OpenEMS/openems](https://github.com/OpenEMS/openems) ⭐ 1,594 | 🐛 63 | 🌐 Java | 📅 2026-10-18 - OpenEMS is an open-source, modular energy management platform for integrating and controlling renewable energy sources, storage systems, and devices including electric vehicle charging stations (Java · ⭐ 1584).
* [SolarNetwork/solarnetwork-central](https://github.com/SolarNetwork/solarnetwork-central) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2026-10-16 - SolarNet is a cloud platform for the SolarNetwork ecosystem that manages user and node accounts, accepts energy data from SolarNodes, and provides REST APIs for data access and analysis (Java · ⭐ 7).

#### Home automation

* [leeyuentuen/alfen\_wallbox](https://github.com/leeyuentuen/alfen_wallbox) ⭐ 104 | 🐛 19 | 🌐 Python | 📅 2026-10-06 - A Home Assistant custom component for controlling and monitoring Alfen EV wallboxes through their REST API (Python · ⭐ 104).
* [lachand/EV\_charger](https://github.com/lachand/EV_charger) ⭐ 38 | 🐛 18 | 🌐 Python | 📅 2026-10-16 - A Home Assistant integration that enables local LAN control of Tuya EV chargers without cloud connectivity using `tinytuya` (Python · ⭐ 35).
* [wimhaanstra/com.sortedbits.smartevse](https://github.com/wimhaanstra/com.sortedbits.smartevse) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - A Homey home automation app that connects Smart EVSE-3 EV chargers via MQTT for local network charging control and monitoring (TypeScript · ⭐ 1).

#### Maps & route planning

* [openchargemap/ocm-system](https://github.com/openchargemap/ocm-system) ⭐ 151 | 🐛 47 | 🌐 C# | 📅 2026-10-19 - Open Charge Map is a global public registry and mapping service for electric vehicle charging locations with crowdsourced data and an open API (C# · ⭐ 151).
* [GeiserX/Pumperly](https://github.com/GeiserX/Pumperly) ⭐ 44 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-19 - An open-source route planner combining live fuel prices from 22 countries and EV charging station data with detour-aware corridor filtering (TypeScript · ⭐ 41).

#### Mobile app

* [ev-map/EVMap](https://github.com/ev-map/EVMap) ⭐ 282 | 🐛 52 | 🌐 Kotlin | 📅 2026-10-14 - Android mobile application for locating electric vehicle charging stations with real-time availability information from community-maintained directories such as GoingElectric.de and OpenChargeMap.org (Kotlin · ⭐ 281).
* [powerly-ev/open-ev-charge-android-app](https://github.com/powerly-ev/open-ev-charge-android-app) ⭐ 9 | 🐛 0 | 🌐 Kotlin | 📅 2026-09-06 - White-label Android application template for discovering and managing EV charging sessions with peer-to-peer charger sharing and OCPP/OCPI backend integration (Kotlin · ⭐ 9).
* [EVtivity/evtivity-mobile-app](https://github.com/EVtivity/evtivity-mobile-app) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-16 - White-label React Native/Expo mobile app for EV charging drivers on the EVtivity platform, supporting iOS and Android with native APIs and multiple languages (TypeScript · ⭐ 6).
* [scroodge/VoltFlow](https://github.com/scroodge/VoltFlow) ⭐ 3 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-14 - VoltFlow is a mobile-first PWA for tracking EV charging sessions, vehicle telemetry, trip history, and maintenance records (TypeScript · ⭐ 3).
* [GallardoNr1/evLoggerV2](https://github.com/GallardoNr1/evLoggerV2) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-21 - A web and mobile application for drivers to track and manage electric vehicle charging sessions (TypeScript · ⭐ 1).

#### Other protocols

* [enbility/ship-go](https://github.com/enbility/ship-go) ⭐ 19 | 🐛 32 | 🌐 Go | 📅 2026-10-15 - Go library implementing SHIP 1.0.1 protocol for EEBUS home and building energy management systems (Go · ⭐ 18).
* [enbility/spine-go](https://github.com/enbility/spine-go) ⭐ 10 | 🐛 28 | 🌐 Go | 📅 2026-09-21 - Go library implementing the SPINE 1.3 protocol, part of the EEBUS specification for device energy management (Go · ⭐ 10).
* [hupe1980/openadr](https://github.com/hupe1980/openadr) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-09-14 - An OpenADR 3.1 implementation in Rust providing a VTN server, VEN runtime, and typed client library for demand response and energy management (Rust · ⭐ 1).
* [juherr/datex4j](https://github.com/juherr/datex4j) ⭐ 0 | 🐛 35 | 🌐 Java | 📅 2026-10-16 - Modular Java 21 SDK for reading, writing, validating and converting DATEX II 2.x/3.x publications, including the AFIR energy-infrastructure models and an EV charging domain module (Java · ⭐ 0).

#### Simulators

* [EVtivity/evtivity-ev-tester](https://github.com/EVtivity/evtivity-ev-tester) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2026-09-27 - An open-source SAE J1772 EV-side charging simulator built on ESP32-S3 for testing AC charging stations and CSMS backends (C++ · ⭐ 3).

#### Specifications & documentation

* [chargeprice/chargeprice-api-docs](https://github.com/chargeprice/chargeprice-api-docs) ⭐ 43 | 🐛 3 | 📅 2026-10-12 - API documentation for the proprietary Chargeprice service providing access to EV charging tariffs, charge point operator data, and station information (⭐ 43).
* [SAFE-eV/OCMF-Open-Charge-Metering-Format](https://github.com/SAFE-eV/OCMF-Open-Charge-Metering-Format) ⭐ 32 | 🐛 12 | 📅 2026-10-15 - Open Charge Metering Format (OCMF) specification maintained as markdown for collaborative development within the SAFE Group (⭐ 32).
* [etalab/schema-irve](https://github.com/etalab/schema-irve) ⭐ 13 | 🐛 13 | 🌐 Elixir | 📅 2026-10-12 - TableSchema specification defining French national standards for EV charging infrastructure data, with separate schemas for static (location and technical characteristics) and dynamic (operational status and availability) information (Elixir · ⭐ 12).
* [charinev/unified-error-codes](https://github.com/charinev/unified-error-codes) ⭐ 11 | 🐛 57 | 🌐 Python | 📅 2026-10-06 - Draft specification for standardizing error codes and diagnostics across the EV charging ecosystem (Python · ⭐ 10).
* [ocpi/openapi-specification](https://github.com/ocpi/openapi-specification) ⭐ 4 | 🐛 13 | 🌐 JavaScript | 📅 2026-05-13 - A universal standard for documenting and describing REST APIs in a machine-readable format (JavaScript · ⭐ 4).
* [unified-error-codes/specification](https://github.com/unified-error-codes/specification) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-10-06 - A specification for unified error codes and diagnostics standardization across the EV charging ecosystem, developed by CharIN e.V (Python · ⭐ 4).
* [ChargePi/oecs](https://github.com/ChargePi/oecs) ⭐ 1 | 🐛 1 | 🌐 Go | 📅 2026-10-07 - A vendor-neutral JSON Schema specification for standardized machine-readable descriptions of EV charger functional and technical specifications including hardware, software, payment, and compliance metadata (Go · ⭐ 1).

### Uncategorized

* [vampirebyte/ocpp-gatling-test](https://github.com/vampirebyte/ocpp-gatling-test) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-08-28 (Java · ⭐ 1)

<!-- END GENERATED PROJECTS -->

## Contributing

Contributions are welcome! If you know of a tool or resource that is not on the list, please feel free to add it.

The easiest way to contribute is to [open an issue](https://github.com/juherr/awesome-ev-charging/issues/new/choose) using the "Add a link" template.

You can also submit a pull request. Note that the project listing above is **generated** — descriptions and categories are edited in `classifications.csv`, not by hand in this file. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full workflow.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-19._
