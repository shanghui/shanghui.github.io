---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

In our group,  we develop the physical algorithm and numerical methods for the scientific calculations as well as accelerating these applications in the highperformance computers. If you find this interesting and exciting, you can find our articles on [Google Scholar profile](https://scholar.google.com/citations?user=HBY4LJ8AAAAJ&hl=zh-CN). Topics we are currently working on include:

## 1. All-electron density functional perturbation theory

We have proposed a computational framework for density functional perturbation theory with all-electron, full-potential accuracy. Pioneered the development and implementation of computational methods simultaneously adaptable to molecules and solids, as well as to external perturbations such as atomic displacements and electric fields. Achieved billion-core scalable all-electron, full-potential first-principles calculations on China's exascale heterogeneous many-core supercomputers.

[1]Shang, H.*, Carbogno, C., Rinke, P. & Scheffler, M. Lattice dynamics calculations based on density-functional perturbation theory in real space. Comput. Phys. Commun. 215, 26–46 (2017). https://doi.org/10.1016/j.cpc.2017.01.017

[2]Shang, H., Raimbault, N., Rinke, P., Scheffler, M., Rossi, M. & Carbogno, C. All-electron, real-space perturbation theory for homogeneous electric fields: theory, implementation, and application within DFT. New J. Phys. 20, 073040 (2018). https://doi.org/10.1088/1367-2630/aace6d

[3]Shang, H., Argondizzo, A., Tan, S., Zhao, J., Rinke, P., Carbogno, C., Scheffler, M. & Petek, H. Electron-phonon coupling in d-electron solids: A temperature-dependent study of rutile TiO2 by first-principles theory and two-photon photoemission. Phys. Rev. Research 1, 033153 (2019). https://doi.org/10.1103/PhysRevResearch.1.033153

[4]Shang, H., Duan, X., Li, F., Zhang, L., Xu, Z., Liu, K., Luo, H., Ji, Y., Zhao, W., Xue, W., Chen, L. & Zhang, Y. Many-core acceleration of the first-principles all-electron quantum perturbation calculations. Comput. Phys. Commun. 267, 108045 (2021). https://doi.org/10.1016/j.cpc.2021.108045

[5]Shang, H., Li, F., Zhang, Y., Zhang, L., Fu, Y., Gao, Y., Wu, Y., Duan, X., Lin, R., Liu, X., Liu, Y. & Chen, D. Extreme-scale ab initio quantum raman spectra simulations on the leadership HPC system in China. In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC '21) 1–13 (Association for Computing Machinery, New York, 2021). https://doi.org/10.1145/3458817.3476145  (Gordon Bell Prize Finalist)

[6]Wu, Z., Wu, Y., Liu, Y.,* Shang, H.*, Gao, Y., Zhang, Z., Zhang, Y., Long, Y., Feng, X. & Cui, H. Portable and scalable all-electron quantum perturbation simulations on exascale supercomputers. In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC '23) (Association for Computing Machinery, New York, 2023). https://doi.org/10.1145/3581784.3607054

[7]Shang, H.,* Liu, Y*., Wu, Z., Chen, Z., Liu, J., Shao, M., Li, Y., Kan, B., Cui, H., Feng, X., Zhang, Y., Truhlar, D. G., An, H., He, X.* & Yang, J.* Pushing the limit of quantum mechanical simulation to the raman spectra of a biological system with 100 million atoms. In Proceedings of the International Conference for High Performance Computing, Networking, Storage, and Analysis (SC '24) (IEEE Press, 2024). https://doi.org/10.1109/SC54273.2024.00097 (Gordon Bell Prize Finalist))


## 2. High performance quantum computing emulation for quantum chemistry

We demonstrate a high-performance and massively parallel variational quantum eigensolver (VQE) simulator based on matrix product states, combined with embedding theory for solving large-scale quantum computing emulation for quantum chemistry on HPC platforms. We apply this method to study the torsional barrier of ethane and the quantification of the protein–ligand interactions. Our largest simulation reaches 1000 qubits, and a performance of 216.9 PFLOP/s is achieved on a new Sunway supercomputer, which sets the state-of-the-art for quantum computing emulation for quantum chemistry. 

[1] Shang, H.*, Fan, Y., Guo, C.*, Zhou, W., Shen, L., Xu, Z., Liu, J.*, Ma, H., Lin, R., Li, F., Zhang, Y., Yang, Y., Wang, Z., & Li, Z. Large-Scale Simulation of Quantum Computational Chemistry on a New Sunway Supercomputer. In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC '22) (IEEE, Dallas, 2022). https://doi.org/10.1109/SC41404.2022.00008

[2] Shang, H.*, Fan, Y., Shen, L., Guo, C.*, Liu, J.*, Duan, X., Li, F., & Li, Z. Towards practical and massively parallel quantum computing emulation for quantum chemistry. npj Quantum Information 9, 33 (2023), https://doi.org/10.1038/s41534-023-00696-7

[3] Ma, H., Liu, J.*, Shang, H.*, Fan, Y., Li, Z., & Yang, J.* Multiscale quantum algorithms for quantum chemistry. Chem. Sci. 14, 3190-3205 (2023), https://doi.org/10.1039/d2sc06875c

[4] Guo, C., Fan, Y., Xu, Z., & Shang, H.* Differentiable matrix product states for simulating variational quantum computational chemistry. Quantum 7, 1205 (2023), https://doi.org/10.22331/q-2023-11-28-1205

[5] Shang, H., Wang, F., Fan, Y., Ma, H., Liu, Q., Guo, C., Zhou, P., Chen, Q., Xiao, Q., Zheng, T., Li, B., Zuo, F., Liu, J.*, Li, Z., & Yang, J. Large-scale quantum emulating simulations of biomolecules: A pilot exploration of parallel quantum computing. Science Bulletin 69, 876-880 (2024), https://doi.org/10.1016/j.scib.2024.01.022

[6] Shang, H., Fan, Y., Liu, J., & Yang, J.* 生物大分子的量子计算模拟:并行量子计算的初步探索. 科学通报 69, 1967-1969 (2024), https://doi.org/10.1360/TB-2024-0376

[7] Xu, Z., Zeng, X., Shang, H.*, Zhang, Y., Fan, Y., & Guo, C*. Scalable and Differentiable Simulator for Quantum Computational Chemistry. In Proceedings of the IEEE International Parallel & Distributed Processing Symposium (IPDPS '24) (IEEE, San Francisco, 2024). https://doi.org/10.1109/IPDPS59261.2024.00109



## 3. QiankunNet: Neural network quantum state (NNQS) method for quantum chemistry

The fundamental many-electron Schrodinger equation is solved straightforwardly with QiankunNet, a neural network quantum state (NNQS) framework based on generative Transformer architecture along with a batched autoregressive sampling method tailored for this Transformer-based ansatz in quantum chemistry calculations. This approach significantly improves the accuracy and efficiency of first-principles calculations compared to previous
fermionic ansatz methods. QiankunNet showcases the power of the Transformer-based language model in achieving
unprecedented efficiency in quantum chemistry calculations, opening up new avenues for chemical discovery and demonstrating the potential to solve the large-scale Schrodinger equation with modest computational cost.

[1] Shang, H.* , Guo, C., Wu, Y., Li, Z., Yang, J.*  Solving Schrödinger Equation with a Transformer-based framework. Nat. Commun. 16, 8464 (2025), https://www.nature.com/articles/s41467-025-63219-2

[2] Wu, Y., Guo, C.,* Fan, Y., Zhou, P. & Shang, H.* NNQS-Transformer: An efficient and scalable neural network quantum states approach for ab initio quantum chemistry. In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC '23) (Association for Computing Machinery, New York, 2023). https://dl.acm.org/doi/10.1145/3581784.3607053

[3] Fu, L., Wu, Y., Shang, H.* & Yang, J.* Transformer-Based Neural-Network Quantum State Method for Electronic Band Structures of Real Solids. J. Chem. Theory Comput. 20, 6218 (2024). https://doi.org/10.1021/acs.jctc.4c00257

[4] Ma, H., Shang, H.* & Yang, J.* Quantum embedding method with transformer neural network quantum states for strongly correlated materials. npj Comput. Mater. 10, 220 (2024). https://doi.org/10.1038/s41524-024-01231-8

[5] Lai, J., Kan, B., Wu, Y., Fu, Q.,* Shang, H.,* Li, Z., Yang, J*. Accurate Calculation of Interatomic Forces with Neural Networks Based on a Generative Transformer Architecture. J. Chem. Theory Comput. 20, 9478 (2024). https://doi.org/10.1021/acs.jctc.4c00756

[6] Kan, B., Tian, Y., Wu, Y., Zhang, Y. & Shang, H.* Bridging the Gap between Transformer-Based Neural Networks and Tensor Networks for Quantum Chemistry. J. Chem. Theory Comput. 21, 3426 (2025). https://doi.org/10.1021/acs.jctc.4c01703

[7] Wu, Y., Cao, W., Zhao, J., Shang, H.* Fast and Scalable Neural Network Quantum States Method for Molecular Potential Energy Surfaces. IEEE Transactions on Parallel and Distributed Systems. 36(7), 1431 (2025). https://doi.org/10.1109/TPDS.2025.3568360

[8] Kan, B., Zhou, Y., Xie D., Zhou P., Zhang Y., Shang, H.*  NNQS-SCI: Tackling Trillion-Dimensional Hilbert Space with  Adaptive Neural Network Quantum States. In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC '25) (Association for Computing Machinery, New York, 2025).

[9] Ma, H., Fu, L., Shang, H.* , Yang, J.* QiankunNet-Solid/DMET: a generative neural network quantum state method for solid material simulations (in Chinese). Chin Sci Bull, 70, 4015 (2025), doi: 10.1360/CSB-2025-0315    




