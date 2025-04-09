# Gym Management App 🏋️‍♂️

Aplicație full-stack pentru gestiunea membrilor unei săli de fitness. Permite înregistrarea noilor membri, reînnoirea abonamentelor și gestionarea datelor într-o interfață ușor de utilizat.

## 🧰 Tehnologii utilizate

- **Frontend**: ReactJS, TailwindCSS
- **Backend**: NodeJS, ExpressJS
- **Bază de date**: MongoDB
- **Testare API**: Postman

## 🔑 Funcționalități principale

- Înregistrare membri cu date personale și poză de profil
- Selectarea planului de abonament (1/3/6/12 luni)
- Salvare automată în MongoDB
- Reînnoirea abonamentelor existente
- Încărcare imagini pe Cloudinary

## 📦 Structură proiect

- `/frontend`: interfața utilizator (React)
- `/backend`: server NodeJS + rute REST API
- `/config`: fișiere de configurare pentru MongoDB și Cloudinary

## ⚙️ Cum rulezi aplicația local

Cum rulezi aplicația local

1. Clonează acest repo:
   ```bash
   git clone https://github.com/numele-tau/gym-management-app.git
   ```

2. Navighează în directorul proiectului:
   ```bash
   cd gym-management-app
   ```

3. Instalează dependențele pentru frontend:
   ```bash
   cd frontend
   npm install
   ```

4. Instalează dependențele pentru backend:
   ```bash
   cd ../backend
   npm install
   ```

5. Creează fișierele de configurare pentru MongoDB și Cloudinary în /config:
   - **MongoDB**: Crează un fișier db.js și adaugă conexiunea la baza de date.
   - **Cloudinary**: Crează un fișier cloudinary.js și adaugă cheia API pentru încărcarea imaginilor pe Cloudinary.

6. Înainte de a porni aplicația, asigură-te că ai setat corect variabilele de mediu pentru MongoDB și Cloudinary:
   ```bash
   MONGO_URI=your_mongo_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   ```

7. Pornește serverul backend:
   ```bash
   cd backend
   npm run dev
   ```

8. Pornește aplicația frontend:
   ```bash
   cd frontend
   npm start
   ```

Acum ar trebui să ai aplicația rulând pe http://localhost:3000, iar backend-ul pe http://localhost:5000.

📝 Licență
Acest proiect este licențiat sub Licența MIT - vezi [LICENSE](LICENSE) pentru detalii.
