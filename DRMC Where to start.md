# Where to Start: Your Guide to the DRMC Governance Documents

**Welcome to the DRMC 2026 Governance Framework!**

If you're feeling overwhelmed by the number of new documents, you're not alone. We've moved from a single, simple document to a comprehensive system designed to protect our community, ensure transparency, and make running the club easier for everyone.

Think of this as your **roadmap**. Each document has a specific job, and they all work together. This guide will explain what each file is, why it exists, and how it relates to the others.

---

## The Big Picture: How It All Fits Together

Imagine our governance system as a house:

1.  **The Foundation (Unalterable):** The **Charter** is the bedrock. It establishes who we are and our core purpose. It cannot be changed without a fundamental restructuring of the corporation.
2.  **The Framework (The Rules):** The **Bylaws** are the walls, roof, and load-bearing beams. They contain all the detailed rules for how we operate, from voting to finances. They can be changed, but only by a rigorous member vote.
3.  **The Daily Life (Living in the House):** The **Code of Conduct, Templates, and Protocols** are the "house rules" and user manuals. They guide our daily interactions, how we plan events, run projects, and elect our leaders. They are easier to update as our needs evolve.

---

## Document Relationships: A Visual Guide

```mermaid
graph TD
    %% Define documents with styling
    Charter["📜 ARTICLES OF INCORPORATION (Charter)<br/>The Unalterable Foundation"]
    Bylaws["📘 BYLAWS 2026<br/>The Comprehensive Rulebook"]
    CoC["⚖️ CODE OF CONDUCT<br/>Daily Behavior & Facility Rules"]
    VotingGuide["🗳️ MEMBERSHIP & VOTING SUMMARY<br/>Plain-Language Voting Guide"]
    Election["🗳️ ELECTION & NOMINATION PROTOCOL<br/>How to Run & Vote in Elections"]
    DirectorAgree["📝 DIRECTOR'S AGREEMENT<br/>Contract for Board Members"]
    ActivityTemp["📋 ACTIVITY PROPOSAL TEMPLATE<br/>For Social Events & Fundraisers"]
    ProjectTemp["📋 PROJECT PROPOSAL TEMPLATE<br/>For Capital Improvements & Major Work"]
    MemberAgree["📝 MEMBERSHIP AGREEMENT<br/>Contract for All Members"]
    OldBylaws["🗑️ BYLAWS 2025 (Old)<br/>Replaced - For Reference Only"]
    WhatsChanging["📄 WHAT'S CHANGING<br/>Summary of 2025 vs 2026"]

    %% Relationships
    Charter -->|"Empowers and restricts"| Bylaws
    Charter -->|"Defines 'Objects' for"| CoC
    Charter -->|"Establishes classes for"| VotingGuide

    Bylaws -->|"Article V-A adopts by reference"| CoC
    Bylaws -->|"Article XI governs"| Election
    Bylaws -->|"Article XV governs"| ActivityTemp
    Bylaws -->|"Article X governs"| ProjectTemp
    Bylaws -->|"Article IV defines"| VotingGuide

    CoC -->|"Must be signed by"| MemberAgree
    Bylaws -->|"Compliance required by"| DirectorAgree
    Bylaws -->|"Compliance required by"| MemberAgree

    OldBylaws -.->|"Compared in"| WhatsChanging
    Bylaws -.->|"Summarized in"| WhatsChanging

    %% Styling
    classDef foundation fill:#f9f,stroke:#333,stroke-width:2px;
    classDef rulebook fill:#bbf,stroke:#333,stroke-width:2px;
    classDef daily fill:#bfb,stroke:#333,stroke-width:2px;
    classDef agreement fill:#ffb,stroke:#333,stroke-width:2px;
    classDef guide fill:#feb,stroke:#333,stroke-width:2px;

    class Charter foundation;
    class Bylaws rulebook;
    class CoC,ActivityTemp,ProjectTemp,Election daily;
    class DirectorAgree,MemberAgree agreement;
    class VotingGuide,WhatsChanging guide;