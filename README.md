# Finlit - Financial Literacy Platform

A comprehensive financial literacy platform with integrated fraud detection capabilities, built using modern web technologies and machine learning.

## 🌟 Features

- Interactive learning modules for:
  - Budgeting
  - Investing
  - Saving
  - Fraud Prevention
- Real-time fraud detection for banking transactions
- User progress tracking with streak system
- Interactive quizzes and assessments
- Responsive modern UI with dark mode support

## 🔧 Tech Stack

### Frontend
- React 18 with TypeScript
- Vite for build tooling
- TailwindCSS for styling
- Radix UI components
- Clerk for authentication
- React Router for navigation
- Recharts for data visualization

### Backend
- Node.js with Express
- MongoDB for database
- Clerk for user management
- Multer for file uploads
- CORS enabled
- JWT authentication

### Machine Learning
- Python-based fraud detection system
- Libraries used:
  - pandas for data manipulation
  - scikit-learn for preprocessing and modeling
  - XGBoost for fraud detection
  - Isolation Forest for anomaly detection

## 📋 Prerequisites

- Node.js (v16 or higher)
- Python 3.8+ with pip
- MongoDB
- Git

## 🚀 Getting Started

1. Clone the repository:
\`\`\`bash
git clone <repository-url>
cd FinlitTemplate
\`\`\`

2. Set up the frontend:
\`\`\`bash
cd frontend
npm install
npm run dev
\`\`\`

3. Set up the backend:
\`\`\`bash
cd backend
npm install
npm start
\`\`\`

4. Set up the ML environment:
\`\`\`bash
cd ml
pip install -r requirements.txt
\`\`\`

5. Configure environment variables:
   - Create .env files in both frontend and backend directories
   - Set up necessary environment variables (see .env.example)

## 🔐 Environment Variables

### Frontend
\`\`\`
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_BACKEND_URL=http://localhost:5000
\`\`\`

### Backend
\`\`\`
CLERK_SECRET_KEY=your_clerk_secret
MONGODB_URI=your_mongodb_uri
\`\`\`

## 📁 Project Structure

\`\`\`
├── frontend/           # React TypeScript frontend
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── pages/     # Page components
│   │   ├── hooks/     # Custom React hooks
│   │   └── assets/    # Static assets
├── backend/           # Express.js backend
│   ├── routes/       # API routes
│   ├── db.js        # Database configuration
│   └── app.js       # Main server file
└── ml/              # Machine Learning components
    └── fraud-detection.py
\`\`\`

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (\`git checkout -b feature/AmazingFeature\`)
3. Commit your changes (\`git commit -m 'Add some AmazingFeature'\`)
4. Push to the branch (\`git push origin feature/AmazingFeature\`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Clerk for authentication
- Shadcn UI for component library base
- TailwindCSS for styling utilities
- All contributors who have helped shape this project

## 📬 Contact

For any queries or support, please open an issue in the repository.