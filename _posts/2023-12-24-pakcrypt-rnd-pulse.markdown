---
layout: post
title:  "PakCrypt R&D Pulse"
date:   2023-12-23 07:22:34 +0500
categories: rnd update
---
### The Silent Threat in SSH Key Security ###
*2023-11-05*
![SSHBreak]({{site.url}}/{{site.baseurl}}/assets/images/pulse/20231105_ssh_break.jpg)
 a groundbreaking discovery has been made. Researchers have unveiled a silent threat lurking in the shadows of Secure Shell (SSH) key security. A paper published in CCS23, titled **[Passive SSH Key Compromise via Lattices](https://eprint.iacr.org/2023/1711.pdf)**, reveals that a passive network attacker can opportunistically obtain private RSA host keys from an SSH server that experiences a naturally arising fault during signature computation. 
The paper shows that for the signature parameters commonly in use for SSH, there is an efficient lattice attack to recover the private key in case of a signature fault.
The paper provides a security analysis of the SSH, IKEv1, and IKEv2 protocols in this scenario, and uses the attack to discover hundreds of compromised keys in the wild from several independently vulnerable implementations.

### Cracking the Code: How a Weekend Laptop Session Broke the Rainbow ###
*2022-06-21*
![RainbowBreak]({{site.url}}/{{site.baseurl}}/assets/images/pulse/20220621_rainbow_break.jpg)
 In the world of cryptography, there's a complex signature scheme known as Rainbow. It's been a finalist in the NIST Post-Quantum Cryptography standardization project, which is a big deal in the cryptography community. The Rainbow signature scheme has been around since 2005 and is based on the Oil and Vinegar signature scheme, which has withstood all cryptanalysis since 1999.

However, a recent **[study](https://eprint.iacr.org/2022/214)** has found a vulnerability in the Rainbow algorithm that allows it to be broken in just 53 hours, or roughly a weekend, on a standard laptop. This is a significant finding because it means that the security provided by the Rainbow signature scheme might not be as robust as previously thought.

### Deep Learning: The New Frontier in Cracking Cryptography ###
*2016-09-24*
 A new player has entered the arena: deep learning. A recent study has shown that deep learning techniques can be used to break cryptographic implementations.

The researchers behind **[this study](https://eprint.iacr.org/2016/921)** have proposed a novel approach to breaking cryptographic implementations using deep learning techniques. They used a large-scale dataset of cryptographic primitives and their implementations to train a neural network. This neural network can predict whether an implementation is vulnerable to certain attacks or not.

In simple terms, the researchers trained a computer program to recognize patterns in the way cryptographic algorithms are implemented. These patterns can reveal vulnerabilities that could be exploited by attackers.

