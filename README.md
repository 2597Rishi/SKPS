body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #f9f9f9;
  color: #333;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #003366;
  color: white;
  padding: 1rem 2rem;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #ffcc00;
}

section {
  padding: 60px 20px;
  border-bottom: 1px solid #ccc;
}

section h2 {
  color: #003366;
}

footer {
  background: #003366;
  color: white;
  text-align: center;
  padding: 1rem;
}
