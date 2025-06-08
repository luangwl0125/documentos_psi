# 🧠 Assistente para Elaboração de Documentos Psicológicos

Este é um sistema desenvolvido para auxiliar psicólogos na elaboração de documentos psicológicos, seguindo as diretrizes da Resolução CFP nº 06/2019.

## 📋 Funcionalidades

O sistema permite a elaboração dos seguintes documentos:
- Declaração Psicológica
- Atestado Psicológico
- Relatório Psicológico
- Laudo Psicológico
- Parecer Psicológico

## 🚀 Tecnologias Utilizadas

- Python 3.x
- Streamlit
- OpenAI API
- PyPDF2
- python-docx
- Pillow
- pytesseract

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/luangwl0125/documentos_psi.git
cd documentos_psi
```

2. Crie um ambiente virtual e ative-o:
```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # Linux/Mac
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Configure as variáveis de ambiente:
- Crie um arquivo `.env` na raiz do projeto
- Adicione sua chave da API OpenAI:
```
OPENAI_API_KEY=sua_chave_aqui
```

## 🔧 Uso

1. Ative o ambiente virtual:
```bash
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # Linux/Mac
```

2. Execute o aplicativo:
```bash
streamlit run app.py
```

3. Acesse o aplicativo em seu navegador (geralmente em http://localhost:8501)

## 🔒 Segurança e Ética

Este sistema foi desenvolvido seguindo:
- Resolução CFP nº 06/2019
- Código de Ética Profissional do Psicólogo
- Lei Geral de Proteção de Dados (LGPD)
- Resolução CFP nº 11/2018

## ⚠️ Importante

Os documentos gerados devem ser revisados, validados e assinados por psicólogo(a) devidamente inscrito(a) no CRP. O sistema é uma ferramenta de apoio e não substitui o julgamento profissional.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Contribuição

Contribuições são bem-vindas! Por favor, sinta-se à vontade para abrir uma issue ou enviar um pull request. 