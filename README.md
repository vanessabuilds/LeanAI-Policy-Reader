[![Lean AI - How to Reduce LLM Cost?](https://tse2.mm.bing.net/th?id=OIP.b06BeWiB_WACItOYKL7f-AHaFL\&pid=Api)](https://bennycheung.github.io/lean-ai-reduce-llm-cost)

Certainly! Here's a comprehensive `README.md` tailored for your GitHub project, integrating references to Replicate and IBM's Granite 3.3-8B model:

---

# LeanAI Policy Reader

**A lightweight, cost-effective AI tool for analyzing and summarizing policy documents using IBM's Granite 3.3-8B model.**

## Overview

The LeanAI Policy Reader is designed to efficiently process and interpret policy documents, providing concise summaries and analyses. By leveraging IBM's Granite 3.3-8B model, the tool ensures high-quality outputs while maintaining resource efficiency.

## Features

* **Policy Document Analysis**: Input policy documents in various formats (e.g., PDF, DOCX, TXT) and receive structured summaries.
* **Granite 3.3-8B Integration**: Utilizes IBM's advanced language model for accurate and context-aware interpretations.
* **Cost-Efficient Processing**: Optimized for minimal computational resources without compromising performance.
* **User-Friendly Interface**: Interactive Jupyter Notebook for seamless user interaction and customization.

## Getting Started

### Prerequisites

* Python 3.8 or higher
* Jupyter Notebook
* Required Python packages (see `requirements.txt`)

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/vanessabuilds/LeanAI-Policy-Reader.git
   cd LeanAI-Policy-Reader
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

   Open `LeanAI_Policy_Reader.ipynb` in your browser.

## Usage

1. **Load a Policy Document**: Upload your policy document into the notebook environment.

2. **Run Analysis**: Execute the notebook cells to process the document. The tool will utilize the Granite 3.3-8B model to generate summaries and insights.

3. **Review Outputs**: Examine the generated summaries, key points, and any additional analyses provided.

## Model Details

* **Model**: [IBM Granite 3.3-8B](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct)
* **Architecture**: 8 billion parameters, 128K context length
* **Capabilities**:

  * Enhanced reasoning and instruction-following
  * Support for long-context tasks
  * Multilingual understanding
* **License**: Apache 2.0

For more information, refer to the [IBM Granite Documentation](https://www.ibm.com/granite/docs/).

## Replicate Integration

To deploy the model using Replicate:

1. **Install Replicate CLI**:

   ```bash
   pip install replicate
   ```

2. **Authenticate**:

   ```bash
   replicate login
   ```

3. **Run the Model**:

   ```bash
   replicate run ibm-granite/granite-3.3-8b-instruct --input "Your policy text here."
   ```

For detailed instructions, visit the [Replicate Documentation](https://replicate.com/docs).


## Acknowledgments

* [IBM Research](https://www.ibm.com/research) for developing the Granite 3.3-8B model.
* [Replicate](https://replicate.com/) for providing an accessible platform to deploy machine learning models.
