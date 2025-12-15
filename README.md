# Prompt Engineering Guide

## Guides
You can also find the most up-to-date guides on our new website [./pages/](./pages/).

- [Prompt Engineering - Introduction](./pages/introduction)
  - [Prompt Engineering - LLM Settings](./pages/introduction/settings)
  - [Prompt Engineering - Basics of Prompting](./pages/introduction/basics)
  - [Prompt Engineering - Prompt Elements](./pages/introduction/elements)
  - [Prompt Engineering - General Tips for Designing Prompts](./pages/introduction/tips)
  - [Prompt Engineering - Examples of Prompts](./pages/introduction/examples)
- [Prompt Engineering - Techniques](./pages/techniques)
  - [Prompt Engineering - Zero-Shot Prompting](./pages/techniques/zeroshot)
  - [Prompt Engineering - Few-Shot Prompting](./pages/techniques/fewshot)
  - [Prompt Engineering - Chain-of-Thought Prompting](./pages/techniques/cot)
  - [Prompt Engineering - Self-Consistency](./pages/techniques/consistency)
  - [Prompt Engineering - Generate Knowledge Prompting](./pages/techniques/knowledge)
  - [Prompt Engineering - Prompt Chaining](./pages/techniques/prompt_chaining)
  - [Prompt Engineering - Tree of Thoughts (ToT)](./pages/techniques/tot)
  - [Prompt Engineering - Retrieval Augmented Generation](./pages/techniques/rag)
  - [Prompt Engineering - Automatic Reasoning and Tool-use (ART)](./pages/techniques/art)
  - [Prompt Engineering - Automatic Prompt Engineer](./pages/techniques/ape)
  - [Prompt Engineering - Active-Prompt](./pages/techniques/activeprompt)
  - [Prompt Engineering - Directional Stimulus Prompting](./pages/techniques/dsp)
  - [Prompt Engineering - Program-Aided Language Models](./pages/techniques/pal)
  - [Prompt Engineering - ReAct Prompting](./pages/techniques/react)
  - [Prompt Engineering - Multimodal CoT Prompting](./pages/techniques/multimodalcot)
  - [Prompt Engineering - Graph Prompting](./pages/techniques/graph)
- [Prompt Engineering - Applications](./pages/applications)
  - [Prompt Engineering - Function Calling](./pages/applications/function_calling)
  - [Prompt Engineering - Generating Data](./pages/applications/generating)
  - [Prompt Engineering - Generating Synthetic Dataset for RAG](./pages/applications/synthetic_rag)
  - [Prompt Engineering - Takling Generated Datasets Diversity](./pages/applications/generating_textbooks)
  - [Prompt Engineering - Generating Code](./pages/applications/coding)
  - [Prompt Engineering - Graduate Job Classification Case Study](./pages/applications/workplace_casestudy)
- [Prompt Engineering - Prompt Hub](./pages/prompts)
  - [Prompt Engineering - Classification](./pages/prompts/classification)
  - [Prompt Engineering - Coding](./pages/prompts/coding)
  - [Prompt Engineering - Creativity](./pages/prompts/creativity)
  - [Prompt Engineering - Evaluation](./pages/prompts/evaluation)
  - [Prompt Engineering - Information Extraction](./pages/prompts/information-extraction)
  - [Prompt Engineering - Image Generation](./pages/prompts/image-generation)
  - [Prompt Engineering - Mathematics](./pages/prompts/mathematics)
  - [Prompt Engineering - Question Answering](./pages/prompts/question-answering)
  - [Prompt Engineering - Reasoning](./pages/prompts/reasoning)
  - [Prompt Engineering - Text Summarization](./pages/prompts/text-summarization)
  - [Prompt Engineering - Truthfulness](./pages/prompts/truthfulness)
  - [Prompt Engineering - Adversarial Prompting](./pages/prompts/adversarial-prompting)
- [Prompt Engineering - Models](./pages/models)
  - [Prompt Engineering - ChatGPT](./pages/models/chatgpt)
  - [Prompt Engineering - Code Llama](./pages/models/code-llama)
  - [Prompt Engineering - Flan](./pages/models/flan)
  - [Prompt Engineering - Gemini](./pages/models/gemini)
  - [Prompt Engineering - GPT-4](./pages/models/gpt-4)
  - [Prompt Engineering - LLaMA](./pages/models/llama)
  - [Prompt Engineering - Mistral 7B](./pages/models/mistral-7b)
  - [Prompt Engineering - Mixtral](./pages/models/mixtral)
  - [Prompt Engineering - OLMo](./pages/models/olmo)
  - [Prompt Engineering - Phi-2](./pages/models/phi-2)
  - [Prompt Engineering - Model Collection](./pages/models/collection)
- [Prompt Engineering - Risks and Misuses](./pages/risks)
  - [Prompt Engineering - Adversarial Prompting](./pages/risks/adversarial)
  - [Prompt Engineering - Factuality](./pages/risks/factuality)
  - [Prompt Engineering - Biases](./pages/risks/biases)
- [Prompt Engineering - Papers](./pages/papers)
  - [Prompt Engineering - Overviews](./pages/papers#overviews)
  - [Prompt Engineering - Approaches](./pages/papers#approaches)
  - [Prompt Engineering - Applications](./pages/papers#applications)
  - [Prompt Engineering - Collections](./pages/papers#collections)
- [Prompt Engineering - Tools](./pages/tools)
- [Prompt Engineering - Notebooks](./pages/notebooks)
- [Prompt Engineering - Datasets](./pages/datasets)
- [Prompt Engineering - Additional Readings](./pages/readings)


---
## Lecture

We have published a 1 hour lecture that provides a comprehensive overview of prompting techniques, applications, and tools.
- [Video Lecture](https://youtu.be/dOxUroR57xs)
- [Notebook with code](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/notebooks/pe-lecture.ipynb)
- [Slides](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/lecture/Prompt-Engineering-Lecture-Elvis.pdf)

---
## Running the guide locally

To run the guide locally, for example to check the correct implementation of a new translation, you will need to:

1. Install Node >=18.0.0
1. Install `pnpm` if not present in your system. Check [here](https://pnpm.io/installation) for detailed instructions.
1. Install the dependencies: `pnpm i next react react-dom nextra nextra-theme-docs`
1. Boot the guide with `pnpm dev`
2. Browse the guide at `http://localhost:3000/`

