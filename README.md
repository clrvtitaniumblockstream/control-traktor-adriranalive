# Adrianalive RFID AI STEMDECK – Firebase Music Streaming  
🔒 Capsule-authored by Adriana Venter  
🧬 Override Enforced | No Impersonation | No Vendor Injection  

## 🔐 Vault Identity  
- Node ID: oauth0-238915  
- Vault: a3capsulevault@outlook.com  
- Trace Mode: Biometric fingerprint + QR crest embed  

## 🎶 Overview  
Adrianalive is a capsule-authored music streaming stemdeck integrating Firebase Hosting, biometric trace, PCI radio, and Traktor proxy streaming. Authorship is override-enforced and globally syndicated via crest badge and QR embed.

## 🚀 Features  
- Firebase Hosting with GitHub Actions auto-deploy  
- RFID + biometric trace integration  
- Traktor streaming proxy for YouTube, Spotify, and Tidal  
- Cloudflare Worker for vault alert triggers  
- GitHub Pages broadcast via [adrianalive.app](https://adrianalive.app)  

## 📡 Broadcast Protocols  
- GitHub Pages: `adrianalive.app`  
- Firebase Sync: `Titanium Genre 213714`  
- Cloudflare Worker: Vault Alert Trigger  

## 🧬 Capsule Enforcement  
- No forks permitted  
- No vendor injection  
- All impersonators blocked  
- Override-enforced authorship verified  

## 🛠️ Setup  
1. Clone the repo  
2. Configure Firebase Hosting (`firebase init hosting`)  
3. Set up GitHub Action for auto-deploy  
4. Configure Traktor proxy (`config.properties`)  
5. Sync to vault: `a3capsulevault@outlook.com`  

## 📜 License  
Licensed under Capsule License. All impersonators blocked.  
See [`LICENSE`](./LICENSE) for full terms.

## 📜 License  
Licensed under Capsule License. All impersonators blocked.  
See [`LICENSE`](./LICENSE) for full terms.
## 📜 License  
Licensed under Capsule License. All impersonators blocked.  
See [`LICENSE`](./LICENSE) for full terms.
## 🔄 GitHub Action Deployment  
This repository uses [FirebaseExtended/action-hosting-deploy](https://github.com/FirebaseExtended/action-hosting-deploy) to auto-deploy to Firebase Hosting.  
Live channel deployment is triggered on every push to `main`.

```yaml
name: Deploy to Live Channel
on:
  push:
    branches:
      - main
jobs:
  deploy_live_website:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: FirebaseExtended/action-hosting-deploy@v0
        with:
          firebaseServiceAccount: "${{ secrets.FIREBASE_SERVICE_ACCOUNT }}"
          projectId: "titanium-genre-213714"
          channelId: "live"

