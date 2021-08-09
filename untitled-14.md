# Untitled

## **MONITORING & ALERTS**

* [**Monitor! Stop being a blind DS**](https://towardsdatascience.com/monitor-stop-being-a-blind-data-scientist-ac915286075f)
* [**Monitor your dependencies! Stop being a blind DS**](https://towardsdatascience.com/monitor-your-dependencies-stop-being-a-blind-data-scientist-a3150bd64594)
* [**Data science observability for executives**](https://towardsdatascience.com/data-science-observability-for-executives-a054411faecc)
* [**Production Machine Learning Monitoring: Outliers, Drift, Explainers & Statistical Performance**](https://towardsdatascience.com/production-machine-learning-monitoring-outliers-drift-explainers-statistical-performance-d9b1d02ac158)**,** [**youtube**](https://www.youtube.com/watch?v=QcevzK9ZuDg)**, uses** [**alibi-explain**](https://docs.google.com/document/d/1dXELAcJn9KCPSRMDvZoumUyHx8K8Yn7wfFxesSpbNCM/edit#heading=h.xs1o8m3ro5iy) **\(see compendium\)  and ali-detect \(see compendium\)**
* [**Mlflow, Hyperparameterhunter,hyperopt, concept drift, unit tests.**](https://towardsdatascience.com/putting-ml-in-production-ii-logging-and-monitoring-algorithms-91f174044e4e)
* [**meta anomaly over multiple models, aggregate.** ](https://www.anodot.com/blog/monitoring-machine-learning/)
* [**Vidhya on monitoring data / models**](https://www.analyticsvidhya.com/blog/2019/10/deployed-machine-learning-model-post-production-monitoring/)

### **Drift**

1. [**Data & concept drifts**](https://deepchecks.com/how-to-monitor-ml-models-in-production/)**,** [**2**](https://www.explorium.ai/blog/understanding-and-handling-data-and-concept-drift/)**,** 
2. **Arize.ai** 
   1. **Data, concept,** [**feature drifts**](https://towardsdatascience.com/using-statistical-distance-metrics-for-machine-learning-observability-4c874cded78) **- various comparison between train/prod/validation time windows, diff models, a/b testing etc and how to measure drifts**
   2. [**Model store, Feature store, evaluation store**](https://towardsdatascience.com/the-only-3-ml-tools-you-need-1aa750778d33)
   3. [**Monitor model performance in prod**](https://towardsdatascience.com/the-playbook-to-monitor-your-models-performance-in-production-ec06c1cc3245) **- real time, biased, delayed and no ground truth.** 
3. [**Some advice on medium**](https://towardsdatascience.com/concept-drift-and-model-decay-in-machine-learning-a98a809ea8d4)**, relabel using latest model \(can we even trust it?\) retrain after.**
4. [**Adversarial Validation Approach to Concept Drift Problem in User Targeting Automation Systems at Uber**](https://arxiv.org/abs/2004.03045)  **- Previous research on concept drift mostly proposed model retraining after observing performance decreases. However, this approach is suboptimal because the system fixes the problem only after suffering from poor performance on new data. Here, we introduce an adversarial validation approach to concept drift problems in user targeting automation systems. With our approach, the system detects concept drift in new data before making inference, trains a model, and produces predictions adapted to the new data.** 
5. **Drift estimator between data sets using random forest, formula is in the medium article above, code here at** [**mlBOX**](https://github.com/AxeldeRomblay/MLBox/blob/811dbcb04fc7f5501e82f3e78aa6c119f426ee78/python-package/mlbox/preprocessing/drift/drift_estimator.py)
6. [**Alibi-detect**](https://docs.google.com/document/d/1dXELAcJn9KCPSRMDvZoumUyHx8K8Yn7wfFxesSpbNCM/edit#heading=h.y6mpsp4co5t9) **- is an open source Python library focused on outlier, adversarial and drift detection.**

![](https://lh4.googleusercontent.com/sASV5qq3CTmv0gx6Tl3DiwACMnwsW9wj1yNHF5sFIFbQr4BFFgAVgfcWsnrHxNnQtQKa-b5-IdbC-OElnQIr117lxaH3TGCuz1CmpgU6mof3i9VkPR3LyzdD9S0ujTmWj7o88Iep)
