# Analysis of thermal shift assay data using KNIME

The Thermal Shift Assay (TSA) – also known as Differential Scanning Fluorimetry (DSF), Thermofluor, and Tm shift – is one of the most popular biophysical screening techniques used in fragment-based ligand discovery (FBLD) to detect protein-ligand interactions. By comparing the thermal stability of a target protein in the presence and absence of a ligand, potential binders can be identified. The technique is easy to set up, has low protein consumption, and can be run on most real-time Polymerase Chain Reaction (PCR) instruments. While data analysis is straightforward in principle, it becomes cumbersome and time-consuming when the screens involve multiple 96- or 384-well plates. There are several approaches that aim to streamline this process, but most involve proprietary software, programming knowledge, or are designed for specific instrument output files. We therefore developed an analysis workflow implemented in the Konstanz Information Miner (KNIME), a free and open-source data analytics platform, which greatly streamlined our data processing timeline for 384-well plates. The implementation is code-free and freely available to the community for improvement and customization to accommodate a wide range of instrument input files and workflows. 
