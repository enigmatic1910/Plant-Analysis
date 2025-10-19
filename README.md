# 🌿 PlantScan: Advanced Plant Analysis Tool

**PlantScan** is a web-based tool that allows users to upload a plant image and receive a detailed AI-powered analysis of its species, health condition, and care instructions. It also generates a downloadable PDF report using Google Gemini AI.

---<img width="1858" height="965" alt="Screenshot 2025-10-19 135220" src="https://github.com/user-attachments/assets/258ce100-3783-4124-88ce-cfcdf7a397a5" />

## 🚀 Features

- 📷 Upload plant images via drag-and-drop or file input  
- 🧠 AI-powered analysis using Google's Gemini 1.5 Flash model  
- 📑 Generates PDF reports with image and analysis  
- ⚡ Fast, user-friendly interface  
- 📥 Instant download of results  

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **AI Integration**: Google Generative AI (Gemini)  
- **PDF Generation**: `pdfkit`  
- **File Uploads**: `multer`  

---

## 🖥️ Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone <your-repo-url>
   cd plantscan
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Create a `.env` file** in the root directory with your Gemini API key:  
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

4. **Run the application**  
   ```bash
   node server.js
   ```

5. **Open in browser**  
   Visit: [http://localhost:3000](http://localhost:3000)

---

## 📌 API Endpoints

- `POST /analyze`  
  Accepts plant image and returns AI-generated plant analysis.

- `POST /download`  
  Generates and sends a PDF report containing the analysis and uploaded image.

---

## 🧪 Sample Workflow

1. Upload or drag and drop a plant image.
2. Click “Analyze Plant”.
3. View the analysis results on-screen.
4. Click “Download PDF Report” to save the report.


