### [WIP]
**This is a heavily adapted fork of the Transformer-XL repository ([https://github.com/kimiyoung/transformer-xl](https://github.com/kimiyoung/transformer-xl))**


This repository includes the code applied for the following two articles

1. ---
>**Novel transformer networks for improved sequence labeling in genomics**
>
>Jim Clauwaert, Willem Waegeman
>
>https://www.biorxiv.org/content/10.1101/836163v1

2. ---
>**An in-depth evaluation of annotated transcription start sites in *E. coli* using deep learning**
>
>Jim Clauwaert, Gerben Menschaert, Willem Waegeman
>
>To be submitted
    ---

## Novel transformer networks for improved sequence labeling in genomics

**Data**

    data
    ├── eco_regulon
    │   ├── eco_regulon_70.npy
    ├── eco_TIS
    │   ├── eco_TIS.npy
    ├── eco_SMRTmeth
    │   ├── eco_m4c.npy


**Train models**

    run_m4c.sh
    run_TIS.sh
    run_TSS.sh
---
## An in-depth evaluation of annotated transcription start sites in *E. coli* using deep learning

**Data**

    data
    ├── eco_regulon
    │   ├── eco_regulon_strong.npy
    ├── eco_capseq
    │   ├── eco_rm_capseq.npy
    ├── eco_smrtcapseq
    │   ├── eco_smrt_capseq.npy
    ├── eco_SEndseq
    │   ├── eco_SEndseq.npy
    ├── eco_custom
    │   ├── eco_custom.npy

**Train models**

    run_regulon.sh
    run_cappable.sh
    run_smrtcappable.sh
    run_send.sh
    run_custom.sh
