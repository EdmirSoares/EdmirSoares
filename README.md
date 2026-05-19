<div align="center">

# Edmir Soares
### Full-Stack Developer · React Native · Node.js

*Construindo produtos escaláveis, acessíveis e resilientes - do backend à interface.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-edmir--soares-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/edmir-soares)
[![GitHub](https://img.shields.io/badge/GitHub-EdmirSoares-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/EdmirSoares)
[![Email](https://img.shields.io/badge/Email-edmir.soares@icloud.com-black?style=flat-square&logo=apple&logoColor=white)](mailto:edmir.soares@icloud.com)

</div>

---

## Sobre mim

Sou desenvolvedor Full-Stack com foco em Mobile, atuando no ciclo completo do produto: APIs REST, modelagem de banco de dados, contêinerização com Docker e desenvolvimento de interfaces mobile e web de alta performance com TypeScript.

Tenho histórico em produtos de alta criticidade, **banking**, **sistemas urbanos com geolocalização em tempo real** e **arquiteturas offline-first** para ambientes com conectividade instável. Combino engenharia com design: sou formado em Design Gráfico e pesquisador científico em UI/UX e acessibilidade, com **dois artigos publicados internacionalmente no WEBIST 2025**.

- 🏦 Desenvolvedor Mobile na **Atos Capital** - apps de banking (React Native + React.js)
- 🏙️ Desenvolvedor Mobile na **Pop Tech** - ecossistema de apps urbanos críticos (React Native + Expo)
- 🎓 Monitor de Desenvolvimento Web - **Universidade Estácio de Sá**
- 📍 Aracaju, SE - Brasil · Disponível para trabalho remoto

---

## Stack principal

### Mobile
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Web
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

### Arquitetura & Qualidade
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-6C63FF?style=flat-square)
![SOLID](https://img.shields.io/badge/SOLID-blueviolet?style=flat-square)
![Offline First](https://img.shields.io/badge/Offline--First-FF6B35?style=flat-square)
![WCAG](https://img.shields.io/badge/WCAG%202.1-005A9C?style=flat-square)

---

## Projetos em destaque

### [TradeFlow - Simulador de Trading Bitcoin Full-Stack](https://github.com/EdmirSoares/monorepo-tradeflow)
> Monorepo fullstack com backend Laravel 11 + app React Native (Expo). Usuários operam compra/venda de BTC com preços de mercado em tempo real.

**Destaques técnicos:**
- Prevenção de gasto duplo com locking em duas camadas: Redis (`Cache::lock`) + `lockForUpdate()` dentro de `DB::transaction` no PostgreSQL
- Precisão financeira com `bcmath` e colunas `DECIMAL(20,8)` - nunca `float`
- Cache de preço BTC no Redis (TTL 30s) com polling via React Query (10s)
- Tratamento tipado de erros de domínio (`InsufficientFundsException`) com HTTP 422

`Laravel 11` `PHP` `PostgreSQL` `Redis` `Docker` `Nginx` `React Native` `Expo` `TypeScript` `Sanctum`

---

### [Clody - App de Clima com Claymorphism e Acessibilidade](https://github.com/EdmirSoares/clody-app)
> App mobile de previsão do tempo com design claymorphism (Skia + Inner Shadow), busca de cidades com debounce e histórico local persistido em SQLite.

**Destaques técnicos:**
- Gerenciamento de estado com Zustand + TanStack Query: queries condicionais ativadas após GPS disponível
- Persistência com Expo SQLite + Drizzle ORM: histórico LRU (máx. 2 entradas) com upsert de timestamp
- Acessibilidade nativa completa: `accessibilityRole`, `accessibilityLabel` e `accessibilityHint` em todos os elementos
- Tipografia responsiva via `useFontScale` (85%–120% baseado na largura do dispositivo)

`React Native` `Expo` `TypeScript` `Zustand` `TanStack Query` `SQLite` `Drizzle ORM` `Skia` `Zod` `Expo Router`

---

### [IoT MQTT Controller - Controle remoto de dispositivos em tempo real](https://github.com/EdmirSoares/virtual_valve_mqtt_controller)
> App Flutter para controle remoto de dispositivos físicos via protocolo MQTT, com foco em baixa latência e alta confiabilidade.

`Flutter` `Dart` `MQTT` `Clean Architecture` `Bloc/Cubit`

---

### [Gerenciamento de Operações Agrícolas](https://github.com/EdmirSoares/gerenciamento_agricola)
> App Flutter para gestão de operações agrícolas em campo, com persistência local robusta e arquitetura modular escalável.

`Flutter` `Dart` `Drift ORM` `Bloc/Cubit` `Clean Architecture` `REST API`

---

## Publicações científicas

| Conferência | Título |
|-------------|--------|
| WEBIST 2025 | *Exploring the Impact of UI/UX on Trust in E-commerce* |
| WEBIST 2025 | *A Framework for Accessible Web Design in Low-Bandwidth Environments* |

---

## Estatísticas

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=EdmirSoares&theme=tokyonight&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=EdmirSoares&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Open to remote opportunities - Brasil e internacional*

</div>
