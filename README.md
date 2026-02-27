<!DOCTYPE html>
<html>
<body>

  <div align="center">
    <h1>🎓 EduAI</h1>
    <p><strong>Your Personal AI Study Partner for 2026</strong></p>
    <p><i>Empowering learners through AI-driven roadmaps, real-time market insights, and personalized tutoring.</i></p>
  </div>

  <hr>

  <h2>📖 Overview</h2>
  <p>
    EduAI is a next-generation EdTech platform designed to bridge the gap between academic learning and industry demands. By leveraging <b>Gemini 3.1 Pro</b>, the platform provides a centralized dashboard to track progress, interactive study materials, and a smart tutor that understands your unique learning pace.
  </p>

  <h2>🚀 Core Functions</h2>

  <table>
    <tr>
      <th>Feature</th>
      <th>Description</th>
    </tr>
    <tr>
      <td><b>Personalized Dashboard</b></td>
      <td>A high-level view of <b>Learning Progress</b>, active roadmaps, and AI-generated insights based on user activity.</td>
    </tr>
    <tr>
      <td><b>AI Study Tutor</b></td>
      <td>A conversational interface to generate custom roadmaps, explain complex topics (like Quantum Computing), or quiz you on your current syllabus.</td>
    </tr>
    <tr>
      <td><b>Study Area</b></td>
      <td>Curated career paths including <b>Full Stack Web Development</b> and <b>Data Science & AI</b> with curriculum highlights (React, Python, etc.).</td>
    </tr>
    <tr>
      <td><b>2026 Market Insights</b></td>
      <td>Live data fetching from global job boards to show trending skills and industry demands in real-time.</td>
    </tr>
    <tr>
      <td><b>Secure Authentication</b></td>
      <td>Integrated with <b>Clerk</b> for seamless Google/GitHub social logins and phone-based authentication.</td>
    </tr>
  </table>

  <h2>🛠️ Tech Stack</h2>
  <ul>
    <li><b>Frontend:</b> React.js / Next.js with Tailwind CSS</li>
    <li><b>AI Engine:</b> Gemini 3.1 Pro API</li>
    <li><b>Auth:</b> Clerk Authentication</li>
    <li><b>Icons:</b> Lucide React / Custom SVG</li>
    <li><b>UI:</b> Dark-themed, glassmorphic dashboard design</li>
  </ul>

  <h2>📂 Project Structure</h2>
  <blockquote>
    <i>"The architecture is modular, separating the AI logic from the UI components for high performance."</i>
  </blockquote>
  <ul>
    <li><code>/overview</code>: Manages progress tracking and user statistics.</li>
    <li><code>/tutor</code>: Handles the chat interface and prompt engineering for Gemini.</li>
    <li><code>/study-area</code>: Contains curriculum data and learning resource links.</li>
    <li><code>/market</code>: Logic for scraping/fetching live job market trends.</li>
  </ul>

  <h2>🔧 Setup Instructions</h2>
  <pre>
<code>
# Clone the repository
git clone https://github.com/yourusername/edu-ai.git

# Install dependencies
npm install

# Set up environment variables (.env)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
GEMINI_API_KEY=your_key

# Run the development server
npm run dev
</code>
  </pre>

  <hr>

  <div align="center">
    <p>Built with ❤️ by Chirag Tankan</p>
  </div>

</body>
</html>
