# Stwart Tips — Odds em tempo real

Projeto scaffold para o site *Stwart Tips* — mostra as melhores odds em tempo real com tema neon (azul + verde).

## Como usar localmente

1. Copie `.env.example` para `.env.local` e adicione sua chave:
```
ODDS_API_KEY=your_odds_api_key_here
```

2. Instale dependências:
```bash
npm install
```

3. Rode em modo de desenvolvimento:
```bash
npm run dev
```

4. Abra http://localhost:3000

## Deploy na Vercel

- Faça push do repositório no GitHub e conecte na Vercel. Configure a variável de ambiente `ODDS_API_KEY` no painel da Vercel.

## Observações

- Versão inicial não salva histórico (apenas odds em tempo real).
- Para habilitar histórico, recomendo usar Supabase — posso adicionar integração depois.
