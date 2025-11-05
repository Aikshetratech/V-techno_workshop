
🧠 Workshop Prerequisites & Installation Guide

Organized by: Aikshetra Tech Solutions


⸻

🧩 1. Prerequisites

Before attending the workshop, participants are expected to have the following:

✅ Accounts
	1.	Gmail Account – For authentication and access to workshop materials and repositories.
➤ Sign up: https://accounts.google.com/signup￼
	2.	GitHub Account – To clone, push, and collaborate on code repositories.
➤ Sign up: https://github.com/￼

⸻

⚙️ 2. Required Software Installations

Please ensure the following software tools are installed before the workshop begins:

2.1 Git

Used for version control and source code management.
	•	Download: https://git-scm.com/downloads￼
	•	Installation Verification:

git --version



⸻

2.2 GitHub Desktop

Graphical interface for managing GitHub repositories.
	•	Download: https://desktop.github.com/￼
	•	After Installation:
	•	Login using your GitHub account.
	•	Clone or create repositories directly from the interface.

⸻

2.3 Visual Studio Code (VS Code)

Lightweight and powerful code editor.
	•	Download: https://code.visualstudio.com/￼
	•	Recommended Extensions:
	•	GitHub Pull Requests and Issues
	•	Docker
	•	Python (if applicable)
	•	Remote – SSH

⸻

2.4 Oracle VirtualBox

Used for creating and managing virtual machines.
	•	Download: https://www.virtualbox.org/￼
	•	Installation Steps:
	1.	Run the installer and follow on-screen instructions.
	2.	After installation, open VirtualBox and confirm it launches without errors.

⸻

2.5 Installing RHEL (Red Hat Enterprise Linux) on VirtualBox

Steps:
	1.	Download RHEL ISO:
➤ https://developers.redhat.com/products/rhel/download￼
(Free for developer use; requires Red Hat account.)
	2.	Create a New Virtual Machine:
	•	Open VirtualBox → New
	•	Name: RHEL
	•	Type: Linux
	•	Version: Red Hat (64-bit)
	•	Allocate RAM: at least 4 GB
	•	Create Virtual Hard Disk: 20 GB (VDI recommended)
	3.	Attach ISO:
	•	Go to Settings → Storage → Empty (Optical Drive)
	•	Click disk icon → Choose a disk file → Select RHEL ISO.
	4.	Start Installation:
	•	Boot VM → Follow RHEL setup wizard.
	•	Complete installation and login.

⸻

2.6 Docker Installation

Containerization tool for building and deploying applications.

For RHEL (or Linux-based systems):

sudo dnf install -y dnf-plugins-core
sudo dnf config-manager --add-repo https://download.docker.com/linux/rhel/docker-ce.repo
sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
sudo systemctl start docker
sudo systemctl enable docker
sudo docker --version

For Windows/Mac:
	•	Download: https://www.docker.com/products/docker-desktop/￼
	•	After Installation:
	•	Start Docker Desktop.
	•	Verify installation:

docker --version




⸻

💡 Tip for Participants
	•	Ensure your laptop has at least 8 GB RAM and 50 GB free disk space.
	•	Keep your internet connection stable for downloads and installations.
	•	Bring your charger and a notebook for notes.

