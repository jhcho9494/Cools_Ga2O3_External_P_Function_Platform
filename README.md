# Cools Ga₂O₃ External P-Function Platform

[한국어](README_KR.md) | [中文](README_ZH.md) | [Patent Portfolio](PATENT_PORTFOLIO.md) | [Public Notice](PUBLIC_NOTICE.md)

## Do not force gallium oxide to become p-type. Import the p-function from outside.

Gallium oxide offers an ultra-wide bandgap, high critical electric field, and a structurally attractive melt-grown substrate route. Its central device limitation is the difficulty of obtaining a practical native p-type region.

Cools addresses that limitation by separating **the n-type Ga₂O₃ power-function layer** from **the p-function block**.

Instead of requiring Ga₂O₃ itself to become p-type, the platform introduces the required depletion, field-control, rectification, gate-safety, or hole-related function through an external functional region.

---

## 1. Platform concept

```text
Conventional target
n-Ga₂O₃ + native p-Ga₂O₃ region
             ↓
Deep acceptor levels, hole self-trapping, impractical p-type conduction

Cools architecture
n-Ga₂O₃ functional layer
        +
external p-function block
        ↓
field termination / junction barrier / normally-off control / p-n heterojunction
```

The external p-function block can be implemented as:

1. a deposited or embedded p-type oxide region,
2. a p-type oxide grid in a junction-barrier Schottky structure,
3. a fixed-charge or external-p-oxide depletion structure for a p-body-free normally-off transistor,
4. a separately grown single-crystal p-type semiconductor layer transferred and grafted onto Ga₂O₃, or
5. a combination of the above with selective photothermal processing and an SiC/RBSC thermal platform.

---

## 2. External p-type oxide region

A p-type oxide such as nickel oxide or copper oxide is placed in contact with n-type Ga₂O₃ to form a heterojunction p-n function without p-doping the Ga₂O₃ itself.

The external p-type oxide can provide:

- junction termination and guard-ring field relief,
- reverse-current blocking,
- depletion expansion,
- heterojunction rectification, and
- local p-functionality only where it is required.

The architecture preserves the high-field n-type Ga₂O₃ drift region while supplementing only the unavailable p-function.

---

## 3. P-body-free normally-off Ga₂O₃ transistor

A normally-off field-effect transistor is formed without a native p-type Ga₂O₃ body.

Zero-bias channel depletion may be produced by:

- fixed negative charge in the gate dielectric or at the dielectric/channel interface,
- an external p-type oxide body under or adjacent to the gate,
- complete depletion of a thin Ga₂O₃ channel combined with gate-work-function design, or
- combinations of these mechanisms.

The design shifts the threshold voltage in the positive direction so that the channel remains closed when the gate drive is absent. This provides a fail-safe device state without requiring native p-Ga₂O₃.

---

## 4. External-p-oxide junction-barrier Schottky diode

The platform places p-type oxide grid regions between Schottky conduction regions.

```text
Forward bias:
current flows through the low-barrier Schottky regions

Reverse bias:
depletion regions expand from the external p-type oxide grid
→ shield the Schottky interface
→ reduce electric-field concentration and reverse leakage
```

The grid width, depth, and Schottky-window spacing form a device-design space for balancing low forward voltage and low reverse leakage.

---

## 5. Grafted single-crystal p-type semiconductor

For applications requiring higher crystalline quality, carrier density, or mobility than a deposited oxide p-block can provide, a separately grown single-crystal p-type semiconductor can be transferred and bonded to n-type Ga₂O₃.

Candidate grafted layers include:

- p-type silicon,
- p-type gallium nitride, and
- p-type diamond.

The grafted layer may function as:

- the p-side of a heterojunction diode,
- a p-gate or depletion-control region,
- a junction-termination region, or
- a field-relief structure.

Band alignment and interface engineering are selected according to whether the objective is reverse blocking, hole injection, depletion control, or electric-field shaping.

---

## 6. Selective photothermal processing

The Ga₂O₃ device family can be combined with selective photothermal annealing on an SiC-containing support.

Rather than heating the entire device stack, optical energy is preferentially absorbed in a designed selective-absorption region such as:

- a heavily doped contact region,
- an ion-implantation damaged region,
- a growth-defect or regrowth-interface region,
- a defect-level-rich region,
- a metal/semiconductor contact interface, or
- an optical absorber-assist layer.

The optical path may be from the Ga₂O₃ side, the SiC side, a sidewall, an oblique direction, or a dedicated opening. The process can locally activate dopants, recover damage, improve ohmic contact, and reduce electrical or thermal interface resistance while protecting the remaining device structure from a full high-temperature cycle.

---

## 7. Thermal integration with SiC and RBSC

The external p-function architecture is compatible with a thermally integrated Ga₂O₃-on-SiC or Ga₂O₃-on-RBSC structure.

The Ga₂O₃ thin functional layer provides the high-field semiconductor function, while the SiC-based support provides:

- heat spreading,
- mechanical support,
- package-base integration,
- optional backside electrical routing, and
- compatibility with local photothermal processing.

This creates a combined architecture:

```text
external p-function device engineering
                    +
Ga₂O₃ ultra-wide-bandgap active layer
                    +
SiC/RBSC thermal and package backbone
```

---

## 8. Patent architecture

The platform is organized as a coordinated family rather than a single device claim:

| Patent axis | Protected technical space |
|---|---|
| External p-type oxide | General bypass of native Ga₂O₃ p-doping difficulty |
| P-body-free normally-off FET | Zero-bias depletion without native p-body |
| External-p-oxide JBS diode | Low forward drop and reverse-leakage shielding |
| Grafted crystalline p-layer | High-quality external p-function through layer transfer |
| Selective photothermal annealing | Local activation and interface recovery without full-stack heating |
| RBSC-integrated Ga₂O₃ | Thermal, package, and high-voltage system integration |

See [PATENT_PORTFOLIO.md](PATENT_PORTFOLIO.md) for the detailed hierarchy.

---

## 9. Target applications

- high-voltage Ga₂O₃ power switches,
- normally-off fail-safe transistors,
- junction-barrier Schottky rectifiers,
- heterojunction diodes,
- electric-field termination and guard structures,
- industrial high-voltage conversion,
- pulsed-power systems,
- HVDC conversion,
- radiation-tolerant power electronics, and
- thermally integrated UWBG power modules.

---

## 10. Related Cools platforms

- [Cools RBSC WBG Power Platform](https://github.com/jhcho9494/Cools_RBSC_WBG_Power_Platform)
- [Cools Transmissive Self-Aligned Annealing](https://github.com/jhcho9494/Cools_Transmissive_Self_Aligned_Annealing)
- [Cools High-Pressure-Free Hydrogen Anneal](https://github.com/jhcho9494/Cools_HighPressureFree_Hydrogen_Anneal)

---

## Collaboration

Cools is open to structured discussion with semiconductor manufacturers, power-device companies, substrate suppliers, equipment companies, research institutions, and strategic partners regarding evaluation, joint development, licensing, and commercialization.

**Cools — Jinhyun Cho**
