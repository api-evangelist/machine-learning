# Machine Learning (machine-learning)
An index and topic collection covering machine learning APIs, MLOps platforms, model serving infrastructure, and inference providers. Machine learning APIs span the full ML lifecycle — from data labeling, experiment tracking, and model training to model registries, hosted inference, and vector search. This collection brings together hyperscaler ML platforms (Amazon SageMaker, Google Vertex AI, Azure Machine Learning), open-source MLOps frameworks (MLflow, Kubeflow, ZenML, DVC), GPU inference providers (Together AI, Fireworks AI, Replicate, Groq, Modal, Baseten), vector databases (Pinecone, Weaviate, Milvus, Qdrant, Chroma), and model hubs (Hugging Face) that together power production machine learning at scale.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Machine Learning, MLOps, Model Serving, Inference, AutoML, Embeddings, Vector Database, Foundation Models

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Model Schema](https://raw.githubusercontent.com/api-evangelist/machine-learning/refs/heads/main/json-schema/machine-learning-model-schema.json)
- [JSONSchema - Inference Request Schema](https://raw.githubusercontent.com/api-evangelist/machine-learning/refs/heads/main/json-schema/machine-learning-inference-request-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/machine-learning/refs/heads/main/json-ld/machine-learning-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/machine-learning/refs/heads/main/vocabulary/machine-learning-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Hosted Model Inference | ML APIs from providers like Hugging Face, Replicate, Together AI, Fireworks AI, and Groq expose pre-trained and fine-tuned models behind HTTP endpoints so developers can call inference without managing GPUs. |
| Model Training and Fine-Tuning | Platforms like Amazon SageMaker, Google Vertex AI, Azure Machine Learning, and OpenPipe expose APIs for launching training jobs, configuring hyperparameters, and fine-tuning foundation models on custom data. |
| Experiment Tracking and Model Registry | MLflow, Weights & Biases, Comet, Neptune.ai, and ClearML provide APIs to log experiments, track metrics, compare runs, and register approved model versions for downstream deployment. |
| Vector Search and Embeddings | Vector databases like Pinecone, Weaviate, Milvus, Qdrant, and Chroma expose APIs to index embeddings and run nearest-neighbor search powering retrieval-augmented generation and semantic search. |
| Model Serving and Deployment | Serving frameworks like KServe, vLLM, Ray Serve, Baseten, and TrueFoundry provide APIs to deploy models as scalable HTTP or gRPC endpoints with autoscaling, batching, and routing. |
| ML Pipeline Orchestration | Kubeflow Pipelines, ZenML, and DVC expose APIs to define, version, and execute ML pipelines spanning data preparation, training, evaluation, and deployment stages. |
| Data Labeling and Annotation | Label Studio and similar platforms expose APIs for managing labeling projects, importing data, assigning tasks to annotators, and exporting labeled datasets for model training. |
| LLM Gateway and Routing | LiteLLM, Portkey, and similar gateways provide unified APIs that route requests across multiple LLM providers with fallback, caching, rate limiting, and observability. |

## Use Cases

| Name | Description |
|------|-------------|
| Retrieval-Augmented Generation | Combining a vector database with an embeddings API and an LLM inference endpoint to ground model responses in private knowledge bases. |
| Fine-Tuning Foundation Models | Using SageMaker, Vertex AI, OpenPipe, or Together AI APIs to fine-tune open foundation models on proprietary datasets and deploy behind a managed inference endpoint. |
| Scalable Model Inference at the Edge | Deploying optimized models through Groq, Modal, Replicate, or Baseten to serve high-throughput, low-latency inference for chatbots and recommendation systems. |
| End-to-End MLOps Automation | Using Kubeflow, MLflow, Weights & Biases, and ZenML to track experiments, register approved models, trigger retraining, and promote models to production via API. |
| Multimodal Application Development | Composing image, audio, video, and text models from Hugging Face, Replicate, and Fireworks AI through standard inference APIs to build multimodal user experiences. |
| Semantic Search and Recommendations | Indexing product catalogs, documents, or media in vector databases like Milvus or Vespa and exposing semantic search APIs to power discovery and personalization. |
| Model Observability and Cost Control | Using gateways like Portkey and LiteLLM alongside observability platforms to monitor inference latency, cost-per-request, and routing across model providers. |
| Distributed Training at Scale | Running large-scale distributed training jobs on Ray, Anyscale, Determined AI, or Databricks via API, including hyperparameter tuning and GPU cluster orchestration. |

## Integrations

| Name | Description |
|------|-------------|
| Hugging Face | Model hub and inference API hosting hundreds of thousands of open-source transformer models, datasets, and Spaces with managed Inference Endpoints. |
| Amazon SageMaker | End-to-end ML platform on AWS for building, training, deploying, and monitoring models, including SageMaker Studio, JumpStart, and managed endpoints. |
| Google Vertex AI | Unified ML platform on Google Cloud covering AutoML, custom training, Model Registry, Pipelines, and Generative AI Studio. |
| MLflow | Open-source platform for ML lifecycle management with APIs for experiment tracking, model registry, and deployment across many backends. |
| Weights & Biases | Experiment tracking, evaluations, model registry, and LLM observability platform with rich APIs for logging metrics and managing models. |
| Replicate | API platform for running open-source models in the cloud with per-second pricing and one-line deployment of custom Cog containers. |
| Together AI | Inference and fine-tuning platform for open foundation models, exposing OpenAI-compatible APIs for chat, completion, and embeddings. |
| Pinecone | Managed vector database for high-scale similarity search, hybrid search, and metadata filtering powering production RAG applications. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Model Schema](json-schema/machine-learning-model-schema.json)
- [Inference Request Schema](json-schema/machine-learning-inference-request-schema.json)

### JSON Structure

- [Model Structure](json-structure/machine-learning-model-structure.json)
- [Inference Request Structure](json-structure/machine-learning-inference-request-structure.json)

### JSON-LD

- [Machine Learning Context](json-ld/machine-learning-context.jsonld)

## Vocabulary

- [Machine Learning Vocabulary](vocabulary/machine-learning-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across model training, serving, registries, and vector search.

## Network

This index references the following machine learning, MLOps, model serving, and vector search repositories:

- [Amazon SageMaker](https://github.com/api-evangelist/amazon-sagemaker)
- [Anyscale](https://github.com/api-evangelist/anyscale)
- [Azure Databricks](https://github.com/api-evangelist/azure-databricks)
- [Azure Machine Learning](https://github.com/api-evangelist/microsoft-azure-machine-learning)
- [Baseten](https://github.com/api-evangelist/baseten)
- [Chroma](https://github.com/api-evangelist/chroma)
- [ClearML](https://github.com/api-evangelist/clearml)
- [Comet](https://github.com/api-evangelist/comet-ml)
- [DagsHub](https://github.com/api-evangelist/dagshub)
- [Databricks](https://github.com/api-evangelist/databricks)
- [Dataiku](https://github.com/api-evangelist/dataiku)
- [DeepInfra](https://github.com/api-evangelist/deepinfra)
- [Determined AI](https://github.com/api-evangelist/determined-ai)
- [DVC](https://github.com/api-evangelist/dvc)
- [Fireworks AI](https://github.com/api-evangelist/fireworks-ai)
- [Google Vertex AI](https://github.com/api-evangelist/google-vertex-ai)
- [Groq](https://github.com/api-evangelist/groq)
- [Hugging Face](https://github.com/api-evangelist/hugging-face)
- [Hyperbolic](https://github.com/api-evangelist/hyperbolic)
- [Jina AI](https://github.com/api-evangelist/jina-ai)
- [KServe](https://github.com/api-evangelist/kserve)
- [Kubeflow](https://github.com/api-evangelist/kubeflow)
- [Label Studio](https://github.com/api-evangelist/label-studio)
- [Lepton AI](https://github.com/api-evangelist/lepton-ai)
- [LiteLLM](https://github.com/api-evangelist/litellm)
- [Marqo](https://github.com/api-evangelist/marqo)
- [Microsoft Azure AI Foundry](https://github.com/api-evangelist/azure-ai-foundry)
- [Milvus](https://github.com/api-evangelist/milvus)
- [MLflow](https://github.com/api-evangelist/mlflow)
- [Modal](https://github.com/api-evangelist/modal)
- [Neptune.ai](https://github.com/api-evangelist/neptune-ai)
- [Novita AI](https://github.com/api-evangelist/novita-ai)
- [OpenPipe](https://github.com/api-evangelist/openpipe)
- [Pinecone](https://github.com/api-evangelist/pinecone)
- [Portkey](https://github.com/api-evangelist/portkey)
- [Qdrant](https://github.com/api-evangelist/qdrant)
- [Ray](https://github.com/api-evangelist/ray)
- [Replicate](https://github.com/api-evangelist/replicate)
- [SiliconFlow](https://github.com/api-evangelist/siliconflow)
- [Together AI](https://github.com/api-evangelist/together-ai)
- [TrueFoundry](https://github.com/api-evangelist/truefoundry)
- [Typesense](https://github.com/api-evangelist/typesense)
- [Vespa](https://github.com/api-evangelist/vespa)
- [vLLM](https://github.com/api-evangelist/vllm)
- [Weaviate](https://github.com/api-evangelist/weaviate)
- [Weights & Biases](https://github.com/api-evangelist/weights-and-biases)
- [ZenML](https://github.com/api-evangelist/zenml)
- [Zilliz](https://github.com/api-evangelist/zilliz)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
