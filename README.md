index.html,
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>G-Xcell Nutrition - Supplements & Privacy Policy</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #287233;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    nav button {
      margin-left: 1rem;
      padding: 0.5rem 1rem;
      font-size: 1rem;
      background: #4CAF50;
      border: none;
      color: white;
      border-radius: 4px;
      cursor: pointer;
    }
    nav button:hover {
      background: #45a049;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: #287233;
      border-bottom: 2px solid #287233;
      padding-bottom: 0.3rem;
    }
    /* Supplements List */
    .supplement-list {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(300px,1fr));
      gap: 2rem;
      margin-top: 1rem;
    }
    article.supplement {
      background: white;
      padding: 1rem 1.5rem;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.07);
    }
    article.supplement h3 {
      margin-top: 0;
      color: #2a5a2f;
    }
    table.nutrition-facts {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1rem;
      margin-bottom: 1rem;
    }
    table.nutrition-facts th,
    table.nutrition-facts td {
      border: 1px solid #ddd;
      padding: 0.5rem;
    }
    table.nutrition-facts th {
      background: #f4f4f4;
    }
    .order-btn {
      background: #287233;
      color: white;
      border: none;
      padding: 0.6rem 1.2rem;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .order-btn:hover {
      background: #1f5627;
    }

    /* Privacy Policy Table of Contents */
    nav#toc {
      background: #e6f2e6;
      padding: 1rem;
      border-radius: 6px;
      border: 1px solid #c1d9c1;
      max-width: 400px;
      margin-bottom: 2rem;
    }
    nav#toc h3 {
      margin-top: 0;
      color: #287233;
    }
    nav#toc ul {
      list-style: none;
      padding-left: 0;
      margin: 0;
    }
    nav#toc li {
      margin-bottom: 0.6rem;
    }
    nav#toc a {
      color: #287233;
      text-decoration: none;
    }
    nav#toc a:hover,
    nav#toc a:focus {
      text-decoration: underline;
    }

    /* Privacy Policy Sections */
    section.privacy-policy section {
      margin-bottom: 2rem;
    }
    section.privacy-policy h3 {
      margin-top: 0;
      color: #2a5a2f;
      border-bottom: 1px solid #ddd;
      padding-bottom: 0.2rem;
    }

    /* Footer */
    footer {
      background: #222;
      color: #eee;
      text-align: center;
      padding: 1rem 1rem;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      nav button {
        margin-top: 0.5rem;
      }
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      .supplement-list {
        grid-template-columns: 1fr;
      }
      nav#toc {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>G-Xcell Nutrition</h1>
    <nav>
      <button onclick="location.href='login.html'">Login</button>
      <button onclick="location.href='signup.html'">Sign Up</button>
    </nav>
  </header>

  <main>

    <!-- Supplement Store Section -->
    <section aria-labelledby="supplements-title">
      <h2 id="supplements-title">Order a Supplement</h2>
      <div class="supplement-list">

        <article class="supplement" aria-labelledby="supplement-1-title">
          <h3 id="supplement-1-title">G-Xcell Protein Blend</h3>
          <p>High-quality protein powder to fuel your workouts and recovery.</p>
          <table class="nutrition-facts" role="table" aria-describedby="desc-protein-blend">
            <caption id="desc-protein-blend">Nutrition facts per serving</caption>
            <thead>
              <tr>
                <th>Nutrient</th><th>Amount</th>
              </tr>
            </thead>
            <tbody>
              <tr><td>Calories</td><td>120</td></tr>
              <tr><td>Protein</td><td>24g</td></tr>
              <tr><td>Total Fat</td><td>1.5g</td></tr>
              <tr><td>Carbohydrates</td><td>3g</td></tr>
              <tr><td>Sugars</td><td>1g</td></tr>
            </tbody>
          </table>
          <button class="order-btn" onclick="alert('Add to cart coming soon!')">Order Now</button>
        </article>

        <article class="supplement" aria-labelledby="supplement-2-title">
          <h3 id="supplement-2-title">G-Xcell Immune Boost</h3>
          <p>Vitamins and minerals formulated to support your immune system.</p>
          <table class="nutrition-facts" role="table" aria-describedby="desc-immune-boost">
            <caption id="desc-immune-boost">Nutrition facts per serving</caption>
            <thead>
              <tr>
                <th>Nutrient</th><th>Amount</th>
              </tr>
            </thead>
            <tbody>
              <tr><td>Vitamin C</td><td>1000mg (1111% DV)</td></tr>
              <tr><td>Vitamin D</td><td>25mcg (125% DV)</td></tr>
              <tr><td>Zinc</td><td>15mg (136% DV)</td></tr>
              <tr><td>Echinacea Extract</td><td>80mg</td></tr>
            </tbody>
          </table>
          <button class="order-btn" onclick="alert('Add to cart coming soon!')">Order Now</button>
        </article>

      </div>
    </section>

    <!-- Privacy Policy Section -->
    <section class="privacy-policy" aria-labelledby="privacy-policy-title">
      <h2 id="privacy-policy-title">Privacy Policy</h2>

      <!-- Table of Contents for Privacy Policy -->
      <nav id="toc" aria-label="Privacy Policy Table of Contents">
        <h3>Contents</h3>
        <ul>
          <li><a href="#info-we-obtain">Information We Obtain</a></li>
          <li><a href="#automated-info">Collection of Information via Automated Technologies</a></li>
          <li><a href="#communications">Communications Preferences</a></li>
          <li><a href="#disclosure">Disclosure of Personal
login.html
signup.html
alert() i
login.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Login - G-Xcell Nutrition</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .login-container {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 320px;
    }
    h2 {
      margin-top: 0;
      color: #287233;
      text-align: center;
    }
    label {
      display: block;
      margin: 1rem 0 0.3rem;
    }
    input[type="email"],
    input[type="password"] {
      width: 100%;
      padding: 0.5rem;
      box-sizing: border-box;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 1.5rem;
      width: 100%;
      padding: 0.7rem;
      background: #287233;
      color: white;
      border: none;
      font-size: 1rem;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background: #1f5627;
    }
    .signup-link {
      margin-top: 1rem;
      text-align: center;
    }
    .signup-link a {
      color: #287233;
      text-decoration: none;
    }
    .signup-link a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form action="#" method="post">
      <label for="email">Email address</label>
      <input type="email" id="email" name="email" required />
      
      <label for="password">Password</label>
      <input type="password" id="password" name="password" required />
      
      <button type="submit">Log In</button>
    </form>
    <div class="signup-link">
      <p>Don't have an account? <a href="signup.html">Sign Up</a></p>
    </div>
  </div>
</body>
</html>
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
const firebaseConfig = {
  apiKey: "AIzaSyBRzts9EVVTSPBxI11DONXVjQu5coEAgcc",
  authDomain: "gxcellbackened.firebaseapp.com",
  projectId: "gxcellbackened",
  storageBucket: "gxcellbackened.firebasestorage.app",
  messagingSenderId: "645406522729",
  appId: "1:645406522729:web:3838e7b7364a6331cc91f8",
  measurementId: "G-5KK2D5WEGH"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
npm install -g firebase-tools
firebase login
firebase init
firebase deploy
const firebaseConfig = {
  apiKey: "...",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "...",
  appId: "..."
};
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sign Up - G-Xcell Nutrition</title>
  <style>
    /* (Same styling as before) */
    /* Add your styles here */
  </style>
</head>
<body>
  <div class="signup-container">
    <h2>Create an Account</h2>
    <form id="signup-form">
      <label for="email">Email address</label>
      <input type="email" id="email" required />

      <label for="password">Password</label>
      <input type="password" id="password" required />

      <button type="submit">Sign Up</button>
    </form>
    <div id="signup-message" style="color: red; margin-top: 10px;"></div>
    <p>Already have an account? <a href="login.html">Log In</a></p>
  </div>

  <!-- Firebase SDK -->
  <script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-auth-compat.js"></script>

  <script>
    // TODO: Replace the following with your app's Firebase project configuration
    const firebaseConfig = {
      apiKey: "YOUR_API_KEY",
      authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
      // ... other config from Firebase Console
    };

    // Initialize Firebase
    firebase.initializeApp(firebaseConfig);

    // Sign up form handler
    const signupForm = document.getElementById('signup-form');
    const signupMessage = document.getElementById('signup-message');

    signupForm.addEventListener('submit', (e) => {
      e.preventDefault();
      const email = signupForm.email.value;
      const password = signupForm.password.value;firebaseConfig

      auth.createUserWithEmailAndPassword(email, password)
        .then(userCredential => {
          signupMessage.style.color = 'green';
          signupMessage.textContent = 'Account created successfully! You may now log in.';
          signupForm.reset();
        })
        .catch(error => {
          signupMessage.style.color = 'red';
          signupMessage.textContent = error.message;
        });
    });
  </script>
</body>
</html>
"YOUR_API_KEY",
"YOUR_PROJECT_ID"
firebaseConfig
auth.signOut().
auth.signOut().
reset-password.html
# Add changed/new files to Git staging area:
git add .

# Commit changes with message:
git commit -m "Add authentication pages and reset password"

# Push to GitHub:
git push origin main

reset-password.html
var cardElement = elements.create('card');
signup.html
login.html
logout.html
member.html
"YOUR_API_KEY" 
