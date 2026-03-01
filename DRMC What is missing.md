# DRMC: What Governance Documents Are Missing?

**Document Version: 1.0 – March 2026**

**Purpose:** This document identifies gaps in the current DRMC governance framework and provides a roadmap for creating additional policies and procedures to strengthen our operations, financial controls, and institutional memory.

Your current documentation is exceptionally strong on **governance structure** (Bylaws, Charter, Code of Conduct). The following recommendations address **operational continuity, financial controls, and human resources** to create a fully resilient organization.

---

## Overview: The Current State

| Strength | Gap |
|----------|-----|
| ✅ Comprehensive Bylaws & Charter | ❌ Limited operational procedures (SOPs) |
| ✅ Strong Code of Conduct | ❌ No formal privacy policy (PIPEDA) |
| ✅ Excellent election & nomination protocol | ❌ Missing financial reserves policy |
| ✅ Robust project & activity templates | ❌ No document retention schedule |
| ✅ Clear membership agreements | ❌ No formal volunteer role descriptions |

---

Descriptive
## Detailed Descriptions of Missing Documents

The following section provides a comprehensive breakdown of each missing document, including its purpose, key components, and how it integrates with the existing governance framework.

---

### 1. Standing Operating Procedures (SOPs)

**Purpose:** To standardize the day-to-day execution of duties for specific officer roles (e.g., Harbour Master, Treasurer, Secretary) and recurring tasks.

**Why It's Missing:** While the Bylaws define the existence of these roles (Article XII), they do not provide step-by-step instructions on *how* to perform the associated duties.

**Key Content:**
- **Harbour Master:** Moorage assignment protocol, waitlist management, dock inspection checklist.
- **Treasurer:** Accounts payable/receivable process, bank reconciliation timeline, financial reporting schedule.
- **Secretary:** Meeting agenda preparation, minute-taking standards, official correspondence log.

**Value:** Ensures consistency of operations during officer transitions, preserving institutional knowledge.

---

### 2. Reserves & Investment Policy

**Purpose:** To establish clear guidelines for the accumulation, management, and expenditure of capital funds and operating reserves.

**Why It's Missing:** The Bylaws imply financial stewardship (Article VI) but lack specific guardrails for surplus funds.

**Key Content:**
- Target reserve levels (e.g., 3-6 months of operating expenses).
- Approved investment vehicles (e.g., high-interest savings, GICs) and prohibited speculative investments.
- Authorization threshold for withdrawing from reserves (e.g., board vote vs. membership vote).

**Value:** Protects the club from financial instability and ensures funds are available for major capital repairs or emergencies.

---

### 3. Document Retention Policy

**Purpose:** To define how long different types of records (financial, legal, membership) must be kept and the process for secure disposal.

**Why It's Missing:** Explicitly required by Article XXIII of the Bylaws to manage the club's records.

**Key Content:**
- Retention schedules for incorporation documents (permanent), financial records (7 years), membership applications (duration of membership + 1 year).
- Protocols for digital vs. physical record storage.
- Destruction procedures for sensitive information (shredding, secure data wiping).

**Value:** Reduces legal risk, ensures compliance with CRA requirements, and manages physical/digital storage costs.

---

### 4. Privacy Policy (PIPEDA Compliance)

**Purpose:** To outline how the club collects, uses, discloses, and protects personal information of members, volunteers, and contractors.

**Why It's Missing:** Mandated by federal law (PIPEDA) for organizations collecting personal data. The current framework does not address consent or data security.

**Key Content:**
- Definition of personal information collected (names, addresses, boat details, payment info).
- Statement of consent and purpose of collection.
- Security safeguards (who has access to member lists).
- Individual access and correction rights.

**Value:** Legal compliance and building trust with members regarding their data privacy.

---

### 5. Volunteer Position Descriptions

**Purpose:** To provide clear, written expectations for all volunteer roles, including squads and committees.

**Why It's Missing:** Article XV of the Bylaws establishes the volunteer structure, but without formal descriptions, roles can become ambiguous.

**Key Content:**
- Role title and reporting structure.
- Primary responsibilities and expected time commitment.
- Required skills or training.
- Term limits (if any).

**Value:** Helps recruit suitable volunteers, sets clear performance expectations, and prevents volunteer burnout by defining scope.

---

### 6. Emergency Response Plan

**Purpose:** To provide a detailed, actionable plan for responding to various crises, ensuring the safety of members and property.

**Why It's Missing:** Required by Article XX.2 of the Bylaws. A general safety awareness is not sufficient for a marina environment.

**Key Content:**
- Specific procedures for fire, medical emergency, fuel spill, severe weather, and man-overboard.
- Emergency contact tree and communication protocol.
- Location of emergency equipment (fire extinguishers, first aid kits, spill kits).
- Evacuation routes and muster points.

**Value:** Ensures a rapid, coordinated response that minimizes harm and liability.

---

### 7. Grievance Procedure

**Purpose:** To establish a formal, fair, and confidential process for resolving disputes between members, or between members and the board.

**Why It's Missing:** The Code of Conduct sets behavioral standards (Section 9), but there is no defined mechanism to address violations or interpersonal conflicts.

**Key Content:**
- Step-by-step process for submitting a formal complaint.
- Formation and role of a grievance committee.
- Timeline for acknowledgment, investigation, and resolution.
- Appeal process and principles of natural justice.

**Value:** Provides a fair pathway to resolve conflicts before they escalate, protecting the club's culture and reducing board liability.

---

### 8. Access Control Policy

**Purpose:** To govern the issuance, use, and recovery of keys, fobs, gate codes, and other security devices for club facilities.

**Why It's Missing:** Security is currently implied, but without a policy, key control can become lax, creating safety and liability risks.

**Key Content:**
- Eligibility criteria for receiving access devices.
- Procedure for requesting and returning keys/fobs (e.g., deposit system).
- Rules against loaning access devices to non-members.
- Protocol for changing codes after theft or non-return.

**Value:** Enhances physical security of the clubhouse, dry storage, and dock facilities, protecting assets and members.


## Document Relationships: What's Missing

```mermaid
graph TD
    %% Existing Documents
    Bylaws["📘 BYLAWS 2026<br/>(The Rulebook)"]
    
    %% Missing Documents (with red outline styling)
    SOPs["🔴 STANDING OPERATING PROCEDURES<br/>For Harbour Master, Treasurer, etc."]
    Reserves["🔴 RESERVES & INVESTMENT POLICY<br/>How we manage capital funds"]
    Retention["🔴 DOCUMENT RETENTION POLICY<br/>What to keep & for how long"]
    Privacy["🔴 PRIVACY POLICY (PIPEDA)<br/>How we handle member data"]
    VolunteerPD["🔴 VOLUNTEER POSITION DESCRIPTIONS<br/>Clear roles for squads"]
    Emergency["🔴 EMERGENCY RESPONSE PLAN<br/>Detailed procedures for crises"]
    Grievance["🔴 GRIEVANCE PROCEDURE<br/>Formal conflict resolution"]
    Access["🔴 ACCESS CONTROL POLICY<br/>Keys, fobs & security"]

    %% Relationships
    Bylaws -->|"Article XXIII requires"| Retention
    Bylaws -->|"Article XII empowers"| SOPs
    Bylaws -->|"Article VI implies"| Reserves
    Bylaws -->|"Article XX.2 requires"| Emergency
    Bylaws -->|"Article XV governs"| VolunteerPD
    CodeOfConduct["⚖️ CODE OF CONDUCT"] -->|"Section 9 implies"| Grievance
    
    PIPEDA["📋 PIPEDA (Federal Law)"] -->|"Mandates"| Privacy

    %% Styling for missing docs
    classDef missing fill:#ffcccc,stroke:#ff0000,stroke-width:2px;
    class SOPs,Reserves,Retention,Privacy,VolunteerPD,Emergency,Grievance,Access missing;
	
	
