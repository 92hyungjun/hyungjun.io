# Hyungjun Oh 

keywords: Deep learning Systems, Distributed Systems, LLM systems  
lab : Machine Learning Systems Lab at Hanyang University  
e-mail : 92hyungjun@gmail.com  
office Address : ITBT 601-1,  222, Wangsimni-ro, Seongdong-gu, Seoul, Republic of Korea  

# About  
I am a Ph.D. student in the Machine Learning Systems Lab at Hanyang University. My research advisor is Prof. Jiwon Seo. 
I am interested in building high-performance distributed systems such as efficient large language model systems for training and inference.  
# Publications  
**ExeGPT: Constraint-Aware Resource Scheduling for LLM Inference (ASPLOS), 2024.**  
**Hyungjun Oh**, Kihong Kim, Jaemin Kim, Sungkyun Kim, Du-seong Chang, and Jiwon Seo*  
1. Led the overall system design and implemented ExeGPT system based on Nvidia's FasterTransformer  
2. Developed allocation methods for distributed LLM inference to maximize GPU resource utilization  
3. Implemented an optimized cuda kernel that minimizes cpu overhead  
4. designed communication-computation overlapping scheduling technology for LLM to maximize hardware resource utilization  
5. participated in scheduling algorithm design  

**Out-Of-Order BackProp: An Effective Scheduling Technique for Deep Learning (EuroSys), 2022.**  
**Hyungjun Oh**, Junyeol Lee, Hyeongju Kim, and Jiwon Seo*  
1. Led the overall system design and implemented OOO BackProp system based on Tensorflow, TensorFlow-XLA and Nvidia’s Megatron.  
2. Developed a novel scheduling technique for efficient training by exploiting the dependencies of gradient computations  
3. Designed an algorithm to find an optimal performance in distributed learning  
4. Developed a communication-computation overlap scheduling technique to efficiently utilize GPU resources for pipeline parallel training  

**Gyro Dropout: Maximizing Ensemble Effect in Neural Network Training (MLSys), 2022.**   
Junyeol Lee, Hyeongju Kim, **Hyungjun Oh**, Jaemin Kim, Hongseok Jeung, Yung-Kyun Noh, and Jiwon Seo*  
1. Implemented MatMul kernel that effectively performs DropOut based on Nvidia's Cutlass  

**Convergence-Aware Neural Network Training(DAC), 2020.**  
**Hyungjun Oh**, Yongseung Yu, Giha Ryu, Gunjoo Ahn, Yuri Jeong, Yongjun Park, and Jiwon Seo*  
1. Led the overall system design and implementation based on Tensorflow and modified Nvidia's Cutlass  
2. Designed an efficient training method by utilizing the parameter convergence behavior  
3. Developed an efficient cuda kernel to monitor the parameter convergence  

**AniFilter: Parallel and Failure-Atomic Cuckoo Filter for Non-Volatile Memories (EuroSys), 2020.**   
**Hyungjun Oh**, Bongki Cho, Changdae Kim, Heejin Park, and Jiwon Seo*  
1. Designed a parallel cache-efficient AMQ Filter in NVM  
