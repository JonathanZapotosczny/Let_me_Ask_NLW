# NLW - Let me Ask

Aplicação web que permite gravar áudios e utilizá-los como fonte de contexto para que uma inteligência artificial responda a perguntas com base nas informações faladas.  

Projeto desenvolvido durante a **20ª edição do NLW (Next Level Week)** da **Rocketseat**, trilha intermediária.  

---

## 🔧 Backend

**Tecnologias**  
- Node.js (TypeScript nativo – experimental strip types)  
- Fastify  
- PostgreSQL + pgvector  
- Drizzle ORM  
- Zod  
- Docker  
- Biome  

**Setup**  
```bash
# Clone o repositório
git clone <url-do-repositorio>
cd server

# Crie o arquivo .env
PORT=3333
DATABASE_URL= ?
GEMINI_API_KEY= ?

# Suba o banco de dados
docker-compose up -d

# Instale dependências
npm install

# Migrações
npx drizzle-kit migrate

# (Opcional) Popular banco
npm run db:seed

# Rodar em dev
npm run dev
```

---

## 💻 Frontend

**Tecnologias**  
- React + TypeScript  
- Vite  
- TailwindCSS  
- React Router Dom  
- TanStack React Query  
- Radix UI  
- Shadcn/ui  
- Lucide React  

**Setup**  
```bash
# Instale dependências
npm install

# Rodar em dev
npm run dev
```

**Acesso**
- Backend: **http://localhost:3333** (deve estar rodando antes do frontend)
- Frontend: **http://localhost:5173**

## 💜 Obrigado!

Este projeto só foi possível graças:  
- À **Rocketseat** e toda a equipe da NLW.  
- À comunidade incrível que compartilha conhecimento todos os dias.  
- A você, que chegou até aqui e se interessou pelo projeto! 🚀