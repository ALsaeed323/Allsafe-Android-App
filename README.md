# Allsafe Android Pentesting Challenges

## Introduction
Welcome to the **Allsafe Android Pentesting Challenges** repository. This project is designed to enhance your Android security skills through practical pentesting challenges. Each challenge guides you through identifying and exploiting vulnerabilities in Android applications using static and dynamic analysis, reverse engineering, and various exploitation techniques.

This repository covers the following areas of Android pentesting:
- **Insecure Logging**
- **Hardcoded Credentials**
- **Firebase Database Misconfigurations**
- **Insecure Shared Preferences**
- **SQL Injection**
- **PIN Bypass**
- **Root Detection Bypass**
- **Secure Flag Bypass**
- **Deep Link Exploitation**
- **Insecure Broadcast Receiver**
- **Vulnerable WebView**
- **Certificate Pinning Bypass**
- **Weak Cryptography**
- **Insecure Service**
- **Object Serialization Vulnerabilities**
- **Insecure Providers**
- **Arbitrary Code Execution**
- **Native Library Vulnerabilities**
- **Smali Patch Exploitation**

---

## Tools Overview

The challenges in this repository involve using a variety of tools to perform static and dynamic analysis, reverse engineering, and exploit Android vulnerabilities. Below is a brief overview of the key tools you will be using:

- **adb (Android Debug Bridge)**: The command-line tool to interact with Android devices and monitor system logs.
- **Frida**: A powerful dynamic instrumentation toolkit used to hook and modify app behavior in real-time.
- **apktool**: A tool for reverse engineering Android APKs, used to decompile and analyze the app’s resources and manifest files.
- **MEDUSA**: An extensible and modularized framework that automates processes and techniques practiced during the dynamic analysis of Android and iOS applications. It assists in:
  - **Dynamic Function Tracing**: Track how sensitive data is processed in real-time during app execution.
  - **Tampering with App Behavior**: Modify or bypass security controls like root detection, SSL pinning, and more.
  - **Cross-Platform Support**: Analyze both Android and iOS apps.
  - **Modular Design**: Extend the framework with custom modules for specific testing needs.
- **Mobile Security Framework (MobSF)**: An open-source security analysis tool for performing static and dynamic analysis of Android APKs.
- **Drozer**: A comprehensive security testing framework that allows interaction with Android apps, particularly for assessing IPC (Inter-Process Communication) mechanisms.
- **IDA Freeware**: A free version of the Interactive Disassembler, used for reverse engineering and disassembling binaries. It helps in static analysis, giving insights into the application’s low-level code structure, making it easier to understand the behavior of an application.

These tools are essential for performing in-depth analysis and crafting efficient exploits in Android applications. Mastering these tools will significantly improve your ability to identify and exploit vulnerabilities in mobile apps.

---

## Using This Repository

### Setting Up Your Environment
Before starting with the challenges, make sure to set up your environment:

1. **Install necessary tools**: Install the tools mentioned above, either manually or using package managers like `apt`, `brew`, or through Docker.
2. **Connect your device**: Ensure you have an Android device or emulator connected via adb for testing purposes.
3. **Set up Frida**: Use `frida-server` to inject code into running processes on the device. Make sure the Frida server is running on the device.
4. **Decompile APKs**: Use `apktool` to decompile the application APKs for static analysis.
5. **Automate analysis**: Use MobSF for automated static and dynamic analysis of APK files.

### Getting Started
