# 🚀 Portfólio Gabriel Nunes - AI Specialist & Data Engineer

<div align="center">

![Portfolio Preview](https://img.shields.io/badge/Status-Online-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**[🌐 Ver Site ao Vivo](https://gabriel-boop-deep.github.io)** | **[📧 Contato](mailto:gabrielnbn@hotmail.com)**

*Um portfólio moderno e interativo desenvolvido com tecnologias web puras*

</div>

---

## 📋 Sobre o Projeto

Este é meu portfólio profissional, desenvolvido para apresentar minha jornada como especialista em Inteligência Artificial e Engenharia de Dados. O site foi construído com foco em **design moderno**, **performance** e **experiência do usuário**, utilizando apenas HTML, CSS e JavaScript puro.

### ✨ Características Principais

- 🎨 **Design Futurista**: Interface moderna com gradientes vibrantes e animações suaves
- 📱 **Totalmente Responsivo**: Adaptação perfeita para desktop, tablet e mobile
- ⚡ **Performance Otimizada**: Carregamento rápido sem dependências pesadas
- 🎯 **UX Intuitiva**: Navegação fluida com call-to-actions estratégicos
- 🌈 **Animações Personalizadas**: Efeitos visuais que capturam atenção sem poluir

---

## 🎨 Destaque: Sistema de Background Dinâmico

Um dos principais diferenciais deste portfólio é o **sistema de background animado** criado do zero com CSS e JavaScript puro:

### 🌌 Camadas do Background

```
┌─────────────────────────────────────────┐
│  Layer 1: Gradient Orbs (Blur 120px)   │
│  ├─ Orb Ciano (#00f5ff)                │
│  ├─ Orb Roxo (#7b2ff7)                 │
│  └─ Orb Rosa (#ff006e)                 │
├─────────────────────────────────────────┤
│  Layer 2: Grid Overlay (40x40px)       │
│  └─ Linhas sutis com opacidade 0.03    │
├─────────────────────────────────────────┤
│  Layer 3: Glassmorphism Cards          │
│  └─ backdrop-filter: blur(20px)        │
└─────────────────────────────────────────┘
```

### 🎭 Animações dos Orbs

Cada orb possui uma **animação independente** que cria um efeito de profundidade:

```css
@keyframes float {
    0%, 100% { transform: translate(0, 0) rotate(0deg); }
    33% { transform: translate(50px, -50px) rotate(120deg); }
    66% { transform: translate(-50px, 50px) rotate(240deg); }
}
```

- **Duração**: 20 segundos por ciclo
- **Delays escalonados**: 0s, 5s, 10s para criar movimento assíncrono
- **Blur**: 120px para efeito de profundidade
- **Opacidade**: 0.4 para não sobrepor o conteúdo

### 🔮 Efeito Glassmorphism

Todos os cards utilizam a técnica moderna de **glassmorphism**:

```css
background: rgba(255, 255, 255, 0.02);
backdrop-filter: blur(20px);
border: 1px solid rgba(0, 245, 255, 0.1);
```

Isso cria:
- ✅ Sensação de profundidade
- ✅ Leitura confortável do conteúdo
- ✅ Estética futurista e profissional
- ✅ Integração harmoniosa com o background

---

## 🛠️ Tecnologias Utilizadas

### Core
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização avançada com Grid, Flexbox e animações
- **JavaScript**: Interatividade e animações dinâmicas

### Bibliotecas Externas
- **Font Awesome 6.4.0**: Ícones vetoriais

### Técnicas Implementadas
- 🎯 CSS Grid & Flexbox para layouts responsivos
- 🎨 Gradientes lineares e radiais personalizados
- ⚡ CSS Animations & Transitions
- 🔍 Backdrop Filter para efeitos de desfoque
- 📐 Custom Properties (CSS Variables)
- 🎪 Keyframes complexos para animações fluidas

---

## 📂 Estrutura do Projeto

```
portfolio/
│
├── index.html              # Arquivo principal
├── profile.jpeg            # Foto de perfil
├── ai-image-1.jpg         # Background card 1
├── ai-image-2.jpg         # Background card 2
├── ai-image-3.jpg         # Background card 3
└── README.md              # Este arquivo
```

---

## 🚀 Como Usar

### 1️⃣ Clonar o Repositório

```bash
git clone https://github.com/Gabriel-boop-deep/Gabriel-boop-deep.github.io.git
cd Gabriel-boop-deep.github.io
```

### 2️⃣ Abrir Localmente

Basta abrir o arquivo `index.html` em qualquer navegador moderno:

```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

### 3️⃣ Deploy no GitHub Pages

1. Faça push para o repositório `seu-usuario.github.io`
2. Acesse: `https://seu-usuario.github.io`
3. Pronto! Seu site está online 🎉

---

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| **Ciano** | `#00f5ff` | Primária, destaques, links |
| **Roxo** | `#7b2ff7` | Secundária, gradientes |
| **Rosa** | `#ff006e` | Accent, call-to-actions |
| **Dark** | `#0a0e27` | Background secundário |
| **Darker** | `#050810` | Background principal |

---

## 📊 Seções do Portfólio

### 🏠 Hero Section
- Introdução pessoal
- Estatísticas de carreira
- Call-to-action para projetos e contato
- Foto profissional com frame animado

### 💼 Projetos
1. **BANVIC Analytics Project**
   - Modern Data Stack
   - Pipeline ETL completo
   - dbt, SQL, Python

2. **Classificação de Imagens CNN**
   - Deep Learning com TensorFlow
   - Redes Neurais Convolucionais
   - Data Augmentation

3. **DBT BV Monitoring**
   - Data Quality
   - Testes automatizados
   - Observabilidade de dados

### 🎯 Skills
- Machine Learning
- Data Engineering
- Python & SQL
- Cloud & DevOps
- Data Analytics
- Deep Learning

### 📬 Contato
- LinkedIn
- GitHub
- E-mail direto com template pré-configurado

---

## 🔧 Personalização

Para adaptar este portfólio para você:

### 1. Informações Pessoais
Edite as seguintes seções em `index.html`:

```html
<!-- Nome e título -->
<h1>Seu Nome</h1>
<p class="subtitle">Sua Profissão</p>

<!-- Bio -->
<p>Sua descrição profissional...</p>

<!-- Estatísticas -->
<span class="stat-number">X+</span>
<span class="stat-label">Sua Métrica</span>
```

### 2. Projetos
Adicione seus projetos no formato:

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-seu-icone"></i>
    </div>
    <h3>Nome do Projeto</h3>
    <p>Descrição...</p>
    <div class="tech-stack">
        <span class="tech-tag">Tech1</span>
        <span class="tech-tag">Tech2</span>
    </div>
    <a href="github.com/seu-repo" class="project-link">
        Ver no GitHub <i class="fas fa-arrow-right"></i>
    </a>
</div>
```

### 3. Cores
Modifique as CSS variables no topo do `<style>`:

```css
:root {
    --primary: #sua-cor;
    --secondary: #sua-cor;
    --accent: #sua-cor;
}
```

---

## 📈 Performance

- ✅ **100% HTML/CSS/JS puro** - Sem frameworks pesados
- ✅ **Imagens otimizadas** - Formatos modernos
- ✅ **CSS minificável** - Código organizado
- ✅ **Lazy loading ready** - Preparado para otimizações
- ✅ **Mobile-first** - Design responsivo desde o início

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Se você tem sugestões de melhorias:

1. Faça um Fork do projeto
2. Crie uma Branch (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a Branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👨‍💻 Autor

<div align="center">

**Gabriel Nunes**

AI Specialist & Data Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-nunes-barbosa-nogueira/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gabriel-boop-deep)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabrielnbn@hotmail.com)

</div>

---

## 🙏 Agradecimentos

- **Font Awesome** pelos ícones incríveis
- **Google Fonts** (caso adicione no futuro)
- **Comunidade Open Source** pela inspiração

---

<div align="center">

### ⭐ Se gostou do projeto, deixe uma estrela!

**Desenvolvido com 💙 e muito ☕**

</div>
