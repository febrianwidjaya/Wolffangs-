body {
  margin: 0;
  font-family: 'Orbitron', sans-serif;
  background-color: #0d0d0d;
  color: #fff;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 2rem 0;
}

header {
  background-color: #111;
  padding: 1rem 0;
  border-bottom: 2px solid #444;
}

.logo {
  font-size: 1.8rem;
  color: #00ffcc;
}

nav {
  display: flex;
  gap: 1.5rem;
  justify-content: flex-end;
  margin-top: -2rem;
}

nav a {
  color: #fff;
  text-decoration: none;
  transition: 0.3s;
}

nav a:hover {
  color: #00ffcc;
}

.hero {
  text-align: center;
  padding: 100px 0;
  background: url('hero.jpg') center/cover no-repeat;
}

.hero-content {
  background-color: rgba(0, 0, 0, 0.7);
  display: inline-block;
  padding: 2rem;
}

section {
  padding: 4rem 0;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}

.gallery img {
  width: 100%;
  border-radius: 8px;
  transition: transform 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

input, textarea {
  padding: 0.75rem;
  border: none;
  border-radius: 5px;
}

button {
  background-color: #00ffcc;
  color: #000;
  border: none;
  padding: 0.75rem;
  cursor: pointer;
  font-weight: bold;
}

button:hover {
  background-color: #00ccaa;
}

footer {
  background-color: #111;
  text-align: center;
  padding: 1rem;
  border-top: 2px solid #444;
}
