# 🛰️ BlueTech Multi-Site Enterprise Network (Simülasyon Projesi)

Bu proje, BlueTech adlı kurgusal bir firmaya ait çok lokasyonlu bir Active Directory ve FortiGate altyapısının simülasyonunu içermektedir.

---

##  Proje Özeti
- İki domain arasında **DNS Zone Replication** ve **Two-Way Forest Trust** yapılandırılmıştır.  
- Kullanıcı, grup ve güvenlik yönetimi için **Group Policy (GPO)**’lar oluşturulmuştur.  
- Ağ güvenliği **FortiGate VM64** üzerinde NAT, VPN ve firewall kurallarıyla sağlanmıştır.  
- Tüm yapı **VMware Workstation** üzerinde sanal ortamda simüle edilmiştir.  

---

## ⚙️ Kullanılan Teknolojiler
| Bileşen | Açıklama |
|----------|-----------|
| **Windows Server 2016 Datacenter** | Active Directory, DNS, DHCP |
| **Windows 11 Pro** | İstemci sistemler |
| **FortiGate VM64 v7.x** | Firewall, VPN, NAT |
| **VMware Workstation 17 Pro** | Sanallaştırma platformu |

---

## 🌐 Ağ Yapısı
| Lokasyon | Domain | Ağ | Subnet | Not |
|-----------|---------|-----|---------|------|
| Türkiye | BlueTech.local | 192.168.10.0 | 255.255.255.0 | TR Ofisi |
| ABD | BlueTechUSA.local | 172.16.0.0 | 255.255.255.0 | US Ofisi |
| WAN | FortiGate | 192.168.1.5 | 255.255.255.0 | Site-to-Site VPN Bağlantısı |

---

## Proje İçeriği
 **[BlueTech Multi-Site Enterprise Network Dokümantasyonu (PDF)](https://github.com/mertroot/BlueTech-Multi-Site-Enterprise-Network-/blob/main/BlueTech_Multi-Site_Enterprise_Network_Dokumantasyonu.pdf)**  
Bu tek doküman içerisinde yer alan bölümler:
- Proje Tanımı ve Amaç  
- Ağ Topolojisi ve Bileşenler  
- OU Hiyerarşisi ve Kullanıcılar  
- Group Policy (GPO) Yapılandırmaları  
- Güvenlik Ayarları  
- Sistem Gereksinimleri  
- Sonuç ve Değerlendirme  

---

##  Hazırlayan
**Mert Bacara**  
💼 Sistem ve Ağ Uzmanı (Junior)  
📅 2025  
 [LinkedIn: linkedin.com/in/mertbacara](https://www.linkedin.com/in/mertbacara/)

---

##  Sonuç
Bu proje, kurumsal ağ altyapısının nasıl planlanacağı, güvenli şekilde yönetileceği ve yedekliliğin nasıl sağlanacağı konusunda uygulamalı bir örnektir.  
Gerçek bir firma yerine senaryo ortamında hazırlanmış olup, **Active Directory, DNS, GPO ve FortiGate güvenlik entegrasyonunu** bir arada göstermektedir.

EN

#🛰️ BlueTech Multi-Site Enterprise Network (Simulation Project)

This project simulates a multi-location Active Directory and FortiGate infrastructure for a fictional company called BlueTech.

##Project Overview
Configured DNS Zone Replication and Two-Way Forest Trust between two domains.
Implemented Group Policy Objects (GPOs) for user, group, and security management.
Secured network infrastructure using FortiGate VM64 with NAT, VPN, and firewall policies.
Entire environment was deployed and tested in VMware Workstation virtual lab.

##Technologies Used

Windows Server 2016 Datacenter (Active Directory, DNS, DHCP)
Windows 11 Pro (Client systems)
FortiGate VM64 v7.x (Firewall, VPN, NAT)
VMware Workstation 17 Pro (Virtualization platform)

## Network Architecture

Turkey Office — BlueTech.local — 192.168.10.0/24
USA Office — BlueTechUSA.local — 172.16.0.0/24
WAN — FortiGate — 192.168.1.5/24 (Site-to-Site VPN Connection)

##Project Documentation

BlueTech Multi-Site Enterprise Network Documentation (PDF)
https://github.com/mertroot/BlueTech-Multi-Site-Enterprise-Network-/blob/main/BlueTech_Multi-Site_Enterprise_Network_Dokumantasyonu.pdf

Includes:

Project Description and Objectives
Network Topology and Components
OU Structure and User Management
Group Policy (GPO) Configurations
Security Settings
System Requirements
Conclusion and Evaluation
Prepared By

##Mert Bacara
Junior System & Network Specialist
2025
LinkedIn: https://www.linkedin.com/in/mertbacara/

##Conclusion

This project demonstrates how an enterprise network infrastructure can be designed, implemented, and secured in a multi-site environment. It was built as a virtual lab scenario showcasing real-world integration of Active Directory, DNS, GPO, and FortiGate security solutions.
