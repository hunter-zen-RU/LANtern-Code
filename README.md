# LANtern Code 💡

<img width="2048" height="768" alt="LANtern Code_ Connect, Collaborate, Code" src="https://github.com/user-attachments/assets/02f807be-03d6-4133-b9e2-067ed0bfa874" />




Illuminate your workflow. Code together, anywhere.

LANtern Code is a high-performance, feature-rich Android IDE and collaborative studio designed for modern developers who need desktop-grade project management on a mobile device. Whether you are working solo on the move or syncing with a local team in a hackathon, LANtern Code bridges the gap between localized offline development and cloud-based version control.
The platform empowers developers to create, edit, compile, and manage complex codebases directly from Android, featuring a powerful real-time shared workspace engine that functions flawlessly across local networks (LAN) and wide area networks (WAN).

# 🚀 Core Features


1. Robust Project & Git Management

• Full Git Integration: Clone, commit, push, pull, branch, and merge directly with GitHub, GitLab, or custom self-hosted repositories.
• Local Project Studio: Create and organize multi-file projects from scratch with an intuitive file tree navigation system.
• Desktop-Grade Editor: Syntax highlighting, code auto-completion, linting, and error checking tailored for mobile screens.

2. LAN/WAN Shared Workspaces

• Decentralized Collaboration: Host a local development session over Wi-Fi/LAN without relying on external internet servers.
• WAN Cloud Syncing: Seamlessly transition to a WAN environment to invite remote teammates into your active workspace.
• Real-Time Peer Editing: Watch your team code in real-time with live cursor tracking, conflict resolution, and instant peer-to-peer file syncing.

3. Integrated Network Browser

• Workspace Discovery: Automatically scan your local network to discover active team studios or broadcast your own.
• Secure Access Controls: Manage permissions easily, allowing read-only access for reviewers or full-write capabilities for core co-developers.

🛠️ Target Audience

• Mobile-First Developers: Software engineers looking for a true, uncompromised IDE experience on Android tablets and foldables.
• Hackathon & Agile Teams: Teams requiring rapid, zero-setup collaborative coding tools over a shared local router.
• Students & Educators: An accessible tool for computer science classrooms to host interactive, local pair-programming sessions.

💻 Tech Stack & Architecture (Overview)

• Frontend: Jetpack Compose (Kotlin) for a fully responsive, modern Material 3 UI.
• Version Control: JGit / Custom native Git binaries optimized for Android architecture.
• Networking Protocol: WebSockets and WebRTC for low-latency peer-to-peer data syncing and workspace discovery via mDNS / NSD (Network Service Discovery).
