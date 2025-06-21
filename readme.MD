# 🧠 Open Source AI Image Generator MVP
Not sure when I start or finish (just hobby)
A cross-platform AI-powered image generator with prompt embedding search, built with:

### 👤 User App
- **Frontend:** Ionic Vue 3
- **Backend:** NestJS
- **Auth:** Firebase Authentication
- **Database:** Firestore
- **Image Gen:** OpenAI DALL·E or Stability API

### 🛠️ Backoffice App
- **Frontend:** Vue 3
- **Search:** Weaviate Vector DB (cloud-hosted)
- **Admin Tools:** Search, flagging, and analytics

---

## 📦 Features

### User Side
- 🔐 Firebase login (email/password or Google)
- 📝 Prompt submission
- 🧠 AI-generated image rendering
- 📜 Firestore history per user
- 🎯 Vector search support via Weaviate
- ⚖️ (Optional) Usage quotas or credit tracking

### Backoffice
- 🔍 Semantic search by prompt meaning
- 🧾 View image metadata
- 🏷️ Tag/flag/moderate content
- 📊 Track usage per user

---

## 🧱 Tech Stack

| Layer       | Tech                           |
|------------|----------------------------------|
| Client UI  | Ionic Vue 3 + Vuex/Pinia         |
| Server     | NestJS + REST/GraphQL            |
| Auth       | Firebase Authentication          |
| Storage    | Firestore (image metadata)       |
| Vector DB  | Weaviate (hosted on WCS)         |
| AI         | OpenAI (DALL·E + Embedding)      |
| Alt AI     | Gemini API or Stability API      |

---

## 🚀 Getting Started

### 1. Clone Repo

```bash
git clone https://github.com/mr-ben-jeckson/weaviate-openai-image-generator
cd ai-image-generator
