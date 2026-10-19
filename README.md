Overview

This repository contains the Low Level Design (LLD) for a network solution built to support nine heat pumps that all use identical, non‑modifiable IP addressing. These devices needed secure access from both an Azure‑hosted server and third‑party VPN users on the corporate network.

Several architectures were evaluated—VRF/VLAN segmentation, nine standalone VDOMs, and firewall‑plus‑switch isolation. The final design selected was a VDOM–VRF hybrid, providing clean separation of overlapping IP spaces while keeping the solution manageable and scalable.

## Low Level Design (LLD)
View the interactive LLD here:  
[LLD (Google Sheets)](https://docs.google.com/spreadsheets/d/18NQ8xfaNX_YdjFtPqTHuHhS8Xu7uAtY0670Lf7OYa2c/edit?usp=sharing)

