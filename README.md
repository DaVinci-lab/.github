#### About Da Vinci Lab 🔭 :electron:	

We are intereted in studying and developing intelligent algorithms enabled by constraints(exposed by representations) that support models targeted at thinking, perception and action.  My recent focus has largely been on Applied Machine Learning, which is is full of [fascinating open problems](https://www.asjadk.io/real-world-rl/) like [Generalization](https://www.asjadk.io/generalization/), [intelligent exploration vs exploitation](https://www.asjadk.io/strategic-exploration-in-online-decision-making/), [counter-factual evaluation](https://www.asjadk.io/counterfactual-policy-evaluation/), Meta-Learning
 and Sample Efficient Learning. Progress in solving these problems, can have a major impact on domains like industrial automation, healthcare and Education. 


##### Decision Support Systems: 

###### Healthcare 

Digitization of healthcare data along algorithmic breakthroughts in AI will have a major impact on healthcare delivery in coming years. I'm particularly interested in application of AI to assist clinicians during partient treatment in a privacy preserving way. While scientific knowledge can help guide interventions, there remains a key need to quickly cut through the space of decision policies to find effective strategies to support patients during the care process. 
 
- In  [MIMIC-RL](https://github.com/asjad99/MIMIC_RL_COACH) I investigate the problem of developing a Clinical Decision Support System for Sepsis Management using Deep Reinforcement Learning. In our implementation we try to answer the following question: Given a particular patient’s characteristics and physiological information at each time step as input, can our proposed framework learn an optimal treatment policy that can prescribe the right intervention(e.g use of ventilator) to the patient each stage of the treatment process, in order to improve the final outcome(e.g patient mortality)?. see [[Blog_post](https://www.asjadk.io/decision_support/)] for more details.

- Medical Data is often geographically dispersed distribtuted and privacy concerns can prevent us from building a central data-warehouse. Using Techniques like fedderated learning and differential privacy we can extract process models from distributed healthcare process logs. We explore the multi-party compute with the the framework of federated learning. see paper for more details. [[paper](https://github.com/asjad99/Distributed-Process-Mining/blob/main/Distributed_Process_Mining.pdf)]. 

###### Process Analytics 

Take a look at the [Survey]() for a broad overview of AI's impact on supporting and improving business processes.

AI plays a key role in operational and strategic Business decision making. I have been involved in the following projects for my PhD thesis:  

 - At operational level AI can provide recommendations to support business process executions. Deep Learning Architectures LIKE LSTMs, MANNs and Transformers provides methods for modeling sequential data problems. In  [DeepProcess:](https://github.com/asjad99/DeepProcess) Project we use Memory Augmented Neural Networks  for Predictive Process Monitoring. see  [[Paper](https://arxiv.org/pdf/1802.00938.pdf)] [[Blog_post](www.asjadk.io/deepprocess/)]

  - At Strategic level AI can help bussiness come up with robust plans. We explore this in the Alpha-GS project: [Alpha-GS](https://github.com/asjad99/rosetta_stone) - Decision making in adversarial settings using Game tree Search Combined With satisfiability(SAT) [[Blog Post](https://www.asjadk.io/strategic_resilience/)] 
