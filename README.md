# Semantic-Parsing-Paper-List
A summary of papers for Semantic Parsing (Continuous updates)

## Text-to-SQL

### Dataset
1. [Spider: A Large-Scale Human-Labeled Dataset for Complex and Cross-Domain Semantic Parsing and Text-to-SQL Task](https://arxiv.org/pdf/1809.08887.pdf) EMNLP, 2018. \
*Tao Yu, Rui Zhang, Kai Yang, Michihiro Yasunaga, Dongxu Wang, Zifan Li, James Ma, Irene Li, Qingning Yao, Shanelle Roman, Zilin Zhang, Dragomir Radev*
2. [A Pilot Study for Chinese SQL Semantic Parsing](https://aclanthology.org/D19-1377) EMNLP, 2019. \
*Qingkai Min, Yuefeng Shi, and Yue Zhang*
3. [DuSQL: A Large-Scale and Pragmatic Chinese Text-to-SQL Dataset
](https://aclanthology.org/2020.emnlp-main.562.pdf) EMNLP, 2020. \
*Lijie Wang, Ao Zhang, Kun Wu, Ke Sun, Zhenghua Li, Hua Wu, Min Zhang, and Haifeng Wang*

### Model
1. [S^2SQL: Injecting Syntax to Question-Schema Interaction Graph Encoder for Text-to-SQL Parsers](https://arxiv.org/pdf/2203.06958.pdf) ACL Findings, 2022 \
*Tao Yu, Chien-Sheng Wu, Xi Victoria Lin, Bailin Wang, Yi Chern Tan, Xinyi Yang, Dragomir Radev, Richard Socher, Caiming Xiong*
2. [LGESQL: Line Graph Enhanced Text-to-SQL Model with Mixed Local and Non-Local Relations
]() ACL, 2021 \
*Ruisheng Cao, Lu Chen, Zhi Chen, Yanbin Zhao, Su Zhu, Kai Yu*
3. [PICARD: Parsing Incrementally for Constrained Auto-Regressive Decoding from Language Models](https://export.arxiv.org/pdf/2109.05093.pdf) EMNLP, 2021 \
*Torsten Scholak, Nathan Schucher, Dzmitry Bahdanau*
4. [RAT-SQL: Relation-Aware Schema Encoding and Linking for Text-to-SQL Parsers](https://arxiv.org/pdf/1911.04942.pdf) ACL, 2020 \
*Bailin Wang, Richard Shin, Xiaodong Liu, Oleksandr Polozov, Matthew Richardson*
5. [Towards Complex Text-to-SQL in Cross-Domain Database with Intermediate Representation](https://aclanthology.org/P19-1444) ACL, 2019 \
*Jiaqi Guo, Zecheng Zhan, Yan Gao, Yan Xiao, Jian-Guang Lou, Ting Liu, and Dongmei Zhang*

### Pretraining
1. [Structure-Grounded Pretraining for Text-to-SQL](https://aclanthology.org/2021.naacl-main.105) NAACL, 2021. \
*Xiang Deng, Ahmed Hassan Awadallah, Christopher Meek, Oleksandr Polozov, Huan Sun, and Matthew Richardson*
2. [GraPPa: Grammar-Augmented Pre-Training for Table Semantic Parsing](https://arxiv.org/pdf/2009.13845.pdf) ICLR, 2021
*Tao Yu, Chien-Sheng Wu, Xi Victoria Lin, Bailin Wang, Yi Chern Tan, Xinyi Yang, Dragomir Radev, Richard Socher, Caiming Xiong*

### Robustness
1. [Towards Robustness of Text-to-SQL Models Against Natural and Realistic Adversarial Table Perturbation](https://arxiv.org/pdf/2106.01065.pdf) ACL, 2022. \
*Xinyu Pi, Bing Wang, Yan Gao, Jiaqi Guo, Zhoujun Li, Jian-Guang Lou*
2. [Towards Robustness of Text-to-SQL Models against Synonym
Substitution](https://arxiv.org/pdf/2106.01065.pdf) ACL, 2021. \
*Yujian Gan, Xinyun Chen, Qiuping Huang, Matthew Purver, John R. Woodward, Jinxia Xie, Pengsheng Huang*

### Generalization
1. [Measuring and Improving Compositional Generalization in Text-to-SQL
via Component Alignment](https://arxiv.org/pdf/2205.02054.pdf) NAACL, 2022. \
*Yujian Gan, Xinyun Chen, Qiuping Huang, Matthew Purver*
2. [SeaD: End-to-end Text-to-SQL Generation with Schema-aware Denoising](https://arxiv.org/pdf/2105.07911.pdf) NAACL, 2022. \
*Kuan Xu and Yongbo Wang and Yongliang Wang and Zujie Wen and Yang Dong*
3. [Weakly Supervised Text-to-SQL Parsing through Question Decomposition](http://export.arxiv.org/pdf/2112.06311) NAACL, 2022. \
*Tomer Wolfson, Daniel Deutch, Jonathan Berant*

## Conversational Text-to-SQL

### Dataset
1. [CoSQL: A Conversational Text-to-SQL Challenge Towards Cross-Domain Natural Language Interfaces to Databases
](https://arxiv.org/pdf/1909.05378.pdf) EMNLP, 2019. \
*Tao Yu, Rui Zhang, He Yang Er, Suyi Li, Eric Xue, Bo Pang, Xi Victoria Lin, Yi Chern Tan, Tianze Shi, Zihan Li, Youxuan Jiang, Michihiro Yasunaga, Sungrok Shim, Tao Chen, Alexander Fabbri, Zifan Li, Luyao Chen, Yuwen Zhang, Shreya Dixit, Vincent Zhang, Caiming Xiong, Richard Socher, Walter S Lasecki, Dragomir Radev*
2. [SParC: Cross-Domain Semantic Parsing in Context](https://aclanthology.org/P19-1443) ACL, 2019. \
*Tao Yu, Rui Zhang, Michihiro Yasunaga, Yi Chern Tan, Xi Victoria Lin, Suyi Li, Heyang Er, Irene Li, Bo Pang, Tao Chen, Emily Ji, Shreya Dixit, David Proctor, Sungrok Shim, Jonathan Kraft, Vincent Zhang, Caiming Xiong, Richard Socher, and Dragomir Radev*
3. [Chase: A Large-Scale and Pragmatic Chinese Dataset for Cross-Database Context-Dependent Text-to-SQL](https://aclanthology.org/2021.acl-long.180) ACL, 2021. \
*Jiaqi Guo, Ziliang Si, Yu Wang, Qian Liu, Ming Fan, Jian-Guang Lou, Zijiang Yang, and Ting Liu*

### Model
1. [HIE-SQL: History Information Enhanced Network for Context-Dependent Text-to-SQL Semantic Parsing](https://arxiv.org/pdf/2203.07376.pdf) ACL Findings, 2022. \
*Yanzhao Zheng, Haibin Wang, Baohua Dong, Xingjun Wang, Changshan Li*
2. [Dynamic Hybrid Relation Network for Cross-Domain Context-Dependent Semantic Parsing](https://arxiv.org/pdf/2101.01686v1.pdf) AAAI, 2021. \
*Binyuan Hui, Ruiying Geng, Qiyu Ren, Binhua Li, Yongbin Li, Jian Sun, Fei Huang, Luo Si, Pengfei Zhu, Xiaodan Zhu*
*Yanzhao Zheng, Haibin Wang, Baohua Dong, Xingjun Wang, Changshan Li*
3. [Tracking Interaction States for Multi-Turn Text-to-SQL Semantic Parsing](https://arxiv.org/pdf/2012.04995v1.pdf) AAAI, 2021. \
*Run-Ze Wang, Zhen-Hua Ling, Jing-Bo Zhou, Yu Hu*
4. [Pay More Attention to History: A Context Modeling Strategy for Conversational Text-to-SQL](https://arxiv.org/pdf/2112.08735v1.pdf) \
*Yuntao Li, Hanchu Zhang, Yutian Li, Sirui Wang, Wei Wu, Yan Zhang*
5. [IGSQL: Database Schema Interaction Graph Based Neural Model for Context-Dependent Text-to-SQL Generation
](https://arxiv.org/pdf/2011.05744v1.pdf) EMNLP, 2020. \
*Yitao Cai, Xiaojun Wan*
6. [Editing-Based SQL Query Generation for Cross-Domain Context-Dependent Questions](https://arxiv.org/pdf/1909.00786.pdf) EMNLP, 2019. \
*Rui Zhang, Tao Yu, He Yang Er, Sungrok Shim, Eric Xue, Xi Victoria Lin, Tianze Shi, Caiming Xiong, Richard Socher, Dragomir Radev*
7. [Learning to Map Context-Dependent Sentences to Executable Formal Queries](https://aclanthology.org/N18-1203) NAACL, 2018. \
*Alane Suhr, Srinivasan Iyer, Yoav Artzi*
