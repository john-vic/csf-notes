
Cyber Security Fundamentals Notes
=================================

Introduction
------------

> - CSF Notes, written to read like an abreviated/simplified Student Guide.  
   I try to rewrite some things in layman's terms, but IT and the DoD is a deadly combo; sometimes trying to rewrite the acronym soup they whip up is like trying to unscramble an egg.
   
   

> - Editing this File
>   - If you'd like to download and edit this file to help with note-taking, it's written in Markdown, which is a document formatting language.  
      It may look intimidating if you're not familiar with coding or markup note-taking, but it's actually pretty easy, and you'll be able to spot how the raw file relates to the formatted view pretty quickly.  
      If you're interested, [this cheat sheet](https://www.markdownguide.org/cheat-sheet/) has all the syntax listed in an easy-to-search format.

> - **Footstomps**
>   - **Bold** items are footstomped notes.
>       - If reading the raw .md file, **Bold** items have \*\*Double Asterisks\*\*.
>   - Footstomped notes may be a definition or the entire item. If I only marked the term, it's probably the latter.

> - \$\$\$
>   - Lines marked with '$' are incomplete notes.
>   - If you're taking notes in Markdown (like editing this file), don't repeat \$s without putting a \\backslash before each one or you'll get a parsing error.

Content
-------

> - **Insights**

> - **B1 - Governance**
>    - L1 - The Nature of Cyberspace
>    - L2 - Strategy, Law, & Guidance
>    - L3 - Organizational Structure

> - **B2 - Terrain**
>    - L1 - DoD Information Network (DoDIN) Architecture
>    - L2 - **(Not Tested)** - Over the Horizon: Defining the Future Enterprise

> - **B3 - Security**
>    - L1 - Threat Landscape
>    - L2 - Threat Analysis
>    - L3 - Threat Intelligence

> - **B4 - Operation**
>    - L1 - Cyberspace Missions
>    - L2 - Enterprise Management
>    - L3 - Cyberspace Weapon Systems

> - **B5 - Crew Operations**
>    - L1 - Cybercrew Operator Training
>    - L2 - Cybercrew Force Management
>    - L3 - Cybercrew Documentation Requirements
>    - L4 - Cyber Mission Planning & "Rules of Engagement" (ROEs)

---

<br>

Insights
--------

> - **Block 4**
>   - Big one to memorize
>   - **L1**
>       - Remember how legacy and new corelate
>       - \______ is how we defend against specific threats
>   - **L2**
>       - Know the difference between change & configuration management.
>   - **L3**
>       - Situational awareness = C3MS
>       - Gateway + Weapon system = AFINC
>       - 616 OC = C3MS

> - **Block 5**
>   - Joint Planning Process = 5-O???

> - 561st Tools
>   - MECM
>   - ARAD
>   - ACAS

---

<br>

B1 - Governance
---------------

### L1 - The Nature of Cyberspace
> - JP-312
>   - Describes the cyberspace environment and operations.

> - Cyberspace 3-Layer Model
>   - Physical
>       - Tangible layer
>   - Logical
>       - Expandable cyberspace platform
>   - Cyber-Persona
>       - Information used to identify or authenticate an individual or group

> - Key Terrain in Cyberspace (KT-C)
>   - A portion of cyberspace which access or control of affords a position of marked advantage.

> - Cyberspace Battleground
>   - **Blue** Cyberspace
>       - AF-Controlled Terrain
>   - **Red** Cyberspace
>       - Adversary-Controlled Terrain
>   - **Grey** Cyberspace
>       - Neutral Terrain - Not Controlled by AF or Adversary

> - Control of Cyberspace
>   - ***Parity***
>       - A condition in which no force has control of cyberspace.
>   - ***Superiority***
>       - A degree of ***dominance*** in cyberspace that permits the secure, reliable conduct of operations.
>   - ***Supremacy***
>       - A degree of cyberspace control renders an adversary incapable of effective interference.

> - In, Through, & External Operations
>   - In
>       - Typically offensive & defensive, denying an adversary's use of resources
>   - Through
>       - Routine operations that conducts joint functions.
>   - External
>       - Physical blockers like damage or a power outage.

> - Cyberspace Vulnerabilities
>   - Dependence on cyberspace is a vulnerability.

> - Assessment of Cyberspace Operations
>   - Strategic-level
>       - Top-level command, planning ahead.
>   - Operational-level
>       - Mid-level management, current operations.
>   - Tactical-level
>       - Ground-level planning.


### L2 - Strategy, Law, & Guidance
> - Strategic Guidance
>   - Command Strategies
>       - Focused on command's specific capabilities.
>       - Link Strategic Guidance to theater, strategies, & joint operations.

> - Key Strategic Guidance/Direction
>   - National Security Strategy **(NSS)**
>       - Published and signed by the POTUS
>       - Provides national objectives & priorities for national security, home & abroad.
>   - National Defense Strategy **(NDS)**
>       - Signed by the SECDEF
>       - Translate NSS into DoD Objectives
>       - 3 Strategies
>           - Integrated Deterrence
>               - Layered Security, like Defense-in-Depth
>           - Campaigning
>           - Building an Enduring Advantage

> - National Military Strategy **(NMS)**
>   - Signed by the CJCS
>   - Implements NDS into Military strategy
>   - Provides near-term objectives.

> - National Cybersecurity Strategy (NCS)
>   - Describes POTUS' cybersecurity priorities
>   - Outlines
>       - Administration's Concerns
>       - Adversaries
>       - Legislation to achieve goals

> - Cyberspace Strategy
>   - Establishes how DoD will Operate
>   - Subordinate to the NSS & NDS
>   - Complementary to the NCS

> - Domestic Cyber Law
>   - POTUS is Commander in Chief
>   - Authority to order military cyber operations, including use of force.
>   - Privacy protections (4th Ammendment)

> - US Statutes
>   - Authorize/restrict military cyber operations.
>   - Title 10, US Code - Armed Forces
>       - Covers use and employment of military forces.
>   - Title 14 - Coast Guard
>   - Title 18 - Crimes & Criminal Procedure
>   - Title 32 - National Guard
>   - Title 40 - Public Buildings, Property, & Works
>   - Title 44 - Pulic Printing & Documents
>   - Title 47 - Telecommunications
>   - Title 50 - War & National Defense
>       - Includes the UCMJ
>       - Governs covert operations. **(Instead of Title 10)**

> - UN Charter
>   - Defines lawful use of force.

> - Laws of Armed Conflict (LOAC)
>   - Regulates hostilities & Identifies victim protections

### L3 - Organizational Structure
> - Directive Authority for Cyberspace Operations (DACO)
>   - Specific authority with broad application.
>       - Authority applicable outside of chain of command
>   - **Provides authority to direct DoDIN global operations for all DoD Components**

> - Authority & Command
>   - Combat Command (COCOM)
>      - Provides authority to organize & employ commands.
>   - Operational Control (OPCON)
>      - Authority over operations
>      - No authority of administration
>   - Tactical Control (TACON)
>      - Authority over immediate concerns
>   - Administrative Control (ADCON)
>       - Not a warfighting authority.

> - Key Personnel / Agencies
>   - SECDEF
>   - **CJCS**
>       - **Advises the POTUS and SECDEF on operational policies, responsibilities, and programs.**
>   - Service Chiefs
>   - USCYBERCOM
>   - Joint Force Headquarters-Cyber (JFHQ-C)
>       - Assigned to USCYBERCOM
>   - JFQ-DoD Information Network (JFQ-DoDIN)
>   - Defense Information Systems Agency (DISA)
>       - Provide IT infrastructure.
>       - **Provides C2 enterprise infrastructure.**

> - AFCYBER Command Structure
>   - Synonymous with 16th AF
>   - Headquartered at Lackland AFB
>   - Integrates intelligence, surveillance, recon (ISR)
>   - **616th Operations Center (616 OC)**
>       - **Provides full-spectrum, multi-domain information warfare effects**
>   - 688th Cyberspace Wing (688 CW)
>       - Operators fall under this Wing (that's us)
>       - **Delivers actionable intelligence and TTPs**

> - 16th AF Partner & Supporting Organizations
>   - National Security Agency (NSA)/Central Security Service (CSS) National Threat Ops Center (NTOC)
>       - Real-time network awareness & threat characterization
>       - Enables coordination of Computer Network Operations
>   - AF Life Cycle Management (AFLCMC)
>       - Lifecycle management of equipment from adoption to retirement
>   - Cyberspace Capabilities Center (CCC)
>       - **Technical Expertise**
>       - Subject Matter Experts
>   - National Air & Space Intelligence Center (NASIC)
>       - Air & Space **predictive** intelligence
>   - AF OSI
>       - Felony-level investigation
>       - Reports to IG, SECAF
>   - Project Managed Office (PMO) Systems
>       - Assets maintained by external entities.
>           - ex. utilites like electricity, commercial software

> - USCYBERCOM Command & Control (C2)
>   - Large Force Employment (LFE) Concepts
>       - Executed when forces are operating: 
>           - in the same AO
>           - in vulnerability window
>           - with mutual support capabilities
>       - Also known as "Force Packaging"
>   - DoD Cyber Mission Forces
>       - Cyberspace Mission Forces
>           - Cyber Protection Force (CPF)
>               - Internal protection, operating on friendly networks.
>           - Cyber National Mission Force (CNMF)
>               - To Defeat Significant Threats
>           - Cyber Combat Mission Force (CCMF)
>               - Supports Priorities of Combat Command
>       - Service Cyber Component Headquarters (CO-IPEs)
>           - Civilian Role
>           - Provides Expertise
>       - Special Capability Providers
>           - Any force organized to accomplish specific missions



---

<br>

B2 - Terrain
---
### L1 - DoD Information Network (DoDIN) Architecture
> - Enterprise
>   - Network Components
>       - Endpoints
>       - Network devices/hardware
>           - Hardware connecting endpoints
>       - Communication protocols
>       - Constituent Networks
>           - Separate specialized domains of a larger network.
>   - DoDIN
>   - AFIN
>       - Includes AFNET
>           - AFNET
>   - Base Boundary
>       - Enclave Control Node (ECN) connects BITI to the AFIN
>   - BITI
>       - Base local network infrastructure.

> - Network Relationships
>   - NIPR Layers
>       - Internet
>       - DoDIN
>           - DISA Gateway IAP (Internet Access Point) - first line of defense against the internet
>       - AFIN
>       - AFNET
>       - BASE
>           - ECN connects base infrastructure (BITI) out to the gateway
>   - SIPR Layers
>       - DoDIN
>       - AFIN
>       - AFNET-S
>       - BASE
>           - SDP Connection can link straight to external AF Resources on other bases

> - Gateway Architecture
>   - Defense Information Systems Agency (DISA)
>       - Manages gateways, DISN & all subdomains, and associated registration databases
>   - Defense Information System Network (DISN)
>       - 3 Major Segments
>           - long-haul telecom infrastructure
>           - deployed telecom infrastructure
>           - sustaining base infrastructure that interfaces with the long-haul infrastructure
>   - DISA gateway defensive capabilities
>       - DoD365-J (MS application suite)
>       - **Enterprise Recursive Service (ERS)**
>           - Handles outbound internet queries as a DNS proxy
>           - Reduces attack surface
>           - Enables DoD-wide policy enforcement

> - AFNGS
>   - Air Force NIPRNet Gateway Systems (AFNGS) / **AFGateway**
>       - **Consolidates AF enclave**
>       - Connects AFNet and DoDIN
>   - **Palo Alto NGFW**
>       - Next-Gen firewall
>           - Collects & manipulates data
>   - Tools & Capabilities
>       - Service Delivery Points (SDPs)
>       - Next Gen Firewall
>       - DNS/DMZ Server
>   - Integrated Management System (IMS)
>       - **Pushes out updates to NIPR systems**
>       - **UNCLASS** logical **out-of-band** management
>   - C2 Nodes / SIPRNet gateways
>       - Provide IP/IDS capabilities.
>       - **No IMS in SIPR**

> - Joint Regional Security Stacks (JRSS)
>   - Joint services network connectivity to reduce redundancy between branches
>   - Meant to replace the AF Gateway model
>   - Being replaced by Zero Trust (ZT) due to frequent data-breaches
>   - Dual-security stack version, and part, of the **Joint Information Environment (JIE)**
>       - Consolidates worldwide resources into regional environments to save cost and man hours.

> - Air Force Data Centers (ADC)
>   - Replaced per-unit data-centers
>   - Base Resources
>   - Created by order of the SECDEF
>       - Save Money
>       - Improve ability to execute missions
>       - Improve manageability

> - Area Processing Centers (APC)
>   - Consolidated ADCs
>       - Regional Coverage for ADCs
>       - Manages all core services
>       - Supports mission system application resources
>   - **Consolidates core services** & provides storage
>       - Includes authentification & application services

> - Air Force Provisional Enterprise Data Centers (AFPEDC)
>   - Consolidates APCs
>   - Larger Regional Area
>   - **Hosts consolidated enterprise applications**

> - Base Boundary (ECN)
>   - Protect local network and segregate local network services.
>   - Standard Base Boundary Architecture
>       - Boundary - Physical In/Out point of traffic
>       - Perimeter - Remote Access
>       - Enclave - Policy-Based Grouping
>       - BITI - Base Physical Network
>       - DMZ - Quarantine Between Internal & External Traffic
>       - SDP - Inter-Base Connectivity
>   - Base Boundary Components
>       - External/Perimeter Router
>       - Firewall
>       - Web Proxy
>       - Internal Router
>       - DMZ Router
>       - Network Time Protocol (NTP) Server

### L2 - **(Not Tested)** - Over the Horizon: Defining the Future Enterprise
> - Zero Trust Network Access (ZTNA)
>   - Operates on the initial assumption that no connection, corporate or user, should be trusted.
>   - 7 Tenets
>       1. Resource Definition
>       2. Secure Communication
>       3. Access to Resources Per-Session
>       4. Policy Defining Access
>       5. Monitor & Measure Integrity & Security Posture
>       6. Authentication & Authorization Enforcement
>       7. Data Collection & Audit
>           - Collect as much data as possible to learn & improve security posture
>   - Principles of ZTNA
>       - Least Access Priviledge
>       - Device Validation
>       - Multi-Factor Authentication
>       - Microsegmentation
>           - Finely segment network to prevent large-scale intrusion & infection
>       - Monitoring
>           - Monitor who & what has access, including user behavior
>   - Pillars of Zero Trust Security
>       - Identities
>       - Devices
>       - Network
>       - Apps & APIs
>           - Using application-level control to prevent misuse & injection.
>       - Infrastructure
>           - **Provides the baseline.**
>       - Data
>           - Protect data in storage, transfer, & use.
>   - **Zero Trust Architecture (ZTA)**
>      - Identify
>      - Protect
>      - Detect
>      - Respond

> - DoD Zero Trust Capabilities
>   - DoD Zero Trust Pillars
>      - User
>      - Devices
>      - Applications & Workloads
>      - Data
>      - Network & Environment
>      - Automation & Orchestration
>      - Visibility & Analytics

> - DAF Migration to Zero Trust
>   - DAF ZT Functional Management Office Objectives
>       - I-Plan
>           1. Coordinate w/ Senior Leaders to meet DoD schedule.
>           2. Focus implementation to DoDIN networks
>           3. Develop I-Plan Success Metrics
>           4. Identify Dependencies
>           5. Track & Document I-Plan activity status
>           6. Facilitate the socialization of ZT across the DAF
>           7. Ensure the I-Plan aligns with DoD ZT strategy & DAF CTO ZA Roadmap
>           8. Bolster relationship with External ZT Partners
>       - Goals of Implementation
>           1. Cultural Adoption of Zero Trust
>           2. Implementation Plan - DoD Info Systems Secured & Defended
>           3. Technology Acceleration
>           4. Zero Trust Enablement

---

<br>

B3 - Security
---
### L1 - Threat Landscape
> - Cybersecurity Concepts
>   - Cybersecurity
>   - Cyberattack
>   - Cyber-attackers
>   - Cybersecurity Framework
>       - People
>           - Cyber Hygiene
>               - General good practices
>       - Processes
>           - Provide the framework for cybersecurity governance
>       - Technology
>           - IT infrastructure used to achieve cybersecurity.
>   - Cybersecurity Threats
>       - A circumstance or event that can impact operations, assets, individuals, or the nation.
>       - Can be decomposed into the Threat Source & Threat Event
>   - The CIA Triad (CIAAN)
>       - Integrity
>           - Authentication (A)
>           - Non-repudiation (N)

> - Understanding Cyber Threats
>   - Characterizing
>       - Capability - Can they do it?
>       - Intent - Do they want to do it?
>       - Opportunity/Targeting - Do they have an opportunity?
> - **Cyber Threat Actors**
>   - **Hats**
>       - Black Hat
>           - Malicious Hackers
>       - White Hat
>           - Privately expose vulnerability to an organization
>           - Ethical Hackers
>       - Grey Hat
>           - Publicly expose vulnerability, usually to shame organization into taking action
>       - Green Hat
>           - Script-kiddies, unexperienced black hats
>       - Red Hat
>           - Hired by organizations to pen-test their systems from the inside
>       - Blue Hat
>           - Hired by organizations to pen-test software & systems
> 
>   - | Threat Actors     | Motivation          |
>     | ----------------- | ------------        |
>     | Nation-States     | Geopolitical        |
>     | Cybercriminals    | Profit              |
>     | Hacktivists       | Ideological         |
>     | Terrorist Groups  | Idological Violence |
>     | Thrill-seekers    | Satisfaction        |
>     | Insider Threats   | Discontent          |
> 
> - Classifying Attacks
>   - Passive
>       - Traffic analysis, monitoring, & capture
>   - Active
>       - Penetration/information exfiltration attempts.
>   - Close-in
>       - Close physical proximity attacks.
>   - Insider
>       - Intention/accidental attack by an insider.
>   - Distribution
>       - Malicious modification of hardware or software at the point of distribution
> - Common Attack Vectors
>   - Buffer Overflow
>   - Mobile Code
>   - XSS
>   - PL/SQL Injections
>   - Race Conditions
>   - Covert Channel
>       - Un-intended intra-system channel
>   - Replay
>   - Return-Oriented
>   - Malicious Code

### L2 - Threat Analysis
> - Cybersecurity Framework
>   - Cyber Attack Framework / Exploitation Framework
>       - Models of thinking and acting taken by threat actors.
>   - Intrusion Kill Chain
>       - Describes the systematic process to target & engage an enemy within cyberspace.
>       - Phases of the Intrustion Kill Chain
>           - | Phase                | Action |
>             | -----                | ------ |
>             | Reconnaissance       | Research, ID, Selection of Targets |
>             | Weaponization        | Preparing weapon into a deliverable payload |
>             | Delivery             | Delivery of weapon to target |
>             | Exploitation         | Triggering weapon |
>             | Installation         | Weapon installs a backdoor |
>             | Command & Control    | External communication with weapon to gain "hands-on-keyboard" access |
>             | Actions on Objective | Attacker uses access to achieve their goals |
>
>   - Diamond Model of Intrusion Analysis
>     - Framework for examining intrusion events
>     - 4 Vertices (Qualities)
>         - Adversary
>         - Capability
>         - Infrastructure
>         - Victim
>   - **MITRE AT&CK Framework**
>     - **Focuses on how a threat actor interacts with systems during an attack.**
>   - **MITRE D3FEND Framework**
>     - **Maps relationships between adversary TTPs & defensive countermeasures to develop countermeasures.**

> - Conducting Threat Research
>   - Reputational Research
>       - Based on past security concerns to determine paterns of poor security
>   - Behavioral Research
>   - Common Vulnerability Scoring System (CVSS)
>       - Used to supply a qualitative measure of severity of vulnerabilities

> - Threat Modeling
>   - Structured representation of all pertinent information that affects the security of an environment. Used to capture, organize, & analyze information regarding cyber threats.
>   - Components
>       - Adversary Capability
>       - Total Attack Surface
>       - Attack Vector
>       - Impact
>       - Likelihood
>   - Process
>       - Define
>       - Visualize
>       - Identify
>       - Mitigate
>       - Validate

### L3 - Threat Intelligence
> - What is Threat Intelligence?
>   - Helps to make informed, data-back determinations about existing and possibe future threats.
>   - Passive
>       - Data gathered without explicit action
>   - Active
>       - When actions are taken to obtain information

> - The Intelligence Cycle
>   - Data, Information, & Knowledge
>       - Data
>           - Large, raw volumes of information
>       - Information
>           - Refined data.
>       - Knowledge
>           - Fully refined, targeted information.
>   - Intelligence Cycle
>       1. Requirements
>           - Sets top-level goals
>           - Requires in-depth understanding of environment
>       2. Collection
>           - Gather information to address the most important intelligence requirements
>       3. Analysis
>           - Process data into usable information
>       4. Dissemination
>           - Distribute information
>       5. Feedback
>           - Identify how effective intelligence was

> - Types of Threat Intelligence
>   - Tactical
>       - Focused on immediate future
>       - Simple indications of compromise
>   - Operational
>       - Longer-lasting countermeasures
>       - Developed with a focus on who, why, and how (attribution, motive, TTPs)
>       - Requires more complex analysis of data
>   - Strategic
>       - Long-term local and international impact
>       - Based on large-scale trends, like global events, foreign policies, and local and international movements

> - Categories of Threat Intelligence
>   - Open Source
>   - Closed Source

> - Cyber Intelligence Support
>   - **616th Operations Center**
>       - **Provides operational command & control, and situational awareness.**
>   - Cyber-Intel Squadrons
>       - Full-spectrum collection, exploitation, analysis, & targeting for cyber ops
>   - NSA National Threat Operations Center **(NTOC)**
>       - Real-time network awareness & threat characterization
>   - National Air & Space Intelligence Center **(NASIC)**
>       - Predictive intelligence
>   - **AFOSI**
>       - **Conducts criminal investigations & provide counterintelligence services.**

> - Intelligence Law Considerations for Cyberspace
>   - Intelligence vs Cyberspace
>       - Common origin, but separate & distinct activities.
>       - Potential Issues
>           - Datasets
>           - PAI (Publicly Available Information)
>           - Command Authority

---

<br>

B4 - Operation
---
### L1 - Cyberspace Missions
> - Cyberspace Missions
>   - DoDIN Operations (DoDIN Ops)
>       - Sustains network connectivity
>       - Threat agnostic; doesn't care who the threat is
>   - Defensive Cyber Operations (DCO)
>       - DCO Internal Defensive Measures (DCO-IDM)
>           - Protect from a **specific** threat on the internal side of the network
>       - DCO Response Actions (DCO-RA)
>           - Protect from a **specific** threat external to the network
>   - Offensive Cyber Operations (OCO)
>       - Intended to project power in foreign cyberspace

> - Cyberspace Actions
>   - System Operations
>       - Ensure specific segments of DoD cyberspace remain in operation
>   - Security
>       - Reduce attack surface
>   - Defense
>       - ID & defeat active threats
>   - Exploitation
>   - Attack

> - Legacy DCO Mission Types
>   - Surveillance
>       - Collect relevant data & information in/on the AO
>   - Reconnaissance
>       - Collect relevant data & information on specified threats in the AO
>   - Access
>       - Provide sufficient access for supported cyber forces
>   - Escort
>       - Provide protection, defense, & support to cyber weapon systems cunducting primary missions in assigned AO
>   - Secure
>       - Enhance defenses of the AO to mitigate risk
>   - Strike
>       - Damage/destroy an objective/capability
>   - Strike Coordination & Reconnaissance (SCAR)
>       - Conduct/facilitate **dynamic targeting** in the AO
>   - Threat Emulation
>       - Replicate realistic TTP's to specific cyber threats to evaluate defenses and prepare DoD-DCO

> - New DCO Mission Types (AFCYBER Mission Areas)
>   - Resolve
>       - Create terrain & resolve priority issues, executed on operationally accepted cyberspace
>       - Build, Operate, Extend
>       - Legacy Analogue: Access & Escort
>   - Identify
>       - Identify threats to refine organizational understanding
>       - Conduct, Scan, Query, Compile, Analyze
>       - Legacy Analogue: Surveillance
>   - Protect
>       - Enhance the AFIN security posture in response to specified or general threats, which reduses risk to systems & missions
>       - Implement, Configure, Remediate
>       - Legacy Analogue: Secure
>   - Detect
>       - Search for specific threats/TTPs & coordinate a strike
>       - Monitor, Hunt
>       - Legacy Analogue: Reconnaissance, SCAR
>   - Respond
>       - Targetted response to specific identified threats
>       - Triage, Strike
>       - Legacy Analogue: Strike
>   - Recover
>       - Recover system in response to a specific attack.
>       - Exercise, Rebuild
>   - Continuous Validation & Assessment (CV&A)
>       - Use approximation of known enemy TTPs to provide measures of effectiveness (MOEs) & performance (MOPs) for detect & protect missions
>       - Replicate, Assess, Validate
>       - Legacy Analogue: Threat Emulation

### L2 - Enterprise Management
> - Defining the Enterprise
>   - Enterprise Devices
>       - Endpoints
>       - Network Devices
>       - Communication Protocols
>       - Constituent Networks
>           - Non-enterprise networks that share infrastructure
>   - DoDIN
>       - Globally connected
>       - Provided by DISA
>   - AFIN
>       - Defines owned/leased AF networks
>       - AFNET & AFNET-S

> - Key Principles of Managing the Enterprise
>   - **Enterprise Architecture Management (EAM)**
>       - Managerial process that develops, maintains, and uses a set of procedures, standards of architecture, and administrative regimes that provide direct direction & realistic assistance in designing & implementing an enterprise formation to achieve its vision, strategic plans, & goals.
>   - NIST Risk Management Framework (RMF)
>       - Prepare
>       - Categorize
>       - Select
>       - Implement
>       - Assess
>       - Authorize
>       - Monitor
>   - NIST Cybersecurity Framework
>       - Identify
>       - Protect
>       - Detect
>       - Respond
>       - Recover

> - Facets of Enterprise Management
>   - IT Service Management (ITSM)
>       - Focuses on customer needs & IT services for customers in adition to IT systems
>   - Configuration Management (CM)
>       - Identifies, records, controls, reports, audits, & verifies service assets & configuration baselines
>   - Change Management
>       - **Designed to minimize disruptions to network services while making necessary updates or changes**
>       - Request for Change (RFC) or Change Proposal flow
>           - Review Request
>           - Evaluate Change
>           - Approve Change
>           - Coordinate Implementation
>           - Review & Close Change Request
>       - Types of Changes
>           - Standard
>               - Preapproved, regular changes like patches
>               - low risk
>           - Normal
>               - Common changes that aren't preaproved, like a new laptop
>           - Emergency
>               - Unexpected issues that require immediat changes, like removing compromised devices
> - Software Management
>   - How we track software licenses
>   - The processes & procedures responsible for managing software licenses throughout their lifespan
> - Incident Management
>   - Steps
>       - Detect
>       - Log
>       - Classify
>       - Diagnose
>       - Resolve
>       - Close
>       - Review
> - Network Management (FCAPS)
>   - Fault Management
>       - Recognize, isolate, collect, & log faults.
>   - Configuration Management
>       - Monitor changes to baseline
>   - Account Management
>       - Tracks network utilization information, authentification & authorization
>   - Performance Management
>       - Ensure that network performance remains at acceptable levels.
>       - Addresses throughput, response time, packet loss, link utilization, percentage utilization, error rates, etc
>   - Security Management
>       - Focuses on the CIA of the network

> - Emergency Preparedness & Response
>   - Mission Critical Mentality
>       - Focuses on risk mitigation
>       - Acknowledges the facility-IT system relationship
>   - Key Elements
>       - Emergency Operating Procedures (EOP)
>       - Crisis Management Plans
>       - Escalation Procedures
>           - Documented, prioritized contact lists, with contact requirements
>       - Emergency Drills
> - Incident Management/Reporting
>   - Anything unplanned, unusual, or unexpected
>   - Impacts operations/safety
>   - Incident Reporting
>       - Report Information
>       - Site Information
>       - Incident Overview
>       - Incident Details
>       - Incident Follow-up
>       - Action Items
>       - Reccomendations
>       - Support Information

### L3 - Cyberspace Weapon Systems
> - Defensive Cyber Weapon Systems & Capabilities
>   - Cyber Command & Control Mission Systems (C3MS)
>       - **616th Ops Center**
>       - Provides situational awarenes
>       - Cyber tasking orders (CTO)
>
> - Air Force Intranet Control (AFINC)
>   - Delivers network centrict services & provides core services
>   - AFNet Situational Awareness, whitelists/blacklists
>   - Cybersecurity Service Provider (CSSP)
> 
> - Cybersecurity & Control System (CSCS)
>   - **Tactical-level weapon system.**
>   - Conducts daily AFNet(-S) operations
>   - Provides 24/7 network defense operations & management functions
>   - **Units**
>       - 83rd NOS
>       - 561st NOS
>       - 690th COS
>       - 691st COS
>   - CSCS Operator Roles
>       - CCC - Crew Commander
>       - CPO - Client-Endpoint Operator
>       - DSO - Directory Services Operator
>       - NMO - Network Management Operator
>       - SVO - Storage & Virtualization Operator
>       - VMO - Vulnerability Management Operator
>
> - Air Force Cyberspace Defense (ACD)
>   - **Designed to carry out defensive cyberspace operations (DCOs) to prevent, detect, respond to, and provide forensics of network intrusions.**
>   - Key Capabilities
>       - Prevent
>       - Detect
>       - Respond
>
> - Cyberspace Vulnerability Assessment/Hunter (CVA/H)
>   - Provides mission assurance to increase defensive capability
>
> - Cyberspace Defense Analysis (CDA)
>   - Monitors, collects, analyzes, and **reports on information**
>   - 688 NW

---

<br>

B5 - Crew Operations
---
### L1 - Cybercrew Operator Training
> - Training Pipeline
>   - Tech School
>   - IQT
>   - Stan/Eval IQT Evaluation
>   - BCQ (Basic Cyber Qualified)
>       - Mission Qualification Training (MQT)
>       - Standards & Evaluation(Stan/Eval) MQT Evaluation
>   - BMC (Basic Mission Capable)
>       - OJT
>       - Stan/Eval MR Evaluation
>       - Certification Brief
>   - MR (Mission Ready)
>       - Maintain MR Status

> - Evaluation & Qualification Process
>   - Evaluations
>       - Written
>       - Performance
>   - Evaluation Categories
>       - Qualification (QUAL)
>       - Mission (MSN)
>           - Focuses on mission readiness (MR)
>       - On the Spot (SPOT)
>   - Qualifications
>       - Every 18 months upon initial qualification
>   - Qualification Levels
>       - Q1
>           - Top Tier
>           - Pass written tests with 90%+
>           - All minor discrepencies noted during evaluation resolved during debrief
>           - No Unsatisfactory (U)
>       - Q2
>           - Acceptable
>           - Pass written tests with 80-90%
>           - Given Unsatisfactory (U) in unimportant/sub areas
>       - Q3
>           - Unacceptable
>           - Fail written tests
>           - Given Unsatisfactory (U) in a significant area

> - Squadron Operations Training Flight (DOT)
>   - DOT Roles & Responsibilities
>       - Operator Training Program
>       - Continuation Training Program
>       - Develops Master Training Task List (MTTL)
>       - Coordinates Training
>       - Tracks/Evaluates Readiness
>       - Create/Maintain ITF (Individual Training Folder)
>           - Basically your permanent record.

> - Tactics, Techniques, & Procedures (TTPs)
>   - TTP
>       - Tactics
>           - Why tasks are executed
>       - Techniques
>           - What tasks need executed
>       - Procedures
>           - How tasks should be completed
>   - Used with crew aids & local policy
>       - Local policy covers base-specific needs
>   - **TTP Documents**
>       - AFTTP 3-1/3-3
>           - Official TTP documents published by the USAFWC
>       - Tactics Bulletins
>           - Official updates to AFTTP between rewrites
>       - Flash Bulletins
>           - Time-sensitive lessons learned, requiring immediate dissemination
>       - Operational Change Request
>           - Formal request to MAJCOM that IDs the the inability of an electronic warfare system to meet operational requirements.
>   - TTP Hierarchy & Relationship to Crew Aids
>       - Pyrimad
>           - Tactics (Top)
>           - Techniques
>           - Procedures
>           - Checklists, Standard Operating Procedures, Technical Orders

> - Tactics Development Program
>   - Documents validated best practices
>   - Improves weapon system combat capabilities & integration
>   - Identify tactical deficiencies & find, validate, & document non-material solutions
>   - 4 Primary Elements
>       - Tactics Improvement Proposals (TIPs)
>       - Tactics Review Boards (TRBs)
>       - Tactics Development & Evaluations (TD&E)
>       - Dissemination of Information
>   - Tactics Cycle
>       - Development (First Phase)
>           - TIP Submission
>           - Review
>           - Tactics Review Board (TRB)
>           - Tasking & Planning
>           - Development & Validation
>           - Documentation
>       - Implementation (Second Phase)
>           - Train
>           - Exercise
>           - Mission Plan
>           - Execute
>           - Assess
>           - ID Deficiencies

> - Squadron Weapons & Tactics (DOK)
>   - Every unit has a DOK shop
>   - Most qualified individuals
>   - Implements TTPs through the Implementation half of the Tactics Cycle
>   - Other Responsibilities
>       - Developing tactical employment guidance
>       - Establishing & maintaining contact w/ mission support functions
>       - Confirm with senior, lateral, & subordinate W&T units

### L2 - Cybercrew Force Management
> - Crew Force Management
>   - Crew Commander/Battle Captain Responsibility
>       - Verify "Go-No Go Status"
>       - Monitors PEX for discrepencies
>       - Initiates remediation actions, if necessary
>       - Includes
>           - Qualification
>           - Proficiency
>           - Currency
>   - Qualification Requirements
>       - Pass IQT
>       - Complete MQT w/i 90 days
>       - Pass Stan/Evals
>       - Complete Upgrade/Special Training
>       - Pass Recertification
>   - Proficiency Requirements
>       - Met through Continuation Training
>       - Ready Cybercrew Program tasks (annual)
>       - Weapons & Tactics Academic (semi-annual)
>       - Crew Risk Management (annual)
>       - Crewmember responsibility
>   - Currency Requirements
>       - AD: One sortie (every 30 days)
>       - ANG/AFRC (every 90 days)
>       - Tracked via PEX

> - Crew Rest & Duty Periods
>   - Individual Risk Assessment
>       - Assesses each operator's level of risk to mission execution
>       - Determines Fit for Duty status
>       - Performed during shift change
>   - Crew Rest
>       - Minimum 10 hour non-duty period
>       - Crew member/operator responisibility
>   - Duty Period
>       - Begins when member reports for duty
>       - Not to exceed 12 hours
>   - PEX (Patriot Excalibur)
>       - Operations management tool
>       - System of record for training, scheduling, & evaluations/qualifications
>       - Must be reviewed prior to assuming shift & upon concluding shift

### L3 - Cybercrew Documentation Requirements
> - Cyber Mission Reporting
>   - Master Station Log
>       - Master repository for significan shift events
>       - Entries must be timely, accurate, & detailed
>       - No set format or medium; per-unit procedures
>       - Mandatory Entries
>           - Date
>           - Time; Julian date, Zulu time
>           - Event(s)
>       - Examples
>           - Physical Security Incident
>           - Safety Incident
>           - High Visibility Item
>           - Environmental
>           - Mission-related Operations
>   - **Crew Information File (CIF)**
>       - Collection of publications & material, necessary for daily operations
>       - **5 Volumes**
>           1. CIF Index & **Current Read File**
>               - Temporary, pertenent material for current operation.
>               - **Read prior to start of every mission, every day**
>           2. HHQ Publications (and supplements)
>               - **AF-level** guidance
>           3. HHQ & Squadron Directives
>               - **Squadron-level** guidance; can override AF-level guidance
>               - Master Training Task List (MTTL) included
>           4. Manuals, Crew Aids, & Technical Orders (TOs)
>               - The hows of performing specific functions
>           5. Safety Information
>   - Crew Aids
>       - Information used to perform daily duties
>       - Locally developed
>       - Requires Group/CC approval
>   - Shift Changeover
>       - Occurs between shifts/missions
>       - Information passed from current to oncoming personnel
>       - Delivered in accordance w/ local policy & directives
>       - Eats into 10 hour non-duty period
>       - No standard format

> - Service Interruptions & Events
>   - Roles & Responsibilities
>       - DISA
>           - Plans, approves, & coordinates planned/authorized service interruptions
>       - AFIN Mission Assurance Center (AMAC)
>           - Processes all authorized service interruptions and tracks non-interrupted periods of service
>       - MCCC
>           - Communicates between a unit and AMAC
>   - Types of Service Interruptions
>       - Authorized Service Interruption (ASI)
>           - Routine
>               - Not high-priority
>               - 21 days to be scheduled
>           - Urgent
>               - scheduled in a 4-20 day period, requires justification & concurrence from user
>           - Emergency/Demand
>               - Immediate action (3-day window), requires justification, but not concurrence from user
>       - Unauthorized Service Interruption (USI)
>       - Period of Non-Disruption (POND)
>           - Designated period of time that a service cannot be interrupted
>           - Breaking a POND requires USCYBERCOM approval
>   - Service Interruption Conditions
>       - Levels of Degredation
>           - **Degraded (Partially Mission Capable)**
>               - Service still usable, but not at 100%
>               - Partial loss of capability, limited service interruption
>           - Hazardous Condition (HAZCON)
>               - Condition in which a service could become isolated, such as a loss of redundancy
>               - **Service could keep full capability, not affecting the end user at all; HAZCON != Degraded**
>           - Isolation (Non-Mission Capable)
>   - Force Presentation
>       - Managed by the 616th
>       - 7 Zulu-day outlook of available forces, no later than 7 Zulu-days prior
>   - COOP (Continuity of Operation)
>       - Plans to keep operations in motion during a service interruption

> - Cyber Operational Reporting
>   - Used to notify Higher Headquarters (HHQ) of any significant event or incident that rises to the level of the DoD, CJCS, Combat Command, or service-level interest.
>   - Cyber Escalation Matrix
>       - Quick-reference document designed to identify incidence that require reporting IAW 16th AF and 688 CW's Commander's Critical Information Requirements (CCIRs)
>   - Types of Operational Reporting
>       - OPREP-3, Event/Incident Report
>       - Cyber 9-line
>           - Used to quickly communicate incidents to USCYBERCOM
>       - Commanders Critical Information Requirements (CCIRs)
>           - Used to report incidents that don't meet AF-level operational reporting criteria but are of interest to the ACC Commander

> - Cyber Mission Reporting
>   - Types
>       - SPINs
>       - Go/No-Go Report
>           - Used by crew commanders to notify 616 of the final Go/No-Go status 15 minutes prior to the execution of the mission
>       - On/Off Station Report
>           - Provided by the mission commander to communicate mission time on station, significant updates, and time off-station(mission complete)
>       - MISREP (Mission Report)
>           - Primary method of task reporting
>           - Required to report status on all CTOs (cyber tasking orders)
>       - Mission Debrief
>           - An evaluation of mission results against mission objectives

### L4 - Cyber Mission Planning & "Rules of Engagement" (ROEs)
> - Cyber Mission Planning
>   - Plans translate broad intent provided by strategy into operations; successful operations achieve the strategy's objectives
>   - Joint Planning Process
>       1. Planning Initiation
>       2. Mission Analysis
>       3. Course of Action (COA) Development
>           - Ideas *w/ plans* become COAs
>       4. COA Analysis & Wargaming
>           - Simulation and trouble-shooting COA
>           - Rehearsal of Concept (RoC) drills
>       5. COA Comparison
>           - How effective was the COA?
>       6. COA Approval
>           - Commander reviews and approves final plan
>       7. Plan or Order Development

> - Mission Planning Concepts
>   - 5 Questions
>       1. What is the Purpose?
>       2. What am I being tasked to do?
>       3. What are my limitations or constraints?
>       4. Do I have the right resources (forces/assets)?
>       5. How will we assess whether the objective was met & correct it for future missions?
>   - Plan, Brief, Execute, Debrief (PBED) Process
>       - Plan
>           - All missions begin here
>           - Happens at the unit level
>           - Designated mission lead is responsible for mission planning
>           - Rehearsal of Concepts (ROC) Drill
>               - Tabletop exercise for the plan
>       - Brief
>           - Conveys the mission & plan to accomplish objectives
>       - Execute
>           - Also referred to as the vulnerability window
>               - Defined by start & stop times
>           - Mission Deviations
>               - Cancel
>               - Abort
>               - Rollback
>       - Debrief
>           - Required after every mission
>           - Covers all aspects of the mission
>               - Only within the scope of the mission plan
>           - Involves feedback
>           - Develops lessons learned & learning

> - Cyber Mission Tasking
>   - Flow
>       - USCYBERCOM
>       - AFCYBER/CC
>       - 616 OC
>       - Various Cyber Units
>   - USCYBERCOM Orders
>       - Operations Orders (OPORDs)
>           - Directives issued to direct implementation of an operational & strategic-level plan
>           - What you're going to do
>       - Tasking Orders (TASKORDs)
>           - Operational-level orders issued to perform specific actions at specific time frames in support of AF & Joint requirements
>           - How you're going to do it
>       - Fragmentary Orders (FRAGOs)
>           - Supplemental, additional instructions; addendums to OPORDs & TASKORDs
>           - Small changes to how you're going to do it
>   - 616 OC Orders
>       - Cyber Tasking Orders (CTO)
>           - Specific actions at specific times
>       - Cyberspace Control Orders (CCO)
>           - Build/shape a portion of cyberspace in support of a CCMD operation or in response to adversary action
>       - Maintenance Tasking Orders (MTO)
>           - Direct maintenance actions
>       - Time Compliance Network Order (TCNO)
>           - Direct, immediate patching of information systems against critical vulnerabilities
>       - Time Compliance Technical Order (TCTO)
>           - Issued to expedite changes to end articles/items, parts & material within specific time periods
>           - Not for immediate, critical changes
>   - Additional Communications
>       - C4 Notice to Airmen (C4NOTAM)
>           - Disseminate local general information that doesn't require action or tracking
>       - Integrated Operations Directive/Integrated Operations Plan (IOD/IOP)
>       - Special Instrucions (SPINS)
>           - Something that needs to be changed right now that affects your mission

---

<br>