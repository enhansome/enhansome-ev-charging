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

<!-- END GENERATED TOC -->

[![ev roaming protocols](img/ev-roaming-protocols.jpg)](https://www.emobilitysimplified.com/2020/08/ev-roaming-protocol-differences-OCPI-OICP-OCHP-eMIP.html)

## Specifications

### OCPP (Open Charge Point Protocol)

The **Open Charge Point Protocol (OCPP)** is a communication protocol between electric vehicle charging stations and a central management system.

* [Configuration Keys (1.6)](https://github.com/juherr/awesome-ev-charging/blob/main/ocpp/OCPP-1.6-configuration-keys.md) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 - Reference table of OCPP 1.6 configuration keys.
* [Wikipedia](https://en.wikipedia.org/wiki/Open_Charge_Point_Protocol)
* [Open Charge Aliance](https://www.openchargealliance.org/)
* Specifications
  * [2.1](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-2.1) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 (2025-01)
  * [2.0.1](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-2.0.1) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 (2020-04)
  * [2.0 (deprecated)](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-2.0) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 (2018)
  * [1.6](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-1.6-Documentation_2019_12) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 (2015)
  * [1.6 - Security Whitepaper Ed3](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/Whitepapers/OCPP-1.6-security-whitepaper-edition-3-2) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16
  * [1.x - Multiple Connectors per EVSE](https://github.com/juherr/awesome-ev-charging/blob/main/ocpp/Whitepapers/ocpp_1_x_multiple_connectors_per_evse.pdf) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16
  * [1.5 (deprecated)](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-1.5) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 (2012)
  * [1.2 (deprecated)](https://github.com/juherr/awesome-ev-charging/tree/main/ocpp/OCPP-1.2) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 (2010)

### ISO 15118

**ISO 15118** is an international standard for communication between electric vehicles and the charging station.

* [Wikipedia](https://en.wikipedia.org/wiki/ISO_15118)
* [iso.org](https://www.iso.org/search.html?PROD_isoorg_en%5Bquery%5D=15118\&PROD_isoorg_en%5Bmenu%5D%5Bfacet%5D=standard)

### OCPI (Open Charge Point Interface)

The **Open Charge Point Interface (OCPI)** is a protocol for roaming between charging station networks.

* [EVRoaming Fundation](https://evroaming.org/)

* [Specifications on GitHub](https://github.com/ocpi/ocpi) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17
  * [2.3.0-d2](https://github.com/ocpi/ocpi/releases/download/v2.3.0-ed2/OCPI-2.3.0-ed2.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2026-06)
  * [2.3.0](https://evroaming.org/wp-content/uploads/2025/02/OCPI-2.3.0.pdf) (2025-02)
  * [2.2.1](https://github.com/ocpi/ocpi/releases/download/2.2.1/OCPI-2.2.1.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2021-10)
  * [2.2.0-d2](https://github.com/ocpi/ocpi/releases/download/2.2-d2/OCPI-2.2-d2.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 - Deprecated, use 2.2.1 instead (2020-06)
  * [2.2.0](https://github.com/ocpi/ocpi/releases/download/2.2/OCPI-2.2.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 - Deprecated, use 2.2.0-d2 instead (2019-09)
  * [2.1.1-d2](https://github.com/ocpi/ocpi/releases/download/2.1.1-d2/OCPI_2.1.1-d2.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2019-06)
  * [2.1.1](https://github.com/ocpi/ocpi/releases/download/2.1.1/OCPI_2.1.1.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 - Deprecated, use 2.1.1-d2 instead (2017-06)
  * 2.1.0 - Deprecated, contains some bugs, use 2.1.1 instead (2016-04)
  * [2.0](https://github.com/ocpi/ocpi/files/135934/OCPI_2.0-d2.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2016-02)

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

OCPI 2.3.0 is published as a [core specification](https://github.com/ocpi/ocpi/tree/2.3.0/release/core) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 plus optional modules packaged separately.

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

* Booking (2.3.0) — exact version labels are still being settled; the OCPI editors deferred on this in [ocpi/ocpi#572](https://github.com/ocpi/ocpi/issues/572) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17
  * [ed1](https://github.com/ocpi/ocpi/releases/download/v2.3.0-bookings/OCPI-2.3.0-bookings.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2026-06, tag `v2.3.0-bookings`)
  * ed2 — not yet released
  * [1.1](https://evroaming.org/wp-content/uploads/2026/01/OCPI-2.3.0-booking-1.1.pdf) (2025-06, no GitHub tag)
* Payments (2.3.0)
  * [ed2](https://github.com/ocpi/ocpi/releases/download/v2.3.0-ed2-payments/OCPI-2.3.0-ed2-payments.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2026-06, core edition 2 + Payments)
  * [ed1](https://github.com/ocpi/ocpi/releases/download/v2.3.0-payments/OCPI-2.3.0-payments.pdf) ⭐ 587 | 🐛 140 | 🌐 Perl | 📅 2026-07-17 (2026-06, core edition 1 + Payments)

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
    * [Part 1 v1.1](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.1/eMI3-standard-v1.1-Part-1.pdf) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16
    * [Terms and definitions v1.4](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.1/eMI3-standard-TermsAndDefinitions-v1.4.pdf) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16
  * eMi³ standard version V1.0 electric vehicle ICT interface specifications (2019-10)
    * [Part 1 v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-v1.0-Part-1.pdf) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16
    * [Part 2 v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-v1.0-Part-2.pdf) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16
    * [Terms and definitions v1.0](https://github.com/juherr/awesome-ev-charging/blob/main/emi3/emi3-1.0/eMI3-standard-TermsAndDefinitions-v1.0.pdf) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16

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

* [steve-community/steve](https://github.com/steve-community/steve) ⭐ 1,104 | 🐛 92 | 🌐 Java | 📅 2026-08-19 - A Java-based OCPP server implementation providing charging station management with support for OCPP 1.2-1.6, security extensions, and certificate management (OCPP 1.2, 1.5, 1.6 · Java · ⭐ 1089).
* [dallmann-consulting/OCPP.Core](https://github.com/dallmann-consulting/OCPP.Core) ⭐ 303 | 🐛 11 | 🌐 C# | 📅 2026-06-09 - OCPP.Core is a .NET OCPP server with a web UI for managing charge points, connectors, RFID tokens, transactions, and supported OCPP messages (OCPP 1.6, 2.0 · C# · ⭐ 300).
* [citrineos/citrineos-core](https://github.com/citrineos/citrineos-core) ⭐ 279 | 🐛 47 | 🌐 TypeScript | 📅 2026-08-18 - An open-source OCPP 1.6 and 2.0.1 charging station management server built in TypeScript with a web-based operator UI (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 268).
* [citrineos/citrineos](https://github.com/citrineos/citrineos) ⭐ 144 | 🐛 10 | 📅 2026-02-10 - CitrineOS is an open source OCPP 2.0.1 Charging Station Management System software stack with modular services for handling charging station communication and CSMS functions (OCPP 2.0.1 · ⭐ 143).
* [apostoldevel/ocpp-cs](https://github.com/apostoldevel/ocpp-cs) ⭐ 76 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - C++20 OCPP central system with a web UI, REST API, schema validation, and built-in charge point emulators for OCPP 1.5, 1.6, and 2.0.1 (OCPP 1.5, 1.6, 2.0.1 · C++ · ⭐ 76).
* [EVtivity/evtivity-csms](https://github.com/EVtivity/evtivity-csms) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-25 - EVtivity CSMS is a TypeScript charging station management system that manages EV charging infrastructure through OCPP 1.6/2.1 station communication, OCPI roaming, ISO 15118 Plug and Charge, REST APIs, and operator/driver web frontends (OCPP 1.6, 2.1 · TypeScript · ⭐ 20).
* [gertjana/ocpp-backend](https://github.com/gertjana/ocpp-backend) ⭐ 23 | 🐛 0 | 🌐 Elixir | 📅 2025-11-11 - An Elixir/Cowboy backend server for OCPP 1.6 charge point operations with limited OCPP 2.0 heartbeat support, a dashboard, and an API for sending charger commands (OCPP 1.6, 2.0 · Elixir · ⭐ 23).
* [ocpp-balanz/ocpp-2w-proxy](https://github.com/ocpp-balanz/ocpp-2w-proxy) ⭐ 16 | 🐛 6 | 🌐 Python | 📅 2026-02-22 - Ocpp-2w-proxy is a Python OCPP proxy that forwards charger traffic between one or more chargers and two central management systems with primary/secondary routing rules (Python · ⭐ 16).
* [savekar-ev/OCPP-1.6-Charging-Point-Management-System](https://github.com/savekar-ev/OCPP-1.6-Charging-Point-Management-System) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-10 - A full-stack OCPP 1.6 JSON Charge Point Management System for managing EV chargers through a WebSocket server, REST API, admin interface, and PostgreSQL backend (OCPP 1.6 · TypeScript · ⭐ 12).
* [OpenChargingCloud/CSMS](https://github.com/OpenChargingCloud/CSMS) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2025-11-19 - An example OCPP 1.6 Central System and OCPP 2.1/2.0.1 Charging Station Management System for testing EV charging infrastructure (OCPP 1.6, 2.1 · C# · ⭐ 8).
* [smartenergycontrol-be/ocpp-proxy](https://github.com/smartenergycontrol-be/ocpp-proxy) ⭐ 5 | 🐛 5 | 🌐 Python | 📅 2025-09-29 - A Home Assistant OCPP proxy that shares one EV charger across multiple backend services with OCPP 1.6/2.0.1 support and control arbitration (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 5).
* [parklapp/steve-pluggable](https://github.com/parklapp/steve-pluggable) ⭐ 4 | 🐛 11 | 🌐 Java | 📅 2026-04-09 - SteVe Pluggable is a Java/Spring Boot OCPP server library for managing charge points, users, RFID authentication, and ESP backend integration (OCPP 1.2, 1.5, 1.6 · Java · ⭐ 4).
* [Beep-Technologies/esteban-ocpp](https://github.com/Beep-Technologies/esteban-ocpp) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-05-15 - Esteban-OCPP is a Go OCPP server for administering charge points and users, exposing REST APIs, and running EV charging deployments in cloud or edge environments (OCPP 2.0 · Go · ⭐ 4).
* [juherr/evolve](https://github.com/juherr/evolve) ⭐ 4 | 🐛 18 | 🌐 Java | 📅 2026-08-19 - EVolve - OCPP server implementation in Java (Java · ⭐ 4).
* [eveys-mobility/OCPP](https://github.com/eveys-mobility/OCPP) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - An OCPP-J 1.6/2.0.1 CSMS gateway that manages EV charging station WebSocket connections and exposes REST, gRPC, and Kafka event interfaces (OCPP 1.6 · Python · ⭐ 3).
* [erik73/app-steve](https://github.com/erik73/app-steve) ⭐ 3 | 🐛 2 | 🌐 Dockerfile | 📅 2026-08-12 - SteVe OCPP charging server packaged as a Home Assistant add-on for communication with charge points (Dockerfile · ⭐ 3).
* [FlipSoftware/moovolt-csms](https://github.com/FlipSoftware/moovolt-csms) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-11-04 - Moov.olt is a Rust-based OCPP central system for managing EV chargers through a charging point service and a management server connected via AMQP (Rust · ⭐ 3).
* [eliodecolli/Medinilla](https://github.com/eliodecolli/Medinilla) ⭐ 3 | 🐛 3 | 🌐 C# | 📅 2026-08-13 - Medinilla is an ASP.NET Core CSMS backend implementing selected OCPP messages for managing EV charging station connections and transactions (OCPP 2.0.1 · C# · ⭐ 3).
* [markrpo/ocppws](https://github.com/markrpo/ocppws) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2025-09-01 - C++ implementation of an OCPP server over WebSockets with support for core charge point messages (C++ · ⭐ 2).
* [elton-saraci/ocpp-central-system](https://github.com/elton-saraci/ocpp-central-system) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2026-08-02 - Spring Boot OCPP 1.6 central system for managing EV charge stations over WebSockets with transaction handling, status monitoring, remote commands, and REST APIs (OCPP 1.6 · Java · ⭐ 2).
* [wimhaanstra/virtual-ocpp](https://github.com/wimhaanstra/virtual-ocpp) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-28 - A self-hosted OCPP 1.6j service that manages Smart EVSE chargers, records charging sessions, proxies OCPP traffic, and includes an integrated charger simulator (OCPP 1.6 · TypeScript · ⭐ 2).
* [alexeimoisseev/ocpp-server-typescript](https://github.com/alexeimoisseev/ocpp-server-typescript) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-12 - A minimal TypeScript OCPP WebSocket server for learning, testing chargers, and running simulators with support for OCPP 1.6J and 2.0.1 core charging flows (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 1).
* [amolsurjuse/ocpp-service](https://github.com/amolsurjuse/ocpp-service) ⭐ 1 | 🐛 12 | 🌐 Java | 📅 2026-08-15 - Production-ready Spring Boot OCPP server (CSMS) microservice for managing charging station WebSocket connections, message routing, and remote commands (OCPP 2.0.1 · Java · ⭐ 1).
* [juherr/steve-ocpp-csms-image](https://github.com/juherr/steve-ocpp-csms-image) ⭐ 1 | 🐛 2 | 🌐 Shell | 📅 2026-08-14 - Pre-built Docker images for SteVe, the open-source OCPP Central System (CSMS), compiled at build time for fast startup with automated database migrations (Shell · ⭐ 1).
* [flowionab/ocpp-csms-server](https://github.com/flowionab/ocpp-csms-server) - OCPP CSMS Server is a Rust-based central system for managing EV charge points over OCPP 1.6 and 2.0.1 with WebSocket communication and authentication (Rust · ⭐ 5).

#### Simulator

* [SAP/e-mobility-charging-stations-simulator](https://github.com/SAP/e-mobility-charging-stations-simulator) ⭐ 222 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-19 - Node.js simulator for OCPP-J charging stations that enables load testing and scaling validation (OCPP 1.6, 2.0, 2.0.1 · TypeScript · ⭐ 220).
* [monta-app/ocpp-emulator](https://github.com/monta-app/ocpp-emulator) ⭐ 177 | 🐛 8 | 🌐 Kotlin | 📅 2026-08-16 - A desktop emulator for OCPP 1.6 and 2.0.1 charge points built with Kotlin Multiplatform and Jetbrains Compose, featuring message interception and testing capabilities (OCPP 1.6, 2.0.1 · Kotlin · ⭐ 172).
* [solidstudiosh/ocpp-virtual-charge-point](https://github.com/solidstudiosh/ocpp-virtual-charge-point) ⭐ 117 | 🐛 21 | 🌐 TypeScript | 📅 2026-08-12 - A Node.js terminal-based simulator for OCPP 1.6 and 2.0.1 charging stations with configurable WebSocket connection settings and schema validation (OCPP 1.6, 2.0.1 · TypeScript · ⭐ 114).
* [OpenChargingCloud/ChargingStationApp](https://github.com/OpenChargingCloud/ChargingStationApp) ⭐ 41 | 🐛 12 | 🌐 TypeScript | 📅 2026-04-03 - Electron-based virtual EV charging station for testing OCPP charging station protocols and related extensions (OCPP 1.6, 2.0.1, 2.1 · TypeScript · ⭐ 41).
* [shiv3/ocpp-cp-simulator](https://github.com/shiv3/ocpp-cp-simulator) ⭐ 39 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-17 - OCPP 1.6J charge point simulator for AI agent testing, CI automation, and CSMS development with browser UI, CLI, and Socket.IO control API (OCPP 1.2, 1.5, 1.6 · TypeScript · ⭐ 38).
* [ozgurbayram/OCPPSimulator](https://github.com/ozgurbayram/OCPPSimulator) ⭐ 27 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-19 - A web-based OCPP 1.6 simulator for creating simulated EV charge points, connecting them to a CSMS, sending OCPP messages, and monitoring charging communication (OCPP 1.6 · TypeScript · ⭐ 26).
* [virta-ltd/charge-device-simulator](https://github.com/virta-ltd/charge-device-simulator) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-08-13 - Python-based device simulator framework for EV charging protocols including OCPP and Ensto, packaged for Docker-based execution (Python · ⭐ 21).
* [road-labs/chargestation-one](https://github.com/road-labs/chargestation-one) ⭐ 17 | 🐛 2 | 🌐 Less | 📅 2026-07-31 - A browser-based charging station simulator supporting OCPP 1.6 and OCPP 2.0.1 that can connect to OCPP backends and simulate transactions with custom messages and meter data signing (OCPP 1.6, 2.0.1, 2.1 · Less · ⭐ 17).
* [c-jimenez/open-ocpp-simu](https://github.com/c-jimenez/open-ocpp-simu) ⭐ 16 | 🐛 4 | 🌐 C++ | 📅 2026-04-15 - Open OCPP simulator provides an MQTT-based environment for launching, managing, monitoring, and configuring simulated OCPP charge points that connect to a central system (C++ · ⭐ 16).
* [kwtycoon/kilowatt-tycoon](https://github.com/kwtycoon/kilowatt-tycoon) ⭐ 7 | 🐛 8 | 🌐 Rust | 📅 2026-07-10 - A tycoon game and full-stack EV charging network simulator that implements OCPP 1.6J, OCPI 2.3.0, and OpenADR 3.0 protocols in Rust/Bevy (OCPP 1.6 · Rust · ⭐ 7).
* [PlugSecure-Inc/ocpp-simulator-lab](https://github.com/PlugSecure-Inc/ocpp-simulator-lab) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-06-17 - OCPP Simulator Lab is a Python/FastAPI and Vue web tool that simulates OCPP charge points and CPMS endpoints for testing OCPP 1.6J, 2.0.1, and 2.1 behavior (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 6).
* [vfg27/EmuOCPP](https://github.com/vfg27/EmuOCPP) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2026-03-22 - EmuOCPP is a Mininet/IPMininet-based OCPP emulator for simulating EV charging stations and central systems across OCPP 1.6, 2.0, and 2.0.1 with security profiles and certificate tooling (OCPP 1.6, 2.0, 2.0.1 · Python · ⭐ 5).
* [ZhongRuoyu/ocppsim](https://github.com/ZhongRuoyu/ocppsim) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-17 - A terminal-based OCPP-J charge point simulator written in Rust that connects to a CSMS, maintains local state for connectors and transactions, and emits protocol-shaped OCPP messages for testing and protocol development (OCPP 1.6, 2.0.1, 2.1 · Rust · ⭐ 4).
* [ReliON-Charging/everest-dcfc](https://github.com/ReliON-Charging/everest-dcfc) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2026-02-24 - A multi-architecture Docker container for running an EVerest-based virtual DC fast charger with configurable OCPP versions, connectors, smart charging, and a Node-RED simulation dashboard (OCPP 1.6, 2.0.1 · C++ · ⭐ 4).
* [wirelane/ocpp-client-simulator](https://github.com/wirelane/ocpp-client-simulator) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-05 - A Node.js command-line simulator for an OCPP 1.6 JSON/WebSocket charging station that connects to an OCPP server and exercises scenarios such as RFID authorization, remote start/stop, connectors, and signed meter values (OCPP 1.6 · JavaScript · ⭐ 3).
* [hlsxx/ocpp-charge-point-simulator](https://github.com/hlsxx/ocpp-charge-point-simulator) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-05-22 - A Rust CLI simulator for testing OCPP 1.6 backends by emulating configurable charge points in automated or idle modes (OCPP 1.6, 2.0.1 · Rust · ⭐ 2).
* [I-Love-OCPP/Charge-Point-Simulator](https://github.com/I-Love-OCPP/Charge-Point-Simulator) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-03 - A React + TypeScript + Vite web framework for simulating EVSE (charging point) operations (TypeScript · ⭐ 1).
* [LastProject-ESIEE/dummy-chargepoint](https://github.com/LastProject-ESIEE/dummy-chargepoint) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2025-08-26 - A Java command-line OCPP chargepoint emulator for manual protocol testing and chargepoint configuration via REST API (Java · ⭐ 1).

#### Libraries

##### C

* [pazzk-labs/ocpp](https://github.com/pazzk-labs/ocpp) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2025-11-06 - C implementation of an OCPP client with configurable build-time settings and example usage (⭐ 9).
* [tux-evse/afb-ocpp-ext](https://github.com/tux-evse/afb-ocpp-ext) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-11-25 - Libafb extension that adds OCPP 1.6 and 2.0.1 transport support for AFB micro-services (OCPP 1.6 · ⭐ 2).

##### C\#

* [OpenChargingCloud/WWCP\_OCPP](https://github.com/OpenChargingCloud/WWCP_OCPP) ⭐ 71 | 🐛 9 | 🌐 C# | 📅 2026-08-11 - A library for building OCPP (Open Charge Point Protocol) servers and gateways between OCPP and WWCP (World Wide Charging Protocol) supporting OCPP v1.6, v2.0.1, and v2.1 (OCPP 1.5, 1.6, 2.0.1, 2.1 · ⭐ 70).

##### C++

* [matth-x/MicroOcpp](https://github.com/matth-x/MicroOcpp) ⭐ 535 | 🐛 130 | 🌐 C++ | 📅 2025-12-04 - MicroOCPP is a portable C/C++ OCPP 1.6 and 2.0.1 client library for integrating microcontroller-based EV chargers with OCPP central systems (OCPP 1.6, 2.0.1 · ⭐ 529).
* [c-jimenez/open-ocpp](https://github.com/c-jimenez/open-ocpp) ⭐ 171 | 🐛 9 | 🌐 C++ | 📅 2026-04-13 - Open OCPP is a C++17 library implementing the WebSocket/JSON variants of OCPP 1.6 and OCPP 2.0.1 (OCPP 1.6, 2.0.1 · ⭐ 171).
* [ChargeLab/OpenOCPP](https://github.com/ChargeLab/OpenOCPP) ⭐ 82 | 🐛 1 | 🌐 C++ | 📅 2025-11-03 - OpenOCPP is multi-platform embedded software implementing OCPP 1.6 and 2.0.1 for EV charging stations (OCPP 1.6 · ⭐ 81).

##### Go

* [lorenzodonini/ocpp-go](https://github.com/lorenzodonini/ocpp-go) ⭐ 369 | 🐛 122 | 🌐 Go | 📅 2025-08-24 - Go library for implementing OCPP-J central systems and charge point clients with support for OCPP 1.6, 1.6 Security, and 2.0.1 (OCPP 1.6, 2.0.1 · ⭐ 367).
* [aliml92/ocpp](https://github.com/aliml92/ocpp) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2026-08-12 - A Go library implementing JSON OCPP 1.6 and 2.0.1 with server and charge point client support (OCPP 1.6, 2.0.1 · ⭐ 28).
* [ChargePi/ocpp-manager](https://github.com/ChargePi/ocpp-manager) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2026-04-19 - A Go library for managing and validating OCPP configuration variables, including defaults, mandatory keys, custom validators, and versioned configurations (OCPP 1.6, 2.0.1 · ⭐ 6).
* [shiv3/gocpp](https://github.com/shiv3/gocpp) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-06-18 - Gocpp is a Go library for building typed OCPP 1.6, 2.0.1, and 2.1 CSMS servers and charge point clients with schema validation and pluggable storage, authentication, and observability (OCPP 1.6, 2.0.1, 2.1 · ⭐ 5).
* [aasanchez/ocpp16messages](https://github.com/aasanchez/ocpp16messages) ⭐ 2 | 🐛 3 | 🌐 Go | 📅 2026-07-24 - A type-safe Go library implementing OCPP 1.6 message types with validation for building EV charging station management systems and charge point implementations (OCPP 1.6 · ⭐ 2).

##### Java

* [ChargeTimeEU/Java-OCA-OCPP](https://github.com/ChargeTimeEU/Java-OCA-OCPP) ⭐ 375 | 🐛 15 | 🌐 Java | 📅 2026-06-19 - Java-OCA-OCPP is a Java library for implementing OCPP Central Systems and Charge Points with OCPP 1.6 JSON/SOAP and OCPP 2.x support (OCPP 1.6, 2.0.1, 2.1 · ⭐ 373).

##### JavaScript

* [mikuso/ocpp-rpc](https://github.com/mikuso/ocpp-rpc) ⭐ 135 | 🐛 14 | 🌐 JavaScript | 📅 2026-08-19 - A Node.js library implementing the WAMP-like RPC-over-WebSocket system for OCPP-J protocols (OCPP 1.6J, 2.0.1J, 2.1) (OCPP 1.6, 2.0.1, 2.1 · ⭐ 132).
* [argonne-vci/node-red-contrib-ocpp](https://github.com/argonne-vci/node-red-contrib-ocpp) ⭐ 37 | 🐛 27 | 🌐 JavaScript | 📅 2026-06-05 - Node-RED nodes for communicating with OCPP 1.5 and 1.6 EV charge points and central systems over SOAP and JSON (OCPP 1.5, 1.6 · ⭐ 37).
* [ampeco/cpd-ocpp](https://github.com/ampeco/cpd-ocpp) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-22 - Node.js library providing an abstraction layer and validation for OCPP 1.6 JSON protocol with server and client implementations (OCPP 2.0 · ⭐ 3).

##### Kotlin

* [IZIVIA/ocpp-toolkit](https://github.com/IZIVIA/ocpp-toolkit) ⭐ 45 | 🐛 7 | 🌐 Kotlin | 📅 2026-07-07 - A Kotlin library providing OCPP protocol implementation for both Charging Station and CSMS roles, supporting versions 1.5, 1.6, and 2.0.1 with WS/JSON and SOAP transport (OCPP 1.5, 1.6, 2.0 · ⭐ 45).
* [monta-app/library-ocpp](https://github.com/monta-app/library-ocpp) ⭐ 6 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-14 - A Kotlin library for parsing and handling OCPP v1.6 and v2.0.1 messages, supporting both charge point and server roles with blocking and asynchronous interfaces (OCPP 1.6 · ⭐ 6).
* [I-Love-OCPP/sdk-1.6j](https://github.com/I-Love-OCPP/sdk-1.6j) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-02 - Kotlin SDK providing OCPP 1.6 JSON protocol message handling and dispatcher for implementing an OCPP Central System (OCPP 1.6 · ⭐ 1).

##### Python

* [mobilityhouse/ocpp](https://github.com/mobilityhouse/ocpp) ⭐ 1,031 | 🐛 16 | 🌐 Python | 📅 2026-07-19 - Python library implementing the Open Charge Point Protocol (OCPP) 1.6 and 2.0.1 in JSON format (OCPP 1.6, 2.0.1 · ⭐ 1024).

##### Rust

* [tommymalmqvist/rust-ocpp](https://github.com/tommymalmqvist/rust-ocpp) ⭐ 102 | 🐛 11 | 🌐 Rust | 📅 2026-06-08 - Rust-ocpp is a Rust library implementing OCPP 1.6, 2.0.1, and work-in-progress 2.1 data models validated against official JSON schemas (OCPP 1.6, 2.0.1, 2.1 · ⭐ 100).
* [flowionab/ocpp-client](https://github.com/flowionab/ocpp-client) ⭐ 5 | 🐛 2 | 🌐 Rust | 📅 2026-08-13 - Ocpp-client is a Rust library for implementing OCPP 1.6 and 2.0.1 client communication with CSMS servers (OCPP 1.6 · ⭐ 4).
* [evlinked/ocpp-rs](https://github.com/evlinked/ocpp-rs) ⭐ 4 | 🐛 10 | 🌐 Rust | 📅 2026-08-18 - A production-grade Rust library implementing OCPP 1.6J and 2.0.1 with integrated CSMS server and Charge Point simulator for conformance testing and observability (OCPP 1.6, 2.0.1 · ⭐ 4).

##### TypeScript

* [voltbras/ts-ocpp](https://github.com/voltbras/ts-ocpp) ⭐ 49 | 🐛 6 | 🌐 TypeScript | 📅 2026-01-20 - TypeScript library for implementing OCPP central systems and charge points with support for OCPP-JSON 1.6 and OCPP-SOAP 1.5 (⭐ 49).
* [jacoscaz/typed-ocpp](https://github.com/jacoscaz/typed-ocpp) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-08 - A TypeScript library for type-aware validation of OCPP 1.6, 2.0, and 2.1 messages against official JSON schemas (OCPP 1.6, 2.0, 2.1 · ⭐ 9).
* [connected-hil/ocpp-tools](https://github.com/connected-hil/ocpp-tools) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-31 - A TypeScript library providing OCPP 1.6J and 2.0.1 message types, RPC utilities, parsers, and schema-based validation (OCPP 1.6, 2.0.1, 2.1 · ⭐ 7).

#### Misc

* [lbbrhzn/ocpp](https://github.com/lbbrhzn/ocpp) ⭐ 389 | 🐛 29 | 🌐 Python | 📅 2026-08-14 - A Home Assistant custom integration that enables communication with OCPP 1.6j/2.0.1/2.1-compatible electric vehicle chargers (Python · ⭐ 382).
* [EVerest/EVerest](https://github.com/EVerest/EVerest) ⭐ 247 | 🐛 279 | 🌐 C++ | 📅 2026-08-19 - EVerest is an open-source modular software framework for building full-stack EV charging infrastructure supporting OCPP 1.6/2.0.1/2.1 and ISO 15118 (OCPP 1.6, 2.0.1, 2.1 · C++ · ⭐ 232).
* [vfg27/CheckOCPP](https://github.com/vfg27/CheckOCPP) ⭐ 13 | 🐛 1 | 🌐 Lua | 📅 2026-03-22 - CheckOCPP is a Wireshark Lua dissector that detects OCPP JSON traffic versions and validates captured messages against protocol schemas for passive compliance auditing (OCPP 1.6, 2.0, 2.0.1 · Lua · ⭐ 12).
* [joulo-nl/joulo-ocpp-proxy](https://github.com/joulo-nl/joulo-ocpp-proxy) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-17 - A lightweight WebSocket proxy for OCPP that forwards charger connections to a primary CSMS and optionally mirrors messages to secondary backends (OCPP 1.6, 2.0, 2.0.1 · TypeScript · ⭐ 10).
* [gyzod/ocpp2mqtt](https://github.com/gyzod/ocpp2mqtt) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - An OCPP 1.6 to MQTT gateway that bridges charging stations with home automation systems through protocol translation (OCPP 1.6 · Python · ⭐ 10).
* [vampirebyte/rabbitmq-web-ocpp](https://github.com/vampirebyte/rabbitmq-web-ocpp) ⭐ 10 | 🐛 0 | 🌐 Erlang | 📅 2026-08-17 - A RabbitMQ plugin that translates OCPP-over-WebSocket charge point messages to native AMQP protocol, enabling scalable distributed backend processing for EV charging networks (Erlang · ⭐ 10).
* [powerly-ev/open-ev-charge-android-app](https://github.com/powerly-ev/open-ev-charge-android-app) ⭐ 8 | 🐛 0 | 🌐 Kotlin | 📅 2026-06-26 - Powerly Open EV Charge Android App is a white-label Kotlin mobile app for discovering chargers, managing EV charging sessions, bookings, billing, roaming, and peer-to-peer charger sharing through the Powerly platform (Kotlin · ⭐ 7).
* [unified-error-codes/csds](https://github.com/unified-error-codes/csds) ⭐ 7 | 🐛 16 | 🌐 Python | 📅 2026-04-30 - UEC Software Stack provides backend, UI, and EVSE-agent components for charging station diagnostics using unified error codes and telemetry retrieved via OCPP (Python · ⭐ 6).
* [ocpp-debugkit/toolkit](https://github.com/ocpp-debugkit/toolkit) ⭐ 5 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-10 - A developer toolkit for debugging and analyzing OCPP charging session traces with trace inspection, failure detection, scenario testing, event replay, and report generation (TypeScript · ⭐ 4).
* [EVtivity/evtivity-mobile-app](https://github.com/EVtivity/evtivity-mobile-app) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-20 - Native iOS and Android driver app for the EVtivity EV charging platform that connects to its REST API for branded driver portal functionality (TypeScript · ⭐ 4).
* [chargex-consortium/ev-charge-seq-state](https://github.com/chargex-consortium/ev-charge-seq-state) ⭐ 4 | 🐛 0 | 📅 2026-06-02 - Open-source UML sequence diagrams and finite-state machine models for SAE J1772, ISO 15118, and OCPP EV charging protocol flows (OCPP 1.6, 2.0.1, 2.1 · ⭐ 4).
* [sepehr-safari/ocpp-handbook](https://github.com/sepehr-safari/ocpp-handbook) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-15 - An open-source course and handbook on EV charging software fundamentals, covering industry context, hardware, protocols (OCPP, OCPI, ISO 15118), and debugging techniques (OCPP 1.6, 2.0.1 · ⭐ 2).
* [OpenChargingTechnology/Whitepapers](https://github.com/OpenChargingTechnology/Whitepapers) ⭐ 2 | 🐛 1 | 📅 2026-08-19 - A collection of open EV infrastructure ICT whitepapers covering cybersecurity, interoperability, OCPP, OCPI, OICP, ISO 15118, EV roaming, OpenADR, and related protocols (OCPP 1.6, 2.1 · ⭐ 2).
* [eliodecolli/ocpp-test-cases](https://github.com/eliodecolli/ocpp-test-cases) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-03-20 - AI-generated test cases for base OCPP 2.0.1 implementations, with scripts and prompts used to extract protocol text and generate additional cases (OCPP 2.0.1 · Python · ⭐ 1).
* [OpenChargingTechnology/OCPP-SBOM](https://github.com/OpenChargingTechnology/OCPP-SBOM) ⭐ 1 | 🐛 0 | 📅 2025-12-05 - OCPP-SBOM provides CycloneDX and SPDX SBOM definitions for OCPP specification release bundles, including PDFs, appendices, schemas, metadata, and hashes for verification and compliance (OCPP 2.1 · ⭐ 1).
* [xBlaz3kx/evcc-helm-chart](https://github.com/xBlaz3kx/evcc-helm-chart) ⭐ 0 | 🐛 0 | 🌐 Go Template | 📅 2026-08-02 - Helm chart for deploying EVCC, an EV charging controller, on Kubernetes with configurable services and SQLite backups (Go Template · ⭐ 0).

#### Charge Point

* [SmartEVSE/SmartEVSE-3](https://github.com/SmartEVSE/SmartEVSE-3) ⭐ 225 | 🐛 12 | 🌐 C | 📅 2026-08-18 - SmartEVSE v3 is open-source firmware and hardware for an EVSE charge controller with smart load balancing, Modbus/RS485 metering, WiFi, MQTT/REST APIs, and OCPP 1.6J support (OCPP 1.6 · C · ⭐ 222).
* [ChargePi/ChargePi-go](https://github.com/ChargePi/ChargePi-go) ⭐ 52 | 🐛 15 | 🌐 Go | 📅 2026-08-02 - ChargePi-go is Linux-based charge point software that abstracts EV charging station hardware and provides OCPP support, a management UI, and an API (OCPP 1.6, 2.0.1, 2.1 · Go · ⭐ 52).

#### Debugger

* [ocpp-debugkit/studio](https://github.com/ocpp-debugkit/studio) ⭐ 3 | 🐛 4 | 🌐 Zig | 📅 2026-07-30 - A native desktop debugger for OCPP charging sessions that captures and analyzes WebSocket traffic between charge points and backend systems with live protocol validation (OCPP 1.6 · Zig · ⭐ 3).

#### Documentation

* [alexeimoisseev/ocpp.md](https://github.com/alexeimoisseev/ocpp.md) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2026-07-12 - A structured OCPP (2.1, 2.0.1, 1.6J) knowledge base with field-level message schemas, sequence diagrams, and decision markers designed as context for AI agents developing EV charging systems (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 23).

#### Proxy

* [openchargehub/ocpp-proxy](https://github.com/openchargehub/ocpp-proxy) ⭐ 19 | 🐛 11 | 🌐 Python | 📅 2025-10-27 - A Home Assistant add-on that proxies a single OCPP 1.6 or 2.0.1 EV charger connection to multiple backend services with arbitration, monitoring, and safety controls (OCPP 1.6, 2.0.1, 2.1 · Python · ⭐ 16).

#### Specification

* [open-ocpp-trace/specification](https://github.com/open-ocpp-trace/specification) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-22 - A machine-readable JSON/JSONL trace format specification and schema for recording OCPP message exchanges between charging stations and management systems, with conformance validation and reference fixtures (JavaScript · ⭐ 3).

#### Test Suite

* [tzi-app/tzi-OCTT](https://github.com/tzi-app/tzi-OCTT) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-03-05 - A Python pytest-based OCTT test suite for verifying CSMS implementations against OCPP 2.0.1 and OCPP 1.6J (OCPP 1.6, 2.0.1 · Python · ⭐ 11).

### OCPI

#### Server

* [citrineos/citrineos-ocpi](https://github.com/citrineos/citrineos-ocpi) ⭐ 21 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-12 - CitrineOS OCPI is a TypeScript/Node.js OCPI 2.2.1 CPO (Charge Point Operator) server implementation providing registration, sessions, CDRs, tariffs, and locations endpoints integrated with CitrineOS Core via GraphQL (OCPI 2.2.1 · TypeScript · ⭐ 21).
* [olisystems/ocn-node-v2](https://github.com/olisystems/ocn-node-v2) ⭐ 1 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-18 - A Kotlin/Spring Boot OCPI broker node that routes traffic between parties and integrates with the Open Charging Network Registry (OCPI 2.2 · Kotlin · ⭐ 1).

#### Simulator

* [savekar-ev/OCPI-2.2.1-EMSP-Simulator](https://github.com/savekar-ev/OCPI-2.2.1-EMSP-Simulator) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-05-07 - A Python OCPI 2.2.1 EMSP simulator for testing CPO backend compliance, credentials exchange, data synchronization, sessions, commands, and CDR submissions (OCPI 2.2.1 · Python · ⭐ 10).
* [OpenChargingCloud/OCPIExplorerDesktopApp](https://github.com/OpenChargingCloud/OCPIExplorerDesktopApp) ⭐ 5 | 🐛 13 | 🌐 TypeScript | 📅 2026-04-23 - OCPI Explorer DesktopApp is an Electron desktop application for testing and certification of OCPI protocol implementations and vendor extensions across multiple OCPI versions (OCPI 2.1, 2.1.1, 2.2, 2.2.1, 2.3.0 · TypeScript · ⭐ 5).
* [rally-finance/ocpi-mock-hub](https://github.com/rally-finance/ocpi-mock-hub) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-04-22 - A Go-based mock OCPI 2.2.1 hub server for developing and testing eMSP/CPO OCPI integrations without a live partner (OCPI 2.2.1 · Go · ⭐ 4).

#### Libraries

##### C\#

* [OpenChargingCloud/WWCP\_OCPI](https://github.com/OpenChargingCloud/WWCP_OCPI) ⭐ 29 | 🐛 1 | 🌐 C# | 📅 2026-08-17 - An OCPI protocol library supporting versions 2.1 through 3.0 with extensions for WWCP integration, GDPR compliance, and regulatory requirements (Eichrecht, AFIR, UK Public Charge Point Regulations) (OCPI 2.0, 2.1, 2.1.1, 2.2, 2.2.1, 2.3.0 · ⭐ 29).
* [BitzArt/OCPI.Net](https://github.com/BitzArt/OCPI.Net) ⭐ 27 | 🐛 5 | 🌐 C# | 📅 2026-08-01 - OCPI.Net is a C#/.NET library implementing the Open Charge Point Interface for EV charging roaming (⭐ 27).

##### Java

* [steve-community/ocpi-models](https://github.com/steve-community/ocpi-models) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2026-08-18 - A Java library providing data models, Spring MVC API mappings, and RestTemplate clients for OCPI 2.2.1 (OCPI 2.2.1 · ⭐ 2).

##### Kotlin

* [IZIVIA/ocpi-toolkit](https://github.com/IZIVIA/ocpi-toolkit) ⭐ 35 | 🐛 15 | 🌐 Kotlin | 📅 2026-08-05 - A Kotlin library implementing the OCPI 2.2.1 protocol standard for electric vehicle charging infrastructure communication with framework-agnostic transport and persistence abstraction (OCPI 2.2.1 · ⭐ 35).

##### PHP

* [mrbig/ocpi-protocol](https://github.com/mrbig/ocpi-protocol) ⭐ 2 | 🐛 1 | 🌐 PHP | 📅 2026-06-09 - PHP library providing OCPI 2.2.1 request/response classes, models, factories, errors, and client helpers for eMSP and CPO integrations using PSR-compatible HTTP interfaces (OCPI 2.2.1 · ⭐ 2).
* [juherr/mobilityid](https://github.com/juherr/mobilityid) ⭐ 2 | 🐛 20 | 🌐 PHP | 📅 2026-08-15 - Multi-language library implementing mobility ID abstractions for e-mobility and EV charging networks (Scala, Java, Go, PHP, TypeScript) (⭐ 2).

##### Python

* [TECHS-Technological-Solutions/ocpi](https://github.com/TECHS-Technological-Solutions/ocpi) ⭐ 63 | 🐛 12 | 🌐 Python | 📅 2025-12-26 - Py-ocpi is a Python library implementing OCPI with schemas, CRUD integration, and adapters for connecting central-system data to the protocol (⭐ 63).
* [elumobility/ocpi-python](https://github.com/elumobility/ocpi-python) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - OCPI Python is a FastAPI and Pydantic v2 implementation of the OCPI protocol supporting versions 2.3.0, 2.2.1, and 2.1.1 for CPO, EMSP, and PTP roles (OCPI 2.2.1, 2.3.0 · ⭐ 7).
* [evorada/ocpi-types](https://github.com/evorada/ocpi-types) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - Ocpi-types provides auto-generated OCPI protocol type definitions for Go, Python, Rust, and TypeScript across multiple OCPI versions (OCPI 2.3.0 · ⭐ 5).

##### Rust

* [evlinked/ocpi-rs](https://github.com/evlinked/ocpi-rs) ⭐ 4 | 🐛 17 | 🌐 Rust | 📅 2026-08-03 - A Rust library providing typed models, async client, and server traits for implementing the OCPI (Open Charge Point Interface) protocol across all versions from 2.0 to 2.3.0 (OCPI 2.0, 2.1.1, 2.2.1, 2.3.0 · ⭐ 3).

##### TypeScript

* [shiv3/gocpi](https://github.com/shiv3/gocpi) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-30 - Gocpi is a Go library that provides generated typed OCPI clients, server handlers, validation, transport semantics, and pricing utilities for OCPI 2.1.1, 2.2.1, and 2.3.0 e-mobility roaming (OCPI 2.1.1, 2.2.1, 2.3.0 · ⭐ 1).

##### Other

* [tandemdrive/ocpi-tariffs](https://codeberg.org/tandemdrive/ocpi-tariffs) - A project for calculating tariffs according to OCPI (⭐ 41).

#### Misc

* [ocpi/ocpi-tool](https://github.com/ocpi/ocpi-tool) ⭐ 32 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-06 - A Node.js command-line tool for extracting and exporting data from OCPI platforms to enable secure ETL pipelines (OCPI 2.2.1 · TypeScript · ⭐ 32).
* [Quentin-BACQUET/GIREVE\_Tech\_OCPI\_V2.1.1](https://github.com/Quentin-BACQUET/GIREVE_Tech_OCPI_V2.1.1) ⭐ 5 | 🐛 1 | 📅 2026-05-13 - GIREVE OCPI V2.1.1 is an implementation guide for integrating CPO and eMSP systems with GIREVE’s IOP OCPI 2.1.1 roaming interface (OCPI 2.1.1 · ⭐ 5).
* [Quentin-BACQUET/GIREVE\_Tech\_OCPI\_V2.2.1](https://github.com/Quentin-BACQUET/GIREVE_Tech_OCPI_V2.2.1) ⭐ 2 | 🐛 1 | 📅 2026-05-12 - GIREVE OCPI V2.2.1 is documentation for implementing GIREVE’s IOP hub interface, including OCPI integration guidelines for CPO and eMSP roaming workflows (OCPI 2.2.1 · ⭐ 2).
* [OpenChargingCloud/OCPIExplorerWebApp](https://github.com/OpenChargingCloud/OCPIExplorerWebApp) ⭐ 2 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-14 - A web application for exploring, testing, and certification support of OCPI protocol implementations and vendor extensions (OCPI 2.1, 2.1.1, 2.2.1, 2.3.0 · TypeScript · ⭐ 2).
* [olisystems/ocn-registry-v2.0](https://github.com/olisystems/ocn-registry-v2.0) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-20 - Ethereum-based smart contract registry and CLI tool for decentralized management and discovery of Open Charging Network (OCN) node operators and OCPI parties (TypeScript · ⭐ 1).

#### Specification

* [juherr/ocpi-fyi](https://github.com/juherr/ocpi-fyi) ⭐ 2 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-05 - A multi-version Antora documentation site that mirrors and publishes official OCPI specifications with version switching and search (OCPI 2.1.1, 2.2.1, 2.3.0 · JavaScript · ⭐ 2).

### iso15118

#### Plug\&Charge

* [SwitchEV/RISE-V2G](https://github.com/SwitchEV/RISE-V2G) ⭐ 259 | 🐛 22 | 🌐 Java | 📅 2025-12-19 - RISE V2G is an open-source reference implementation of the ISO 15118 vehicle-to-grid communication interface between EVs and charging stations, including Plug & Charge and load control support (Java · ⭐ 259).
* [hubject/opcp](https://github.com/hubject/opcp) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2026-04-02 - Open Plug\&Charge Protocol is an open protocol specification for creating, transferring, signing, and interoperating Plug\&Charge certificate and contract information based on ISO 15118 (JavaScript · ⭐ 73).
* [charinev/opnc](https://github.com/charinev/opnc) ⭐ 25 | 🐛 19 | 🌐 JavaScript | 📅 2025-08-14 - OPNC is an open-source protocol specification for trusted Plug\&Charge communication and PKI ecosystem interoperability in EV charging, covering related ISO 15118 functions (JavaScript · ⭐ 25).

#### Misc

* [EcoG-io/iso15118](https://github.com/EcoG-io/iso15118) ⭐ 242 | 🐛 78 | 🌐 Python | 📅 2026-08-14 - Python implementation of the ISO 15118-2, ISO 15118-20, and ISO 15118-8 communication protocols with SECC and EVCC components (Python · ⭐ 242).
* [uhi22/pyPLC](https://github.com/uhi22/pyPLC) ⭐ 232 | 🐛 7 | 🌐 Python | 📅 2026-05-22 - Python tools for experimenting with CCS charging communication, including PLC traffic sniffing and EVSE/PEV modes for ISO 15118/DIN 70121 workflows (Python · ⭐ 227).
* [uhi22/ccs32clara](https://github.com/uhi22/ccs32clara) ⭐ 111 | 🐛 10 | 🌐 C | 📅 2026-06-22 - Embedded STM32 firmware for a CCS charge controller that communicates with a QCA7005 HomePlug Green PHY modem to control EV charging (C · ⭐ 107).
* [dspace-group/dsV2Gshark](https://github.com/dspace-group/dsV2Gshark) ⭐ 103 | 🐛 2 | 🌐 C++ | 📅 2026-08-18 - DsV2Gshark is a Wireshark plugin for decoding and analyzing ISO 15118, DIN 70121, and related V2G communication between EVs and charging stations (C++ · ⭐ 102).

### Eichrecht

#### Misc

* [SAFE-eV/transparenzsoftware](https://github.com/SAFE-eV/transparenzsoftware) ⭐ 34 | 🐛 13 | 🌐 Java | 📅 2025-10-28 - Transparenzsoftware is a Java CLI and Swing application for verifying OCMF metrology measurement data from EV charging station meters for MID and German Eichrecht compliance (Java · ⭐ 34).

#### OCMF Libraries

* [road-labs/ocmf-js](https://github.com/road-labs/ocmf-js) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-31 - TypeScript/JavaScript library for signing, parsing, and verifying Open Charge Metering Format signed meter data (TypeScript · ⭐ 3).

### Other

* [leeyuentuen/alfen\_wallbox](https://github.com/leeyuentuen/alfen_wallbox) ⭐ 101 | 🐛 18 | 🌐 Python | 📅 2026-04-11 - A Home Assistant custom integration for monitoring and controlling Alfen wallboxes (Python · ⭐ 101).
* [open-ev-data/open-ev-data-dataset](https://github.com/open-ev-data/open-ev-data-dataset) ⭐ 29 | 🐛 3 | 🌐 JavaScript | 📅 2025-12-30 - OpenEV Data Dataset is a versioned open dataset of electric vehicle specifications authored as layered JSON and compiled into canonical records for analysis and integration (JavaScript · ⭐ 27).
* [ChargePi/openev-data-mcp](https://github.com/ChargePi/openev-data-mcp) ⭐ 1 | 🐛 0 | 🌐 PLpgSQL | 📅 2026-05-07 - An MCP server that exposes the open-ev-data electric vehicle specifications dataset as JSON resources backed by PostgreSQL (PLpgSQL · ⭐ 1).

#### API Specification

* [ocpi/openapi-specification](https://github.com/ocpi/openapi-specification) ⭐ 4 | 🐛 13 | 🌐 JavaScript | 📅 2026-05-13 - This project provides an OpenAPI specification for EV charging-related APIs (JavaScript · ⭐ 4).

#### Analytics

* [appspace/kwwhat](https://github.com/appspace/kwwhat) ⭐ 14 | 🐛 49 | 📅 2026-08-18 - A dbt data pipeline that transforms OCPP logs into structured models for EV charging analytics, reliability, and utilization metrics (⭐ 14).
* [MTES-MCT/qualicharge](https://github.com/MTES-MCT/qualicharge) ⭐ 10 | 🐛 39 | 🌐 Python | 📅 2026-08-17 - QualiCharge is a data analytics platform for analyzing EV charging infrastructure supervision data to assess and improve charging service quality (Python · ⭐ 10).

#### App

* [ev-map/EVMap](https://github.com/ev-map/EVMap) ⭐ 274 | 🐛 50 | 🌐 Kotlin | 📅 2026-08-03 - Android mobile application for discovering and mapping EV charging stations with real-time availability, search, filtering, and navigation features (Kotlin · ⭐ 268).

#### Battery

* [dalathegreat/Battery-Emulator](https://github.com/dalathegreat/Battery-Emulator) ⭐ 2,883 | 🐛 139 | 🌐 C++ | 📅 2026-08-18 - Embedded firmware that translates between end-of-life EV battery packs and home solar inverters to enable repurposing batteries for stationary energy storage (C++ · ⭐ 2824).
* [mnh-jansson/open-battery-information](https://github.com/mnh-jansson/open-battery-information) ⭐ 1,665 | 🐛 84 | 🌐 C++ | 📅 2026-08-15 - Open Battery Information provides Arduino and Python/Windows tools and battery data to help inspect and repair locked battery management systems (C++ · ⭐ 1588).
* [remontsuri/EV-QA-Framework](https://github.com/remontsuri/EV-QA-Framework) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - ML-powered Python framework for EV battery health monitoring, anomaly detection, SOH prediction, and compliance testing with CAN bus support (Python · ⭐ 7).

#### Charge Management

* [evcc-io/evcc](https://github.com/evcc-io/evcc) ⭐ 7,093 | 🐛 132 | 🌐 Go | 📅 2026-08-19 - Evcc is an extensible open-source home energy management system that orchestrates EV charging with solar production via OCPP, EEBus, and 100+ charger integrations (Go · ⭐ 7019).

#### Charger Controller

* [OpenEVSE/openevse\_esp32\_firmware](https://github.com/OpenEVSE/openevse_esp32_firmware) ⭐ 228 | 🐛 198 | 🌐 C | 📅 2026-08-18 - ESP32-based WiFi gateway for OpenEVSE chargers with web dashboard, OCPP 1.6-J integration, solar divert, and energy management (C · ⭐ 228).
* [lachand/EV\_charger](https://github.com/lachand/EV_charger) ⭐ 18 | 🐛 4 | 🌐 Python | 📅 2026-08-14 - Home Assistant integration providing local LAN control of Tuya EV chargers without cloud connectivity (Python · ⭐ 11).

#### Charging location registry/API

* [openchargemap/ocm-system](https://github.com/openchargemap/ocm-system) ⭐ 146 | 🐛 48 | 🌐 C# | 📅 2026-08-11 - Open Charge Map is a backend, website, API, and import-processing system for maintaining and serving an open global registry of EV charging locations (C# · ⭐ 145).

#### Data Platform

* [chargeprice/chargeprice-api-docs](https://github.com/chargeprice/chargeprice-api-docs) ⭐ 43 | 🐛 3 | 📅 2026-08-17 - Documentation and API reference for Chargeprice, a proprietary platform providing EV charging tariffs, charging stations, operators, and market data with optional OCPI compatibility (⭐ 43).

#### Data Tool

* [Jungle-Bus/ref-EU-EVSE](https://github.com/Jungle-Bus/ref-EU-EVSE) ⭐ 4 | 🐛 10 | 🌐 Python | 📅 2026-08-14 - A data processing tool that consolidates, validates, and standardizes French open data about EV charging stations for integration into OpenStreetMap (Python · ⭐ 4).

#### Dataset

* [vbalagovic/cars-dataset](https://github.com/vbalagovic/cars-dataset) ⭐ 24 | 🐛 0 | 📅 2026-07-08 - CarsDataset is a global automotive specifications database and REST API providing technical specs, performance data, and market prices for 54,000+ vehicle variants (cars, trucks, motorcycles) across 370+ brands from 1898–2026 (⭐ 24).

#### EEBUS

* [enbility/eebus-go](https://github.com/enbility/eebus-go) ⭐ 119 | 🐛 42 | 🌐 Go | 📅 2026-07-31 - Go library implementing EEBUS/SHIP/SPINE protocols for device communication and energy management systems (Go · ⭐ 117).

#### EVSE firmware

* [dzurikmiroslav/esp32-evse](https://github.com/dzurikmiroslav/esp32-evse) ⭐ 144 | 🐛 18 | 🌐 C | 📅 2026-08-05 - ESP32 EVSE is J1772 charging station firmware with web control, OTA updates, metering, REST, Modbus, scripting, and hardware abstraction (C · ⭐ 141).

#### Energy management

* [OpenEMS/openems](https://github.com/OpenEMS/openems) ⭐ 1,523 | 🐛 36 | 🌐 Java | 📅 2026-08-19 - OpenEMS is an open-source, modular energy management platform with distributed Edge and cloud Backend components for monitoring, controlling, and integrating renewable energy, storage, and EV charging (Java · ⭐ 1479).
* [SolarNetwork/solarnetwork-central](https://github.com/SolarNetwork/solarnetwork-central) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2026-08-19 - A cloud platform for the SolarNetwork system that manages user accounts, provisions IoT nodes, and provides REST APIs for accessing energy monitoring data from distributed nodes (Java · ⭐ 7).

#### Home Automation

* [wimhaanstra/com.sortedbits.smartevse](https://github.com/wimhaanstra/com.sortedbits.smartevse) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - A Homey home automation app that integrates Smart EVSE-3 EV chargers via MQTT for local monitoring and control of charging operations (TypeScript · ⭐ 1).

#### Libraries

##### Java

* [juherr/datex4j](https://github.com/juherr/datex4j) ⭐ 0 | 🐛 32 | 🌐 Java | 📅 2026-08-14 - A modular Java SDK for the DATEX II European transportation standard that reads, writes, validates, and converts DATEX II publications with optional domain modules for traffic, parking, and EV charging (⭐ 0).

#### Maps & route planning

* [GeiserX/Pumperly](https://github.com/GeiserX/Pumperly) ⭐ 31 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-17 - An open-source route planner combining real-time fuel prices and EV charging station data with detour-aware corridor filtering across 36 countries (TypeScript · ⭐ 25).

#### Open Data

* [openchargemap/ocm-export](https://github.com/openchargemap/ocm-export) ⭐ 47 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-23 - Ocm-export exports live Open Charge Map EV charging POI data into per-country, per-POI JSON files for granular change tracking and reuse (JavaScript · ⭐ 47).

#### RTOS

* [zephyrproject-rtos/zephyr](https://github.com/zephyrproject-rtos/zephyr) ⭐ 16,254 | 🐛 3,941 | 🌐 C | 📅 2026-08-19 - Zephyr is a scalable, real-time operating system (RTOS) for resource-constrained embedded devices and IoT systems supporting multiple hardware architectures (C · ⭐ 16044).

#### Registry

* [juherr/open-idro-directory](https://github.com/juherr/open-idro-directory) ⭐ 2 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-17 - Open IDRO Directory aggregates, normalizes, validates, and publishes e-mobility identifiers from national and regional registries with preserved provenance and API access (TypeScript · ⭐ 2).

#### Specification

* [SAFE-eV/OCMF-Open-Charge-Metering-Format](https://github.com/SAFE-eV/OCMF-Open-Charge-Metering-Format) ⭐ 32 | 🐛 13 | 📅 2026-07-20 - The Open Charge Metering Format (OCMF) specification for EV charging metering data, maintained collaboratively as markdown within the SAFE Group (⭐ 32).
* [etalab/schema-irve](https://github.com/etalab/schema-irve) ⭐ 12 | 🐛 23 | 🌐 Elixir | 📅 2026-07-27 - TableSchema specification for standardizing static and dynamic data (location, technical specifications, operational status, availability) of French EV charging infrastructure (Elixir · ⭐ 12).
* [charinev/unified-error-codes](https://github.com/charinev/unified-error-codes) ⭐ 9 | 🐛 37 | 🌐 Python | 📅 2026-08-07 - A draft specification standardizing error codes and diagnostics across the entire EV charging ecosystem, developed by CharIN e.V.'s Charging Communication Subgroup (Python · ⭐ 9).
* [unified-error-codes/specification](https://github.com/unified-error-codes/specification) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-18 - Specification for unified error codes to standardize error reporting and diagnostics across the EV charging ecosystem, developed by CharIN (Python · ⭐ 4).

<!-- END GENERATED PROJECTS -->

## Contributing

Contributions are welcome! If you know of a tool or resource that is not on the list, please feel free to add it.

The easiest way to contribute is to [open an issue](https://github.com/juherr/awesome-ev-charging/issues/new/choose) ⭐ 161 | 🐛 4 | 🌐 Python | 📅 2026-08-16 using the "Add a link" template.

You can also submit a pull request. Note that the project listing above is **generated** — descriptions and categories are edited in `classifications.csv`, not by hand in this file. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full workflow.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
