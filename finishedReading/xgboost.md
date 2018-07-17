- There are two important factors that drive these successful applications: usage of effective (statistical) models that capture the complex data dependencies and scalable learning systems that learn the model of interest from large datasets.
- 推动机器学习成功应用的因素有两个：使用捕获复杂数据依赖关系的有效（统计）模型和可从大型数据集中学习兴趣的模型的可扩展学习系统。

- The most important factor behind the success of XGBoost is its scalability in all scenarios.
- XGBoost成功背后最重要的因素是它在所有场景中的可扩展性。

- The scalability of XGBoost is due to several important systems and algorithmic optimizations. These innovations include: a novel tree learning algorithm is for handling sparse data; a theoretically justified weighted quantile sketch procedure enables handling instance weights in approximate tree learning. 
Parallel and distributed computing makes learning faster which enables quicker model exploration. 
More importantly, XGBoost exploits out-of-core computation and enables data scientists to process hundred millions of examples on a desktop. 
Finally, it is even more exciting to combine these techniques to make an end-to-end system that scales to even larger data with the least amount of cluster resources. 
- XGBoost的可扩展性归功于几个重要的系统和算法优化。这些创新包括：一种新颖的树学习算法用于处理稀疏数据;理论上合理的加权分位数草图过程使得能够在近似树学习中处理实例权重。
并行和分布式计算使学习更快，从而实现更快的模型探索。
更重要的是，XGBoost利用核外计算，使数据科学家能够在桌面上处理数亿个示例。
最后，结合这些技术使端到端系统以最少的集群资源扩展到更大的数据更令人兴奋。

-  We design and build a highly scalable end-to-end tree boosting system.
• We introduce a novel sparsity-aware algorithm for parallel tree learning.
• We propose a theoretically justified weighted quantile sketch for efficient proposal calculation.
• We propose an effective cache-aware block structure for out-of-core tree learning.
-  我们设计并构建了一个高度可扩展的端到端树提升系统。
•我们为并行树学习引入了一种新颖的稀疏感知算法。
•我们提出了一个理论上合理的加权分位数草图，用于有效的提案计算。
•我们提出了一种有效的缓存感知块结构，用于核外树学习。
