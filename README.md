# Eine Demonstration des LIME-Verfahrens zur Interpretation von ML-Modellen. 
Ribeiro et al. (2016) stellen in Ihrem Papier das sog. Die Abkürzung LIME steht für "local, interpretable, model-agnostic explanation". Im Zusammenhang mit der Interpretation von Black-Box (BB) Machine Learning Modellen bedeutet lokal, dass es darum geht, die Prognose des BB-Modells für ein ausgewähltes Subjekt zu erklären. Erklären bedeutet hier, dass einer Anwender\*in transparent wird, wie die Merkmalsausprägungen des Subjekts die Prognose des BB-Modells beeinflusst haben. Es soll z.B. deutlich werden, wie höhere oder niedrigere Werte eines Merkmals *Einkommen* die Prognose der Zielvariablen beeinflussen. 

LIME untersützt auch andere Arten von Daten, insbesondere Text- und Bilddaten. Der Erstautor des Papiers, Marco Tulio Correia Ribeiro, stellt in seinem [GitHub-Repository](https://github.com/marcotcr/lime/tree/master/lime) and leistungsfähige und flexibel einsatzbare Implementierung des LIME-Verfahrens bereit. Dort finden sich auch viele nützliche Beispiele und Erklärungen. Das Notebook LIME_from_scratch.ipynb demonstriert wesentliche Schritte des LIME-Verfahrens am Beispiel tabellarischer Daten. Es enthält ferner eine vereinfachte Implementierung des Verfahrens, welche für Lehrzwecke geeignet ist.


Referenzen:
- Alvarez-Melis, D., & Jaakkola, T. S. (2018). On the Robustness of Interpretability Methods. ICML Workshop on Human Interpretability in Machine Learning (WHI 2018), Stockholm, Sweden. https://arxiv.org/abs/1806.08049
- Molnar, C. (2019). Interpretable Machine Learning. Victoria, BC, Canada: Leanpub. https://christophm.github.io/interpretable-ml-book/ 
- Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). "Why Should I Trust You?": Explaining the Predictions of Any Classifier. Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (ACM KDD2016), ACM: New York, NY, USA. https://doi.org/10.1145/2939672.2939778

