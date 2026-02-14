# VAKTRA - System Design

## 🏗️ Architecture Overview


## 🔄 Data Flow
1. **User Input** → Speech/text in language X
2. **Language Detection** → Identify language & dialect
3. **Intent Classification** → Translate, Preserve, or Empower?
4. **Processing** → Specialist microservice
5. **Response** → Translation + Suggested action

## 🛠️ AWS Implementation
| Component | AWS Service | Purpose |
|-----------|-------------|---------|
| Base Model | Amazon Bedrock (Llama 3) | Core LLM |
| Assistant | Amazon Q | Development help |
| Storage | Amazon S3 | Datasets, models |
| Compute | Amazon EC2 (GPU) | Training |

## 📈 Hackathon MVP (Due Feb 22, 2026)
1. Working prototype translating 5 languages (Hindi, Tamil, Bengali, Telugu, Marathi)
2. Simple web interface for demo
3. 3-minute demo video
4. 10-12 slide pitch deck
5. Blog post for AWS Builder Center
