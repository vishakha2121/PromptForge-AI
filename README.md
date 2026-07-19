# 🚀 PromptForge AI - Enterprise Prompt Optimization Platform

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/PromptForge-AI?style=for-the-badge&color=gold)](https://github.com/vishakha2121/PromptForge-AI/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/PromptForge-AI?style=for-the-badge&color=blue)](https://github.com/vishakha2121/PromptForge-AI/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/PromptForge-AI?style=for-the-badge&color=red)](https://github.com/vishakha2121/PromptForge-AI/issues)
[![GitHub license](https://img.shields.io/github/license/vishakha2121/PromptForge-AI?style=for-the-badge&color=green)](https://github.com/vishakha2121/PromptForge-AI/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)

</div>

## 📖 Overview

**PromptForge AI** is an intelligent platform that revolutionizes how organizations create, test, and optimize prompts for Large Language Models (LLMs). Think of it as a **"Testing Laboratory"** for AI prompts where you can experiment, compare, and perfect your prompts before deploying them in production.

<p align="center">
  <img src="https://via.placeholder.com/800x400/1A237E/FFFFFF?text=PromptForge+AI+Dashboard" alt="PromptForge AI Dashboard" width="80%">
</p>

---

## 🎯 **What Problem Does It Solve?**

| Problem | Solution |
|---------|----------|
| ❌ Manual prompt testing is time-consuming | ✅ Automated A/B testing |
| ❌ No way to compare prompt versions | ✅ Version control system |
| ❌ Don't know which prompt performs best | ✅ Performance metrics & analytics |
| ❌ Hard to optimize prompts | ✅ AI-powered suggestions |
| ❌ Single LLM limitation | ✅ Multiple LLM support |
| ❌ No quality metrics | ✅ Built-in evaluation system |

---

## ✨ **Core Features**

### 1️⃣ **Intelligent Prompt Management**
- Create, edit, and version prompts
- Organize prompts by categories
- Track prompt evolution history
- Export/Import prompt templates

### 2️⃣ **Multi-LLM Integration**
- Support for multiple AI models:
  - ✅ **Google Gemini** (Primary)
  - ✅ **OpenAI GPT-4** (Planned)
  - ✅ **Llama 2/3** (Planned)
  - ✅ **Claude** (Planned)
- Compare performance across models
- Cost optimization insights

### 3️⃣ **Automated A/B Testing**
- Test multiple prompt variations simultaneously
- Compare response quality
- Statistical significance analysis
- Real-time results monitoring
- Side-by-side comparison view

### 4️⃣ **Reinforcement Learning Optimization**
- Learn from test results automatically
- Auto-suggest improvements
- Continuous performance enhancement
- Adaptive learning algorithm
- Historical improvement tracking

### 5️⃣ **Advanced Analytics Dashboard**
- Performance visualization with charts
- Quality metrics tracking
- Response time analysis
- Cost optimization insights
- Export reports in multiple formats

### 6️⃣ **Quality Metrics System**
- **BLEU Score** - Response quality measurement
- **ROUGE Score** - Content relevance assessment
- **Response Coherence** - Logic flow analysis
- **Toxicity Score** - Safety check
- **Bias Detection** - Fairness analysis
- **Response Time** - Speed metrics
- **User Satisfaction** - Feedback scoring

### 7️⃣ **Collaboration Tools**
- Share prompts with team members
- Comment and review system
- Collaborative optimization
- Permission management
- Activity tracking

---

## 🏗️ **Technical Architecture**

---

## 💻 **Tech Stack**

### **Backend Technologies:**
| Technology | Version | Purpose |
|------------|---------|---------|
| 🐍 **Python** | 3.9+ | Core language |
| 🚀 **FastAPI** | Latest | Modern web framework |
| 🗄️ **PostgreSQL** | 14+ | Relational database |
| 🔐 **JWT** | Latest | Authentication |
| 🧠 **Gemini API** | Latest | Primary LLM |
| 📊 **SQLAlchemy** | Latest | ORM |
| 🔄 **Alembic** | Latest | Database migrations |
| 🧪 **Pytest** | Latest | Testing framework |

### **Frontend Technologies:**
| Technology | Version | Purpose |
|------------|---------|---------|
| ⚛️ **React** | 18+ | UI framework |
| 🎨 **Material-UI** | Latest | Component library |
| 📈 **Recharts** | Latest | Data visualization |
| 🎭 **Framer Motion** | Latest | Animations |
| 🔄 **React Query** | Latest | Data fetching |
| 🌐 **Axios** | Latest | HTTP client |
| 🎯 **React Router** | Latest | Navigation |
| 📝 **Formik** | Latest | Form management |

---

## 📊 **Database Schema**

### **Key Tables & Relationships:**

```sql
1. users              - User management & authentication
2. prompts            - Store prompt versions & templates
3. prompt_templates   - Template storage & categories
4. ab_tests          - A/B test configuration & setup
5. test_results      - Test outcomes & performance data
6. performance_metrics - Quality metrics & scores
7. optimization_logs - Auto-optimization history
8. llm_models        - Available AI models configuration
9. feedback          - User feedback & ratings
10. analytics        - Usage analytics & statisticsgit clone https://github.com/vishakha2121/PromptForge-AI.git
cd PromptForge-AI# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env

# Update .env with your credentials
# Edit .env file and add your Gemini API key# Navigate to frontend directory
cd ../frontend

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Update .env with backend URL
# Edit .env file and set REACT_APP_API_URL=http://localhost:8000