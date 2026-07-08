# SnapClass - AI Attendance Project Landing Page

Welcome to the landing page repository for **SnapClass**, an AI-powered attendance system. This project serves as the marketing and informational frontend, showcasing the features and flows for both students and teachers using the application.

## 🚀 Features Highlighted
- **Teacher Flow**: Secure login, dashboard access, course creation, generating QR codes/links, and viewing stored attendance records.
- **Student Flow**: Easy enrollment and interactive dashboards.
- **Smart Attendance**: Showcase of Voice and Photo-based AI attendance systems.

## 🛠 Tech Stack
- **Backend**: Python, Flask, Gunicorn
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Configured for Vercel (`vercel.json` included)

## 📸 Screenshots & Demos
The project includes various demo snapshots under `static/img/demo/` visualizing the UI/UX for both student and teacher portals.

## 💻 Running the Project Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/gayatribakle/SnapClass.git
   cd SnapClass
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: .\venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```

5. **Access the application:**
   Open your browser and navigate to `http://127.0.0.1:5002`.

## 🌐 Deployment
This app is ready to be deployed on Vercel. Simply connect your GitHub repository to Vercel, and the provided `vercel.json` will handle the routing and deployment automatically.