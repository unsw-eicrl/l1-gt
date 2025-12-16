# contributing

L1-GT is an open research platform developed within the embodied intelligence & collective robotics lab at UNSW. Contributions are welcome, but the project is curated and maintained on a best-effort basis. Inclusion in the reference design is discretionary and depends on scope, fit, and maintainer capacity.

This document outlines what kinds of contributions are useful and how to engage constructively.

---

## what to contribute

The most useful contributions are concrete and self-contained, for example:
- validated substitutions for unavailable components
- alternative mechanical designs or adaptations
- build notes, corrections, or assembly tips
- measurements, test data, or failure reports

Feature requests without accompanying work are unlikely to be acted upon.

---

## current areas of interest

The reference design uses the mjbots **qdd100** actuator, which may be unavailable. 

Well-documented experiments with alternative geared BLDC actuators are particularly welcome, including:
- mechanical integration and mounting (e.g., the Cubemars AKE80-8 (KV30) appears promising, but requires mechanical and controller integration)
- compatibility with controllers such as mjbots *moteus*
- practical performance observations and limitations
- software and documentation

Independent exploration, with clear documentation of what worked and what did not, is valued.


---

## how to contribute

1. Fork the repository  
2. Create a focused feature branch  
3. Make scoped, well-documented changes  
4. Open a pull request with a concise description

Where applicable, include drawings, CAD exports, BOM updates, and test notes.

---

## CAD contributions

Mechanical designs are authored in Fusion 360, but collaboration does not take place inside shared Fusion projects.

Contributors should work in their own CAD environments and submit changes as:
- neutral CAD exports (STEP)
- optionally, clean `.f3d` or `.f3z` files for reference

STEP files are treated as the authoritative interface for review and integration.  
Shared access to Fusion projects is not used.

---

## issues and communication

This repository is not a support forum.

Issues should be used to report clear errors or omissions in the documentation.  
Not all issues or pull requests will receive a response.

---

## licensing

By contributing, you agree that your contributions will be licensed under the same terms as the relevant parts of the repository, as described in `LICENSE.md`.
