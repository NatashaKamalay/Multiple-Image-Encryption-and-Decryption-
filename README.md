Multiple Image Encryption and Decryption using DNA-Based Genetic Encoding

**Overview**
This project implements a secure and reversible multiple image encryption and decryption system using a hybrid approach that combines cryptographic hashing, image processing techniques, and bio-inspired DNA/genetic encoding. The system ensures high security while preserving the integrity of the original images during decryption.


**Key Features**
- Multi-image encryption support
- Secure key generation using SHA-256 hashing
- Bit-plane level image manipulation
- XOR-based diffusion for strong pixel confusion
- DNA/Genetic encoding using nucleotide representations (A, C, T, G / A, C, U, G)
- Fully reversible decryption pipeline (lossless reconstruction)

---

**Core Techniques Used**
- **SHA-256 Hashing** – For cryptographically secure key generation  
- **Bit-Plane Decomposition** – Binary-level image representation  
- **XOR Operations** – Pixel diffusion and manipulation  
- **Matrix Reshaping & Permutation** – Breaking spatial correlations  
- **DNA / Genetic Encoding** – Bio-inspired encoding of pixel data  
- **Reverse Engineering** – Accurate and lossless decryption  



**System Workflow**

1. Input multiple images
2. Generate secure encryption key using SHA-256
3. Decompose images into bit planes
4. Apply XOR-based pixel diffusion
5. Perform reshaping and permutation
6. Encode pixel data using DNA/genetic encoding
7. Generate encrypted image(s)

**Decryption Process**
- Apply reverse DNA decoding
- Perform inverse XOR operations
- Reconstruct bit planes
- Restore original images losslessly

**How to Run**
streamlit run app.py

**Applications**
- Secure image storage and transmission
- Privacy-preserving computer vision systems
- Medical and healthcare image security
- Defense and surveillance applications
- Secure AI/ML data pipelines

---

**Relevance to AI / ML**
This project demonstrates strong foundations in:
- Image preprocessing and pixel-level transformations
- Data representation and encoding techniques
- Algorithmic system design
- Security-aware AI system development


**Technologies Used**
- Python
- NumPy
- Image Processing Libraries
- Cryptographic Hashing (SHA-256)

---

**Future Enhancements**
- Integration of entropy, NPCR, and UACI security metrics
- Performance benchmarking against standard encryption algorithms
- Secure dataset preparation for ML training pipelines
- Extension to video encryption

---

**Author**
**Natasha Kamalay**  
AI & Machine Learning Engineer (Aspirant)

---

**License**
This project is intended for academic and learning purposes.
