---
title: "WebRTC"
category:
featured: false
date: 2026-05-05T10:10:00+02:00
draft: true
---

#### About WebRTC
WebRTC is a free, open technology that provides browsers and mobile applications with Real-Time Communications (RTC) capabilities via simple APIs. It supports browser-to-browser applications for voice, video and data without the need of proprietary plugins.​

WebRTC consists of three APIs that can be used in both desktop and mobile browsers, IoT devices and mobile platforms:
- getUserMedia (camera and microphone access and capture media)
- RTCPeerConnection (sending and receiving media)
- RTCDataChannel (allow browsers to share data via peer-to-peer)

WebRTC`s architecture looks like this
[comment]: # (add WebRTC architecture image)

WebRTC is increasingly becoming supported by all major browser vendors like Chrome, Firefox and Opera and mobile platforms such as Android and iOS.

#### Advantages
- **​It`s free**  
WebRTC is an open-source API introduced in 2011. The main goal of WebRTC is to provide standard-based, real-time communications (RTC) technology that will be free and native in all browsers.
- **Cross platform**  
WebRTC is designed to work uniformly across multiple devices (Android and iOS), platforms (Windows, Linux, Mac) and browsers (Chrome, Firefox and Opera).
- **It`s secure**  
WebRTC has built-in encryption. It uses secure protocols to provide end-to-end encryption for media and data. This is especially beneficial over public WiFi networks. This also prevents eavesdropping and recording of the voice and video.
- **Cost effective**  
Peer to peer channel enable clients and devices to connect directly. This saves cost in terms of bandwidth and server utilization, as well as provides higher data speeds for end users.
- **High quality voice and video codecs**  
The technology uses Opus audio codec standardized by IETF. Opus allows adjusting sound quality to the internet channel bandwidth. iSAC and iLBC audio codecs are also part of WebRTC. For video WebRTC uses VP8 and soon VP9 codec which is comparable in quality with H.264/H.265 codecs but does not requires licensing royalties.
- **It adapts to changing network conditions**  
WebRTC supports variable bit rate. This enables efficient use of bandwidth and delivers the best possible voice and video quality.
- **Interoperability with legacy VOIP and Video technologies**  
One of the biggest value of WebRTC is interoperability with existing systems and platforms. WebRTC relies on established protocols and codecs, so it can be easily integrated with older platforms and services. This includes devices using SIP, Jingle, XMPP, PSTN, PBXs, UC systems.
- **Reliable Firewall/NAT traversal**  
WebRTC utilizes a technique called ICE, Interactive Connectivity Establishment, to traverse NATs and firewalls. As part of the ICE process, the browser may utilize STUN and TURN servers. It is estimated that 85-90% of connections do not require TURN, however that still leaves a significant percentage which does require it. By deploying TURN as part of the WebRTC infrastructure, one can reach 100% connectivity rate, even in highly restrictive networks.

#### Why should we use WebRTC?
**The short answer:** It is the only industry standard that allows high-quality, secure, real-time communication directly in the browser—no downloads, no plugins, and no friction.