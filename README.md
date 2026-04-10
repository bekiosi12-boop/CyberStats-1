🛸 CyberStats
A Futuristic, High-Performance System Monitor for macOS

CyberStats is a specialized macOS menu bar application built with SwiftUI. It provides real-time hardware telemetry with a deep-space, cyberpunk aesthetic. Monitor your machine's "vital organs" through a glowing, animated dashboard designed for power users and aesthetic enthusiasts.

🚀 Features
Processor (CPU): Real-time load tracking with dynamic micro-graphs and thermal (Celsius) monitoring.

Graphics (GPU): Live GPU engine analysis with high-contrast orange neon telemetry.

Memory (RAM): Accurate physical memory tracking with segmented "old-school terminal" progress bars.

Storage (SSD): Detailed disk space analysis with sector-based visual indicators.

Energy (Battery): Smart power monitoring with charging states and circular health gauges.

Cyberpunk Aesthetic: Deep blue and purple animated gradients, blurred glass effects (Glassmorphism), and neon-glow UI components.

🛠 Tech Stack
Language: Swift 5.10+

Framework: SwiftUI

Architecture: MVVM (EnvironmentObject for live data binding)

System Hooks: ProcessInfo, mach_host_self, FileManager, and IOKit simulations for real-time hardware polling.

📜 License
Distributed under the MIT License. See LICENSE for more information.
