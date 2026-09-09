# Sunshine Health AD AI Version History

This document records the iterative development of the Sunshine Health AI-assisted advertising workflow.

Formal Git version control was introduced in September 2026.

Earlier versions were developed as internal working documents before Git adoption and are preserved under `/historical`.

Historical Git commit dates have not been backdated.

---

## V1.0 — Initial Unified Skill Library

**Status:** Historical Version

### Development Stage

Initial business-rule modelling.

### Architecture

Business Requirements  
→ Unified AI Skill Library

### Main Scope

- Advertisement generation
- WeChat Moments advertisement copywriting
- Product knowledge explanation
- Product comparison
- Promotion planning
- WeChat layout
- Brand visual consistency

### Key Characteristics

- Real product photographs used as the design basis
- Product packaging preserved
- Real shelf environment retained
- Promotions shown only when explicitly provided
- Basic Sunshine Health visual consistency established

### Engineering Significance

V1.0 established the first reusable rule-based AI workflow for Sunshine Health advertising.

At this stage, recognition, generation, copywriting, promotion, comparison and brand rules were maintained together inside one broad skill library.

### Evidence

`historical/v1.0/`

---

## V2.1 — Production Design Specification

**Status:** Historical Version

### Development Stage

Production workflow formalisation.

### Architecture

Product Input  
→ Recognition  
→ Advertisement Classification  
→ Generation Rules  
→ Quality Control

### Major Changes from V1.0

- Added Recognition First, Generation Second principle
- Added explicit advertisement categories
- Added formal product recognition workflow
- Added production visual rules
- Added copywriting standards
- Added sensitive-word handling
- Added quality-control checklist
- Introduced clearer separation between advertisement tasks and other system functions

### Engineering Significance

V2.1 moved the system from a broad instruction library toward a more structured production workflow.

Input recognition, task classification, generation rules and validation started to become separate stages.

### Evidence

`historical/v2.1/`

---

## V3.0 — Master Design Specification

**Status:** Historical Version

### Development Stage

Rule consolidation and integrity enforcement.

### Architecture

Recognition  
→ Product Integrity  
→ Advertisement Type  
→ Visual Rules  
→ Copy Rules  
→ Asset Governance  
→ Final QA

### Major Changes from V2.1

- Strengthened product integrity rules
- Expanded supported advertisement types
- Added gift-set rules
- Added collection and shelf-display rules
- Expanded promotion requirements
- Added logo governance
- Expanded sensitive-language rules
- Added final quality-control checklist
- Strengthened authenticity-first principle

### Engineering Significance

V3.0 marked the transition from a production guideline into a master rule system.

Product identity, packaging integrity, advertisement type, layout, promotion, logo usage, copywriting and QA were managed as distinct rule layers.

This version prepared the system for later modularisation into separate active skills.

### Evidence

`historical/v3.0/`

---

## V4.1 — Retail Advertisement Skill

**Status:** Current Active Version

### Development Stage

Modular retail advertisement skill.

### Architecture

Product Recognition Gate  
→ Product Lock  
→ Information / Store Rules  
→ Fixed Retail Layout  
→ Feature / Ingredient / Promotion Rules  
→ Quality Validation

### Major Changes from V3.0

- Stronger authenticity-first architecture
- Mandatory recognition gate
- Fixed Sunshine Health retail layout
- Product occupancy rules
- Structured feature layout
- Ingredient sticker validation
- Promotion sticker validation
- Stronger real-shelf preservation
- Explicit anti-fabrication rules
- Unified quality checklist

### Current Implementation

`skills/retail-ad/`

---

## Dynamic Video Advertisement Skill V3.0

**Status:** Current Active Video Workflow

### Development Stage

AI video workflow expansion.

This branch evolved from the original advertisement system but is now maintained as a separate active skill.

### Architecture

Product Research  
→ Core Extraction  
→ Five Locks  
→ L1-L10 Visual Definition  
→ Keyframe State Design  
→ Keyframe Validation  
→ Video Transition Definition  
→ Final Video  
→ Final QA

### Major Additions

- PRODUCT LOCK
- INFORMATION LOCK
- STORE LOCK
- LOGO LOCK
- HUMAN LOCK
- L1-L10 visual system
- State-based keyframe generation
- Material-driven motion
- Causal transitions
- Local revision workflow
- Final video QA

### Current Implementation

`skills/dynamic-video-ad/`

---

## Git Formalisation

Formal Git source control was introduced in September 2026.

Historical source documents created before Git adoption are retained under `/historical`.

The repository does not backdate historical Git commits.

All subsequent development, refactoring, testing and documentation changes are tracked through normal Git commits.
