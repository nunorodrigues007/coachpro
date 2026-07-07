# CoachPro — High Performance Fitness Coach

App PWA de coaching de alta performance. Dashboard semanal com análise IA baseada nos dados Hume Health.

## Funcionalidades

- 📊 Check-in semanal com todos os dados da balança Hume Health
- 🤖 Análise IA via Claude API (automático em Claude.ai, API key opcional no Vercel)
- 📋 Plano nutricional completo com carb cycling (HIGH/MEDIUM/LOW)
- 💪 Plano de treino semanal (calistenia + KB + skipping)
- 📈 Histórico de progresso com gráficos
- 📱 PWA installável como ícone no iPhone/Android

## Deploy no Vercel

```bash
git init
git add .
git commit -m "CoachPro v1"
gh repo create coachpro --public --push
```

Depois importa no Vercel → Deploy.

## iPhone Icon

1. Abre o URL no Safari
2. Partilhar → Adicionar ao Ecrã de Início
3. Nome: CoachPro

## API Key (opcional)

Em Configurações da app → Anthropic API Key → `sk-ant-...`
Necessária apenas no Vercel. No Claude.ai funciona automaticamente.
