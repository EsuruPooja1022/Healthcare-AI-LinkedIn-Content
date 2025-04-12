# Pulse: AI-Powered Perspective-Driven Content Generation

## Project Overview

**Pulse** is an AI-powered system designed to assist healthcare executives in maintaining a strong LinkedIn presence. The system generates content that reflects the client's expertise in healthcare AI, while adhering to their philosophy: **"AI should enable healthcare professionals, not replace them."**

### Key Features:
- **AI-driven content generation**: Utilizes HuggingFace GPT-2 for generating LinkedIn posts based on article summaries and perspective-driven prompts.
- **Perspective Alignment**: Custom prompts ensure content reflects the client's healthcare perspectives on AI in healthcare.
- **Confidence Scoring**: A confidence score evaluates how well the generated post aligns with predefined perspectives.
- **Ethical Considerations**: Posts emphasize the ethical use of AI, ensuring that AI amplifies human expertise rather than replacing it.

## How It Works

1. **Input**: An article summary or URL is provided.
2. **Perspective Alignment**: The system applies client-specific perspective statements, such as "AI should enable healthcare professionals, not replace them."
3. **Content Generation**: HuggingFace GPT-2 generates a LinkedIn post based on the input and perspectives.
4. **Confidence Score**: The system assigns a confidence score based on keyword matching to indicate alignment with the client's philosophy.
5. **Output**: The generated LinkedIn post is ready for posting, with a high confidence level ensuring it reflects the intended tone and perspective.

### Example Outputs:
1. **Healthcare Workflow Optimization**:
   - Generated post highlights AI tools transforming workflows by reducing physician burnout and allowing more patient-facing time.
   - **Confidence Score**: 100%

2. **Ethical AI in Clinical Decision Making**:
   - Focuses on the importance of ethical AI frameworks in clinical decision-making, ensuring transparency and trust.
   - **Confidence Score**: 100%

3. **Physician Burnout Reduction**:
   - Discusses how AI reduces physician burnout by automating administrative tasks, emphasizing AI's role in supporting healthcare professionals.
   - **Confidence Score**: 100%

## Requirements

- **Python 3.x**
- **HuggingFace GPT-2** for text generation
- **Google Colab** for easy cloud-based execution
- **Jupyter Notebook** for running the code

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/EsuruPooja1022/Healthcare-AI-LinkedIn-Content.git
   cd Healthcare-AI-LinkedIn-Content
