# Sample notebooks for using IBM watsonx.governance

The sample notebooks showcase the features of IBM watsonx.governance.

# Notebooks

| Notebook | Description |
| -------- | ----------- |
| [Evaluate Metrics](python_sdk/evaluate_metrics/rag/Evaluate%20Metrics.ipynb) |This notebook evaluates RAG metrics using IBM watsonx.governance SDK. It can evaluate RAG metrics by taking in the data containing contexts, question, answer and ground truth(Optional) information. The metrics result can be visualized using the ModelInsights.|
| [Model Insights](python_sdk/model_insights/Model%20Insights.ipynb) | This notebook uses `ModelInsights` to interactively visualize the violated records based on the metrics threshold using venn diagrams and tables.|
| [Model Risk Evaluation Engine](python_sdk/model_risk_evaluation/Model%20Risk%20Evaluation%20Engine.ipynb)| The notebook evaluates the risk associated with a given foundation model using IBM watsonx.governance. The foundation model to evaluate can be either in IBM watsonx.ai or in an external model provider. The risk evaluation result can be stored in Governance Console or can be downloaded as a pdf file.  |
| [Governing Langgraph application using evaluator nodes](python_sdk/agentic/IBM%20watsonx%20governance%20evaluation%20with%20LangGraph.ipynb)| This notebook demonstrates how to use the Agentic AI evaluators from IBM watsonx.governance for governing your applications right in your development environment.  |
