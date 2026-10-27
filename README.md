# WK1-PM1 - Cybersecurity Lab Setup

**Name:** Emihle Memela
**Batch:** B083
**Program:** NETWORKWALKS

## What I Built
I built a Cybersecurity Lab using VirtualBox and Kali Linux on a custom NATNetwork.

## Lab Design
- **Network:** NATNetwork - 10.0.0.0/24
- **Kali Linux IP:** 10.0.0.2 / 255.255.255.0
- **Gateway:** 10.0.0.1
- **DNS:** 8.8.8.8
- **Clipboard / Drag & Drop:** Bidirectional
- **Shared Folder:** downloads (Auto-mount + Make Permanent)

## Steps
1. Installed VirtualBox and 7-Zip
2. Created NATNetwork 10.0.0.0/24 in VirtualBox > Tools > Network
3. Imported Kali Linux
4. Set Kali Network to NATNetwork, Clipboard to Bidirectional, Shared Folder to downloads
5. Configured static IP 10.0.0.2 inside Kali
6. Verified internet with ping google.com - 0% packet loss
7. Took Snapshot named Ngaphambi kwe-10.0.0.2

## Troubleshooting
My screenshot would not take while Kali was in fullscreen because Windows + PrtScn was going to Kali. I fixed it by pressing Right Ctrl + F to exit fullscreen, then Windows + PrtScn worked.

## Screenshots
