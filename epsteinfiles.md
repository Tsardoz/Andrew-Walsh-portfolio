# AI-Powered Legal Document Processing System (2025)

**Technologies:** Next.js, TypeScript, Python, PostgreSQL (Supabase), Machine Learning, NLP

## Project Overview
Developed a production-grade AI system to process and analyze 36,000+ released Epstein court documents, making previously inaccessible legal records searchable and analyzable through advanced machine learning techniques. See it in action [here](https://epstein-files.org)

## Technical Architecture
- **Frontend:** Next.js/TypeScript application with responsive UI and dark mode support
- **Backend:** Supabase PostgreSQL with pgvector extension for semantic search capabilities
- **Storage:** Cloudflare R2 CDN with hybrid local fallback (achieved 90% compression: 53GB→5GB)
- **Processing Pipeline:** Python-based batch processing with 40+ specialized scripts

## Machine Learning & NLP Implementation
- **Semantic Search:** Implemented BGE-base-en-v1.5 embedding model generating 768-dimensional vectors for 36,000+ documents
- **Hybrid Search:** Reciprocal Rank Fusion (RRF) combining keyword and semantic search methods
- **Entity Extraction:** Production-grade spaCy NER (en_core_web_trf) with smart consolidation algorithms
- **Multi-Modal Processing:** 
  - OCR text extraction (EasyOCR with multi-GPU support)
  - Image captioning (Florence2/Gemini-2.5-pro)
  - Audio transcription (OpenAI Whisper with timestamping)
  - AI-generated podcast summaries from document discoveries

## Advanced Features
- **Collaborative Intelligence System:** Crowdsourced rating and validation platform with anti-gaming mechanisms for community-driven investigative lead discovery
- **AI Analysis Engine:** LLM-powered query generation system analyzing social media and news to generate strategic search queries, reducing research time from months to hours
- **Query Optimization:** Intelligent stop-word filtering (70+ terms) and relevance ranking with database caching
- **Real-time Analytics:** Pattern detection and breakthrough discovery identification through user feedback

## Technical Skills Demonstrated
- Advanced NLP and semantic search implementation
- Large-scale data pipeline development and optimization
- Vector database design and query optimization
- Full-stack application architecture
- Cloud infrastructure and CDN integration
- Multi-modal AI processing (text, image, audio)
- Production-grade error handling and caching strategies

## Impact & Scalability
- Processed 36,024 documents with 79 audio transcripts containing 102K+ extracted entities
- System designed for cost-effective scaling on free-tier infrastructure
- Established foundation for AI-powered legal document analysis with potential enterprise applications ($2K-25K/month revenue model)

---

**Historical Context:** This project demonstrates the evolution of practical ML applications from my 2006 PhD research in physiological signal processing to modern legal document analysis—bridging two decades of AI advancement while maintaining focus on real-world problem-solving and clinical/legal-grade accuracy standards.
