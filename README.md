<div align="center">

# Edmir Soares
### Mobile Developer · React Native · Node.js

*Construindo produtos escaláveis, acessíveis e resilientes - do backend à interface.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-edmir--soares-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/edmir-soares)
[![GitHub](https://img.shields.io/badge/GitHub-EdmirSoares-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/EdmirSoares)

</div>

---

## Sobre mim

Desenvolvedor mobile com foco em React Native, migrando também para Flutter, construindo aplicativos de alta performance para cenários de conectividade instável, arquiteturas offline-first, sincronização de dados e integrações nativas.



Tenho histórico em produtos mobile de alta criticidade: aplicações bancárias (mobile + web), sistemas urbanos com geolocalização em tempo real e apps de campo com operação offline. Sólido em Clean Architecture, persistência local (SQLite, MMKV, Drift) e publicação/ciclo de vida de apps nas lojas.



Como venho de uma trajetória full-stack, também domino a construção de APIs e de serviços back-end (Node.js, Express, Fastify, NestJS, PostgreSQL, Prisma/Drizzle, Docker, JWT/OAuth). Isso me dá uma vantagem real em mobile: entendo o contrato de API de ponta a ponta, o que ajuda a resolver problemas de integração, performance e segurança sem depender só do time de backend.



Meu diferencial é a combinação entre engenharia e design: conduzi redesigns completos com processo estruturado de UI/UX (heurísticas de Nielsen, design tokens, WCAG 2.1), resultando em produtos mobile mais acessíveis e consistentes entre plataformas.



Publiquei pesquisa científica internacional (WEBIST 2025 e 2026) sobre UI/UX e acessibilidade e ministro minicursos sobre Clean Architecture e React Native offline-first.



Tenho buscado ir além da implementação: entender onde a IA acelera o desenvolvimento mobile e onde ainda exige julgamento humano na arquitetura, nos trade-offs de performance offline-first e nas decisões de UX. Minha trajetória de designer gráfico a desenvolvedor mobile reflete uma capacidade real de adaptação técnica, não só um histórico de mudanças.

---

## Stack principal

### Mobile
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-20232A?style=flat-square&logo=flutter&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3178C6?style=flat-square&logo=dart&logoColor=white)
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
