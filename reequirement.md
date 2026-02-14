# VAKTRA - Project Requirements

## 🎯 Problem Statement
India has 780+ languages, 197 endangered, but existing AI solutions:
- Bhashini: Translation-only, centralized
- Adi Vaani: Only 4 tribal languages
- No community ownership or revenue sharing

## 👥 Target Users
- Rural farmers (accessing govt schemes)
- ASHA workers (healthcare delivery)
- Tribal communities (language preservation)
- Litigants (legal aid in native languages)

## 🏗️ Functional Requirements
| ID | Requirement | Priority |
|----|-------------|----------|
| F1 | Translate between 22 scheduled languages + English | P0 |
| F2 | Speech-to-text for all supported languages | P0 |
| F3 | Offline functionality for rural areas | P0 |
| F4 | Oral tradition recording & preservation | P1 |
| F5 | Government scheme form auto-filling | P1 |

## 📋 Technical Stack
- **AWS Services**: Amazon Bedrock (Llama 3), Amazon Q, S3, EC2
- **ML Framework**: PyTorch, Hugging Face
- **Models**: MBART-50, IndicBERT, LoRA adapters
- **Mobile**: Flutter, TFLite

## 📊 Success Metrics
- Languages supported: 22 + 4 tribal (Phase 1)
- Users reached: 10,000+ (pilot)
- Translation accuracy: >25 BLEU
- Community revenue share: 70% to contributors
