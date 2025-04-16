# 💼 ZezMetrics – SaaS Ágil para Controle de Qualidade Industrial

**A plataforma mais acessível, prática e inteligente para pequenas e médias fábricas monitorarem, analisarem e melhorarem seus processos de qualidade.**

## ⚡ Visão

Oferecer uma solução enxuta e poderosa para controle estatístico da qualidade, com foco em simplicidade, insights automáticos e acessibilidade.

---

## 🛠️ Funcionalidades

- 📋 Registro simples de processos e produtos
- 📈 Cálculo automático de indicadores clássicos: Cp, Cpk, CEP, DPMO, PPM
- 📂 Importação de dados por planilha (.csv / .xlsx)
- 📊 Dashboard interativo com gráficos e relatórios em PDF
- 💸 Plano freemium com opção Pro (R$ 49/mês)

---

## 🔥 Diferenciais

- Foco no pequeno e médio industrial
- Onboarding em 5 minutos
- Marketing direto (WhatsApp, LinkedIn, eventos)
- SaaS escalável e enxuto

---

## 💡 Casos de Uso

- Análise de variação em peças plásticas
- Demonstração de melhoria contínua por consultores
- Monitoramento de estabilidade de processo em tempo real

---

## 🧱 Arquitetura Proposta

### Frontend
- **Framework:** Next.js com Tailwind CSS
- **Gráficos:** Recharts ou Chart.js
- **Exportação de PDF:** react-pdf

### Backend
- **Linguagem:** Python
- **Framework:** Django + Django REST Framework
- **Auth:** JWT com `djoser` ou `simplejwt`
- **Job de Cálculos Estatísticos:** Celery + Redis (para tarefas assíncronas)

### Banco de Dados
- **DB:** PostgreSQL (compatível com nuvem e local)

### Infraestrutura
- **Deploy Inicial (Free):** 
  - Backend: [Render](https://render.com/) ou [Railway](https://railway.app/)
  - Frontend: [Vercel](https://vercel.com/)
  - Banco de Dados: PostgreSQL free do Railway ou Supabase

---

## 🚀 Como Rodar Localmente

### 1. Clone o repositório

git clone https://github.com/Zezoca29/zez-metrics.git
cd zezmetrics
