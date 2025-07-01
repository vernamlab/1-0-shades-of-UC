# 1/0 Shades of UC – Dataset

This repository contains supporting datasets and circuit images for the paper:

**_1/0 Shades of UC: Photonic Side-Channel Analysis of Universal Circuits_**  
by Dev M. Mehta, Mohammad Hashemi, Domenic Forte, Shahin Tajik, and Fatemeh Ganji  
Published in *IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES), 2024*  
[📄 View on ePrint (Report 2024/072)](https://eprint.iacr.org/2024/072)

---

## 📄 Description

- **`datasets/`**  
  Contains image data used for photonic analysis of triggered combinational blocks. Each subfolder represents a unique trigger pattern or logic function (`block_x`, `block_y`, `block_u`).

- **`attack_circuits/`**  
  Includes two circuit-level illustrations:
  - `c17_attack.png`: Demonstrates UC trigger embedded in the ISCAS-85 `c17` benchmark.
  - `adder_1bit_attack.png`: UC trigger embedded in a simple 1-bit ripple-carry adder.

---

## 📚 Citation

If you use this dataset, please cite our work:

**BibTeX:**

```bibtex
@article{Mehta2024Shades,
  author    = {Dev M. Mehta and Mohammad Hashemi and Domenic Forte and Shahin Tajik and Fatemeh Ganji},
  title     = {1/0 Shades of {UC}: Photonic Side‐Channel Analysis of Universal Circuits},
  journal   = {IACR Trans. Cryptogr. Hardw. Embed. Syst.},
  volume    = {3},
  pages     = {574--602},
  year      = {2024},
  doi       = {10.46586/tches.v3.i3.574-602},
  eprint    = {2024/072},
  archivePrefix = {IACR ePrint},
  primaryClass  = {cryptography}
}
```

## 📬 Contact

**Dev M. Mehta**  
*PhD Candidate, Vernam Lab*  
📧 Email: [dmmehta2@wpi.edu](dmmehta2@wpi.edu)
