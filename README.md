# Lecture Slides 

## WEEK 1 

#### 1. [Lecture0.ppt - Course Introduction](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%201/Lecture0.ppt)
- **Course Overview**: Introduction to the course, its structure, and key topics.

- **Course Project**: The focus is on preparing for and obtaining the JNCIA-SEC certification from Juniper Networks.

- **Communication Guidelines**: Emphasizes the importance of using the course's discussion forum for content-related questions and using email for private issues.

- **Email Communication Style**: Encourages concise, clear communication to facilitate prompt responses.

#### 2. [Lecture1.ppt - State of Cybersecurity](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%201/Lecture1.ppt)

- **Overview of Cybersecurity Positions**: Differentiates between engineering (e.g., security-focused software engineers, penetration testers) and non-engineering positions (e.g., incident reporters, legacy historians).

- **Industry Demand**: Highlights the growing demand for cybersecurity professionals and the increasing number of job openings.

- **Preparation for Cybersecurity Careers**: Discusses the importance of having security-focused projects, certifications, and knowledge of industry practices.

- **Cybersecurity Academic Positions**: Covers roles in teaching and research, with details on how to prepare for each.

- **Interviews**: Provides tips on preparing for both industry and academic interviews, focusing on security programming, deployment, and research presentations.

#### 3. [Lecture1-2.ppt - Cloud Infrastructure and Virtualization](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%201/Lecture1-2.ppt)

- **Cloud Computing Basics**: Covers the shift from traditional to cloud-based computing, with a focus on the advantages and disadvantages of cloud computing.

- **Cloud Components and Architectures**: Describes the essential components of cloud infrastructure, such as networking, compute servers, storage, and software, along with different cloud architectures (private, public, hybrid).

- **Cloud Delivery Models**: Discusses Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS), along with specialized sub-models like MBaaS and FaaS.

- **Virtualization**: Details the concept of virtualization, hypervisors, provisioning, and various types of virtualization (hardware, terminal).

- **Snapshot, Migration, and Failover**: Discusses the importance of snapshots, migration of virtual machines, and failover mechanisms for maintaining cloud services.

- **Nesting and Licensing**: Explores the implications of nesting virtual machines and the importance of licensing compliance.

- **Virtualization vs. Containerization**: Highlights the differences between virtualization and containerization, which is described as OS-level virtualization.

These lecture files cover foundational topics in cybersecurity, cloud infrastructure, and virtualization, providing essential knowledge for understanding the course's focus on security and cloud technologies.

--- 

## WEEK 2 

#### 1. [Lecture2.ppt - CIA Triad and Security Design Principles](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%202/Lecture2.ppt)

- **CIA Triad**:
  - **Confidentiality, Integrity, Availability**: Fundamental concepts in cybersecurity, each with a unique focus. Confidentiality ensures that information is not accessible to unauthorized users, integrity ensures data accuracy and completeness, and availability ensures that data and systems are accessible when needed.

  - **Prioritization**: In practice, availability often takes precedence, followed by integrity and confidentiality.

- **Security Design Principles**:
  - **Economy of Mechanism**: Keeping security designs simple and straightforward.

  - **Fail-Safe Defaults**: Default settings should be secure, denying access unless explicitly allowed.

  - **Complete Mediation**: All access requests should be checked every time.

  - **Open Design**: The security of a system should not depend on secrecy.

  - **Separation of Privilege & Least Privilege**: Ensuring that access rights are minimal and distributed.

  - **Least Common Mechanism**: Reducing shared mechanisms to limit potential vulnerabilities.

  - **Psychological Acceptability**: Security mechanisms should not be so cumbersome that users bypass them.

  - **Work Factor**: Security measures should be proportionate to the effort required to exploit vulnerabilities.

  - **Compromise Recording**: Prioritizing reliable detection of security breaches over perfect security.
 
#### 2. [Lecture3.ppt - Threat Modeling](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%202/Lecture3.ppt)

- **Threat Modeling Overview**:
  
  - **Structured vs. Unstructured Modeling**: Structured modeling uses systematic approaches like DFDs and attack trees, while unstructured modeling is more freestyle.

  - **DFDs (Data Flow Diagrams)**: Visual representation of a system's components and data flow, highlighting trust boundaries and potential attack surfaces.

  - **STRIDE Model**: A methodology for identifying potential threats: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege.
    
  - **Threat Mitigation**: Once threats are identified using STRIDE, appropriate mitigations are proposed to secure the system.

- **Practical Application**: Creation of DFDs and application of STRIDE to a generic process to identify and mitigate threats.

#### 3. [Lecture3ExampleDFDnSTRIDEnMitigate.pdf](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%202/Lecture3ExampleDFDnSTRIDEnMitigate.pdf)
- **Example of Threat Modeling**:
  - Provides a practical example of a DFD with associated threats identified using the STRIDE model.

  - Each element in the DFD (e.g., processes, data stores, data flows) is analyzed for potential threats, and corresponding mitigations are suggested.

  - This serves as a companion to Lecture3.ppt, showing how to apply the theoretical concepts in a real-world scenario.

#### 4. [Lecture4.ppt - Cryptography Basics](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/blob/Slides-Lectures/Week%202/Lecture4.ppt)
- **Cryptography Goals**:
  - Confidentiality, Integrity, Authenticity, and Authentication: Key goals that cryptographic techniques aim to achieve.

- **Cryptographic Implementations**:
  - **Symmetric Key Encryption**: Uses the same key for encryption and decryption. Efficient but poses challenges in key management.

  - **Asymmetric Key Encryption**: Utilizes a public-private key pair, providing advantages in key distribution and digital signatures.

  - **Hash Functions**: One-way functions that convert data into a fixed-length digest, crucial for ensuring data integrity.

- **Types of Cryptography**:
  - **Block vs. Stream Ciphers**: Different methods of processing data in symmetric encryption.

  - **Digital Signatures and MACs**: Mechanisms to verify authenticity and integrity.

These lectures provide a deep dive into critical cybersecurity concepts such as the CIA triad, security design principles, threat modeling, and cryptography. They equip students with the knowledge necessary to understand and apply security measures effectively.

---

## WEEK 3

#### [1. Lecture5.ppt - Authentication]()

- **Authentication Basics**:
  - Definition: The process of verifying an identity claimed by or for a system entity.
  - E-Authentication: Concepts such as credentials, tokens, CSP (Credential Service Provider), and the role of registration authorities.

- **Authentication Factors**:
  - Single-factor authentication (passwords, tokens, biometrics) and multifactor authentication (MFA).
  - NIST-defined levels of authentication (Level 1 to Level 4).

- **Password Security**:
  - Discussion on entropy, password strength, and the challenges of storing passwords securely.
  - Common threats like brute-force attacks, keyloggers, and password reuse.

- **Message Authentication Codes (MACs)**:
  - Concepts and examples of MACs, highlighting their role in providing integrity and authentication.

- **Digital Signatures**:
  - Explanation of how digital signatures work, using asymmetric encryption to ensure authenticity and integrity.

- **Digital Certificates**:
  - The concept of certificates as a root of trust in securing communications.

#### [2. Lecture6.ppt - Authentication Methods]()

- **Cracking Passwords**:
  - Password cracking techniques, including brute-force attacks and the use of rainbow tables.

- **Password Managers**:
  - The role of password managers, with a preference for local over cloud-based options.

- **Secret/Security Questions**:
  - Vulnerabilities and historical exploits related to security questions.

- **Biometrics**:
  - Advantages and disadvantages of biometric authentication, including privacy issues and accuracy challenges.

- **Tokens**:
  - Overview of token-based authentication (e.g., RSA SecureID, OTPs) and the challenges associated with it.

- **Network Authentication Protocols**:
  - Introduction to protocols like Challenge-Response, Needham-Schroeder, Kerberos, and OpenID.
  - The pros and cons of different protocols, including their vulnerability to various attacks.

#### [3. Lecture7.ppt - Access Control]()

- **Access Control Overview**:
  - Definition of access control and the distinction between authentication, authorization, and access control.

- **Access Control Approaches**:
  - **Discretionary Access Control (DAC)**: Based on ownership, typical in Unix/Linux systems.
  - **Mandatory Access Control (MAC)**: Controlled by a security administrator, often used in systems requiring high security.
  - **Role-Based Access Control (RBAC)**: Roles are used to manage permissions, suitable for large organizations.

- **Access Control Lists (ACLs)**:
  - How ACLs work, their strengths and weaknesses, and common issues like the "Confused Deputy Problem."

- **Basic Unix Access Control**:
  - Inode-based permissions, the concept of groups and users, and the challenges in managing granular permissions.

- **MAC Models**:
  - Bell-LaPadula Model (confidentiality focus) and Biba Model (integrity focus).
  - Chinese Wall Model (conflict of interest focus).

- **RBAC Implementation**:
  - Types of RBAC, session management, and the strengths and drawbacks of RBAC.

#### [4. Lecture8.ppt - Access Control Exploits]()
- **Advanced Access Control Techniques**:
  - **AppArmor**: A Linux kernel module providing enhanced security through DAC, MAC, and RBAC.
  - **Hardware Enforced Access Control (HEAC)**: Hardware-based privilege levels (e.g., CPU rings) and their strengths/weaknesses.

- **CPU Execution**:
  - Differences between in-order and out-of-order execution and their implications for security.

- **Meltdown & Specter Exploits**:
  - Overview of these vulnerabilities that exploit speculative execution to bypass access controls.
  - Discussion of how these attacks work, the differences between Meltdown and Specter, and the mitigation strategies.

These lectures cover essential concepts in authentication, access control, and security vulnerabilities, providing a comprehensive understanding of both foundational and advanced topics in cybersecurity.


---

## WEEK 4

#### 1. [Lecture8-2.ppt - Malware and Popular Attacks]()
- **Malware Overview**:
  - Definition and differentiation between malware and software bugs.
  - Modes of operation: Covert (e.g., spyware) and overt (e.g., ransomware).
    
- **Types of Malware**:
  - **Persistent Threats**: Includes worms, viruses, trojans, and rogues.
  - **Backdoors**: Exploiting undisclosed access points, with examples like Back Orifice and Clipper Chip.
  - **Kits**: Bootkits and rootkits, used to gain unauthorized control over systems.
  - **Denial of Service (DoS)**: Explaining DoS and Distributed Denial of Service (DDoS) attacks.
  - **Loggers, Logic Bombs, Scareware, Spyware, and Ransomware**: Understanding these types and their impacts.
  - **Social Engineering**: Tactics like phishing and impersonation.

- **Advanced Persistent Threats (APTs)**:
  - Characteristics of APTs, which often involve multiple types of malware and sophisticated attack strategies.

#### 2. [Lecture9.ppt - Software Vulnerabilities]()
- **Pervasive Insecurity in Software**:
  - Statistics on software bugs and vulnerabilities, with a focus on the Common Vulnerabilities and Exposures (CVE) database.

- **Software Vulnerability Classification**:
  - Categories: Time-induced, design-induced, and implementation-induced vulnerabilities.

- **Memory Management**:
  - Explanation of memory stacks, memory corruption, and buffer overflows.

- **Memory Corruption Examples**:
  - Case studies illustrating memory corruption and its effects, such as segmentation faults.

- **Security Forensics and Mitigation**:
  - Techniques like copying essential code or using shellcode to manage memory.

- **Shellcode**:
  - An introduction to shellcode, its purpose, and restrictions.

- **Defense Mechanisms**:
  - Stack canaries, access control configurations, and Address Space Layout Randomization (ASLR) to mitigate vulnerabilities.

#### 3. [Lecture10.ppt - Software Vulnerabilities (Continued)]()
- **Input Validation and Representation**:
  - Issues arising from accepting untrusted inputs, with examples like SQL Injection and Cross-Site Scripting (XSS).
    
- **Temporal- and State-based Vulnerabilities**:
  - Examples include race conditions and reused authentication sessions, with mitigation strategies.

- **API Abuse**:
  - How improper API usage can lead to vulnerabilities, such as unchecked return values.

- **Security Failures**:
  - Issues like unchecked randomness, as seen in the 2008 Debian OpenSSL vulnerability.

- **Error Handling**:
  - Problems with mishandled errors, including NullPointerException.

- **Code Quality**:
  - Impact of poor code quality, with examples like memory leaks and use-after-release issues.

- **Encapsulation**:
  - Trust boundary violations and how they lead to vulnerabilities, exemplified by the Heartbleed bug.

These lectures cover crucial topics in malware, software vulnerabilities, and various types of attacks, providing a deep understanding of the threats and defenses related to cybersecurity.

---


## WEEK 5

#### [1. Lecture11.ppt - Web Security]()
- **Overview of Web Security**:
  - Importance of web security in the context of HTTP and SQL vulnerabilities, including command injection, Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF).

- **HTTP and HTTPS**:
  - Explanation of HTTP requests and responses, status codes, and the nature of HTTP as a stateless protocol.

- **SQL Injection**:
  - Detailed exploration of SQL injection, including how it occurs, common vulnerabilities, and methods for protecting against it (e.g., input sanitization and parameterized queries).

- **Cross-Site Scripting (XSS)**:
  - Different types of XSS (stored and reflected), with examples and protection mechanisms, including input validation and Content Security Policy (CSP).

- **Cross-Site Request Forgery (CSRF)**:
  - Explanation of CSRF attacks, practical examples, and protection methods like CSRF tokens.

- **HTTPS Issues**:
  - Problems with HTTPS, such as MiTM attacks and TLS CA compromises, and potential solutions​.

#### [2. Lecture12.ppt - Web Privacy]()
- **Overview of Web Privacy**:
  - Focuses on cookies, HTTPS, side-channel attacks, and improving privacy for users on the web.

- **Cookies**:
  - How cookies work, their impact on privacy, and how they can be used for web profiling and targeted advertising.

- **EverCookies and SuperCookies**:
  - Advanced forms of cookies that are difficult to remove and can be used to track users persistently.

- **Side-Channel Attacks**:
  - How side-channel attacks can extract information from encrypted traffic without decryption, with examples of HTTPS side-channel leaks.

- **Improving Privacy**:
  - Discussion on Privacy Enhancing Technologies (PET) such as browser plugins, Tor browser, and Tails OS, along with the limitations of "Do Not Track" settings​(Lecture12).

#### [3. Lecture13.ppt - Crypto History]()

- **Overview of Cryptography**:
  - Historical perspective on cryptographic systems and the importance of randomness in cryptography.

- **Randomness in Cryptography**:
  - True Random Number Generators (TRNGs) and Pseudo-Random Number Generators (PRNGs), with a focus on their role in cryptographic applications.

- **Historic Cryptosystems**:
  - Explanation of classic cryptographic methods, including One-Time Pad, Substitution Cipher (e.g., Caesar cipher), and Transposition Cipher.

- **Threats to Historic Cryptosystems**:
  - Discussion of the vulnerabilities and limitations of these older cryptographic methods​.

These lectures cover critical aspects of web security, web privacy, and the historical context of cryptographic techniques, providing a comprehensive understanding of how these fields have evolved and how they impact modern cybersecurity practices.

---

## WEEK 6 

#### [Lecture14.ppt - Symmetric Key Cryptosystems]()
- **Overview**:
  - Introduction to symmetric key cryptosystems, including block ciphers and stream ciphers.

- Symmetric Key Approaches:
  - **Block Ciphers**: Encrypts text in fixed-size blocks using a shared secret key. Examples include DES, 3DES, and AES.

  - **Stream Ciphers**: Encrypts data as a continuous stream, XORing the plaintext with a keystream to produce ciphertext. Stream ciphers are harder to implement correctly due to the requirement that keystreams must be unique.

- **Advanced Encryption Standard (AES)**:
  - Developed to replace DES and 3DES due to their vulnerabilities. AES uses a series of rounds based on the key size (128-bit, 192-bit, or 256-bit).

  - **AES Rounds**: Each round includes substitution, shifting, permutation, and adding a round key. The number of rounds increases with key size.

- **AES Modes of Operation**:
  - **Electronic Codebook (ECB)**: Encrypts each block independently, but is vulnerable due to pattern retention in the ciphertext.
    
  - **Cipher Block Chaining (CBC)**: Each block of plaintext is XORed with the previous ciphertext block before being encrypted, reducing vulnerability to pattern-based attacks.

- **RC4**:
  - A popular stream cipher developed by Ron Rivest. Although fast and widely used in protocols like TLS/SSL, RC4 has been broken due to its non-random keystream.

- **Security of AES**:
  - Discussion of key length and computational difficulty involved in breaking AES encryption, highlighting its robustness for different use cases (e.g., 128-bit for general use, 256-bit for top-secret information).

This lecture provides a comprehensive overview of symmetric key cryptosystems, their operation, and their vulnerabilities. The focus is on the technical aspects of encryption methods and their practical implementations in modern cryptography​.

---

## WEEK 7

#### [Lecture15.ppt - Asymmetric Key Cryptosystems]()
- **Overview**:
  - Introduction to asymmetric key cryptosystems, focusing on key algorithms like RSA and Diffie-Hellman, and the X.509 certificate format.

- **Asymmetric Key Systems**:
  - Motivation for asymmetric systems due to challenges in key management with symmetric systems.
  - Public key systems where the public key is shared openly, and the private key is kept secret.

- **RSA Algorithm**:
  - Developed by Rivest, Shamir, and Adleman in 1977, RSA is widely used for encrypting online sessions and digital signatures.
  - The algorithm is based on the difficulty of factoring large numbers. However, it is relatively slow compared to symmetric key algorithms like AES.

- **Attacking RSA**:
  - Discusses the vulnerabilities of RSA, particularly through reverse engineering and factoring the large number used in the key.
  - RSA-512, RSA-768, and RSA-1024 have been cracked; RSA-2048 is currently secure but still part of layered security strategies.

- **Diffie-Hellman Key Exchange**:
  - Developed in 1976, it allows secure creation of shared keys between parties without direct key exchange.
  - Based on discrete logarithms and provides forward secrecy, meaning past communications remain secure even if current keys are compromised.

- **Digital Certificates**:
  - RSA and Diffie-Hellman are vulnerable to Man-in-the-Middle (MitM) attacks without authentication, which is mitigated by digital certificates.
  - X.509 is a popular digital certificate implementation used to establish trusted roots.

- **Digital Certificate Problems**:
  - Issues with Certificate Authorities (CAs) being spoofed, which can compromise the entire security ecosystem.

- **Improvements and Alternatives**:
  - Certificate Revocation Lists (CRLs), Online Certificate Status Protocol (OCSP), HTTP Public Key Pinning (HPKP), and transparent certificates are discussed as methods to improve the security and reliability of digital certificates​.
    
This lecture provides a comprehensive understanding of asymmetric key cryptosystems, their applications, vulnerabilities, and the role of digital certificates in securing communications.



---


## WEEK 8

#### [Lecture16.ppt - Hashing, TLS, and AEAD]()
- **Overview**:
  - This lecture covers the properties of hash functions, the details of the SHA-512 algorithm, Transport Layer Security (TLS), and Authenticated Encryption with Associated Data (AEAD).

- **Hash Functions Recap**:
  - A one-way function that creates a unique ‘digest’ of a message. Used in HMACs, password storage, and digital checksums. Popular implementations include SHA and MD5.

- **Properties of Hash Functions**:
  - **Preimage Resistance**: Given a hash, it should be impossible to determine the original plaintext.
  - **Duplicity Resistance (Second Preimage Resistance)**: The hash function should always produce the same hash for a given input.
  - **Collision Resistance**: Two different inputs should never produce the same hash.

- **Hash Function Exercises**:
  - Various exercises to reinforce the understanding of hash properties using SHA1.

- **Hashing Algorithms**:
  - Discussion on MD5, SHA-1, SHA-2, and SHA-3, including their strengths, weaknesses, and collision resistance.

- **Security for Transmission**:
  - Explores methods for securing data transmission across networks, emphasizing the importance of ensuring confidentiality, integrity, and availability (CIA) of transmission.

- **Transport Layer Security (TLS)**:
  - Details about the evolution of SSL to TLS, the various versions of TLS, and how it provides integrity, authentication, and confidentiality using MACs and encryption.
  - Discussion on TLS records, handshakes, and the different types of attacks on SSL/TLS, including POODLE and BEAST.

- **Authenticated Encryption and Associated Data (AEAD)**:
  - Previously known as AEAD, this section covers how to combine encryption and authentication, exploring different approaches like Galois Counter Mode (GCM), Offset Codebook Mode (OCB), and ChaCha20 with Poly1305.

This lecture provides a thorough understanding of hash functions, their properties, and their use in securing data transmission through protocols like TLS, as well as the importance of combining encryption and authentication for enhanced security

---

## WEEK 9

Lecture17.ppt - Anonymity (Tor and Signal)
Overview:
This lecture covers the concept of anonymity in the digital age, with a focus on Virtual Private Networks (VPNs), Tor, Onion Routing, and Signal.
Anonymity:
The state of being unidentified, offering privacy and freedom of speech but potentially undermining authority and facilitating illegal activities.
Discussion of the pros and cons of anonymity, including case studies like PRISM and Operation Onymous.
Total vs. Reasonable Anonymity:
Total anonymity is nearly impossible in modern computing systems, but reasonable anonymity can be achieved through privacy-focused services like ProtonMail, Tor, VPNs, Signal, and Tails OS.
Virtual Private Networks (VPNs):
VPNs create a secure tunnel within a network, encrypting traffic and providing stability to wireless connections. However, they are not reliable for complete anonymity since VPN providers can monitor traffic and are subject to local laws.
Tor (The Onion Router):
A free and open-source project providing anonymous communication over the internet using Onion Routing. Tor offers protection against network surveillance and traffic analysis, but it is not foolproof.
Tor’s benefits include protecting human rights and enabling free speech, but it also provides a platform for illegal activities and faces vulnerabilities such as exit node compromise and traffic timing analysis.
Onion Routing:
The method used by Tor to ensure anonymity by routing traffic through multiple nodes (relays). However, it is vulnerable to traffic timing analysis and compromised exit nodes.
Signal:
A secure messaging app providing end-to-end encryption (E2E) for text messaging and voice calling. It uses the Signal Protocol, which includes the Double Ratchet algorithm for key sharing, and offers strong security with AES-256, HMAC-SHA256, and Curve 25519.
Signal's vulnerabilities include theoretical attacks like compromising one end of the communication and practical issues like DoS attacks and code injection due to bugs in Android/iOS.
Double Ratchet:
The algorithm used in the Signal Protocol to ensure secure key exchange and message confidentiality.
This lecture provides a detailed understanding of the tools and protocols used to achieve anonymity and secure communication online, along with the associated risks and challenges​(Lecture17)

---

## WEEK 10

ecture18.ppt - Cryptocurrency and Blockchain
Overview:
The lecture covers the fundamental concepts of cryptocurrencies and blockchain technology, focusing on their mechanisms, uses, and vulnerabilities.
Cryptocurrencies:
Older Cryptocurrencies: Currencies derived from cryptographic ledgers, facing issues like the double spending problem. Solutions include peer-to-peer (P2P) ledgers, which differ in implementation by currency.
Modern Cryptocurrencies: Decentralized and hard to regulate, popular for various activities including anti-fiat hedges, money laundering, and darknet transactions.
Bitcoin Blockchain:
A distributed ledger where each peer (node) stores a copy of the blockchain. Blocks consist of transactions computed using Merkle Trees, which allow for efficient verification.
Bitcoin and Distributed Consensus:
The blockchain ensures integrity through Byzantine fault-tolerant consensus mechanisms. Transactions are verified by all peers before being added to the blockchain.
Mining:
Miners create new Bitcoins through the Nakamoto Consensus, involving proof of work. Mining pools increase the chances of earning rewards, but they also contribute to the rising difficulty and energy consumption associated with mining.
Energy Consumption:
The environmental impact of cryptocurrency mining, with Bitcoin's network using more energy than countries like Argentina as of May 2022.
Ethereum:
Unlike Bitcoin, Ethereum supports Turing-complete smart contracts, which are programs that run on the Ethereum Virtual Machine (EVM). Ether, the currency of Ethereum, is used to power these smart contracts.
Vulnerabilities of Cryptocurrency:
Includes 51% attacks, where malicious miners control the majority of a network, and privacy issues, where public transaction records can be misused.
Smart Contract Bugs: Exploits in smart contracts can lead to significant financial losses, such as the $50 million lost by DAO due to a bug.
Future of Crypto:
Discussion on the sustainability of cryptocurrency, the need for more energy-efficient consensus mechanisms, and the challenges of selling the concept of distributed trust.
This lecture provides a detailed exploration of how cryptocurrencies operate, their underlying blockchain technology, the challenges they face, and the implications for the future​

---

## WEEK 11

Lecture19.ppt - Security Information and Event Management (SIEM)
Overview:
This lecture covers Security Information and Event Management (SIEM), including its components, functions, and related security tools like IDS/IPS, firewalls, and anti-malware tools.
SIEM:
SIEM is a product or service that manages security events by collecting, monitoring, and analyzing event data in real-time. It provides notifications, console views, and long-term storage for event analysis.
Common uses include checking connectivity, security, virtualization, and incident response. SIEM systems often include add-ons like anti-malware and IDS/IPS.
Compliance: SIEM systems must comply with regulations like HIPAA, GDPR, PCI-DSS, and NIST standards to manage data growth and ensure stable data storage.
SIEM Basic Steps:
Collect data from connected services/devices.
Normalize and aggregate the data.
Analyze the data to detect anomalies.
Classify anomalies as threats or non-threats.
Locate the threat’s provenance and notify the relevant parties, with some systems capable of automatic threat response.
Intrusion Detection Systems (IDS):
IDS provide anomaly detection and response capabilities for SIEM systems. They come in two types:
NIDS: Network Intrusion Detection Systems for monitoring network traffic.
HIDS: Host Intrusion Detection Systems for monitoring system files.
IDS that can respond to threats and mitigate them are known as Intrusion Prevention Systems (IPS).
Firewalls:
Firewalls analyze network traffic to allow or block it based on configured rules. They can be stateless or stateful, with modern firewalls capable of deep packet inspection, user identity management, and application-layer analysis.
Proper configuration is essential to avoid breaking systems or allowing threats.
Anti-Malware Tools:
These tools detect, prevent, or remove malware from a host system. They operate in various modes, including sandboxing, real-time analysis, and different detection techniques like signature-based, heuristics-based, and access-based detection.
SIEM Integration:
IDS/IPS, firewalls, and anti-malware tools are integral components of SIEM systems. Event data management and additional skills like dashboard building in ELK or Splunk are also crucial for effective SIEM implementation.
This lecture provides a comprehensive overview of SIEM systems and the associated security tools necessary for managing and responding to security events in real-time

--- 

## WEEK 12

Lecture20.ppt - Critical Infrastructure & BlackEnergy
Overview:
This lecture focuses on critical infrastructure, its transition from analog to digital systems, and the increased cyber threats associated with this shift. It also covers the December 2015 Ukraine power grid cyberattack, known as Operation Sandworm.
Critical Infrastructure:
Defines critical infrastructure as organizations providing essential resources like electricity, water, and internet. The shift from analog to digital to cyber systems has increased efficiency and reduced maintenance costs but also introduced significant cyber threats.
Transition in Device Capabilities:
Describes the evolution from no networking (analog) to global communication (cyber). Post-2005, network-based cyber threats have become predominant.
Operation Sandworm:
Details the December 2015 Ukraine cyberattack, which resulted in the shutdown of 30 substations and left 230,000 people without power. The attack used the BlackEnergy malware to infiltrate, control, and destroy parts of the network.
BlackEnergy Malware:
Describes the features of BlackEnergy, including its capabilities to hide processes, invoke botnets, and corrupt BIOS and firmware. The malware was used in the multi-stage attack on the Ukrainian power grid.
Lessons Learned:
Emphasizes the importance of training employees to avoid phishing attacks, setting up hot switches, simulating attacks, and maintaining offline backups.
Lecture21.ppt - Stuxnet
Overview:
This lecture covers Stuxnet, the first known cyber weapon developed by a nation-state, its impact on critical infrastructure, and the operations that deployed it.
Stuxnet:
Discovered in 2010 but active since 2005, Stuxnet was developed by Israel and the US to sabotage Iran’s nuclear program. It targeted Siemens SCADA systems, causing significant physical damage.
Stuxnet Features:
Capable of corrupting PLCs, spoofing data, and evading detection. It was spread using USB drives, allowing it to cross air-gapped networks.
Operations Olympic Games and SecretTwin:
Operation Olympic Games: Successfully damaged 25% of Iran’s nuclear centrifuges by infecting systems through USB drives.
Operation SecretTwin: A failed attempt to sabotage North Korea’s nuclear program using similar methods.
Stuxnet Derivatives:
Stuxnet led to the development of other malware variants like Duqu and Flame. The lecture also references the documentary "Zero Days," which explores these events.
Lessons Learned:
Highlights the importance of regular maintenance, employee training, and avoiding the use of unknown USB drives in critical systems. It also explains the difference between quick and full memory formatting, stressing the need for thorough data wiping.
These lectures provide detailed insights into significant cyber threats to critical infrastructure, the methods used to execute such attacks, and the lessons learned from these incidents​


