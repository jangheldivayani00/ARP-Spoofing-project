# ARP Spoofing (ARP Poisoning)

## 📌 Overview
ARP Spoofing (also known as ARP Poisoning) is a **Man-in-the-Middle (MITM)** attack technique used in local area networks (LAN).  
In this attack, an attacker sends fake ARP replies to associate their MAC address with the IP address of another device (usually the gateway).

---

## 🧠 What is ARP?
**ARP (Address Resolution Protocol)** maps an IP address to a MAC address in a local network.

Example:
- IP: `10.150.65.132`
- MAC: `98-01-a7-96-c7-4d`

  <img width="721" height="262" alt="Image" src="https://github.com/user-attachments/assets/ae227e83-44d3-41b9-aec7-3946a6743963" />


ARP has **no authentication**, which makes it vulnerable.

---

## ⚔️ How ARP Spoofing Works
1. Attacker scans the local network
2. Attacker sends forged ARP replies
3. Victim believes attacker is the router

   <img width="912" height="389" alt="Image" src="https://github.com/user-attachments/assets/be48f179-2caf-4d54-b94e-ed758890fa54" />

   
4. Traffic passes through attacker


5. Attacker can sniff, modify, or block data

 
 Screenshot Before attack

<img width="675" height="912" alt="Image" src="https://github.com/user-attachments/assets/b495b4da-32db-4b6a-9a59-4e5bfd66fc0f" />

 Screenshot after attack

![Image](https://github.com/user-attachments/assets/d8eaaab5-a2d6-497f-80d5-d623df3de482)


---

## 🎯 Impact of ARP Spoofing
- Packet sniffing
- Session hijacking
- Credential theft
- DNS spoofing
- MITM attacks

---

## 🛡️ Prevention Techniques
- Use **Static ARP entries**
- Enable **Dynamic ARP Inspection (DAI)**
- Use **HTTPS / TLS**
- Monitor ARP tables
- Use IDS/IPS systems

---

## 🧪 Learning Environment
This concept should be practiced only in:
- Virtual labs
- Test networks
- CTF challenges
- Authorized environments

---

## ⚠️ Disclaimer
This repository is created **strictly for educational and ethical purposes only**.  
Any misuse of this knowledge is the sole responsibility of the user.

---
