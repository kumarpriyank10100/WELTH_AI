💰 WELTH_AI: Intelligent Financial ManagementA next-generation wealth management platform that leverages advanced Artificial Intelligence to provide personalized financial analysis, predictive modeling, and proactive investment guidance. Built to help users make smarter, data-driven decisions about their financial future.✨ Key FeaturesWELTH_AI is designed to transform complex financial data into actionable insights:Personalized AI Analyst: An intelligent assistant that analyzes your spending habits, income, and goals to provide tailored budget and saving recommendations.Predictive Market Insights: Utilizes large language models (LLMs) and real-time data to identify potential market trends and risks before they fully materialize.Goal-Oriented Planning: Interactive dashboards to set, track, and optimize long-term financial goals (e.g., retirement, major purchases, debt repayment).Secure & Scalable: Built on a modern, secure architecture ensuring data privacy and high performance.Intuitive UI/UX: A clean, responsive design optimized for desktop and mobile use, powered by Tailwind CSS.💻 Tech StackThis project is built using a robust and modern stack, ensuring high performance, scalability, and maintainability.CategoryTechnologyPurposeFrameworkNext.js 14 (App Router)React framework for server-side rendering, routing, and API handling.StylingTailwind CSS & shadcn/uiUtility-first CSS framework for rapid, responsive, and beautiful design.DatabasePrisma (ORM)Next-generation ORM for simplified database access and schema management.API/DataOpenAI/Gemini API (Inferred)Integration point for core AI/LLM functionalities and data processing.LanguageJavaScript/TypeScript (jsconfig.json)Core language for application logic.LintingESLintCode quality and standard enforcement.🚀 Getting StartedFollow these instructions to get a local copy of the project up and running for development and testing.PrerequisitesYou need to have Node.js (v18+) and npm installed on your machine.InstallationClone the Repository:git clone [https://github.com/kumarpriyank10100/WELTH_AI.git](https://github.com/kumarpriyank10100/WELTH_AI.git)
cd WELTH_AI
Install Dependencies:npm install
(If you prefer yarn or pnpm, use the corresponding command.)Set Up Environment Variables:Create a file named .env.local in the root directory and add the necessary environment variables. At a minimum, you will need:# Database URL for Prisma
DATABASE_URL="file:./dev.db" 

# Key for your AI provider (e.g., OpenAI, Google Gemini)
AI_API_KEY="your_api_key_here" 

# NextAuth/Authentication variables (if using)
NEXTAUTH_SECRET="your_secure_secret"
Database Setup:Initialize the database and run migrations using Prisma:npx prisma migrate dev --name init
Running the ApplicationStart the development server:npm run dev
The application will be accessible at: http://localhost:3000🤝 ContributionWe welcome contributions! Whether it's adding a new feature, fixing a bug, or improving documentation, your help is appreciated.Fork the repository.Create a new feature branch (git checkout -b feature/AmazingFeature).Commit your changes (git commit -m 'Add some AmazingFeature').Push to the branch (git push origin feature/AmazingFeature).Open a Pull Request.📄 LicenseDistributed under the MIT License. See LICENSE.md for more information.📞 ContactKumar Priyank - https://github.com/kumarpriyank10100Project Link: https://github.com/kumarpriyank10100/WELTH_AI


<img width="1470" alt="Screenshot 2024-12-10 at 9 45 45 AM" src="https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432">

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```
