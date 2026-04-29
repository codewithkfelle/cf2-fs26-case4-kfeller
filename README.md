# Peer-Unternehmen Beta Rechner

## Overview
This web application was developed for **CF2 – Case IV: Kapitalkosten (Teilaufgabe 2c)**.  
It allows users to estimate the **Equity Beta of a target company** using a peer group.

Users can input **Equity Betas** and **FK/EK ratios** for up to 10 peers. The app calculates **asset betas**, derives the **mean and median**, and computes a **relevered Equity Beta** based on a chosen target capital structure.

---

## Methodology

**Delevering (Asset Beta):**
`Asset Beta = Equity Beta / (1 + D/E)`


**Relevering:**
`Equity Beta = Asset Beta × (1 + D/E_target)`

Assumption: **Debt Beta = 0**, no tax shield.

---

## Features

- Input for 10 peer companies  
- Automatic calculation of mean & median asset beta  
- Selection between mean or median for relevering  
- Input of target FK/EK ratio  
- Simple, browser-based interface  

---

## Usage

1. Enter Equity Beta and FK/EK for each peer  
2. Select method (mean or median)  
3. Enter target FK/EK  
4. Click "Berechnen"  

---

## Notes

- Assumes risk-free debt (β = 0)  
- No outlier handling  
- Results depend on peer quality  