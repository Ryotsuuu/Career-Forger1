# AI Career Pathfinder

**AI Career Pathfinder** is a sophisticated Angular application designed to help tech professionals strategize their career growth. Powered by Google's Gemini API, it generates hyper-personalized career roadmaps, market intelligence, and strategic positioning analysis based on real-time data.

## 🚀 Features

### 1. Strategic Roadmap
- **Personalized Timeline**: Generates a phase-by-phase execution plan for career growth.
- **Skill Gap Analysis**: Identifies critical missing skills and verifies current strengths.
- **Target Credentials**: Recommends high-value certifications specific to the role and level.
- **CV Optimization**: AI-driven resume audit tips.

### 2. Market Intelligence
- **Global vs. Local Radar**: Compares adoption lags, salary arbitrage, and tech trends between the user's location and global Tier-1 hubs.
- **Financial Benchmarking**: Visualizes local salary trajectories vs. global compensation ranges (Base + Bonus + Stock).
- **Cost of Living & Benefits**: AI-estimated breakdown of monthly expenses (Rent, Food, Transport) and typical perk packages (ESOPs, Insurance) for the specific region.
- **Ecosystem Landscape**: Categorizes local companies into Global Titans, National Leaders, and High-Growth Startups.

### 3. Strategic Positioning (Check Where You Stand)
- **Fit Score**: Calculates a "readiness score" (0-100) based on education, skills, and experience vs. market demand.
- **Strengths & Growth Areas**: AI-identified key differentiators and areas for improvement.
- **Target Organizations**: A detailed dossier of 12 specific companies with "Match Level", "Culture Vibe", and "Hiring Focus".

### 4. Interview Prep
- **AI Mock Questions**: Generates 15 strategic interview questions (Behavioral, Technical, System Design).
- **Topic Heatmap**: Visualizes high-probability interview topics for the specific role.

## 🛠️ Tech Stack

- **Framework**: Angular v21+ (Zoneless, Standalone Components)
- **Language**: TypeScript
- **Styling**: Tailwind CSS (Dark Mode Aesthetic)
- **AI Integration**: Google Gemini API (`gemini-2.5-flash`) via `@google/genai` SDK
- **Data Visualization**: D3.js
- **State Management**: Angular Signals

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ai-career-pathfinder
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure API Key**
   - Ensure the environment has the `API_KEY` set for Google Gemini API access.
   - *Note: In this specific environment, the key is accessed via `process.env['API_KEY']`.*

4. **Run the application**
   ```bash
   npm start
   ```

## 📜 Usage

1. Enter your **Target Role**, **Location**, **Current Level**, and **Primary Goal**.
2. Click **Generate Strategy**.
3. Explore the data tabs: Roadmap, Market, Positioning, and Interview Prep.
4. Use the "Check Where You Stand" tab to input detailed skills/education for a deep-dive analysis.

## 🎨 Design

The application features a modern, "Cyber-Dark" aesthetic using:
- **Glassmorphism**: Backdrop blurs and semi-transparent backgrounds.
- **Gradients**: Subtle violet/emerald accents.
- **Typography**: Inter font family for clean readability.
- **Animations**: CSS keyframe animations for smooth entry transitions.