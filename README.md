<table>
  <tr>
    <th>Feature</th>
    <th>Paper 7: Post-Quantum Blockchain IoV</th>
    <th>Paper 8: GAKE with LibOQS</th>
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
