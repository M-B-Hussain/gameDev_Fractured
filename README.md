Project Name: Fractured
Project Overview: 
Fractured is an Unreal Engine 5 (UE5) project focused on the end-to-end pipeline of high-fidelity digital humans. It covers everything from cloud-based design in the MetaHuman Creator to advanced gameplay systems like Motion Matching and IK Retargeting.

🚀 Key Features
Next-Gen Movement: Implementation of Motion Matching (UE 5.4+) for fluid, mocap-quality animations without traditional state machines.

Custom Character Pipeline: Full integration of MetaHuman characters from Quixel Bridge with custom LOD and shader optimizations.

Advanced Rigging: Use of IK Retargeters to bridge animations between the UE5 Mannequin (Manny/Quinn) and the MetaHuman skeleton.

Facial Performance: Setup for Live Link Face and MetaHuman Animator for realistic facial expressions.

🛠️ Technical Prerequisites
To run this project, ensure you have the following installed and configured:

Engine Version: Unreal Engine 5.4 or newer (required for Motion Matching features).

Required Plugins:

MetaHuman

Quixel Bridge

Motion Matching

Live Link / Live Link Face

Hardware: High-end GPU recommended for 8K texture rendering and real-time shader compilation.

📦 Installation & Setup
1. Clone the Repository
To get a local copy of this project, use the following command:

Bash
git clone https://github.com/M-B-Hussain/gameDev_Fractured.git
2. Configure Your Environment
Before opening the project, ensure your Git user information is set up:

Bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
3. Importing Your MetaHuman
Open the project in Unreal Engine 5.

Navigate to Window > Quixel Bridge.

Sign in and download your MetaHuman at Highest Quality.

Click Add to import. Note: Shader compilation may take 10–45 minutes depending on your hardware.

🏗️ Development Workflow
Branching Strategy
We use feature branches to keep the main branch stable. To start working on a new feature (e.g., adding a specific animation set), create a new branch:

Bash
git checkout -b feature/animation-logic
Committing Changes
Always include a descriptive message with your commits:

Bash
git add .
git commit -m "Add IK Retargeter for MetaHuman Body"
Synchronizing with Remote
To push your changes to your specific branch on the remote server:

Bash
git push -u origin feature/animation-logic
⚠️ Troubleshooting & Tips
Nested Repositories: If you accidentally clone another repo inside this one, remember to remove the inner .git folder to avoid the "embedded repository" error.

Shader Compilation: If your MetaHuman appears "bald" or gray, wait for the shaders at the bottom right to finish compiling.

Force Pushing: Only use git push --force if you are absolutely sure you want to overwrite the remote history of your private branch.

📄 License
This project is for educational and developmental purposes within the gameDev_Fractured workflow.
