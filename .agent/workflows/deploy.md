---
description: Deploy rápido no Vercel
---

## Deploy Automático

Toda vez que você fizer push para o branch `main`, o Vercel automaticamente:
1. Detecta o push via webhook do GitHub
2. Executa `npm run build` 
3. Faz deploy da pasta `dist`
4. Deploy completo em 1-3 minutos ⚡

## Deploy Manual (se necessário)

1. **Build local para testar:**
```bash
npm run build
```

2. **Commit e push:**
```bash
git add .
git commit -m "feat: sua mensagem"
git push origin main
```

3. **Acompanhar no Vercel:**
   - Acesse https://vercel.com/dashboard
   - Veja o deployment em progresso
   - Tempo esperado: 1-3 minutos

## Troubleshooting

### Build está lento?
- Verifique se há `pnpm-lock.yaml` (deve ser deletado)
- Use apenas `package-lock.json`

### Deploy falhou?
- Verifique variáveis de ambiente no Vercel:
  - `VITE_SUPABASE_URL`
  - `VITE_SUPABASE_ANON_KEY`

### Rotas não funcionam em produção?
- Verifique se `vercel.json` tem o rewrite para `/index.html`
