\# Task 8 – Working with VPNs

\#\# Objective  
Learn to install, configure, and test a VPN to secure internet traffic, hide the real IP address, and understand its benefits & limitations.

\---

\#\# Steps Performed

\#\#\# Step 1 – Chose VPN Provider  
\- Selected \*\*Windscribe Free\*\* due to multiple free server locations and built-in privacy features.

\#\#\# Step 2 – Installation  
\- Downloaded Windscribe from \[https://windscribe.com/download\](https://windscribe.com/download).  
\- Installed and logged in using a free account.

\#\#\# Step 3 – Connected to VPN Server  
\- Connected to \*\*Best Location: Victoria\*\*.  
\- Observed new IP location in Kolkata (while physically in Mumbai).

\#\#\# Step 4 – Verified IP Change  
\- Checked IP at \[https://whatismyipaddress.com\](https://whatismyipaddress.com).  
\- IP changed from real ISP IP (Mumbai) to VPN IP (Kolkata).

\#\#\# Step 5 – Checked Traffic Encryption  
\- Used \[Cloudflare SSL Test\](https://www.cloudflare.com/ssl/encrypted-sni/).  
\- Results:  
  \- TLS 1.3 ✅  
  \- DNSSEC ✅  
  \- Secure DNS ❌  
  \- Encrypted SNI ❌

\#\#\# Step 6 – Disconnected & Compared  
\- Disabled VPN & Firewall in Windscribe to reveal real IP.  
\- Confirmed real IP and location restored.

\#\#\# Step 7 – VPN Technical Details (Windscribe)  
\- \*\*Encryption\*\*: AES-256 with SHA-512 auth & 4096-bit RSA key exchange.  
\- \*\*Protocols\*\*: WireGuard, OpenVPN, IKEv2.  
\- \*\*No-Logs Policy\*\*: Claims no browsing or connection logs.  
\- \*\*Extra Features\*\*: Ad/tracker blocker, firewall, location spoofing.

\---

\#\# Benefits of Using VPN  
1\. \*\*Hides Real IP Address\*\* – Mumbai IP masked to Kolkata.  
2\. \*\*Encrypts Traffic\*\* – Strong encryption prevents ISP/Wi-Fi snooping.  
3\. \*\*Bypasses Geo-Restrictions\*\* – Access to region-locked content.  
4\. \*\*Privacy Protection\*\* – No-logging policy enhances anonymity.  
5\. \*\*Extra Features\*\* – Ad blocker, tracker blocker, firewall.

\#\# Limitations  
1\. \*\*Speed Reduction\*\* – Due to encryption & remote routing.  
2\. \*\*Incomplete Privacy\*\* – DNS/SNI leaks possible.  
3\. \*\*Data Limits\*\* – Free plan capped at 2–10 GB/month.  
4\. \*\*Not Fully Anonymous\*\* – Cookies & fingerprinting still trackable.  
5\. \*\*Firewall Confusion\*\* – Can block internet even when VPN off.

\---

\---

\#\# Conclusion  
VPNs like Windscribe provide strong privacy and encryption, effectively hiding a user’s real IP address and securing most traffic. However, users should be aware of possible leaks, speed drops, and limitations of free plans.

