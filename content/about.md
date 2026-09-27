+++
title = "CV"
description = "Ryan Starr's CV — Junior System Administrator. OpenStack and Proxmox/Ceph clusters, CI/CD deployments, single sign-on, and the devices people use every day."
path = "about"
template = "cv.html"

[extra]
lede = "I build and run the infrastructure, and look after the laptops, Wi-Fi and logins that people rely on every day."
interests = ["3D printing", "Game creation", "Home lab", "Cooking"]

[[extra.skills]]
name = "Automation & CI/CD"
items = ["Ansible roles", "CI/CD pipelines", "GitLab", "Bash", "Python", "Git", "Configuration management"]

[[extra.skills]]
name = "Infrastructure"
items = ["OpenStack", "Linux", "Windows Server", "Server hardware", "Docker", "Kubernetes / K3s", "Proxmox & Ceph", "ESXi", "TrueNAS", "Oracle Cloud"]

[[extra.skills]]
name = "Networking & security"
items = ["Firewall rules", "Wi-Fi", "Single sign-on", "Reverse proxy (NGINX)", "VPN (Tailscale)", "pfSense & OPNsense", "Cisco / CCNA-level", "DNS & DHCP", "Patching", "Cyber Essentials"]

[[extra.skills]]
name = "People & devices"
items = ["MacBooks & macOS", "User onboarding", "Active Directory", "Microsoft 365", "Azure fundamentals", "Mobile device management", "Desk hardware"]

[[extra.skills]]
name = "Monitoring"
items = ["Grafana", "Prometheus", "Uptime Kuma"]

[[extra.experience]]
title = "Junior System Administrator"
dates = "Apr 2025 – Present"
points = [
  "Built a full OpenStack cluster from start to finish, and keep developing it",
  "Built a Proxmox cluster backed by Ceph storage",
  "Deploy services through CI/CD pipelines rather than by hand",
  "Set up our single sign-on service and connect each new service to it",
  "Look after GitLab, OpenStack and our Docker services, and keep them patched",
  "Install server hardware and the networking around it",
  "Look after the MacBooks, Wi-Fi and desk kit people use every day, and enrol new starters into the central user database",
]

[[extra.experience]]
title = "IT Engineer (contract)"
org = "Alliance Homes"
org_url = "https://www.alliancehomes.org.uk/"
dates = "Nov 2024 – Mar 2025"
points = [
  "Six-month contract upgrading the mobile estate to be Cyber Essentials compliant",
]

[[extra.experience]]
title = "Technical Analyst"
org = "WestSpring IT"
org_url = "https://westspring-it.co.uk"
dates = "May 2023 – Aug 2024"
place = "Bristol"
points = [
  "End user support across a managed service provider's client base",
  "VPN and network configuration",
  "Hardware configuration and builds",
]

[[extra.experience]]
title = "IT Technician"
org = "University of Bristol"
org_url = "https://www.bristol.ac.uk/"
dates = "Sep 2022 – Mar 2023"
place = "Bristol"
points = [
  "In-person support across campus",
  "Workstation setup and deployment",
  "Supporting a satellite campus",
]

[[extra.experience]]
title = "IT Service Desk Analyst"
org = "Royal United Hospitals Bath NHS Foundation Trust"
org_url = "https://www.ruh.nhs.uk/"
dates = "Feb 2021 – Mar 2022"
place = "Bath"
points = [
  "IT support over phone, email and in person",
  "Writing documentation for staff and users",
  "Creating and editing accounts in Active Directory and other services",
]

[[extra.education]]
title = "BSc Computer Systems and Networks"
org = "University of Plymouth"
dates = "Sep 2020 – May 2022"
detail = "Cisco networking, security, Python and C#, virtualisation and Docker."

[[extra.education]]
title = "BTEC Level 3 Computing"
org = "Bridgwater and Taunton College"
dates = "Sep 2015 – Jun 2017"
detail = "Active Directory and NAS administration, networking, game design."

[[extra.certifications]]
name = "Microsoft 365 Certified: Fundamentals (MS-900)"
issuer = "Microsoft"
date = "Jul 2023"

[[extra.certifications]]
name = "Microsoft Certified: Azure Fundamentals (AZ-900)"
issuer = "Microsoft"
date = "Oct 2020"

[[extra.certifications]]
name = "Linux: Bash Shell and Scripts"
issuer = "LinkedIn Learning"
date = "Aug 2020"

[[extra.certifications]]
name = "Azure Active Directory Basics"
issuer = "LinkedIn Learning"
date = "Jul 2020"

[[extra.certifications]]
name = "Windows Server 2019 Essential Training"
issuer = "LinkedIn Learning"
date = "Jul 2020"
+++

I'm a junior system administrator based in the South West. My job runs from the bottom
of the stack to the top — whether that's building OpenStack clusters from scratch or
making sure new starters can log in on their first morning without any hiccups.

The heavy lifting happens through CI/CD pipelines and our single sign-on service, which I
set up and have gradually got every other system talking to. The day-to-day covers
everything people actually use: MacBooks, Wi-Fi access, and the kit sitting on their
desks. And yes, if someone needs hardware installed or a new account created, that's
usually me doing it.

Before this I spent six months on contract at Alliance Homes, getting their mobile
estate through Cyber Essentials, and three years in support — a managed service
provider, a university IT team, and an NHS service desk. That's where I learned that a
clear note saves the next person an hour, and I've kept the habit.

Outside work I run a home lab. For a while it was the only place I got to touch
infrastructure directly: Docker containers behind an NGINX reverse proxy, and Tailscale so I
can reach them from anywhere. For monitoring I just use Uptime Kuma with Discord
notifications — simple and effective. I write about it all on
[The Adventuring Dev](https://theadventuringdev.com), including the bits that went wrong
and how I worked around them.
