---
layout: post
title:  "Crypt Pulse"
date:   2023-12-23 07:22:34 +0500
categories: pulse v1
---
### Timekeepers of the Future need Change ###
*2023-12-01*
![SSHBreak]({{site.url}}/{{site.baseurl}}/assets/images/pulse/20231201_uwb_time.gif)
In a world where technology is advancing at an unprecedented pace, security remains a paramount concern. A recent study titled **[Time for Change](https://www.usenix.org/system/files/usenixsecurity23-anliker.pdf)** presented at USENIX 2023, sheds light on this critical issue.
The research, conducted by Claudio Anliker, Giovanni Camurati, and **[Srdjan Capkun](https://syssec.ethz.ch/people/capkun.html)** from ETH Zurich, unveils two novel attacks against UWB, which offers precise localization, making it a key player in secure ranging applications such as keyless car entry systems and contact tracing apps.
The researchers discovered that the very element that keeps us in sync *the clock* could be the Achilles heel of UWB secure ranging. By manipulating the clock, attackers could trick the system, leading to severe security breaches.


### The Silent Threat in SSH Key Security ###
*2023-11-05*
![SSHBreak]({{site.url}}/{{site.baseurl}}/assets/images/pulse/20231105_ssh_break.jpg)
 A groundbreaking discovery has been made. Researchers have unveiled a silent threat lurking in the shadows of Secure Shell (SSH) key security. A paper published in CCS23, titled **[Passive SSH Key Compromise via Lattices](https://eprint.iacr.org/2023/1711.pdf)**, reveals that a passive network attacker can opportunistically obtain private RSA host keys from an SSH server that experiences a naturally arising fault during signature computation. 
The paper shows that for the signature parameters commonly in use for SSH, there is an efficient lattice attack to recover the private key in case of a signature fault.
The paper provides a security analysis of the SSH, IKEv1, and IKEv2 protocols in this scenario, and uses the attack to discover hundreds of compromised keys in the wild from several independently vulnerable implementations.

### How a Weekend Laptop Session Broke the Rainbow ###
*2022-06-21*
![RainbowBreak]({{site.url}}/{{site.baseurl}}/assets/images/pulse/20220621_rainbow_break.jpg)
 In the world of cryptography, there's a complex signature scheme known as Rainbow. It's been a finalist in the NIST Post-Quantum Cryptography standardization project, which is a big deal in the cryptography community. The Rainbow signature scheme has been around since 2005 and is based on the Oil and Vinegar signature scheme, which has withstood all cryptanalysis since 1999.

However, a recent **[study](https://eprint.iacr.org/2022/214)** has found a vulnerability in the Rainbow algorithm that allows it to be broken in just 53 hours, or roughly a weekend, on a standard laptop. This is a significant finding because it means that the security provided by the Rainbow signature scheme might not be as robust as previously thought.

### The Impact of zxcvbn on Password Security ###
*2020-04-25*
![RainbowBreak]({{site.url}}/{{site.baseurl}}/assets/images/pulse/20200425_zxcvbn.gif)
 The research, conducted by Daniel Lowe Wheeler from Dropbox Inc., introduces **[zxcvbn](https://www.usenix.net/system/files/conference/usenixsecurity16/sec16_paper_wheeler.pdf)**, a compact, swift tool designed to estimate password strength. This tool stands out for its ability to provide accurate and conservative estimates at low magnitudes, making it particularly effective in mitigating online attacks.
The introduction of ‘zxcvbn’ has had a profound impact on the industry. By providing users with real-time feedback on password strength, ‘zxcvbn’ empowers users to make informed decisions, thereby bolstering their defense against potential cyber threats.

### Deep Learning is the New Frontier in Cracking Crypto ###
*2016-09-24*
 A new player has entered the arena: deep learning. A recent study has shown that deep learning techniques can be used to break cryptographic implementations.

The researchers behind **[this study](https://eprint.iacr.org/2016/921)** have proposed a novel approach to breaking cryptographic implementations using deep learning techniques. They used a large-scale dataset of cryptographic primitives and their implementations to train a neural network. This neural network can predict whether an implementation is vulnerable to certain attacks or not.

In simple terms, the researchers trained a computer program to recognize patterns in the way cryptographic algorithms are implemented. These patterns can reveal vulnerabilities that could be exploited by attackers.
