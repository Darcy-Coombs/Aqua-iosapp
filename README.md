# Project Aqua - Decentralized Gossip Node


## Features
- **Kotlin Multiplatform** for code reuse across **macOS, Windows, Linux, iOS, and Android**.
- **Gossip Protocol** (WIP) for peer-to-peer communication.
- **DAG Consensus** for secure, high-speed validation.
- **Jetpack Compose for Desktop** UI for macOS (later for Windows/Linux).
- **Apple Secure Enclave** (planned) for identity authentication.

---

## Project Structure
📁 ProjectRoot/ ├── 📁 shared/ # Core gossip protocol + DAG logic (common to all platforms) ├── 📁 macosApp/ # macOS UI + Secure Enclave integration ├── 📁 desktopApp/ # Jetpack Compose UI for Windows/Linux/macOS (future) ├── 📁 iosApp/ # iOS (future implementation) ├── build.gradle.kts # Gradle build configuration ├── settings.gradle.kts
