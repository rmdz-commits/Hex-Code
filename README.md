# 🔢 Hex Value Reference

![Platform](https://img.shields.io/badge/Platform-ARM%20%2F%20Mobile-blue?style=for-the-badge&logo=android)
![Type](https://img.shields.io/badge/Type-Memory%20Editing-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-green?style=for-the-badge)

> **A curated reference of Hex values commonly used for memory modification.** > Optimized for modifying Integers, Floats, Doubles, Booleans, and Assembly Instructions (NOP).

---

## 📑 Table of Contents
- [Control & Operations](#-control--operations)
- [Boolean Logic](#-boolean-logic)
- [Double Values (Currency/Points)](#-double-values)
- [Numeric Constants](#-numeric-constants)
- [Usage Guide](#-usage-guide)

---

## 🛠 Control & Operations
Use these values to freeze memory addresses, disable instructions, or manipulate specific data types.

| Description | Hex Value | Type |
| :--- | :---: | :---: |
| **Freeze Integer** | `E70300E31EFF2FE1` | `int` |
| **Freeze Float** | `7A0404E31EFF2FE1` | `float` |
| **NOP (No Operation)** | `00F020E31EFF2FE1` | `instruction` |
| **String (Coins/Gems)** | `747080E51EFF2FE1` | `string` |

---

## ✅ Boolean Logic
Force specific states (Enable/Disable features).

| State | Value | Hex Code |
| :--- | :---: | :---: |
| **TRUE** (Enable) | `1` | `0100A0E31EFF2FE1` |
| **FALSE** (Disable) | `0` | `0000A0E31EFF2FE1` |

---

## 💎 Double Values
Commonly used for setting large currency amounts, scores, or resources.

| Target Value | Hex Code |
| :--- | :---: |
| **3,000** | `3B0544E31EFF2FE1` |
| **4,000** | `7A0544E31EFF2FE1` |
| **5,984** | `840945E31EFF2FE1` |
| **8,000** | `FA0544E31EFF2FE1` |
| **9,984** | `1C0644E31EFF2FE1` |
| **9,999** | `1C0644E31EFF2FE1` |
| **10,048** | `1D0644E31EFF2FE1` |
| **99,840** | `C30744E31EFF2FE1` |
| **348,160** | `AA0844E31EFF2FE1` |
| **946,176** | `670944E31EFF2FE1` |
| **99,614,720** | `BE0C44E31EFF2FE1` |
| **998,244,352** | `6E0E44E31EFF2FE1` |
| **99,857,989,632** | `BA0145E31EFF2FE1` |

---

## 🔢 Numeric Constants
Standard integer values often used for level counts, item quantities, or stats.

| Number | Hex Code | Special Note |
| :---: | :---: | :--- |
| **2** | `0200A0E31EFF2FE1` | - |
| **7** | `0700A0E31EFF2FE1` | - |
| **10** | `0A00A0E31EFF2FE1` | - |
| **15** | `0F00A0E31EFF2FE1` | - |
| **16** | `1000A0E31EFF2FE1` | - |
| **17** | `1100A0E31EFF2FE1` | - |
| **50** | `3700A0E31EFF2FE1` | - |
| **255** | `FF00A0E31EFF2FE1` | Max Byte Value |
| **High Value** | `1207A0E31EFF2FE1` | Generic High Money |

---

## 📘 Usage Guide

### 1️⃣ Freezing Values
To prevent a value (like Health or Ammo) from decreasing:
> Apply `E70300E31EFF2FE1` to the target address.

### 2️⃣ Enabling Features
To force a feature on (e.g., Unlock All):
> Replace the check instruction with **Boolean True**: `0100A0E31EFF2FE1`

### 3️⃣ Disabling Checks
To bypass a security check or function:
> Overwrite the instruction with **NOP**: `00F020E31EFF2FE1`

---

###### ⚠️ Disclaimer: This documentation is for educational and reference purposes only.
