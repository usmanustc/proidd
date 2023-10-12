# proidd
Code for the paper: Pro-IDD : Pareto-based ensemble for imbalanced and drifting data streams

# Brief:
ProIDD is an ensemble based method capable to tackle both concept drifts and class imbalance in data streams. Min++ proposed in ProIDD handles the class imbalance at an advanced level using oversampling and undersampling techniques which are targetted at cluster-level and boundary area respectively. Furthermore, the ensemble management under ProIDD is capable to address both core issues i.e. the class imbalance and concept drifts. It prunes the ensemble using a time-decayed recall-based weight criterian and ensemble diversity through Pareto-based optimization, providing high generalization performance. 

# Paper Abstract:
Concept drifts and class imbalance are two primary challenges in supervised data stream classification, whereas their  co-occurrence presents a more complicated learning problem. To tackle these challenges, this paper proposes Pro-IDD, a Pareto-based ensemble for imbalanced and drifting data streams. As part of Pro-IDD, Min++ module resolves the class imbalance issue by improving the minority class visibility such that class overlaps are reduced and small disjuncts in minority space are enlarged. Additionally, the ProEns module is designed to construct the ensemble pool by taking concept drifts and class imbalance into account. ProEns prunes the ensemble pool by using Pareto-based multi-objective learning for two measures: time-decayed recall-based weight and ensemble diversity. Experiments are conducted on 12 data streams with concept drifts and class imbalance and comparisons are reported against 10 state-of-the-art methods. Results show that improving the minority class visibility and using time-decayed recall-based weight and diversity for ensemble selection through Pareto-based multi-objective learning could improve the classification performance of data streams learners in the presence of concept drifts and class imbalance.

__Authors:__ Muhammad Usman, Huanhuan Chen

__For any queries:__ muhammadusman@mail.ustc.edu.cn
