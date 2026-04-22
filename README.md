# 🌱 Soil Nutrient Prediction from Historical Data Using Random Tree Algorithm  

## 📖 Overview  
Brief description of the thesis system, purpose, and main goals.  

---

## 🚀 Tech Stack  
- **Frontend**: Next.js (React, TailwindCSS, Figma/UI)  
- **Backend**: Next.js API Routes  
- **Database**: Supabase (PostgreSQL + Auth + Storage)  
- **Machine Learning**: Random Tree Algorithm (Python / API)  
- **Deployment**: Vercel & Supabase  

---

## 📂 Project Structure  
soil-nutrient-prediction/

Not yet available

---

## ⚙️ Features  
- 🔑 User Authentication (Supabase)  
- 📊 Data Management (Upload, store, edit, delete soil data)  
- 🌾 Prediction Module (Random Tree algorithm)  
- 📈 Visualization (Charts & historical trends)  
- 📑 Reports (Export to PDF/Excel)  
- 🛠️ Admin Features (Manage users & datasets)  

---

## 🧪 Machine Learning Model  
- **Algorithm**: Random Tree (simplified Random Forest)  
- **Input**: N, P, K, pH, temperature, rainfall, etc.  
- **Output**:  
  - Soil nutrient predictions  
  - Fertilizer recommendations  
  - Crop suitability suggestions  

---

## 🔧 Installation & Setup  

### 1. Clone the Repository  
```bash
git clone https://github.com/osizwr/soil-nutrient-prediction.git
cd soil-nutrient-prediction
```

### 2. Install Dependencies 
```bash
npm install
```

### 3. Configure Environment Variables
Create a .env.local file:
```bash
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
```

### 4. Run Development Server
App will run at http://localhost:3000
```bash
npm run dev
```

## 📖 Thesis Context  

**Title:** Soil Nutrient Prediction from Historical Data Using Random Tree Algorithm  

**Objective:** Provide decision support for farmers in soil nutrient management  

**Dataset:** Kaggle (soil/crop data) + DA Palawan reference NPK values  

**Methodology:** Data-Driven Research + Agile SDLC  

---

## 🛠️ Future Enhancements  

- Add multiple ML models for comparison  
- Offline-ready mode for local farmers  
- Mobile-first optimization  
- IoT sensor data integration  
---

## 📜 License  

Licensed under the **MIT License**.  
