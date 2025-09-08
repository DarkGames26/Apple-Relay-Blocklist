# Dark's Private Relay Blocklist

Dark's Private Relay Blocklist blocks iCloud Private Relay and related private relays (Apple Private Relay / traffic relays), preventing anonymous routing through Apple relays.

## What this list does
Block domains and patterns associated with iCloud Private Relay and Apple's private relays to prevent devices from anonymously redirecting traffic through Apple's relays. Using it will block Private Relay from working on Apple devices and affect the behavior of Safari and other services that rely on those relays. Especially if you have iCloud+.

---

## Why it may be more noticeable on iOS 14+
Changes in how encrypted transports and DNS interact can make relay-related behavior more apparent on newer iOS releases. See: https://blog.cloudflare.com/speeding-up-https-and-http-3-negotiation-with-dns/ and ttps://community.fortinet.com/t5/FortiGate/Technical-Tip-How-to-block-iCloud-Private-Relay-from-bypassing/ta-p/228629

---

## Usage
1. Import or paste the blocklist into your AdGuard Home / Pi-hole / hosts manager as a hostlist (one entry per line).  
2. Test incrementally: enable the list, verify affected services (Safari Private Relay, iCloud, Mail), then add or remove entries as needed.  

---
