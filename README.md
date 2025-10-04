# Homelab

<!--toc:start-->
- [Homelab](#homelab)
  - [Hardware](#hardware)
  - [Diagrams](#diagrams)
  - [Roadmap](#roadmap)
<!--toc:end-->

**Homelab**
: *A server set up in one's home for the purpose of testing various configurations of hardware, operating systems, etc.*

My homelab is a project that started with a simple NAS in 2023 during my first internship as a sysadmin.
During a converstation, I discovered that they all had some servers to test things and practice so I simply said why not try myself ?

My only goal with this HomeLab is to be able to try things however I want and to learn. As my main topic of interest is network security, I'm very happy I started this HomeLab.

I tried to buy hardware with a minimalist approach, I don't wanted things too noisy or too big. It had to fit in a bookshelves and be in a living room.

## Hardware

**List :**
- Fortigate 60E (Firewall)
- Cisco SG300-10 (Switch L2)
- Synology DS223 (NAS)
- Minisforum NAB5 (Mini server)
- Ubiquiti UniFi UAP-nanoHD (Wi-Fi Access Point)
- APC Back-UPS (Battery backup & Surge protector)

I will try to explain my choice as much as possible but some just don't have explanation...

I started with the Synology NAS, today I think it was a mistake but I had to start somewhere. I think it was too expensive and today I only use it purely as a NAS but it can be used as a home server as it support Docker and has a lot of app built-in.

I got the fortigate, switch, and AP from second-hand. No need to buy them full price as I'm not a company...

The fortigate is a great appliance and nice to have because I use them at work and so I can practice with it. I use it as a traffic filter for my VLANs.

A switch ? Cisco

I bought the NAB5 mini pc because I simply wanted something powerfull, small and not too noisy. It has a great CPU and 32GB of RAM and run Proxmox VE.

I got the AP from second hand and it's working fine so far. The Ubiquiti UI is very great and the AP can be fully configured. I used it to broadcast different SSIDs.

I bought the UPS because there is power cut sometimes so my lab doesn't go offline.

## Diagrams

You will find network diagram [here](/diagram/README.md).

## Roadmap

- [ ] PVE Cluster
- [ ] Automate VM/LXC creation
- [ ] Multi sites topology
