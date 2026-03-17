# Nonlinear Control Systems Group

The group is a leading Estonian research unit in automatic control, focusing on learning-enabled and data-driven control of complex energy systems. Its work builds on a strong foundation in nonlinear control theory, including non-smooth, hybrid, and time-delay systems, while increasingly integrating machine learning and optimization methods.

The group develops methodologies for trustworthy control of cyber-physical systems, with emphasis on transparency, robustness, and safety guarantees under uncertainty and incomplete information. Current research focuses on energy systems and the built environment, including intelligent building control, demand-side flexibility, and integration of renewable energy sources, while bridging machine learning and control engineering through explainability-aware learning, supervisory safety mechanisms, and data-centric design approaches.

Through interdisciplinary collaboration, the group contributes to the emerging field of energy informatics, addressing challenges in digitalization, sustainability, and reliable operation of modern energy systems.

---

## Links
- <a href="https://www.linkedin.com/company/nonlinear-control-systems-group" target="_blank"> LinkedIn – Nonlinear Control Systems Group </a>
- <a href="[https://www.linkedin.com/company/nonlinear-control-systems-group](https://taltech.ee/en/department-of-software-science/research-groups#p40025)" target="_blank"> TalTech – Department of Software Science, Research Groups </a>

---

## Projects

### [Detecting Battery Degradation Factors using Explainable AI](https://github.com/nlcontrol/XAI_battery_SoH-Public)
Accurate prediction of battery State-of-Health (SoH) is essential for ensuring safe, reliable, and efficient battery operation. While deep learning models such as Convolutional Neural Networks (CNNs) provide strong predictive performance, their lack of transparency limits trust and real-world adoption.

This project combines CNN-based SoH prediction with explainable artificial intelligence (XAI) techniques. A CNN is used to model temporal dependencies in battery time-series data (current, voltage, temperature), and SHAP is applied post hoc to explain model predictions. In addition to local explanations, a temporally-aware Global SHAP aggregation highlights consistent degradation patterns across the battery lifecycle, enabling transparent identification of key degradation factors.
