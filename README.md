# nughmaan-portfolio
Welcome to my Portfolio!  I'm Nughmaan, passionate about  travel and tourism (Ninthware),  Here you’ll find:  My top skills in electronics and tourism  Projects like Mini Tesla Coil, Solar Fast Charger, and Travel Promotion Projects  My passion for learning, innovation, and creativity!. Thank you for visiting!
[nughmaan_portfolio.zip](https://github.com/user-attachments/files/19929428/nughmaan_portfolio.zip)
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background: #f0f2f5;
  color: #333;
}

.header {
  text-align: center;
  background: #4CAF50;
  padding: 2rem 1rem;
  color: white;
}

.profile img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid white;
  margin-bottom: 10px;
}

.profile h1 {
  margin: 10px 0 5px;
}

nav {
  margin-top: 1rem;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

nav a:hover {
  text-decoration: underline;
}

main {
  padding: 2rem 1rem;
  max-width: 900px;
  margin: auto;
}

h2 {
  text-align: center;
  color: #4CAF50;
  margin-bottom: 1rem;
}

section {
  margin-bottom: 3rem;
}

.card-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 1rem;
}

.card {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  text-align: center;
  font-weight: bold;
  transition: transform 0.3s, background 0.3s;
}

.card:hover {
  transform: translateY(-8px);
  background: #e8f5e9;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #ddd;
}

.fade-in {
  animation: fadeIn 1.5s ease-in;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
