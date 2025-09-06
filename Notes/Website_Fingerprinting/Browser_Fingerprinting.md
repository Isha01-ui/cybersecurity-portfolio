# Browser Fingerprinting

## Overview
- Browser fingerprinting collects information from a user’s browser to create a **unique profile**.  
- Can identify users even without cookies or IP addresses.

## Key Elements
- **User-Agent** – browser type and version  
- **HTTP Headers** – accepted languages, encoding, etc.  
- **Screen Resolution & Plugins** – display settings and installed plugins  
- **Canvas & WebGL** – graphics rendering can uniquely identify a device  
- **Fonts & System Settings** – installed fonts, OS information  

## Privacy & Security Implications
- Tracking without consent  
- Circumventing anonymity in Tor or VPNs  
- Targeted attacks based on browser/OS fingerprints  

## Python / Tools Examples
- Use `selenium` or `requests` to collect headers and user-agent info  
- Combine multiple attributes to create a fingerprint hash  
- Analyze patterns in a safe lab environment
