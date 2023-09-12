# <img src="https://github.com/fiddler-labs/fiddler-auditor/blob/main/docs/source/images/fiddler-auditor-logo.png?raw=true" width="60%" alt="Fiddler Auditor">

Auditing Large Language Models made easy!

<!-- [![lint](https://github.com/fiddler-labs/fiddler-auditor/actions/workflows/codelint.yml/badge.svg?event=schedule)](https://github.com/fiddler-labs/fiddler-auditor/actions/workflows/codelint.yml)
[![test](https://github.com/fiddler-labs/fiddler-auditor/actions/workflows/test.yml/badge.svg?event=schedule)](https://github.com/fiddler-labs/fiddler-auditor/actions/workflows/test.yml) -->


## What is Fiddler Auditor?

<div align="left">
    <img src="https://github.com/fiddler-labs/fiddler-auditor/blob/main/docs/source/images/monitoring-generative-ai-models_fiddler-auditor.png?raw=true"
         alt="Fiddler Auditor Capabilities"/>
</div>

Language models enable companies to build and launch innovative applications to improve productivity and increase customer satisfaction. 
However, it’s been known that LLMs can hallucinate, generate adversarial responses that can harm users, and even expose private information that they were trained on when prompted or unprompted. It's more critical than ever for ML and software application teams to minimize these risks and weaknesses before launching LLMs and NLP models. As a result, it’s important for you to include a process to audit language models thoroughly before production.
The Fiddler Auditor enables you to test LLMs and NLP models, identify weaknesses in the models, and mitigate potential adversarial outcomes before deploying them to production.

## Features and Capabilities

<p>
<div align="left">
    <img src="https://github.com/fiddler-labs/fiddler-auditor/blob/main/examples/images/fiddler-auditor-flow.png?raw=true"
         alt="Fiddler Auditor Flow"/>
</div>
</p>

Fiddler Auditor supports

- Red-teaming LLMs for your use-case with prompt perturbation
- Integration with LangChain
- Custom evaluation metrics
- Generative and Discriminative NLP models
- Comparison of LLMs

<p>
<div align="left">
    <img src="https://github.com/fiddler-labs/fiddler-auditor/blob/main/docs/source/images/fiddler-auditor-prompt-evaluation.png?raw=true"
         alt="Example Report"/>
    <em> An example report generated by the Fiddler Auditor for text-davinci-003. </em>
</div>
</p>


## Installation

### From PyPI
Auditor is available on PyPI and we test on Python 3.8 and above. We recommend creating a virtual python environment and installing using the following command

```bash
pip install fiddler-auditor
```

### From source
You can install from source after cloning this repo using the following command

```bash
pip install .
```

## Quick-start guides
- [Evaluate LLM Correctness and Robustness](https://github.com/fiddler-labs/fiddler-auditor/blob/main/examples/LLM_Evaluation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fiddler-labs/fiddler-auditor/blob/main/examples/LLM_Evaluation.ipynb)
- [Evaluate LLMs with custom metrics](https://github.com/fiddler-labs/fiddler-auditor/blob/main/examples/Custom_Evaluation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fiddler-labs/fiddler-auditor/blob/main/examples/Custom_Evaluation.ipynb)
- [Prompt injection attack with custom transformation](https://github.com/fiddler-labs/fiddler-auditor/blob/main/examples/Custom_Transformation.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fiddler-labs/fiddler-auditor/blob/main/examples/Custom_Transformation.ipynb)


## Contribution
We are continuously updating this library to support language models as they evolve. 

- Contributions in the form of suggestions and PRs to Fiddler Auditor are welcome!
- If you encounter a bug, please feel free to raise issues in this repository.

## Community
- For questions and support, join the [Fiddler Community](https://www.fiddler.ai/slackinvite)
- Discover the latest guides, videos, and research with the [Fiddler Resources Library](https://www.fiddler.ai/resources)
- Stay informed by following us on [Twitter](https://twitter.com/fiddlerlabs)
- Subscribe to our [monthly newsletter](https://www.fiddler.ai/blog#subscribe)
- [Try Fiddler for free](https://www.fiddler.ai/trial)
