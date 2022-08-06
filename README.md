Interpretability: Peeking inside the Black Box using ICE and PD plots

<p align="justify">In machine learning, there are two ways of extracting inferences from data. The first technique is data modeling, which assumes that the data is created by a certain stochastic data model. Common models include linear and logistic regression. These models forecast future input variable responses and give information on how the response variables and input variables are related. (In other words, they can be interpreted.) Second, algorithmic modeling models are based on the assumption that the underlying data process is unknown. The objective is to create an algorithm, such as random forests or neural networks, that predicts the response variables based on the input variables. These algorithms predict future input variable responses but do not give information on how the response variables and input variables are connected. To put it another way, these algorithms produce black box models since they do not give a concrete explanation for their predictions. (In other words, they cannot be interpreted.)</p>

<p align="justify">Because they can model complex data relationships, algorithms such as gradient boosting, random forest, and neural nets outperform classical models in terms of prediction accuracy for complex prediction tasks. These machine learning algorithms just make predictions and do not give any explanations. As a consequence, they simply address the "what" of a query but not the "why," and so do not allow for genuine scientific results[1]. The capacity to interpret scientific findings is essential, especially in disciplines such as biological and social sciences, which aim to uncover causal connections between input and response variables.</p>

<p align="justify">This notebook introduces current post-hoc and model agnostic approaches such as Partial Dependence Plots (PDP) and Individual Conditional Expectation (ICE). These methods can be used to explain the behavior and predictions of trained machine learning models. However, their reliability and compactness deteriorate when models use a high number of features, have strong feature interactions and complex feature main effects among others.</p>

<b>Highlights</b>
<ol>
	<li>It is possible to interpret the behavior of complex machine learning models using PD and ICE plots.</li>
	<li>PD plots can show if the relationship between target and feature is linear, monotonic, or complex.</li>
	<li>These plots can be quite effective at sharing insights to colleagues or non-technical people.</li>
</ol>

Open <a href="https://github.com/jazeljayme/Interpretable-ML-model-using-ICE-and-PD-Plots/blob/master/Technical_paper_ICE-PD-plots.ipynb">Technical_paper_ICE-PD-plots.ipynb</a> to view the full report.
