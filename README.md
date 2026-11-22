# Cloud-based Tutorials on AI for Protein Design
### Institute for Biological and Medical Engineering [(IIBM)](http://iibm.uc.cl), Pontificia Universidad Catolica de Chile
### ANID – Millennium Science Initiative Program – Millennium Institute for Integrative Biology [(iBio)](http://ibio.cl)
##
## Introduction
This is an ever-evolving set of tutorials on AI for Protein Design to be executed over a **Google Colab** free cloud-computing environment.

These tutorials were created November 2025 and January 2026 as part of the **IBM3410 AI for Protein Design course** for full execution over Google Colab and remote accesibility via web browsers.

Each tutorial includes installation instructions of the software to be used in each session and several programming, visualization and data analysis activities to be achieved during the tutorial. The notebooks will soon be updated with a brief introduction of the activities to be performed in each tutorial.

## Description of the Tutorials

The following is a brief description of each tutorial, along with the software used for each task:

| Tutorial | Description                           | Software                                                        |
|--------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Lab.01 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/ibm3410/blob/master/tutorials/rfd3/RFD3_unconditional_design.ipynb) | Unconditional *de novo* protein design with RFDiffusion3 | RFDiffusion3 [1], ProteinMPNN [2], LigandMPNN [3], SolubleMPNN [4], AlphaFold3 [5], OpenFold3 [6], Boltz-2 [7], RoseTTAFold3 [8], 3dmol.js [9], Biotite [10], MMseqs2 [11], ColabFold [12] |
| Lab.02 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/ibm3410/blob/master/tutorials/rfd3/RFD3_unconditional_symmetry_design.ipynb) | Unconditional *de novo* symmetric protein design with RFDiffusion3 | RFDiffusion3 [1], ProteinMPNN [2], LigandMPNN [3], SolubleMPNN [4], AlphaFold3 [5], OpenFold3 [6], Boltz-2 [7], RoseTTAFold3 [8], AtomWorks [8], 3dmol.js [9], Biotite [10], MMseqs2 [11], ColabFold [12] |
| Lab.03 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pb3lab/ibm3410/blob/master/tutorials/rfd3/RFD3_protein_binder_design.ipynb) | *De novo* protein & protein-ligand binder design with RFDiffusion3 | RFDiffusion3 [1], ProteinMPNN [2], LigandMPNN [3], SolubleMPNN [4], AlphaFold3 [5], OpenFold3 [6], Boltz-2 [7], RoseTTAFold3 [8], AtomWorks [8], 3dmol.js [9], Biotite [10], MMseqs2 [11], ColabFold [12], biopython [13], py3Dmol [9], ipSAE [14] |

## Authors and Contributors
- Cesar A. Ramirez-Sarmiento (Pontificia Universidad Católica de Chile)
- Max Beining (Leipzig University - Example Colab Tutorials on RFDiffusion3)
- Sergey Ovchinnikov (MIT - Code for Colab version of AlphaFold3 and OpenFold3)

## Licensing / Weights
The AlphaFold3 model weights, available at the official [AlphaFold3 GitHub](https://github.com/google-deepmind/alphafold3), require requesting access directly from Google DeepMind under their [terms of use](https://github.com/google-deepmind/alphafold3/blob/main/WEIGHTS_TERMS_OF_USE.md). Foundry (RFDiffusion3/RoseTTaFold3/MPNN), OpenFold3, and Boltz-2 model weights are open-source and can be downloaded automatically.

## References
1. Butcher J, Krishna R, Mitra R, Woodbury SM, Kim D, Brent RI, Li Y, Corley N, Favor A, Chen A, Kim PT, Funk J, Reinoso GB, Wu K, Muraishi A, Eisenach HE, Salike S, Mathis S, Thompson TR, Ruder A, Sehgal E, Kubaney A, Chen J, Politanska Y, Coventry B, Zhang O, Hardy FJ, Qiang B, Didi K, Kazman M, Schaaf LL, DiMaio F, Baker D. Atomic functional site scaffolding in biopolymers with RFdiffusion3. Science. 2026;eaeh2982. doi: 10.1126/science.aeh2982.
2. Dauparas J, Anishchenko I, Bennett N, Bai H, Ragotte RJ, Milles LF, Wicky BIM, Courbet A, de Haas RJ, Bethel N, Leung PJY, Huddy TF, Pellock S, Tischer D, Chan F, Koepnick B, Nguyen H, Kang A, Sankaran B, Bera AK, King NP, Baker D. Robust deep learning-based protein sequence design using ProteinMPNN. Science. 2022;378(6615):49-56. doi: 10.1126/science.add2187.
3. Dauparas J, Lee GR, Pecoraro R, An L, Anishchenko I, Glasscock C, Baker D. Atomic context-conditioned protein sequence design using LigandMPNN. Nat Methods. 2025;22(4):717-723. doi: 10.1038/s41592-025-02626-1.
4. Goverde CA, Pacesa M, Goldbach N, Dornfeld LJ, Balbi PEM, Georgeon S, Rosset S, Kapoor S, Choudhury J, Dauparas J, Schellhaas C, Kozlov S, Baker D, Ovchinnikov S, Vecchio AJ, Correia BE. Computational design of soluble and functional membrane protein analogues. Nature. 2024;631(8020):449-458. doi: 10.1038/s41586-024-07601-y.
5. Abramson J, Adler J, Dunger J, Evans R, Green T, Pritzel A, Ronneberger O, Willmore L, Ballard AJ, Bambrick J, Bodenstein SW, Evans DA, Hung CC, O'Neill M, Reiman D, Tunyasuvunakool K, Wu Z, Žemgulytė A, Arvaniti E, Beattie C, Bertolli O, Bridgland A, Cherepanov A, Congreve M, Cowen-Rivers AI, Cowie A, Figurnov M, Fuchs FB, Gladman H, Jain R, Khan YA, Low CMR, Perlin K, Potapenko A, Savy P, Singh S, Stecula A, Thillaisundaram A, Tong C, Yakneen S, Zhong ED, Zielinski M, Žídek A, Bapst V, Kohli P, Jaderberg M, Hassabis D, Jumper JM. Accurate structure prediction of biomolecular interactions with AlphaFold 3. Nature. 2024;630(8016):493-500. doi: 10.1038/s41586-024-07487-w.
6. Ahdritz G, Bouatta N, Floristean C, Kadyan S, Xia Q, Gerecke W, O'Donnell TJ, Berenberg D, Fisk I, Zanichelli N, Zhang B, Nowaczynski A, Wang B, Stepniewska-Dziubinska MM, Zhang S, Ojewole A, Guney ME, Biderman S, Watkins AM, Ra S, Lorenzo PR, Nivon L, Weitzner B, Ban YA, Chen S, Zhang M, Li C, Song SL, He Y, Sorger PK, Mostaque E, Zhang Z, Bonneau R, AlQuraishi M. OpenFold: retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization. Nat Methods. 2024;21(8):1514-1524. doi: 10.1038/s41592-024-02272-z.
7. Passaro S, Corso G, Wohlwend J, Reveiz M, Thaler S, Somnath VR, Getz N, Portnoi T, Roy J, Stark H, Kwabi-Addo D, Beaini D, Jaakkola T, Barzilay R. Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction. bioRxiv. 2025;2025.06.14.659707. doi: 10.1101/2025.06.14.659707.
8. Corley N, Mathis S, Krishna R, Bauer MS, Thompson TR, Ahern W, Kazman MW, Brent RI, Didi K, Kubaney A, McHugh L, Nagle A, Favor A, Kshirsagar M, Sturmfels P, Li Y, Butcher J, Qiang B, Schaaf LL, Mitra R, Campbell K, Zhang O, Weissman R, Humphreys IR, Cong Q, Funk J, Sonthalia S, Liò P, Baker D, DiMaio F. Accelerating Biomolecular Modeling with AtomWorks and RF3. bioRxiv. 2025;2025.08.14.670328. doi: 10.1101/2025.08.14.670328.
9. Rego N, Koes D. 3Dmol.js: molecular visualization with WebGL. Bioinformatics. 2015;31(8):1322-4. doi: 10.1093/bioinformatics/btu829.
10. Kunzmann P, Müller TD, Greil M, Krumbach JH, Anter JM, Bauer D, Islam F, Hamacher K. Biotite: new tools for a versatile Python bioinformatics library. BMC Bioinformatics. 2023 Jun 5;24(1):236. doi: 10.1186/s12859-023-05345-6.
11. Steinegger M, Söding J. MMseqs2 enables sensitive protein sequence searching for the analysis of massive data sets. Nat Biotechnol. 2017;35(11):1026-1028. doi: 10.1038/nbt.3988.
12. Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S, Steinegger M. ColabFold: making protein folding accessible to all. Nat Methods. 2022;19(6):679-682. doi: 10.1038/s41592-022-01488-1.
13. Cock PJ, Antao T, Chang JT, Chapman BA, Cox CJ, Dalke A, Friedberg I, Hamelryck T, Kauff F, Wilczynski B, de Hoon MJ. Biopython: freely available Python tools for computational molecular biology and bioinformatics. Bioinformatics. 2009;25(11):1422-3. doi: 10.1093/bioinformatics/btp163.
14. Dunbrack RL Jr. RēsipSAEloquunt: What's wrong with AlphaFold's ipTM score and how to fix it. bioRxiv. 2025;2025.02.10.637595. doi: 10.1101/2025.02.10.637595.
