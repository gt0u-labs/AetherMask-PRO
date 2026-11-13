# 🛡️ AetherMask PRO | Local Network Identity & Telemetry Manager

![Status](https://img.shields.io/badge/Status-Architectural_Case_Study-black?style=for-the-badge)
![Network](https://img.shields.io/badge/Module-Network_Obfuscation-darkred?style=for-the-badge)
![Framework](https://img.shields.io/badge/Built_with-ElectronJS-191970?style=for-the-badge&logo=Electron&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows_10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)

> **Note:** This repository serves as an architectural case study for local network management and system telemetry. The source code is maintained privately (Closed Source). 

AetherMask PRO is a lightweight, offline-first networking utility focused on local network adapter identity management, system telemetry, and clean desktop workflows. It was engineered for homelab administrators, power users, and IT professionals who require precise local control without cloud dependencies.

## ⚡ Technical Overview

Built to operate entirely independent of external servers, AetherMask PRO provides a secure local environment for modifying hardware identifiers and monitoring system loads, utilizing encrypted local storage for configuration persistence.

## 🚀 Core Capabilities

### 🌐 Network Identity Obfuscation
*   **Dynamic Identity Refresh:** Manage and modify local network adapter configurations (MAC addresses) through a clean, intuitive UI interface to bypass local restrictions or facilitate VPN routing protocols.

### 📊 Real-Time System Telemetry
*   **Hardware Monitoring:** Live data streams tracking CPU cycles, memory allocation, and active network states directly from the Windows kernel.

### 🔐 Encrypted State Management
*   **Secure Local Storage:** All user configurations, saved identities, and application states are secured locally using **AES-256 encryption**.

### 🛑 Offline-First Architecture
*   **Air-Gapped Operation:** No subscriptions, no cloud sync, no online accounts. Designed to function in completely isolated network environments.

## 💻 System Requirements
*   Windows 10 / Windows 11 (64-bit)
*   x64 Architecture
*   **Note:** Administrator privileges are required to execute network adapter configuration changes.

## 📥 Deployment
Check the **Releases** tab for the latest stable build. 
The application functions as a standalone desktop utility—no external launchers or activation platforms required.

---
*Architected and maintained by [GT0u Labs](https://gt0u-labs.github.io).*
