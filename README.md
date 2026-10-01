
# ThesisWeave 🔬
> An AI-powered research and knowledge discovery assistant built for literature synthesis and citation-backed document analysis.

---

## 📌 Overview
ThesisWeave simplifies academic literature reviews by allowing researchers to upload academic papers (PDFs), extract meaningful context, and query documents with synthesized, citation-aware responses powered by Google Gemini.

---

## 🚀 Key Features
- **Document Processing:** Ingests and parses research papers in PDF format.
- **Context-Aware Q&A:** Grounded synthesis using Google Gemini to answer complex literature questions.
- **Source Grounding:** Direct referencing to uploaded texts to minimize AI hallucinations.
- **Fast Full-Stack Architecture:** Responsive modern UI paired with an Express and MongoDB data pipeline.

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite, Tailwind CSS, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (Mongoose)
- **AI Engine:** Google Gemini API (`@google/genai`)

---

## ⚙️ Local Setup & Installation

### 1. Clone the repository
\`\`\`bash
git clone https://github.com/your-username/thesis-weave.git
cd thesis-weave
\`\`\`

### 2. Configure Environment Variables
Create a \`.env\` file in the \`server\` directory:
\`\`\`env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
GEMINI_MODEL=gemini-2.5-flash
\`\`\`

### 3. Install Dependencies and Run

**Start the Backend:**
\`\`\`bash
cd server
npm install
npm run dev
\`\`\`

**Start the Frontend:**
\`\`\`bash
cd ../client
npm install
npm run dev
\`\`\`

Open https://zp1v56uxy8rdx5ypatb0ockcb9tr6a-oci3-wsv2lped--5173--d5306e6f.local-credentialless.webcontainer-api.io/in your browser.
