# 🔁 Modified TSPC Flip-Flop Design 

Designing and comparing a baseline TSPC flip-flop against a modified low-power version in Cadence Virtuoso.

---

## 🔍 Overview

This project involves designing **two TSPC (True Single-Phase Clock) flip-flops** — a standard baseline topology and a modified version aimed at reducing redundant switching activity — and comparing them across key performance and power parameters, including layout-level analysis.

---

## 🎯 Objectives

- Design the baseline TSPC flip-flop and a modified low-power variant.
- Compare both designs on:
  - Area
  - Average Power
  - Clock-to-Q (C2Q) Delay
  - Power-Delay Product (PDP)
  - Setup Time
  - Hold Time
- Extend comparison to the **layout level**, not just schematic.

---

## 🧠 Approach

- **Schematic design:** Built both baseline and modified TSPC flip-flops in Cadence Virtuoso.
- **CMOS analysis:** Studied transistor sizing, leakage current, and setup/hold constraints under varying supply voltages and frequencies.
- **Corner simulation:** Extracted clock-to-Q delay across process corners for both designs.
- **Layout:** Designed layouts for both topologies to compare post-layout area and parasitics.
- **Benchmarking:** Compared area, average power, C2Q delay, PDP, setup time, and hold time between the two designs.

---

## 🛠️ Tools Used

- Cadence Virtuoso (Schematic + Layout)
- Spectre / ADE (Simulation & Corner Analysis)

---

## 🚧 Status

Work in progress — schematic designs for both flip-flops are complete; layout and full parameter-wise comparison are ongoing.

## 📌 Next Steps

- Complete layout for both designs.
- Finalize comparison table (Area, Power, C2Q Delay, PDP, Setup/Hold Time).
- Add simulation waveforms and layout screenshots.
