---
title: Introducting Mini DNS
date: 2019-10-03
tags: ["haas","mindis"]
---

I fnished working on a DNS solution for HaaS. I was finding existing DNS automation solutions to be too clunky and complicated to set up.

Introducing MiniDNS: <https://github.com/homelabaas/dns-api>!

This is a Bind DNS server, wrapped with a HTTP API, which lets you manage the DNS zones and records using the API.

This has now also been integrated with HaaS, so it can now connect to and use Mini DNS as the final DNS management tool of choice for DNS automation.

Mini DNS will get it's own documentation site, detailing how it works and how to use it.
