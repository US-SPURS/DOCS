# United States Department of Special Projects and Unified Response Services (US-SPURS)

## Enterprise Documentation Overview

US-SPURS is organized as an independent federal agency model focused on unified response, infrastructure modernization, defense and public-safety support, health and human services, education, housing stabilization, advanced technology, logistics, energy resilience, and strategic operations.

This repository provides the enterprise documentation baseline for internal teams, partners, developers, mission planners, and future contributors.

## Mission

US-SPURS exists to improve safety, stability, resilience, capability, and quality of life through coordinated response systems, infrastructure development, public service, advanced technology, and long-term operational support.

## Organizational Model

US-SPURS uses centralized strategic authority with distributed operational execution.

The consolidated structure consists of:

- **Division 0 / 0000 — Headquarters, US-SPURS**
- **13 operating divisions**
- regional offices
- state and territorial offices
- international offices, liaison elements, and temporary mission units where required

### Executive Direction

The Director is the head of US-SPURS and holds agency-wide responsibility for strategic direction, mission authorization, executive oversight, and institutional accountability.

**Current Director:** Philip A. Cotton Jr.

Additional executive offices, chiefs, boards, councils, and program offices may be established through formal appointment, directive, charter, or reorganization order. Proposed offices are not treated as permanent organizational elements unless formally documented.

## Headquarters

### Division 0 / 0000 — Headquarters, US-SPURS

Headquarters provides:

- strategic direction and mission authorization
- policy, doctrine, legal review, and accountability
- enterprise finance, workforce, procurement, and administration
- national, regional, state, territorial, and international coordination
- technology, security, data, infrastructure, and operational standards
- oversight of joint and unified-response missions
- continuity of operations and continuity planning

**Principal headquarters:**

1000 Patriot Way  
Joint Force Base Freedom Island, California 94500

## Operating Divisions

### Division 1 / 1000 — Unified Response and Emergency Management

All-hazards preparedness, emergency management, disaster response, incident coordination, stabilization, recovery support, and interagency response operations.

### Division 2 / 2000 — Infrastructure, Engineering, and Public Works

Critical infrastructure planning, construction, restoration, modernization, public works, utilities, remediation, and resilient systems engineering.

### Division 3 / 3000 — Defense, Military Support, and Operational Readiness

Military-support functions, defense support to civil authorities, readiness, mobilization, engineering support, logistics integration, and assigned military personnel coordination.

### Division 4 / 4000 — Law Enforcement, Investigations, and Public Safety

Law enforcement, investigations, protective services, inspections, public-safety support, fraud and misconduct investigations, and emergency enforcement coordination.

### Division 5 / 5000 — Health, Medical, and Human Services

Medical, dental, vision, behavioral-health, public-health, emergency healthcare, veteran, family, disability, and direct human-services programs.

### Division 6 / 6000 — Education, Training, and Workforce Development

United States Academy programs, K–12 education, adult diploma programs, vocational and college education, youth programs, tuition support, credentialing, and workforce development.

### Division 7 / 7000 — Housing, Homelessness, and Community Stabilization

Emergency and transitional housing, homelessness response, shelter, sanitation, relocation assistance, neighborhood recovery, and community stabilization.

### Division 8 / 8000 — Science, Research, Technology, and Artificial Intelligence

ATLANTIS AI Multi-AI System, SWARM modules, advanced computing, research, software, automation, robotics, cybersecurity, data systems, and technology transition.

### Division 9 / 9000 — Space, Aviation, Maritime, and Advanced Mobility

Space partnerships, aviation, airfield operations, maritime systems, shipyard development, unmanned systems, advanced mobility, and related infrastructure.

### Division 10 / 10000 — Energy, Environment, and Climate Resilience

Microgrids, advanced energy, environmental cleanup, remediation, endangered-species coordination, climate adaptation, and resilient power systems.

### Division 11 / 11000 — Logistics, Procurement, Supply Chain, and Fleet

Procurement, contracting support, warehousing, transportation, fleet, fuel, equipment, emergency supply chains, asset management, and field sustainment.

### Division 12 / 12000 — Finance, Administration, and Enterprise Services

Budgeting, accounting, financial controls, human resources, payroll, benefits, records, internal services, facilities support, and enterprise administration.

### Division 13 / 13000 — Strategic Affairs, Intergovernmental Coordination, and Global Operations

Strategic projects, intergovernmental relations, regional and state-office oversight, external partnerships, international coordination, and cross-division global operations.

## Geographic Command Structure

### Priority Order

Unless superseded by a lawful emergency directive or mission-specific order, agency priorities are evaluated in this order:

1. Alameda County
2. California
3. United States
4. United States territories and allies
5. Earth
6. The Great Beyond

### Geographic Layers

- Headquarters
- Regional offices
- State and territorial offices
- International offices, liaison elements, project teams, or temporary mission units

## Mission Coordination Models

US-SPURS missions may use:

- **Single-division command** for focused missions
- **Joint mission command** for cross-division operations
- **Unified command** with federal, state, tribal, territorial, local, military, nonprofit, private-sector, or international partners

Headquarters retains strategic oversight, resolves cross-division conflicts, authorizes exceptional actions, and maintains agency-wide accountability.

## Technology Architecture

US-SPURS uses a layered architecture built for real-world operations.

### Key Systems

- **ATLANTIS AI Multi-AI System** for orchestration, routing, situational awareness, and decision support
- **SWARM** as an integrated ATLANTIS coordination module
- distributed, cloud, edge, on-premises, and mobile computing
- resilient communications and network infrastructure
- data integration, analytics, and operational intelligence
- automation, robotics, and autonomous operational support
- policy, identity, security, and trust-boundary controls

## Infrastructure Footprint

The organizational infrastructure model includes:

- Joint Force Base Freedom Island headquarters and development programs
- regional operations centers
- state and territorial satellite offices
- mobile command and deployment units
- engineering, research, training, and innovation campuses
- airfield, shipyard, space-center, healthcare, energy, and public-works infrastructure

## Documentation Set

The enterprise documentation lives in the `spurs/` directory.

### Enterprise Overview

- `spurs/index.mdx` — agency overview and documentation map
- `spurs/organization.mdx` — corrected Headquarters and 13-division structure
- `spurs/missions.mdx` — operational domains and programs
- `spurs/infrastructure.mdx` — facilities, deployment footprint, and partnerships

### Technology & Engineering

- `spurs/technology.mdx` — ATLANTIS AI, computing, data, and innovation
- `spurs/architecture.mdx` — systems architecture and integration layers
- `spurs/integrations.mdx` — APIs, events, MCP, identity, and interoperability
- `spurs/engineering-standards.mdx` — production, security, reliability, and quality standards

### Operations & Delivery

- `spurs/deployment-playbooks.mdx` — deployment, validation, rollback, incidents, and recovery
- `spurs/architecture-decisions.mdx` — architecture decision process and governance
- `docs/adr/0000-template.md` — reusable Architecture Decision Record template

### Governance & Contribution

- `spurs/governance.mdx` — doctrine, authority, and accountability
- `spurs/developer-onboarding.mdx` — contributor orientation and workflow
- `CONTRIBUTING.md` — contribution and review requirements
- `SECURITY.md` — vulnerability reporting and security expectations

### GitHub Workflow Support

- `.github/PULL_REQUEST_TEMPLATE.md`
- `.github/ISSUE_TEMPLATE/documentation-change.yml`
- `.github/ISSUE_TEMPLATE/architecture-proposal.yml`
- `.github/ISSUE_TEMPLATE/operational-request.yml`

## Local Documentation Development

Install the Mintlify CLI:

```bash
npm install -g mint
```

Run the local documentation site from the repository root:

```bash
mint dev
```

## Status

This documentation is a living enterprise baseline. Formal establishment, renaming, consolidation, or dissolution of divisions, executive offices, regional commands, state offices, and subordinate programs should be documented through an approved directive, charter, reorganization order, or controlling policy.

## Closing Statement

US-SPURS is designed as an integrated, scalable, technology-enabled organization capable of coordinating public service, emergency response, infrastructure, research, readiness, and long-term stabilization across local, national, and global missions.
