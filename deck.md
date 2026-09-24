# Advanced Incident Response – Enhanced Teaching Deck

## Slide 1 — Module Title
**Advanced Incident Response: Information Security**  
Lecturer: Michael Gleeson  
Email: michael.gleeson@setu.ie

**Background/Explanation**
- This module introduces how organizations prepare for, detect, respond to, and recover from cybersecurity incidents.
- It combines technical security controls with policy, governance, and legal/compliance perspectives.
- The goal is to build both operational capability and strategic decision-making for modern cyber risk.

---

## Slide 2 — Overview
**Topics**
- Why Study Incident Response?
- Some History/Background
- Personal Information Security
- The CIA Triad (Confidentiality, Integrity, Availability)

**Background/Explanation**
- The module starts by establishing *why* incident response matters in real organizations.
- It then uses historical incidents to show how current practices evolved.
- It links enterprise incidents to personal data protection behaviors.
- The CIA Triad provides a foundational framework used throughout all security analysis.

---

## Slide 3 — Why Study Incident Response?
**Key Points**
- When there is a fire, it must be extinguished.
- Ideally, you prevent it occurring at all.
- Security incidents follow the same logic.
- If an incident occurs, you need an effective response.
- Assess likelihood of recurrence.
- Predict and avoid future incidents.
- Incidents are not becoming fewer.
- Incidents are becoming more advanced and more targeted.

**Background/Explanation**
- Prevention controls fail at times; response capability determines business damage.
- Response quality affects downtime, legal impact, customer trust, and costs.
- Mature teams convert incidents into lessons learned and improved controls.

---

## Slide 4 — Why Study Incident Response? (Demand / Jobs)
**Demand, also called jobs**

**Background/Explanation**
- As cyber incidents increase, organizations require professionals across Security Operations Centers (SOCs), Digital Forensics and Incident Response (DFIR), threat intelligence, governance, risk, and compliance.
- Incident response is now a core business function rather than a niche technical specialty.
- Hiring demand is strong in public sector, private sector, healthcare, finance, and critical infrastructure.

---

## Slide 5 — Demand Drivers
**Key Points**
- Increasing criticality of information
  - To individuals (photographs, work)
  - To organizations (payroll, intellectual property, business processes)
- Increasing quantity of information
  - Customer details, purchase history, Global Positioning System (GPS) data, clickstream data
- Increasing computerization of information
  - No more paper; everything digitized

**Background/Explanation**
- The value and sensitivity of data have increased dramatically.
- More data creates a larger attack surface and greater breach impact.
- Digitization improves efficiency but concentrates risk in interconnected systems.

---

## Slide 6 — Demand Drivers (More)
**Key Points**
- More copies of information
  - Laptops (can be stolen/lost)
  - Smartphones, tablets, smartwatches
  - Bring Your Own Device (BYOD)
- More diverse population of users
  - Not necessarily computer-savvy
  - Less security awareness
- Hence, more committed attackers
- Recent incidents are generally motivated by profit

**Background/Explanation**
- Endpoint sprawl makes governance difficult and expands compromise paths.
- Human behavior and social engineering remain major breach factors.
- Cybercrime monetization models (ransomware, fraud, data resale) intensify attacker focus.

---

## Slide 7 — Trends
**Trend Focus Areas**
- Increasing attack sophistication
- More targeted campaigns
- Growth in ransomware and extortion
- Supply-chain compromise expansion
- Blending of criminal and state-sponsored activity

**Background/Explanation**
- Trend analysis guides investment priorities and incident readiness.
- Defenders must plan for advanced persistence, lateral movement, and stealth.

---

## Slide 8 — What Do Information Security Professionals Do?
**Technical Work**
- Plan, implement, upgrade, and monitor security measures for networks and information
- Ensure controls are in place to safeguard digital files and critical infrastructure
- Respond to security breaches and malware

**Non-Technical Work**
- Research emerging technologies
- Manage internal and political issues
- Manage regulatory compliance
- Develop internal policies, standards, and procedures

**Background/Explanation**
- Effective incident response combines engineering, communication, governance, and legal awareness.
- Technical actions must align with organizational risk appetite and compliance duties.

---

## Slide 9 — Survey Feedback (International Information System Security Certification Consortium, ISC², 2015)
**Background/Explanation**
- Workforce surveys identify skill shortages and recruitment pressure.
- They highlight needs in cloud security, detection engineering, and incident response readiness.
- Survey evidence supports curriculum alignment with market demand.

---

## Slide 10 — The Future of Cyber Survey 2019 (Deloitte)
**Background/Explanation**
- Industry studies emphasize board-level cyber governance and business resilience.
- Organizations increasingly prioritize rapid response and continuity planning over perimeter-only defense.

---

## Slide 11 — Survey Feedback (ISC², 2015)
**Background/Explanation**
- Repeated survey references reinforce that talent, process maturity, and culture are recurring gaps.
- Technical controls alone are insufficient without trained teams and clear decision pathways.

---

## Slide 12 — Survey Feedback (ISC², 2015)
**Background/Explanation**
- Security capability development requires long-term investment in people, playbooks, and exercises.
- Survey findings justify practical labs, simulations, and incident case analysis in this module.

---

## Slide 13 — Brief History: Early Internet Foundations
**Key Points**
- Many current procedures come from past incidents.
- These incidents became industry folklore and vocabulary.
- Sources include Wikipedia and publications (InformationWeek, Computerworld).
- 1981: Transmission Control Protocol/Internet Protocol (TCP/IP) finalized.
- No explicit security design assumptions.
- Internet community generally considered benign.

**Background/Explanation**
- Security was not a primary design objective in early networking standards.
- Legacy trust assumptions still influence modern vulnerabilities.

---

## Slide 14 — Brief History: 1982–1983 (The 414s)
**Key Points**
- Six teenagers from Milwaukee (“414” area code).
- Broke into around 60 high-profile systems (e.g., Los Alamos).
- Became a Newsweek cover story.
- Popularized the term “hacker” in InfoSec language.
- Prompted United States congressional hearings.
- Computer Fraud and Abuse Act enacted in 1986.

**Background/Explanation**
- Publicized incidents can rapidly drive legal and policy change.
- Legal frameworks became central to modern cyber enforcement.

---

## Slide 15 — Brief History: 1988 Morris Worm
**Key Points**
- Created by Robert Morris Jr., graduate student at Cornell.
- Released 2 November 1988.
- 99-line program intended to estimate Internet size.
- A bug caused severe disruption and system crashes.
- Approximately 10% of the Internet affected.
- First conviction under the 1986 Computer Fraud and Abuse Act.

**Background/Explanation**
- Demonstrates how unintended effects can produce large-scale cyber impact.
- Incident drove improvements in coordination and response practices.

---

## Slide 16 — Brief History (Operating Systems): 1995–1998
**Key Points**
- Microsoft Windows 95 released 24 August 1995.
- Low cost expanded ownership and Internet participation.
- Designed mainly as a stand-alone desktop system.
- Minimal built-in security.
- Windows 95 + TCP/IP created fertile conditions for security issues.
- Windows 98 released 25 June 1998.
- Added stronger Internet integration but little security improvement.

**Background/Explanation**
- Large-scale adoption of insecure defaults accelerates threat spread.
- Consumer platform choices can shape global cyber risk.

---

## Slide 17 — Brief History (Health/Data Protection): 1996
**Key Points**
- Health Insurance Portability and Accountability Act (HIPAA).
- Push for Electronic Health Records (EHR).
- Goal: reduce waste and healthcare costs.
- Healthcare sector responsible for confidentiality of patient data.
- Target to move fully to EHR by 2014.

**Background/Explanation**
- Healthcare cybersecurity directly affects privacy, safety, and service continuity.
- Regulation links incident response to legal and ethical obligations.

---

## Slide 18 — Brief History (Virus): 2000 ILOVEYOU
**Key Points**
- ILOVEYOU virus, 5 May 2000.
- Deleted image files on infected systems.
- Estimated global damage exceeded USD 8 billion.
- Significant losses from employee cleanup time.
- Created by students in the Philippines (Reomel Ramones and Onel de Guzman).
- Quickly traced.
- No charges initially; virus writing not yet a local offense.
- Legal differences across countries remain important.

**Background/Explanation**
- Highlights social engineering power and legal-jurisdiction challenges.
- Incident response must include legal and international coordination.

---

## Slide 19 — Brief History (Financial/Data Protection): 2002
**Key Points**
- Sarbanes–Oxley Act (SOX).
- Followed major corporate fraud (Enron, MCI WorldCom).
- Protected investors and pension stakeholders.
- Senior executives personally accountable for report accuracy.
- Financial statements rely on information technology systems.
- Section 404 requires formal internal controls.

**Background/Explanation**
- Cybersecurity and financial governance are tightly linked.
- Control failures in IT can become regulatory and executive-liability events.

---

## Slide 20 — Brief History (Financial): 2005–2007 Retail Breaches
**Key Points**
- TJ Maxx, BJ’s Wholesale Club, OfficeMax (United States-based).
- Millions of payment cards stolen.
- Data sold on criminal black markets.
- Exploited insecure wireless networks.
- Exploited web application Structured Query Language (SQL) injection vulnerabilities.
- Albert Gonzalez identified as ring leader.
- March 2010: sentenced to 20 years.

**Background/Explanation**
- Shows direct business impact of weak network and application security.
- Reinforces need for layered controls and proactive vulnerability management.

---

## Slide 21 — Brief History: 2008 Georgia–Russia Conflict
**Key Points**
- Conventional conflict accompanied by cyber operations.
- Large-scale Denial of Service (DoS) attacks in Georgia.
- Government websites defaced.
- Suspected Russian state involvement.
- If true, among first known state-sponsored cyberwar examples.

**Background/Explanation**
- Introduced mainstream understanding of cyber as a military domain.
- Incident response at state level requires cross-sector coordination.

---

## Slide 22 — Brief History: 23 June 2009 US Cyber Command
**Key Points**
- Establishment of United States Cyber Command (USCYBERCOM).
- Mission: defend military networks and conduct cyberspace operations as needed.
- Triggered by major threat reporting:
  - Joint Strike Fighter program data theft (terabytes from contractors)
  - Reported penetration of United States electricity grid

**Background/Explanation**
- National cyber institutions emerged in response to strategic-scale threats.
- Highlights escalation from enterprise incidents to national security concerns.

---

## Slide 23 — Brief History: 12 January 2010 Google/China (Operation Aurora)
**Key Points**
- Attempted theft of source code base.
- Compromise associated with unencrypted version-control systems.
- Effort to access emails of Chinese human-rights activists.
- Activity traced to two educational institutions in China.
- Chinese government framed activity as students refining skills.
- United States Congress indicated investigation intent.

**Background/Explanation**
- Demonstrates overlap of espionage, intellectual property theft, and geopolitical tension.
- Strong secure development and access controls are essential response-prevention links.

---

## Slide 24 — Brief History: 17 April 2011 Sony PlayStation Network Breach
**Key Points**
- Network serving approximately 70 million subscribers compromised.
- Credit card data suspected exposed.
- Network disruption persisted for an extended period.
- Significant revenue impact.
- Loss of customer trust, brand confidence, and market position.

**Background/Explanation**
- Incident cost extends beyond direct technical remediation.
- Communications, recovery speed, and trust restoration are core response functions.

---

## Slide 25 — Brief History: February 2013 Mandiant Report
**Key Points**
- Mandiant report attributed many attacks to “APT1” linked to a Chinese military unit.
- APT = Advanced Persistent Threat.
- Framed cyber activity as state-sponsored industrial espionage.

**Background/Explanation**
- Attribution reports influence international policy, defense planning, and enterprise threat models.
- Organizations must plan for persistent and resourced adversaries.

---

## Slide 26 — Brief History: July 2015 Ashley Madison Breach
**Key Points**
- “The Impact Team” copied user personal data.
- Threatened publication unless site shut down.
- Incident combined extortion, privacy violation, and reputational harm.

**Background/Explanation**
- Breaches can produce severe social and personal consequences for victims.
- Incident response must address legal, ethical, media, and victim-support dimensions.

---

## Slide 27 — Today: SolarWinds Supply-Chain Attack
**Key Points**
- Attackers compromised trusted software update mechanisms.
- Downstream customers were indirectly affected through vendor trust.

**Background/Explanation**
- Supply-chain compromise bypasses many perimeter defenses.
- Requires software provenance, third-party assurance, and zero-trust validation strategies.

---

## Slide 28 — Today: Colonial Pipeline
**Key Points**
- Critical infrastructure operations disrupted by cyber incident.
- Demonstrated linkage between information technology (IT) compromise and operational technology/business continuity impact.

**Background/Explanation**
- Incident response planning must include executive decision-making, crisis communications, and continuity operations.

---

## Slide 29 — Dedicated CIA Triad Slide
**Confidentiality**
- Ensure information is accessible only to authorized entities.
- Controls: encryption, access control, identity and access management, data classification.

**Integrity**
- Ensure information remains accurate, complete, and unaltered without authorization.
- Controls: hashing, digital signatures, change control, logging, integrity monitoring.

**Availability**
- Ensure systems and data are available when needed.
- Controls: redundancy, backups, disaster recovery, denial-of-service protections, resilience testing.

**Background/Explanation**
- The CIA Triad is a foundational model for analyzing all security controls and incidents.
- Most incidents affect more than one CIA dimension.
- Incident response decisions should explicitly map actions to CIA restoration priorities.

---

## Slide 30 — Incident Response Lifecycle (Suggested Improvement #1)
**Phases**
1. Preparation
2. Detection and Analysis
3. Containment
4. Eradication
5. Recovery
6. Post-Incident Lessons Learned

**Background/Explanation**
- The lifecycle structures response decisions and accountability.
- Rehearsed workflows reduce chaos and speed recovery during active incidents.

---

## Slide 31 — Case Study Framework (Suggested Improvement #2)
**Standard Template for Each Historical Incident**
- Attack vector
- Affected assets
- Business/operational impact
- Immediate response actions
- Root causes
- Long-term controls implemented
- Lessons learned

**Background/Explanation**
- A common framework enables consistent analysis, comparison, and assessment.

---

## Slide 32 — Workforce and Survey Data Refresh (Suggested Improvement #3)
**Enhancement**
- Add current workforce and risk trend reports (2023–2026) alongside ISC² 2015 and Deloitte 2019.

**Background/Explanation**
- Updated evidence improves relevance for students entering today’s job market.

---

## Slide 33 — Security Timeline Visual (Suggested Improvement #4)
**Enhancement**
- Add a single timeline linking:
  - Technical incidents
  - Regulatory/legal changes
  - Geopolitical cyber events

**Background/Explanation**
- Visual chronology improves retention and clarifies cause-and-effect across decades.

---

## Slide 34 — Incident Metrics Slide (Suggested Improvement #5)
**Key Metrics**
- Mean Time to Detect (MTTD)
- Mean Time to Respond (MTTR)
- Dwell Time
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)

**Background/Explanation**
- Metrics convert security performance into measurable business outcomes.
- They support governance reporting and continuous improvement.

---

## Slide 35 — Quality and Terminology Review (Suggested Improvement #6)
**Enhancement**
- Correct typographical and terminology issues (e.g., “compeditors” → “competitors”).
- Standardize capitalization, date formats, and acronym expansions on first use.

**Background/Explanation**
- Language clarity improves professionalism, comprehension, and assessment accuracy.

---

## Slide 36 — Cross-Slide Connections and Revision Summary
**How the Story Connects**
- Rising data value and digitization (Slides 5–6) create demand (Slide 4).
- Historical incidents (Slides 13–28) explain modern legal, technical, and strategic controls.
- CIA Triad (Slide 29) is the analytic lens used across all incidents.
- Lifecycle, metrics, and case structure (Slides 30–34) turn lessons into operational practice.

**Revision Summary Implemented**
- Added improvements 1–6.
- Added full acronym expansions.
- Added dedicated CIA slide.
- Expanded explanatory/background detail for each slide.
- Preserved and incorporated all pasted source content into this enhanced deck.
