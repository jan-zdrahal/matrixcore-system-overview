# MatrixCore™ System Overview

Version: 1.0  
Status: Stable  
Date: 2026-03-21  

Author: Jan Zdráhal  
ORCID: https://orcid.org/0009-0005-2012-1234  
DOI: https://doi.org/10.5281/zenodo.19154320  
Web: https://matrixcore.org  

---

## Overview

MatrixCore™ System Overview describes the conceptual structure of the MatrixCore ecosystem and the relationships between specification layers.

The document explains how architectural space, projections, profiles, and representations interact to provide a deterministic and extensible architecture meta-model.

---

## Scope

This specification defines:

- conceptual structure of the MatrixCore specification stack
- relationships between specification layers
- separation of structure, constraints, interpretation, and representation
- roles of profiles and projections

This specification does not define:

- mathematical formalization of architectural space
- implementation technologies
- execution semantics
- domain-specific constraints

---

## Conceptual Structure

The MatrixCore ecosystem is organized into layered specifications.

### L0 — Core Model

Defines the mathematical structure of architectural space.

- architectural dimensions
- artifacts
- relations
- invariants
- projection mechanisms

### L1 — Meta Model

Defines interpretation mechanisms over architecture.

- projection systems
- visualization models
- projection composition
- conflict formalization

### L2 — Profile Framework

Defines constraint systems over architectural space.

- dimension specialization
- invariant extension
- admissible subspaces

### L3 — Domain Profiles

Defines domain-specific structural specializations.

- layered architecture structures
- distributed system structures
- AI system structures

### L4 — Domain Projections

Defines interpretation layers over architectural structures.

- responsibility mappings
- licensing mappings
- compliance semantics

### L5 — Technical Representation

Defines canonical external representations.

- JSON models
- graph representations
- diagram representations

---

## Canonical Version

The canonical version of this specification is defined by the DOI record:

https://doi.org/10.5281/zenodo.19154320

Repository working versions may contain drafts that are not canonical.

---

## Publication

DOI:  
https://doi.org/10.5281/zenodo.19154320

Repository:  
https://github.com/jan-zdrahal/matrixcore-system-overview

Release tag:  
v1.0

---

## Versioning

Version identifiers follow semantic versioning.

v1.0 — initial stable release  
v1.1 — clarifications, wording improvements, examples  
v2.0 — changes affecting conceptual structure

Canonical versions are immutable once published.

---

## Related Specifications

MatrixCore Architectural Space Framework  
https://doi.org/10.5281/zenodo.19153595  

MatrixCore Design Principles  
https://doi.org/10.5281/zenodo.19155760  

MatrixCore Licensing Model  
https://doi.org/10.5281/zenodo.19160540  

---

## License

This specification is licensed under:

Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)

https://creativecommons.org/licenses/by-nd/4.0/
