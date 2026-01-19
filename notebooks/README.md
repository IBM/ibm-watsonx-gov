# Sample notebooks for using IBM watsonx.governance

The sample notebooks showcase the features of IBM watsonx.governance.

## Agentic Evaluation

| Notebook                                                                                                                                                                | Description                                                                                                                                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Basic Evaluation of LangGraph Agent](python_sdk/agentic/Basic%20Evaluation%20of%20LangGraph%20Agent.ipynb)                                                             | This notebook demonstrates how to use the Agentic AI evaluators from IBM watsonx.governance for governing your applications right in your development environment.                                                              |
| [Advanced Evaluation of LangGraph Agent](python_sdk/agentic/Advanced%20Evaluation%20of%20LangGraph%20Agent.ipynb)                                                       | This notebook demonstrates advanced evaluation capabilities of IBM watsonx.governance for monitoring and governing production-grade LangGraph agentic systems.                                                                  |
| [Evaluation of Tool Calls in LangGraph Agent](python_sdk/agentic/Evaluation%20of%20Tool%20Calls%20in%20LangGraph%20Agent.ipynb)                                         | This notebook demonstrates how to use the Tool call metrics evaluator from IBM watsonx.governance for governing your applications right in your development environment.                                                        |
| [LangGraph agent using governed catalog and experiment tracking](python_sdk/agentic/LangGraph%20agent%20using%20governed%20catalog%20and%20experiment%20tracking.ipynb) | This notebook demonstrates how to build LangGraph agents using tools from the Governed Catalog, evaluate them using IBM watsonx.governance, track and compare experiments, and register agents in the Governed Agentic Catalog. |
| [Advanced Evaluation of LangGraph Agent with Watsonx model](python_sdk/agentic/Advanced%20Evaluation%20of%20LangGraph%20Agent%20with%20Watsonx%20model.ipynb)                                                       | This notebook demonstrates advanced evaluation capabilities of IBM watsonx.governance for monitoring and governing production-grade LangGraph agentic systems with Watsonx model. 

## Guardrails

| Notebook                                                                                                                       | Description                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Invoking Guardrails with the IBM watsonx.governance Python SDK](python_sdk/guardrails/Real%20Time%20Detections.ipynb)         | This notebook demonstrates how to use the IBM watsonx.governance Python SDK to invoke AI guardrails on user inputs and model-generated responses.               |
| [Invoking Guardrails with the IBM watsonx.governance REST API](rest_api/guardrails/Real%20Time%20Detections%20via%20API.ipynb) | This notebook demonstrates how to use the IBM watsonx.governance Real time detections API to invoke AI guardrails on user inputs and model-generated responses. |
| [Invoking Custom Guardrails with the IBM watsonx.governance REST API](rest_api/guardrails/IBM%20Watsonx.Governance%20Guardrails%20Setup%20and%20Invocation.ipynb) | This notebook demonstrates how to create and manage Custom Guardrails using the IBM watsonx.governance using Guardrails Manager API. |

## Metrics evaluation

| Notebook                                                                                 | Description                                                                                                                                                                                                                                                     |
| ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Evaluate Metrics](python_sdk/evaluate_metrics/Evaluate%20Metrics.ipynb)                 | This notebook evaluates metrics using IBM watsonx.governance SDK. RAG metrics evaluation is shown by taking in the data containing contexts, question, answer and ground truth(Optional) information. The metrics result is visualized using the ModelInsights. |
| [Evaluate Custom Metrics](python_sdk/evaluate_metrics/Evaluate%20Custom%20Metrics.ipynb) | This notebook showcase the evaluation of the custom metrics using IBM watsonx.governance SDK. The custom metrics are created by using LLM As Judge and code. The metrics result is visualized using the ModelInsights.                                          |

## Model Risk Evaluation Engine

| Notebook                                                                                                  | Description                                                                                                                                                                                                                                                                                                  |
| --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Model Risk Evaluation Engine](python_sdk/model_risk_evaluation/Model%20Risk%20Evaluation%20Engine.ipynb) | The notebook evaluates the risk associated with a given foundation model using IBM watsonx.governance. The foundation model to evaluate can be either in IBM watsonx.ai or in an external model provider. The risk evaluation result can be stored in Governance Console or can be downloaded as a pdf file. |

## Model Insights

| Notebook                                                           | Description                                                                                                                                       |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Model Insights](python_sdk/model_insights/Model%20Insights.ipynb) | This notebook uses `ModelInsights` to interactively visualize the violated records based on the metrics threshold using venn diagrams and tables. |

## Prompt Evaluation

| Notebook                                                                                                                       | Description                                                                |
| ------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| [End to End Prompt Template Evaluation](python_sdk/prompt_evaluator/rag/End%20to%20End%20Prompt%20Template%20Evaluation.ipynb) | This notebook uses `PromptEvaluator` to evaluate detached prompt template. |
