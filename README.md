# Gridcode
Gridcode is a global, human‑readable coordinate system that encodes any point on Earth into a short, unambiguous alphanumeric code. It defines a deterministic, reversible mapping between latitude/longitude and a fixed‑resolution hierarchical grid.
Gridcode
Gridcode is a global, human‑readable coordinate system that encodes any point on Earth into a short, unambiguous alphanumeric code. It defines a deterministic, reversible mapping between latitude/longitude and a fixed‑resolution hierarchical grid.

This repository contains the public specification, canonical rules, and reference implementation of the Gridcode system.
Its purpose is to establish a clear, timestamped public record of the core ideas and mathematical structure.

Overview
Gridcode provides:

A sequential, hierarchical global grid

A phoneme‑clean alphanumeric alphabet designed for clarity and mishear‑resistance

A deterministic mapping between geographic coordinates and code strings

A reversible decoding process

A fixed, predictable resolution at each refinement level

A canonical format suitable for speech, text, and emergency use

Gridcode is designed for:

Navigation

Logistics

Emergency services

Field operations

Offline and low‑bandwidth environments

Everyday location sharing

Design Goals
Human‑readable: short, pronounceable, unambiguous

Human‑speakable: compatible with NATO/ICAO phonetics

Deterministic: no lookup tables, no databases

Reversible: every code maps back to a unique geographic region

Canonical: one correct representation per location

Predictable: fixed grid geometry and refinement sequence

Robust: resistant to mishearing, mistyping, and transcription errors

Specification
The Gridcode system is defined by:

A global base grid

A refinement sequence

A canonical encoding rule

A canonical decoding rule

A restricted alphabet

A fixed resolution at each level

The full mathematical description is included in the /spec directory.

Reference Implementation
A minimal reference implementation is provided in /src.
It demonstrates:

Encoding latitude/longitude into a Gridcode

Decoding a Gridcode into its geographic bounds

Validation of canonical format

This implementation is intended for clarity, not optimisation.

Status
Gridcode is an evolving open standard.
This repository serves as the authoritative public record of the system’s structure and behaviour.

Licence
MIT Licence for code.
CC‑BY 4.0 for documentation.

Contributions
Gridcode is currently under active development.
Feedback, issues, and proposals are welcome.
