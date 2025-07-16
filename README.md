# ☁️ Generative AI with Cloud (AWS SageMaker + Lambda + Bedrock)

This repository demonstrates **end-to-end Generative AI applications deployed on AWS**, including usage of **HuggingFace open-source LLMs with SageMaker endpoints** and **Blog generation using AWS Lambda and Bedrock**.

---

## 📁 Project Structure

```
Generative-AI-with-cloud/
├── AWS sagemaker/
│   ├── falcon40B-instruct-notebook-full.ipynb
│   ├── test.py
│   └── Untitled (2).ipynb
├── Blog generation in aws/
│   ├── app.py
│   └── requirements.txt
├── LICENSE
└── README.md
```

---

## 🚀 Included Projects

### 📌 1. Blog Generation using AWS Lambda + Bedrock
- **Directory**: `Blog generation in aws/`
- **Overview**: This app allows users to generate high-quality blog posts using GenAI capabilities of Amazon Bedrock models, triggered through AWS Lambda.
- **Tech Stack**: `Bedrock`, `Lambda`, `API Gateway`, `Langchain`, `Streamlit`
- **Deployment**: Ideal for serverless, low-cost GenAI applications.

---

### 📌 2. Deploying HuggingFace Open-Source LLMs on AWS SageMaker
- **Directory**: `AWS sagemaker/`
- **Model**: `falcon40B-instruct`
- **Overview**:
  - Demonstrates fine-tuning and inference using HuggingFace-hosted models.
  - Leverages **SageMaker endpoints** for efficient real-time LLM serving.
- **Use Case**: Scalable inference and experimentation with large open-source models on managed infrastructure.

---

## 🧰 Technologies Used

- **LLMs**: Falcon-40B, Amazon Bedrock Foundation Models
- **Cloud Services**: SageMaker, Lambda, Bedrock, IAM, API Gateway
- **Frameworks**: LangChain, Streamlit
- **Languages**: Python, Jupyter Notebooks

---

## ▶️ Quick Start

### 🔧 Install Requirements (for local testing)

```bash
pip install -r requirements.txt
```

### ▶️ Run Blog Generator Locally

```bash
cd "Blog generation in aws"
streamlit run app.py
```

> Note: For production, this app is deployable via AWS Lambda and exposed via API Gateway.

---

### 💻 Run SageMaker Model Notebook

1. Open `falcon40B-instruct-notebook-full.ipynb` in your **SageMaker Studio or Notebook Instance**
2. Ensure your IAM Role has access to SageMaker and required S3 buckets
3. Deploy the HuggingFace model endpoint and test it using `test.py`

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Aparna K**  
🔗 [LinkedIn](https://www.linkedin.com/in/aparna-k-628005167/)  
💻 [GitHub](https://github.com/Aparna-k246)

---

## 🔗 Explore More GenAI Projects

- [Langchain-based Projects](https://github.com/Aparna-k246/GENAI-Projects-Langchain)
- [Gemini Pro End-to-End Apps](https://github.com/Aparna-k246/Gen-AI_Google-Gemini)
- [LLM Fine-tuning](https://github.com/Aparna-k246/Finetuning_LLM)
