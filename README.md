
<table>
  <tr>
    <th>Feature</th>
    <th>Paper 1: IoMT (Post-Quantum)</th>
    <th>Paper 2: Lightweight 2FA</th>
    <th>Paper 3: Quantum-Safe MFA</th>
    <th>Paper 4: Quantum Authentication</th>
  </tr>
  <tr>
    <td><b>Domain</b></td>
    <td>Internet of Medical Things (IoMT)</td>
    <td>General IoT and user authentication</td>
    <td>Cloud-assisted Medical IoT</td>
    <td>Quantum authentication systems</td>
  </tr>
  <tr>
    <td><b>Authentication Factors</b></td>
    <td>Multi-factor authentication (MFA)</td>
    <td>Two-factor authentication (2FA)</td>
    <td>Multi-factor authentication (MFA)</td>
    <td>Quantum-based authentication</td>
  </tr>
  <tr>
    <td><b>Security Model</b></td>
    <td>Post-quantum cryptography</td>
    <td>Lightweight cryptography</td>
    <td>Quantum-safe cryptography</td>
    <td>Quantum key distribution (QKD)</td>
  </tr>
  <tr>
    <td><b>Attack Resistance</b></td>
    <td>Resists quantum, replay, MITM, impersonation</td>
    <td>Defends against replay, MITM, password attacks</td>
    <td>Defends against quantum threats, replay, MITM</td>
    <td>Unconditional security against MITM</td>
  </tr>
  <tr>
    <td><b>Cryptographic Techniques</b></td>
    <td>Lattice-based cryptography, LWE, Ring-LWE</td>
    <td>Hash-based security, ECC</td>
    <td>Lattice-based, hash functions</td>
    <td>Quantum key distribution, BB84 protocol</td>
  </tr>
  <tr>
    <td><b>Key Exchange Mechanism</b></td>
    <td>Post-quantum secure key exchange</td>
    <td>Elliptic Curve Cryptography (ECC)</td>
    <td>Post-quantum key exchange</td>
    <td>Quantum key exchange (QKD)</td>
  </tr>
  <tr>
    <td><b>Lightweight Implementation</b></td>
    <td>Moderate computational overhead</td>
    <td>Highly optimized for constrained devices</td>
    <td>Moderate computational overhead</td>
    <td>High due to quantum computations</td>
  </tr>
  <tr>
    <td><b>Communication Overhead</b></td>
    <td>Low to moderate</td>
    <td>Very low</td>
    <td>Low to moderate</td>
    <td>High due to quantum communication</td>
  </tr>
  <tr>
    <td><b>Computation Complexity</b></td>
    <td>Moderate due to post-quantum methods</td>
    <td>Low due to ECC and hash-based techniques</td>
    <td>Moderate</td>
    <td>High (Quantum processing)</td>
  </tr>
  <tr>
    <td><b>Scalability</b></td>
    <td>Scalable for large medical networks</td>
    <td>Scalable for IoT and mobile applications</td>
    <td>Scalable for cloud-based IoMT</td>
    <td>Limited scalability</td>
  </tr>
  <tr>
    <td><b>Energy Efficiency</b></td>
    <td>Moderate</td>
    <td>High energy efficiency</td>
    <td>Moderate</td>
    <td>Low due to quantum operations</td>
  </tr>
  <tr>
    <td><b>Resistance to Password Guessing</b></td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td><b>Anonymity & Privacy</b></td>
    <td>Provides user anonymity and unlinkability</td>
    <td>Partially supports anonymity</td>
    <td>Ensures user privacy</td>
    <td>Quantum encryption ensures privacy</td>
  </tr>
  <tr>
    <td><b>Forward Secrecy</b></td>
    <td>Ensured through post-quantum techniques</td>
    <td>Ensured through ECC-based key agreement</td>
    <td>Ensured</td>
    <td>Ensured via quantum no-cloning theorem</td>
  </tr>
  <tr>
    <td><b>Mutual Authentication</b></td>
    <td>Yes, between user and IoMT devices</td>
    <td>Yes, between user and authentication server</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td><b>Session Key Establishment</b></td>
    <td>Dynamic key agreement</td>
    <td>ECC-based session key generation</td>
    <td>Dynamic session key agreement</td>
    <td>Quantum-generated session keys</td>
  </tr>
  <tr>
    <td><b>Implementation Feasibility</b></td>
    <td>Requires quantum-resistant cryptographic libraries</td>
    <td>Easily deployable on IoT devices</td>
    <td>Requires cloud-based support</td>
    <td>Requires quantum communication devices</td>
  </tr>
  <tr>
    <td><b>Use in Real-World Applications</b></td>
    <td>Suitable for medical IoT</td>
    <td>Suitable for general IoT authentication</td>
    <td>Best suited for cloud-based IoMT</td>
    <td>Experimental stage, not widely used</td>
  </tr>
  <tr>
    <td><b>Authentication Latency</b></td>
    <td>Moderate delay due to post-quantum processing</td>
    <td>Very low latency</td>
    <td>Moderate latency</td>
    <td>High due to quantum state preparation</td>
  </tr>
  <tr>
    <td><b>Protocol Standardization</b></td>
    <td>Future adoption in post-quantum cryptography</td>
    <td>Aligns with lightweight security standards</td>
    <td>Aligned with post-quantum security</td>
    <td>Requires new quantum cryptography standards</td>
  </tr>
   <tr>
    <th>Feature</th>
    <th>Paper 5: Post-Quantum Blockchain IoV</th>
    <th>Paper 6: GAKE with LibOQS</th>
  </tr>
  <tr>
    <td><b>Domain</b></td>
    <td>Intelligent Vehicular Transportation Systems (IVTS)</td>
    <td>Post-Quantum Group Authenticated Key Exchange (General)</td>
  </tr>
  <tr>
    <td><b>Authentication Factors</b></td>
    <td>Multi-factor (anonymous, traceable, linkable)</td>
    <td>Group authenticated key exchange (GAKE) – key-based auth</td>
  </tr>
  <tr>
    <td><b>Security Model</b></td>
    <td>Post-quantum + blockchain + linkability</td>
    <td>Post-quantum cryptographic security in QROM</td>
  </tr>
  <tr>
    <td><b>Attack Resistance</b></td>
    <td>Resists Sybil, quantum, MITM, replay</td>
    <td>Resists quantum, replay, MITM, impersonation</td>
  </tr>
  <tr>
    <td><b>Cryptographic Techniques</b></td>
    <td>Kyber-based linkable ring signature, PQ-KEM</td>
    <td>IND-CCA KEMs: Classic McEliece, Kyber, NTRU, Saber</td>
  </tr>
  <tr>
    <td><b>Key Exchange Mechanism</b></td>
    <td>Kyber-based secure key exchange</td>
    <td>Post-quantum GAKE using FSXY and Abdalla et al. compilers</td>
  </tr>
  <tr>
    <td><b>Lightweight Implementation</b></td>
    <td>Optimized using permissioned blockchain (Hyperledger)</td>
    <td>Moderate overhead from lattice cryptography</td>
  </tr>
  <tr>
    <td><b>Communication Overhead</b></td>
    <td>Low (thanks to blockchain and key reuse)</td>
    <td>Low to moderate depending on KEM used</td>
  </tr>
  <tr>
    <td><b>Computation Complexity</b></td>
    <td>Moderate due to KEM and blockchain</td>
    <td>Moderate due to post-quantum lattice-based operations</td>
  </tr>
  <tr>
    <td><b>Scalability</b></td>
    <td>Scalable across RSUs and client IoV entities</td>
    <td>Scalable to any n-user GAKE setting</td>
  </tr>
  <tr>
    <td><b>Energy Efficiency</b></td>
    <td>Moderate to high (blockchain optimization)</td>
    <td>Moderate</td>
  </tr>
  <tr>
    <td><b>Resistance to Password Guessing</b></td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td><b>Anonymity & Privacy</b></td>
    <td>Strong anonymity, traceability, unlinkability</td>
    <td>Provides anonymity and unlinkability (via commitment scheme)</td>
  </tr>
  <tr>
    <td><b>Forward Secrecy</b></td>
    <td>Yes (via Kyber KEM session keys)</td>
    <td>Yes (via IND-CCA KEMs and secure transformation)</td>
  </tr>
  <tr>
    <td><b>Mutual Authentication</b></td>
    <td>Yes (via RSU and client identity chains)</td>
    <td>Yes (group-wide via GAKE protocol)</td>
  </tr>
  <tr>
    <td><b>Session Key Establishment</b></td>
    <td>Dynamic session keys from Kyber-based exchange</td>
    <td>Dynamic session key derived in GAKE</td>
  </tr>
  <tr>
    <td><b>Implementation Feasibility</b></td>
    <td>Feasible using blockchain and standard PQ algorithms</td>
    <td>Requires LibOQS + integration with KEM libraries</td>
  </tr>
  <tr>
    <td><b>Use in Real-World Applications</b></td>
    <td>Suited for IoV/IVTS with blockchain</td>
    <td>General-purpose GAKE; adaptable to various domains</td>
  </tr>
  <tr>
    <td><b>Authentication Latency</b></td>
    <td>Low to moderate (optimized with chaincode APIs)</td>
    <td>Moderate (depends on KEM and transformation used)</td>
  </tr>
  <tr>
    <td><b>Protocol Standardization</b></td>
    <td>Aligned with NIST PQ standards and Hyperledger</td>
    <td>Aligned with NIST PQ standard KEMs (Round 3 finalists)</td>
  </tr>
</table>
