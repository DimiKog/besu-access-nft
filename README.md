# 🪙 Besu Access NFT

Το **Besu Access NFT** είναι μια αποκεντρωμένη εφαρμογή (DApp) που επιτρέπει στους φοιτητές να δημιουργήσουν (mint) το **Course Starter NFT** στο ιδιωτικό δίκτυο **QBFT Besu EduNet** του Πανεπιστημίου Δυτικής Αττικής (ΠΑΔΑ).

Το NFT λειτουργεί ως **ψηφιακή απόδειξη συμμετοχής** στο μάθημα *Υπολογιστικά συστήματα υψηλών επιδόσεων για εφαρμογές blockchain* και θα χρησιμοποιηθεί για **πρόσβαση σε επόμενες δραστηριότητες, εργαστήρια ή εκπαιδευτικό περιεχόμενο** μέσα στο οικοσύστημα του Besu EduNet.

---

## 🌐 Περιγραφή

Μέσω της σελίδας mint, οι φοιτητές μπορούν:

1. 🔗 Να συνδέσουν το πορτοφόλι τους (**MetaMask**) στο δίκτυο Besu EduNet  
2. 🪙 Να δημιουργήσουν το προσωπικό τους **Course Starter NFT**  
3. ✅ Να επαληθεύσουν την κατοχή του NFT μέσω της σελίδας **Verify Access**

Το NFT αποθηκεύεται **on-chain** στο Besu EduNet και περιέχει μεταδεδομένα που συνδέονται με το προφίλ του φοιτητή, το έτος και το μάθημα.

---

## ⚙️ Τεχνικές Λεπτομέρειες

| Παράμετρος | Τιμή |
|-------------|------|
| **Network Name** | QBFT Besu EduNet |
| **RPC URL** | `https://rpc.dimikog.org/rpc/` |
| **Chain ID** | `424242` |
| **Currency Symbol** | `EDU-D` |
| **Explorer** | [https://blockexplorer.dimikog.org](https://blockexplorer.dimikog.org) |
| **Contract Name** | CourseStarterNFT |
| **Standard** | ERC-721 (NFT) |
| **Framework** | HTML + JavaScript (ethers.js) |

---

## 🧠 Χρήσεις του NFT

- 🎓 Πρόσβαση σε επόμενα Web3 εργαστήρια και projects  
- 🧩 Απόδειξη συμμετοχής σε μαθήματα του Besu EduNet  
- 🪪 Επαλήθευση ταυτότητας χρήστη για DAO / Web3Edu  
- 🏅 Απόκτηση επόμενων “εκπαιδευτικών NFTs” με βάση την πρόοδο

---

## 🧩 Αρχεία Repository
besu-access-nft/
│
├── index.html          ← Σελίδα Mint NFT
├── verify.html         ← Σελίδα επαλήθευσης NFT κατοχής
├── /scripts/
│   └── mint.js         ← Λογική σύνδεσης και mint με ethers.js
├── /assets/
│   └── nft.png         ← Εικόνα NFT
└── /metadata/
└── course-starter.json ← Metadata NFT

---

## 🧑‍💻 Συντήρηση

Αναπτύχθηκε από τον  
**Δρ. Δημήτρη Γ. Κόγια**  
Blockchain Educator & Researcher – Πανεπιστήμιο Δυτικής Αττικής  
🌐 [https://dimikog.org](https://dimikog.org)

© 2025 Blockchain Lab – UniWA. Όλα τα δικαιώματα διατηρούνται.
