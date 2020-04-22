## <center> 문법 및 화용론적 자질을 고려한 어텐션 네트워크 기반 상호참조해결</center>
### <center>Combining Linguistic & Pragmatic Features with Transformer for Coreference Resolution</center> <br><br><br>

### 1. 서론
#### &nbsp;&nbsp;&nbsp;&nbsp; 1.1 연구목적
#### &nbsp;&nbsp;&nbsp;&nbsp; 1.2 연구방법 및 기여
#### &nbsp;&nbsp;&nbsp;&nbsp; 1.3 논문의 구성 <br><br><br>

### 2. 이론적 배경
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.1 용어와 정의
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.1 조응어와 상호참조
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.2 데이터세트
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2.1 Message Undedrstanding Conferences
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2.2 Automatic Content Extraction
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.2.3 OntoNotes
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.3 평가도구
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.1 MUC
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.2 B3
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.3 CEAF
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.4 BALNC 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.5 CoNLL
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.3.6 Error-Driven Evaluation
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.4 상호참조해결 모델
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.4.1 언어학적 모델 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.4.2 규칙기반 모델 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.4.3 기계학습 모델
<br><br><br>

### 3. 연구방법
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.1 고차 추론 및 트랜스포머 기반 상호참조해결
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.1.1 고차 추론 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3.1.2 규칙기반 모델 
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.2 그래프 임베딩을 통한 사전적 지식 활용
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.3 접근성 계층구조(Accessibility Hierarchy)
<br><br><br>

### 4. 실험 및 평가
<br><br><br>


### 5. 결론
<br><br><br>


### [참고문헌](#참고문헌)

<br><br><br>
#참고문헌
***
* 강승식․윤보현․우종우(2004), “Coreference Resolution을 위한 3인칭 대명사의 선행사 결정 규칙,” 소프트웨어 및 데이터 공학 11(2), 227-232
* 김경석(2017), “지시 연쇄 삼각형: 조응과 연상, 직관적 동일 지시,” 어학연구 53(2), 391-414.
* 김경석․김서영(2016), “조응에서 ‘연상’과 ‘추론’의  대위적  상관성,” 어학연구 52(3), 369-392.
* 김기훈․박천음․이창기․김현기(2019), “고차 추론을 이용한 한국어 End-to-end 신경망 기반 상호 참조해결,” Proceeding of KCC.
* 박천음․김기훈․이창기․임준호․류지희․김현기(2019), “BERT 기반 Deep Biaffine을 이용한 한국어 상호참조해결,” 한국컴퓨터종합학술대회 논문집, 488-490.
* 박천음․이창기(2015), “Bidirectional LSTM-CRF 모델을 이용한 멘션탐지,” Proceeding of HCLT.
* 박천음․이창기(2017), “포인터 네트워크를 이용한 한국어 대명사 상호참조해결,” 정보과학회논문지 44(5), 496-502.
* 박천음․이창기(2017), “계층적 포인터 네트워크를 이용한 상호참조해결,”정보과학회 컴퓨팅의 실제 논문지 23(9), 542 – 549.
* 박천음․이창기(2017), “포인터 네트워크를 이용한 멘션탐지,” 정보과학회논문지 44(8), 774-781.
* 박천음․이창기․김현기(2019), “Multi-resolution 포인터 네트워크를 이용한 상호참조해결,” 정보과학회논문지 46(4), 334-340.
* 박천음․최경호․이창기(2014), “Multi-pass Sieve를 이용한 한국어 상호참조 해결,” 정보과학회논문지 41(11), 992-1005.
* 신기연․한기종․이민호․김건태․최기선(2018), “언급 특질을 이용한   Bi-LSTM 기반 한국어 상호참조해결 종단간 학습,” 제 30회 한글 및 한국어 정보처리 학술대회 논문집, 247-251.
* 안영훈․강승식․우종우․윤보현(2001), “경험 규칙에 의한 대명사의 Coreference Resolution,” 한국정보과학회 학술발표논문집 28(2), 193-195.
* 정석원․최맹식․김학수(2016), “랜덤 포레스트를 이용한 한국어 상호참조 해결,” 소프트웨어 및 데이터 공학 5(11), 535-540.
* 조은경․서정연(2005), “인간 기계 대화 시스템에서 조응어 해석,” 한국어 의미학 18, 73-98.
* 최경호․박천음․이창기(2014), “SVM 기반의 Mention Pair Model을 이용한 한국어 상호참조해결,” 한국컴퓨터종합학술대회 논문집, 598-600.
* 최미란․이창기․왕지현․장명길(2017), “온톨로지 인스턴스 생성을 위한 상호참조 해결 연구,” 한국정보과학회 언어공학연구회 학술발표 논문집, 140-144.
* 최형택․나승훈(2017), “k-Max Pooling을 적용한 Cluster-Pair Encoder를 이용한 상호참조해결,” 한국컴퓨터종합학술대회 논문집, 559-601.
* Ariel, M. (1990), Accessing noun-phrase antecedents. London: Routledge. 
* Ariel, M. (2001), “Accessibility theory: an overview,” Text representation: Linguistic and psycholinguistic aspects, 29-87.
* Ariel, M. (2013), “Centering, accessibility and the next mention,” Theoretical Linguistics 39(1-2), 39-58.
* Bengtson, E. and Roth, D. (2008), “Understanding the value of features for coreference resolution,” Proceedings of the 2018 EMNLP, 294–303.
* Clark, K. and Manning, C. D. (2015), “Entity-centric coreference resolution with model stacking,” Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), 1405–1415.
* Clark, K. and Manning, C. D. (2016), “Deep reinforcement learning for mention-ranking coreference models,” Proceedings of the 2016 Conference on EMNLP, 2256–2262.
* Denis, F. and Baldridge, J. (2008), “Specialized models and ranking for coreference resolution,” Proceedings of the 2016 Conference on EMNLP, 660–669.
* Devlin, J., Chang, M., Lee, K. and Toutanova, K. (2019), “BERT: Pre-training of deep bidirectional transformers for language understanding,” Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers), 4171–4186.
* Durrett, G. and Klein, D. (2013), “Easy victories and uphill battles in coreference resolution,” Proceedings of the 2013 Conference on EMNLP, 1971–1982.
* Fei, H., Li, X., Li, D., and Li, P. (2019), “End-to-end deep reinforcement learning based coreference resolution,” Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 660–665.
* Fernandes, E., Santos, C., and Milidi´u, R. (2012), “Latent structure perceptron with feature induction for unrestricted coreference resolution,” Joint Conference on EMNLP and CoNLL – Shared Task, 41–48. 
* Li, H., Wang, A., Liu, Y., Tang, D., Lei, Z., and Li, W. (2019), “An Augmented Transformer Architecture for Natural Language Generation Tasks,” arXiv preprint arXiv:1910.13634v1.
* Lu, Z., Du, P., and Nie, J. (2020), “VGCN-BERT: Augmenting BERT with Graph Embedding for Text Classification,” ECIR 2020: Advances in Information Retrieval, 369-382.
* Jawahar, G., Sagot, B., and Seddah, D. (2019), “What does BERT learn about the structure of language?” Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 3651-3657.
* Joshi, M., Chen, D., Liu, Y. Weld, D. S., Zettlemoyer, L., and Levy, O. (2020), “SpanBERT: Improving Pre-training by Representing and Prediction Spans,” arXiv preprint arXiv:1907.10529v3.
* Joshi, M., Levy O., Weld, D. S., and Zettlemoyer, L. (2019), “BERT for Coreference Resolution: Baselines and Analysis,” arXiv preprint arXiv:1908.09091v4.
* Jurafsky, D. and Martin, J. (2019), Speech and Language Processing, Draft of October 2, 2019.
* Kantor, B. and Globerson, A. (2019), “Coreference resolution with entity equalization,” Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 673–677.
* Lee, K., He, L., Lewis, M., and Zettlemoyer, L. (2017), “End-to-end Neural Coreference Resolution,” Proceedings of the 2017 Conference on EMNLP, 188-197.
* Lee, K., He, L., and Zettlemoyer, L. (2018), “Higher-order Coreference Resolution with Coarse-to-fine Inference,” Proceedings of NAACL-HLT, 687-692.
* Liu, F., Zettlemoyer, L., and Eisenstein, J. (2019), “The referential reader: A recurrent entity network for anaphora resolution,” Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 5918–5925.
* Liu, Y., Ott, M., Goyal, N., Du, J., Joshi, M., Chen, D., Levy, O., Lewis, M., Zettlemoyer, L., and Stoyanov, V. (2019), “RoBERTa: A robustly optimized BERT pretraining approach,” arXiv preprint arXiv:1907.11692v1.
* Martschat, S. and Strube, M. (2015), “Latent structures for coreference resolution,” Transactions of the Association for Computational Linguistics, 3:405–418.
* Ng, V. (2017), “Machine Learning for Entity Coreference Resolution: A Retrospective Look at Two Decades of Research,” Proceedings of the 31st AAAI Conference on Artificial Intelligence (AAA-17), 4877-4884.
* Ng, V. and Cardie, C. (2002), “Identifying anaphoric and non-anaphoric noun phrases to improve coreference resolution,” Proceedings of the 19th International Conference on Computational Linguistics - Volume 1, COLING, 1–7.
* Pradhan, S., Moschitti, A., Xue, N., Uryupina, O., and Zhang, Y. (2012), “Conll-2012 shared task: Modeling multilingual unrestricted coreference in ontonotes,” Joint Conference on EMNLP and CoNLL - Shared Task, 1–40.
* Ren, M. and Kang, S. (2016), “A Context-Restricted Multi-Stage Korean Coreference Resolution Model,” International Journal of Software Engineering and Its Applications Vol. 10, No. 2, 139-148.
* Sukthanker, R., Poria, S., Cambria, E., and Thirunavukarasu, R. (2018), “Anaphora and Coreference Resolution: A Review,” arXiv preprint arXiv:1805.11824.
* Webster, K. and Nothman, J. (2016), “"Using Mention Accessibility to Improve Coreference Resolution," The 54th Annual Meeting of the Association for Computational Linguistics.
* Webster, K., Recasens, M., Axelrod, V., and Baldridge J. (2018), “Mind the GAP: A balanced corpus of gendered ambiguous pronouns,” Transactions of the Association for Computational Linguistics, 6:605–617.
* Wiseman, S., Rush, A., Shieber, S., and Weston, J. (2015), “Learning anaphoricity and antecedent ranking features for coreference resolution,” Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), 1416–1426.
* Wiseman, S., Rush, A., and Shieber, S. (2016), “Learning global features for coreference resolution,” Proceedings of the 2016 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, 994–1004.
* Wu, W., Wang, F., Yuan, A., Wu, F., and Li, J. (2019), “Coreference Resolution as Query-based Span Prediction,” arXiv preprint arXiv:1911.01746.
* Zhou, W., Zhang, X., and Jiang, H. (2019), “Ensemble BERT with Data Augmentation andLinguistic Knowledge on SQuAD 2.0.” 
