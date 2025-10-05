# 🎙️ Meeting Summary Generator

Aplicação em Python + Streamlit que utiliza os modelos da OpenAI (Whisper + GPT) para transcrever áudios de reuniões e gerar resumos estruturados automaticamente.

---

## 🚀 Funcionalidades
- Upload de arquivos de áudio **(.mp3 ou .wav)**
- Transcrição automática com **Whisper**
- Resumo estruturado com **GPT** contendo:
  - Resumo executivo
  - Decisões tomadas
  - Próximos passos
- Exportação do resultado em **TXT, DOCX e PDF**

---

## 📂 Estrutura do projeto
```
meeting-summary-generator/
│── app.py              # Código principal do aplicativo
│── requirements.txt    # Dependências
│── README.md           # Documentação do projeto
│── venv/               # Ambiente virtual (ignorado pelo Git)
```

---

## 🔧 Como instalar e executar

### 1. Clone este repositório:
```bash
git clone https://github.com/SabrinaMafe/meeting-summary-generator.git
cd meeting-summary-generator
```

### 2. Crie e ative um ambiente virtual:
```bash
python -m venv venv
```

- **Windows (PowerShell)**:
```bash
venv\Scripts\activate
```

- **Mac/Linux**:
```bash
source venv/bin/activate
```

### 3. Instale as dependências:
```bash
pip install -r requirements.txt
```

### 4. Configure sua API Key da OpenAI:
- **Windows (PowerShell)**:
```bash
$env:OPENAI_API_KEY="sk-sua-chave-aqui"
```

- **Mac/Linux**:
```bash
export OPENAI_API_KEY="sk-sua-chave-aqui"
```

### 5. Execute a aplicação:
```bash
python -m streamlit run app.py
```

O aplicativo abrirá no navegador em:  
👉 [http://localhost:8501](http://localhost:8501)

---

## 🖼️ Demonstração
<img width="1276" height="675" alt="demo1" src="https://github.com/user-attachments/assets/e83455ed-9fcc-42b9-9908-2faf91e85c8e" />
<img width="1227" height="552" alt="demo2" src="https://github.com/user-attachments/assets/f3a829d8-f518-4e4f-a134-0c5f7e0a12d3" />

---

## 🚀 Demo Online
App rodando no **Streamlit Cloud**:  
👉 [Meeting Summary Generator](https://meeting-summary-generator-razfft2ie5fh2ixkggkwzj.streamlit.app/)

---

## 📜 Licença
Este projeto é de uso livre para estudo e prática de integração com IA.
