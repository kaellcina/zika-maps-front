# 🦟 ZikaMaps

<div align="center">

<img src="./logo%20zikamaps.png" alt="ZikaMaps Logo" width="220"/>

**Plataforma cidadã de monitoramento e mapeamento de focos do *Aedes aegypti* em Manaus — AM**

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-4AADA8?style=flat-square)](https://github.com/kaellcina/zika-maps-front)
[![Licença](https://img.shields.io/badge/licença-MIT-4AADA8?style=flat-square)](LICENSE)
[![TCC](https://img.shields.io/badge/TCC-ADS%20%7C%20Fametro-4AADA8?style=flat-square)](#)
[![Cidade](https://img.shields.io/badge/cidade-Manaus%2C%20AM-4AADA8?style=flat-square)](#)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)

[Reportar Bug](https://github.com/kaellcina/zika-maps-front/issues) · [Solicitar Feature](https://github.com/kaellcina/zika-maps-front/issues)

</div>

---

## 📋 Sobre o Projeto

O **ZikaMaps** é uma plataforma web colaborativa de monitoramento e mapeamento da proliferação de mosquitos causadores de arboviroses, desenvolvida como Trabalho de Conclusão de Curso (TCC) no curso de **Análise e Desenvolvimento de Sistemas (ADS)** no Centro Universitário Fametro — Manaus, AM.

O sistema público de notificação (SINAN) é passivo e depende exclusivamente de profissionais de saúde, gerando subnotificação massiva de focos do *Aedes aegypti* — mosquito transmissor da Dengue, Zika e Chikungunya.

O ZikaMaps busca transformar o próprio morador em agente ativo da vigilância sanitária do seu bairro: qualquer cidadão pode registrar uma ocorrência pelo navegador, utilizando geolocalização automática e foto como evidência.

---

## ✨ Principais Funcionalidades

- 📍 **Geolocalização automática** — captura a posição do cidadão via GPS ao registrar um foco, sem necessidade de inserir endereço manualmente.
- 🗺️ **Mapa de calor em tempo real** — visualização interativa via Leaflet.js sobre OpenStreetMap, mostrando a densidade de focos por bairro.
- 📸 **Registro com foto** — o cidadão tira ou envia uma foto do criadouro como evidência, aumentando a confiabilidade das denúncias.
- 🏥 **Painel do Agente Sanitário** — interface exclusiva para agentes de vigilância confirmarem, descartarem e marcarem focos como resolvidos.
- 📊 **Histórico de denúncias** — cada cidadão acompanha o status de todas as suas denúncias em tempo real.

---

## 🎬 Demonstração

### 📸 Screenshots

<div align="center">

| Tela de Login | Mapa de Focos |
|:---:|:---:|
| ![Tela de Login](./tela%20de%20login.png) | ![Mapa de Focos](./mapa%20de%20focos.png) |

| Registrar Denúncia | Minhas Denúncias |
|:---:|:---:|
| ![Registrar Denúncia](./registrador%20de%20den%C3%BAncias.png) | ![Minhas Denúncias](./minhas%20den%C3%BAncias.png) |

</div>

### 🎥 Vídeo Demonstrativo

> [▶️ VÍDEO DEMONSTRATIVO](https://youtu.be/tLx0F75abqw)

---

## 🛠️ Tecnologias Utilizadas

### Design & Prototipação

[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)](https://figma.com)
[![Lovable](https://img.shields.io/badge/Lovable%20Dev-FF6B6B?style=flat-square)](https://lovable.dev)

### Front-end

[![React](https://img.shields.io/badge/React%2018-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Leaflet](https://img.shields.io/badge/Leaflet.js-199900?style=flat-square&logo=leaflet&logoColor=white)](https://leafletjs.com)

### Back-end & Banco de Dados

[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Python](https://img.shields.io/badge/Python%203.11-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)

### Ferramentas & Infraestrutura

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com)

---

## 🚀 Começando

Este repositório contém o **front-end** do ZikaMaps. Para rodar localmente, você precisa do Node.js e da API FastAPI do projeto em execução.

### 📦 Pré-requisitos

- [Node.js](https://nodejs.org/) `>= 18.x`
- [npm](https://npmjs.com/) ou [Bun](https://bun.sh/)
- [Git](https://git-scm.com/)
- API FastAPI do ZikaMaps em execução (ex.: `http://127.0.0.1:5000`)

### 💻 Instalação

#### 1. Clone o repositório

```bash
git clone https://github.com/kaellcina/zika-maps-front.git
```

#### 2. Acesse a pasta do projeto

```bash
cd zika-maps-front
```

#### 3. Instale as dependências

```bash
npm install
```
#### 4. Configure as variáveis de ambiente

Copie o arquivo de exemplo:

```bash
cp .env.example .env
```

#### 5. Execute o projeto

Com npm:

```bash
npm run dev
```

Ou com Bun:

```bash
bun dev
```

#### 6. Acesse no navegador

```text
http://localhost:8080
```
---

## 📖 Como Usar

### 👤 Perfil Cidadão

1. Cadastre-se ou faça login.
2. Acesse o **Mapa** para visualizar os focos registrados.
3. Clique em **Denunciar**.
4. Permita o acesso à localização.
5. Tire ou envie uma foto do foco.
6. Adicione uma descrição, se necessário.
7. Confirme o envio.
8. Acompanhe a denúncia em **Minhas Denúncias**.

### 🏥 Perfil Agente

1. Faça login com sua conta de agente.
2. Acesse o **Painel de Gestão**.
3. Analise as denúncias recebidas.
4. Confirme ou descarte a ocorrência.
5. Após a intervenção, marque o foco como **Resolvido**.
---

## 🗂️ Estrutura de Pastas

```text
zika-maps-front/
├── public/
├── src/
│   ├── components/
│   ├── hooks/
│   ├── lib/
│   └── pages/
├── .env.example
├── package.json
├── vite.config.ts
├── tailwind.config.ts
├── tsconfig.json
└── README.md
```

---

## 🧪 Testes
O projeto utiliza **Vitest** para testes unitários e **Playwright** para testes end-to-end.

### Testes unitários

```bash
npm run test
```

### Modo watch

```bash
npm run test:watch
```
---

## 🔗 Repositórios Relacionados

**Front-end:**  
https://github.com/kaellcina/zika-maps-front

**Back-end:**  
https://github.com/kaellcina/zika-maps-back
---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**.

Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👥 Equipe

| Nome | Papel | GitHub |
|---|---|---|
| **Kaell Soares Calacina** | Desenvolvedor & Documentador | [@kaellcina](https://github.com/kaellcina) |
| **Ana Lívia da Costa Silva** | Documentadora & Analista | [@liviacosttaa](https://github.com/liviacosttaa) |
| **Vitória Santos de Azevedo** | Testadora & Documentadora | [@csvick](https://github.com/csvick) |
| **Luiz Henrique Moutinho Laranjeira** | Documentador & Analista | [@luizhmoutinho](https://github.com/luizhmoutinho) |
| **João Etto de Souza Gomes** | Designer & Documentador | [@JoaoEtto](https://github.com/JoaoEtto) |

**Orientadora:** Luana Magalhães Leal

---

## 🙏 Agradecimentos

- À professora orientadora **Luana Magalhães Leal** pelo suporte durante o desenvolvimento do TCC.
- À **Fametro** pela estrutura acadêmica e oportunidade de desenvolver o projeto.
- Ao [OpenStreetMap](https://www.openstreetmap.org/) pela base cartográfica gratuita e aberta.
- Ao [Leaflet.js](https://leafletjs.com/) pela biblioteca de mapas interativos.

---

<div align="center">

**Manaus, AM · TCC — ADS Fametro 2026**

Feito com ❤️ pela equipe ZikaMaps.

</div>
