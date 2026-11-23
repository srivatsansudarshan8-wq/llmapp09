# llmapp09 - CI/CD Submission

- LLM Multiroute CI and LLM Frontend Python CI: unit tests, Docker build, Trivy scan and push to Docker Hub (srivatsansg) - passing.
- PromptFoo Tests and DeepEval Tests: pipelines configured, but runs fail with HTTP 402 (Payment Required) because my personal Ollama API key does not have access to the cloud models used (e.g. glm-5.2). They will pass once the course OLLAMA_API_KEY is set as a repository secret.
