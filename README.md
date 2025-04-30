/* Reset e Variáveis */
:root {
  --cor-primaria: #2563eb; /* Azul */
  --cor-texto: #1e293b;
  --cor-fundo: #f8fafc;
  --cor-destaque: #3b82f6;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background-color: var(--cor-fundo);
  color: var(--cor-texto);
  line-height: 1.6;
}

/* Header */
header {
  background-color: white;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  padding: 1rem;
}

nav a {
  text-decoration: none;
  color: var(--cor-texto);
  margin: 0 1rem;
  font-weight: 500;
}

/* Hero Section */
.hero {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 0 2rem;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.destaque {
  color: var(--cor-primaria);
}

.btn {
  background-color: var(--cor-primaria);
  color: white;
  padding: 0.8rem 1.5rem;
  border-radius: 5px;
  text-decoration: none;
  margin-top: 1rem;
  display: inline-block;
}

/* Seções */
section {
  padding: 5rem 2rem;
  max-width: 1200px;
  margin: 0 auto;
}

h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2rem;
}

/* Habilidades */
.habilidades-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.habilidade-item {
  background: white;
  padding: 1.5rem;
  border-radius: 8px;
  text-align: center;
  width: 120px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.habilidade-item i {
  font-size: 2rem;
  margin-bottom: 0.5rem;
  color: var(--cor-primaria);
}

/* Projetos */
.projeto-card {
  background: white;
  padding: 2rem;
  border-radius: 8px;
  margin-bottom: 2rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Responsivo */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 2rem;
  }
}
