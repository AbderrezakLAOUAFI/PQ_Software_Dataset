This repository contains the open-source software and synthetic dataset described in: Towards efficient solutions for automatic recognition of complex power quality disturbances.

Abstract [1]:
The integration of renewable energy sources and the emergence of many innovative technologies make abnormal deviations in voltage waveforms more complex and severe, as different combinations of power quality disturbances (PQDs) are likely to be produced simultaneously, significantly impacting the reliability, security, and stability of the grid. Unlike previous studies that considered only a small number of single and double PQDs, the present research addresses the challenge of identifying multiple PQDs with superimposition of up to 4 single disturbances on the same waveform. To this end, a new model is proposed in this paper, which combines the principles of wavelet denoising, hybrid signal processing, feature selection, and pattern classification with a bagged ensemble of decision trees. The main idea behind this integration is to enhance information diversity, track the amplitude variation of complex PQDs, and achieve better generalization capability while ensuring a trade-off between accuracy and computational efficiency. Due to the lack of reliable data on power quality studies, open-source software and a synthetic dataset containing 71 types of disturbances are also provided to support future work and serve as references for evaluating and comparing different methods. The results obtained by the study show: (1) an accuracy rate of 97.03 %, 96.82 %, 96.60 % and 95.16 % for noise-free, 50 dB, 40 dB and 30 dB SNR cases, respectively; (2) superior performance compared to 28 state-of-the-art algorithms; (3) average computation time of 0.5779 s; and (4) promising potential for recognizing PQDs with a large number of possible classes.

Keywords [1]: Smart grid; Power quality disturbances; Open data; Pattern recognition; Artificial intelligence

AutRecPQ.mlappinstall: An app installation file to share my application with MATLAB users. 

PQDs_Dataset_1_24.xlsx: Excel file containing signals related to C1-C24 (class 1 to class 24). 

PQDs_Dataset_25_48.xlsx: Excel file containing signals related to C25-C48. 

PQDs_Dataset_49_72.xlsx: Excel file containing signals related to C49-C72. 

Reference 

[1] Abderrezak Laouafi, Towards efficient solutions for automatic recognition of complex power quality disturbances, Expert Systems with Applications, Volume 286, 2025, 128077, ISSN 0957-4174, https://doi.org/10.1016/j.eswa.2025.128077.

Cite As

Abderrezak Laouafi, Data & materials for: Towards efficient solutions for automatic recognition of complex power quality disturbances, 2025, https://github.com/AbderrezakLAOUAFI/PQ_Software_Dataset.
