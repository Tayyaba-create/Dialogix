# DialogixAI - AI-Powered Data Analytics Chatbot

Welcome to DialogixAI, an innovative AI-driven data analytics web application designed to simplify how users interact with datasets and extract meaningful insights. This application bridges the gap between raw data and actionable understanding through natural language processing and dynamic visualizations.

## Overview

DialogixAI is built with modern web technologies to provide a seamless, intuitive experience for analyzing and visualizing data. Whether you're a business user, student, or analyst, DialogixAI makes data analysis accessible through natural language interactions and interactive visualizations.

### Key Features

- 📊 Interactive data visualization
- 💬 Natural language data querying
- 📈 Dynamic chart generation
- 📑 Structured data (CSV) support
- 💾 Save and manage analysis dashboards
- 🤖 AI-powered insights and summaries

## Technology Stack

- React, TypeScript, Vite. Tailwind CSS, Supabase,Python, FastAPI, FAISS (for embeddings & retrieval), LangChain (RAG pipeline), NLP, Machine Learning, PyTorch, Pandas, NumPy

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Tayyaba-create/Dialogix.git
cd dialogix
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Configure environment variables:
   Create a `.env` file in the root directory and add your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

## Usage Guide

1. **Authentication**

   - Sign up or log in using the authentication modal
   - Secure access to your personal dashboards and analysis history

2. **Data Upload**

   - Click the upload button in the dashboard
   - Support for CSV file formats
   - Preview data before confirmation

3. **Data Analysis**

   - Use natural language to query your data
   - Ask questions like "Show me sales trends for last quarter"
   - Request specific visualizations: "Create a bar chart of monthly revenue"

4. **Dashboard Management**

   - Save your analyses as custom dashboards
   - Name and organize your visualizations
   - Share insights with team members
   - Access your history of analyses

5. **Visualization Options**
   - Bar charts
   - Line graphs
   - Scatter plots
   - Pie charts
   - Data tables
   - Custom views

## Contributing

We welcome contributions to DialogixAI! Please feel free to submit issues, fork the repository and create pull requests for any improvements.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
.

## Support

If you encounter any issues or have questions, please:

1. Check the existing issues or create a new one
2. Join our community discussions
3. Contact support at tayyabaf28@gmail.com

---

Built with ❤️ by the Tayyaba Faisal
