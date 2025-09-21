**# Machine Servicing & Parts Website

A dynamic company website designed for a machine servicing and spare parts provider.  
The site includes multiple pages such as Homepage, Services, Products, Admin Panel, and Login/Signup functionality.  

It is built with **HTML (inline CSS)** and integrated with **Firebase SDK** for form management and authentication.  
Google Maps integration and placeholders for images are also included.

---

## 🚀 Features
- **Homepage**: Company introduction and highlights.
- **Services Page**: List of machine servicing options.
- **Products Page**: Spare parts listing with placeholders for images.
- **Login & Signup**: Firebase-based form handling and authentication.
- **Admin Panel**: Manage services, parts, and user data.
- **Google Maps Integration**: Placeholder section for embedding location.
- **Inline CSS**: Simple styling directly within HTML.
- **Firebase SDK Integration**: For form submission and user management.

---

## 📂 Project Structure
**

├── admin.html # Admin dashboard page
├── homepage.html # Landing page with company details
├── login_signup.html # Login & signup form (Firebase SDK integrated)
├── products.html # Spare parts/products listing
├── services.html # Services offered
├── demo view.jpg # Project demo screenshot
├── .gitattributes



## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git


   Open the HTML files

 Open homepage.html in a browser to start.

2. Configure Firebase SDK

3. Add your Firebase configuration in the <script> section of login_signup.html (and any other forms if needed).


// Example Firebase Config
const firebaseConfig = {
  apiKey: "YOUR-API-KEY",
  authDomain: "YOUR-PROJECT-ID.firebaseapp.com",
  projectId: "YOUR-PROJECT-ID",
  storageBucket: "YOUR-PROJECT-ID.appspot.com",
  messagingSenderId: "SENDER-ID",
  appId: "APP-ID"
};
firebase.initializeApp(firebaseConfig);


4. Add Images

Replace placeholders (<img src="your-image-here.jpg">) with your actual company/product/service images.

5. Google Maps Integration

Replace the map <iframe> placeholder with your company’s actual Google Maps embed link.

<iframe src="YOUR_GOOGLE_MAP_EMBED_URL" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>


