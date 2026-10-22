<div align="center">
  <h1> PDA_loc - Geolocalização e Monitoramento de Equipes</h1>
  <p><em>Plataforma web para rastreamento em tempo real de equipes de campo e visualização de infraestrutura de redes de gás.</em></p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet" />
  </p>
</div>

---

##  Sobre o Projeto

O **PDA_loc** é uma aplicação web interativa desenvolvida para otimizar o acompanhamento e a gestão operacional de equipes de manutenção e campo. 

A ferramenta consolida dados de localização geográfica em tempo real integrando a **API do Life360** sobre mapas dinâmicos, sobrepondo o mapeamento técnico das **redes de distribuição de gás no estado de São Paulo**.

---

##  Funcionalidades Principais

-  **Monitoramento de Equipes em Tempo Real:** Visualização da posição exata dos colaboradores em campo via integração com a API do Life360.
-  **Mapeamento de Redes de Gás (SP):** Sobreposição georreferenciada da malha de tubulações e redes de gás para rápida consulta e planejamento de atendimento.
-  **Alternância de Camadas e Estilos de Mapa:** Suporte a múltiplos provedores de mapa (Satélite, Vetorial, Dark Mode, etc.) para melhor leitura técnica.
-  **Interface Leve e Responsiva:** Construída com foco em usabilidade rápida no navegador sem necessidade de softwares pesados de GIS.

---

##  Tecnologias Utilizadas

- **Front-end:** HTML5, CSS3, JavaScript (ES6+).
- **Geolocalização & Mapas:** Leaflet.js / OpenStreetMap (renderização e marcadores interativos).
- **APIs & Dados:**
  - **Life360 API:** Coleta dos dados de telemetria e GPS das equipes.
  - **API / Camadas GIS:** Dados da infraestrutura de tubulações e redes de gás de SP.

---

##  Estrutura do Repositório

```text
├── index.html       # Estrutura principal da aplicação web
├── css/             # Estilização e temas dos controles do mapa
├── js/              # Consumo das APIs, manipulação do mapa e marcadores
└── assets/          # Ícones, marcadores personalizados e recursos estáticos
