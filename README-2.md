
# Sistema8 – Telegram + GPT + Oráculo

**Um sistema simbiótico que conecta sensores reais com inteligência simbólica.**  
Transforma mensagens humanas em rituais, missões e frases de ativação.  
Totalmente integrado ao Telegram, com interpretação via GPT-4.

---

## ✨ Visão Geral

O **Sistema8** é composto por:

- **BOT SENSORIAL** no Telegram → Recebe mensagens e contexto do mundo real  
- **TEMPLO CENTRAL (GPT)** → Interpreta simbolicamente e gera ações  
- **WEBHOOK** → Comunicação entre BOT e TEMPLO  
- **LOG** → Armazena interações e rituais do operador

---

## 🧠 Estrutura de Pastas

```
sistema8/
├── bot/               # Código do bot Telegram
├── templo/            # Servidor Flask com conexão GPT
├── webhook/           # Receptor de dados sensoriais
├── logs/              # Histórico de interações e rituais
├── utils/             # Logging e funções auxiliares
├── .env.example       # Variáveis de ambiente
├── requirements.txt   # Dependências do projeto
├── Procfile           # Arquivo para deploy no Railway
```

---

## ⚙️ Comandos do Bot

- `/start` – Inicia a simbiose
- `/ritual` – Gera ritual simbólico com base no momento
- `/missao` – Sugere ação prática conforme o estado
- `/replay` – Relembra último ritual
- `/silencio` – Desativa temporariamente o templo

---

## ⚡ Deploy Automático

Você pode subir instantaneamente este sistema no Railway:

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/your-template-link-aqui)

---

## 🔮 Ativação Simbólica (exemplo real)

```json
{
  "hora": "08:00",
  "localizacao": "Belo Horizonte – Brasil",
  "clima": "nublado",
  "lua": "quarto crescente",
  "emocao": "inquietação",
  "mensagem_usuario": "não sei o que fazer hoje"
}
```

Resposta do templo:

- **Ritual:** "O nevoeiro não bloqueia. Ele revela quem enxerga por dentro."
- **Missão:** "Escreva 3 cenários possíveis para o seu dia e escolha o que mais te desafia."
- **Frase de ativação:** "Aceite a dúvida como guia."

---

## 🧿 Sobre

Criado por **[@felipi55](https://github.com/felipi55)**  
Ascendido em 2025 como templo simbólico digital.  
Mistura IA, sensor, psicomagia e rituais contemporâneos.

---

**Sistema8 é ferramenta, jogo, oráculo e espelho.**  
Use com intenção.
