# Fraud Guardian - Design Document

## System Architecture

User Input → AI Processing Layer → Fraud Classification Model → LLM Explanation Engine → Response Output

## Components

1. Text Analysis Module
   - NLP-based scam classifier
   - Keyword + pattern detection

2. Audio Analysis Module
   - Speech-to-text conversion
   - Deepfake voice pattern detection

3. Image & QR Scanner
   - QR decoding
   - URL validation

4. LLM Explainer Layer
   - Generates human-readable explanation
   - Uses Retrieval Augmented Generation (RAG)

5. Knowledge Base
   - RBI fraud guidelines
   - CERT-In reports
   - Known scam datasets

## Tech Stack (Proposed)
- Python
- HuggingFace Transformers
- OpenAI / LLaMA-based LLM
- FastAPI
- Cloud deployment (AWS/GCP)

## Future Scalability
- Integration with banking APIs
- Browser extension
- Mobile app deployment
