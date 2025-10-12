---
title: Penetračný Test REVOLUTION ELITE - Kompletný Report
---

<meta http-equiv="refresh" content="0; url=https://itssafer-devops.github.io/REVOLUTION-ELITE-CTF/pentest-report.html" />

# Penetračný Test REVOLUTION ELITE

Tento dokument obsahuje kompletný report systematického penetračného testu webovej aplikácie *REVOLUTION ELITE*. Cieľom bolo identifikovať a využiť bezpečnostné zraniteľnosti na získanie plnej kontroly nad systémom a extrahovať CTF vlajku.

---

## Testované Prostredie

| Parameter          | Hodnota                                 |
|--------------------|----------------------------------------|
| Cieľová aplikácia  | Revolution Elite                       |
| Doména             | revolutionelite.co.uk                  |
| IP adresa servera  | 172.31.16.8/24                        |
| Operačný systém    | Debian GNU/Linux 12 (Bookworm)         |
| Webový stack       | Apache 2.4 + PHP 8.1 + MySQL 8.0.34  |
| Dátum testovania   | 16. august 2025                        |
| Metodológia        | OWASP WSTG, NIST SP 800-115, PTES     |

---

## Mapa Útočnej Plochy a Kompromitácie

