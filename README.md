# 🚀 Capiva LinkedIn AI Poster — Automação com n8n

> Automação completa para curadoria, geração e postagem de conteúdos no LinkedIn da página da Capiva usando n8n, RSS, GPT-4o e aprovação humana.

---

## 🧠 Visão Geral

Este projeto automatiza a criação e publicação de posts semanais no LinkedIn da Capiva com as seguintes etapas:

- Coleta de artigos relevantes sobre IA
- Curadoria com IA (seleção dos 5 melhores)
- Geração de texto com linguagem personalizada
- Aprovação humana por email
- Publicação automática no LinkedIn da página Capiva

---

## 🔧 Ferramentas Utilizadas

| Ferramenta           | Finalidade                                                       |
|----------------------|------------------------------------------------------------------|
| [n8n](https://n8n.io) | Orquestrador principal da automação                             |
| OpenAI (GPT-4o)      | Geração de texto com estilo personalizado                        |
| RSS Feed (VentureBeat)| Fonte de notícias da semana                                     |
| Gmail API            | Disparo de aprovação com formulário interativo                  |
| LinkedIn API         | Postagem automática na página da Capiva                         |

---

## 🧱 Arquitetura do Fluxo

1. Trigger manual ou agendado
