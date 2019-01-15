# Research Advances In Semantic Slot Filling 

This repo mainly summary latest research advances on semantic slot filling.

# Performance

#### Note: these results from ATIS dataset.

| Model | F1 Score | Intent Accuracy | Year |
| ------ | ------ |------ |------ |
|Recursive NN  | 0.9396 | 0.954 |Guo et al. 2014 |
|Joint model with recurrent intent and slot label context  | 0.9447 | 0.984 | Liu and Lane, 2016b |
|Joint model with recurrent slot label context  | 0.9464 |  0.984 | Liu and Lane, 2016b |
|RNN with Label Sampling  | 0.9489 | NA | Liu and Lane, 2015 |
| Hybrid RNN | 0.9506 | NA | Mesnil et al., 2015 |
| RNN-EM | 0.9525 |  NA  | Peng and Yao, 2015 |
| CNN-CRF | 0.9435 | NA  | Xu and Sarikaya, 2013 |
| Encoder-labeler Deep LSTM | 0.9566 | NA  | Kurata et al., 2016 |
| Joint GRU model(W) | 0.9549 | 0.9810  |Zhang and Wang, 2016|
| Attention Encoder-Decoder NN | 0.9587 | 0.9843 | Liu and Lane, 2016a|
| Bi-model with a decoder | 0.9665 | 0.9876  | Wang and Shen, 2018 |
| Bi-model with a decoder | 0.9689 | 0.9899  | Wang and Shen, 2018 |


# Related Papers
#### 2010
- [Tur, Gokhan, Dilek Hakkani-Tür, and Larry Heck. "What is left to be understood in ATIS?." Spoken Language Technology Workshop (SLT), 2010 IEEE. IEEE, 2010.](https://ieeexplore.ieee.org/abstract/document/5700816)

#### 2013
- [Mesnil, Grégoire, et al. "Investigation of recurrent-neural-network architectures and learning methods for spoken language understanding." Interspeech. 2013.](https://www.isca-speech.org/archive/archive_papers/interspeech_2013/i13_3771.pdf)

- [Yao, Kaisheng, et al. "Recurrent neural networks for language understanding." Interspeech. 2013.](https://www.isca-speech.org/archive/archive_papers/interspeech_2013/i13_2524.pdf)

#### 2014
- [Yao, Kaisheng, et al. "Spoken language understanding using long short-term memory neural networks." Spoken Language Technology Workshop (SLT), 2014 IEEE. IEEE, 2014.](https://groups.csail.mit.edu/sls/publications/2014/Zhang_SLT_2014.pdf)

#### 2015
- [Peng, Baolin, and Kaisheng Yao. "Recurrent neural networks with external memory for language understanding." arXiv preprint arXiv:1506.00195 (2015).](https://arxiv.org/abs/1506.00195.pdf)

- [ Mesnil, Grégoire, et al. "Using recurrent neural networks for slot filling in spoken language understanding." IEEE/ACM Transactions on Audio, Speech, and Language Processing 2015](https://ieeexplore.ieee.org/abstract/document/6998838)

- [Liu, B., and Lane, I. 2015. Recurrent neural network structured output prediction for spoken language understanding. In NIPS Workshop.](https://pdfs.semanticscholar.org/b75b/59f38c874a920102834c9e218c960fc35c81.pdf)

- [Peng, B., and Yao, K. 2015. Recurrent neural networks with external memory for language understanding.arXiv.](https://ieeexplore.ieee.org/abstract/document/7078572)

#### 2016
- [Vu, Ngoc Thang. "Sequential convolutional neural networks for slot filling in spoken language understanding." arXiv preprint arXiv:1606.07783 (2016).](https://arxiv.org/abs/1606.07783.pdf)

- [Vu, Ngoc Thang, et al. "Bi-directional recurrent neural network with ranking loss for spoken language understanding." Acoustics, Speech and Signal Processing (ICASSP), 2016 IEEE International Conference on. Ieee, 2016.](https://ieeexplore.ieee.org/abstract/document/7472841)

- [ Hakkani-Tür, Dilek, et al. "Multi-Domain Joint Semantic Frame Parsing Using Bi-Directional RNN-LSTM." Interspeech 2016](https://pdfs.semanticscholar.org/d644/ae996755c803e067899bdd5ea52498d7091d.pdf)

- [ Zhang, Xiaodong, and Houfeng Wang. "A Joint Model of Intent Determination and Slot Filling for Spoken Language Understanding." IJCAI 2016](https://www.ijcai.org/Proceedings/16/Papers/425.pdf)

- [ Liu, Bing, and Ian Lane. "Attention-based recurrent neural network models for joint intent detection and slot filling." Interspeech 2016](https://arxiv.org/abs/1609.01454)

- [ Kurata, Gakuto, et al. "Leveraging sentence-level information with encoder lstm for semantic slot filling." EMNLP 2016](https://arxiv.org/abs/1601.01530.pdf)

#### 2017
- [Zhang, Yuhao, et al. "Position-aware attention and supervised data improve slot filling." Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing. 2017.](http://www.aclweb.org/anthology/D17-1004)

- [Zhao, Tiancheng, et al. "Generative encoder-decoder models for task-oriented spoken dialog systems with chatting capability." arXiv preprint arXiv:1706.08476 (2017).](https://arxiv.org/abs/1706.08476)

- [Zhai, Feifei, et al. "Neural Models for Sequence Chunking." AAAI. 2017.](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14776/14262)

- [Zhu, Su, and Kai Yu. "Encoder-decoder with focus-mechanism for sequence labelling based spoken language understanding." 2017 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2017.](https://ieeexplore.ieee.org/abstract/document/7953243)

#### 2018
- [ Constantin, Stefan, Jan Niehues, and Alex Waibel. "Multi-task learning to improve natural language understanding." 2018](https://arxiv.org/abs/1812.06876.pdf)

- [ Zhao, Lin, and Zhe Feng. "Improving Slot Filling in Spoken Language Understanding with Joint Pointer and Attention." ACL 2018](http://www.aclweb.org/anthology/P18-2068)

- [Wang, Yu, Yilin Shen, and Hongxia Jin. "A Bi-model based RNN Semantic Frame Parsing Model for Intent Detection and Slot Filling." Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Short Papers). Vol. 2. 2018.](http://www.aclweb.org/anthology/N18-2050)

- [ Gong, Yu, et al. "Deep Cascade Multi-task Learning for Slot Filling in Online Shopping Assistant." 2019](http://www.cs.sjtu.edu.cn/~kzhu/papers/kzhu-slot.pdf)







