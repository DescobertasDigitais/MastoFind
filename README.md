# MastoFind 🔍

![banner](https://files.catbox.moe/xnrf73.png)

Uma ferramenta OSINT para busca e análise de perfis na rede social Mastodon.

## ✨ Funcionalidades

- **Lookup detalhado** de perfis Mastodon
- **Saída colorida** no terminal para fácil leitura
- **Exportação para JSON** para análise posterior

## 📦 Requisitos

- Python 3.8+
- Gerenciador de pacotes `pip`
- Conexão com internet

## 🛠️ Instalação

1. Clone o repositório:
```bash
git clone https://github.com/DescobertasDigitais/MastoFind.git
cd MastoFind
```

2. Crie um ambiente virtual (recomendado):
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

## 📋 Dependências
```
requests==2.32.4
termcolor==3.1.0
```

## 🚀 Como Usar

### Busca básica:
```bash
python mastofind.py nome_de_usuario
```

### Busca com exportação para JSON:
```bash
python mastofind.py nome_de_usuario -o perfil.json
```


## 🖥️ Saída de Exemplo
![teste](https://files.catbox.moe/75it93.png) 

## 🌐 API Utilizada
A ferramenta consome o endpoint público:
```
GET https://mastodon.social/api/v1/accounts/lookup
```

## 🤝 Contribuição
Contribuições são bem-vindas!

## 📄 Licença
Distribuído sob a licença MIT.
