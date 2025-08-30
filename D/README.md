# 📊 Análise de Localização para Centro de Distribuição - Nordeste

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

Dashboard interativo para análise comparativa entre Recife e Salvador para implantação de um Centro de Distribuição no Nordeste brasileiro.

## 🎯 Sobre o Projeto

Este projeto apresenta uma análise estratégica comparando as cidades de Recife e Salvador como possíveis localizações para um novo Centro de Distribuição na região Nordeste. A ferramenta fornece insights baseados em dados reais sobre custos, logística, demografia e potencial econômico.

## ✨ Funcionalidades

- **📊 Métricas Principais**: Comparativo de população, custos, tempo de entrega e PIB
- **💰 Análise Econômica**: Análise detalhada de custos e projeção de economia
- **🗺️ Mapa Interativo**: Visualização geográfica com área de influência
- **📈 Análise Comparativa**: Gráficos de radar e tempo de entrega
- **🎯 Recomendação**: Análise final com score estratégico

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**
- **Streamlit** - Framework para dashboard web
- **Pandas** - Manipulação e análise de dados
- **Plotly** - Gráficos interativos
- **Folium** - Mapas interativos
- **Matplotlib** - Visualização de dados

## 🚀 Como Executar Localmente

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/analise-localizacao-cd.git
cd analise-localizacao-cd
```

2. **Instale as dependências**:
```bash
pip install -r requirements.txt
```

3. **Execute a aplicação**:
```bash
streamlit run app.py
```

4. **Acesse o dashboard**:
Abra seu navegador e vá para `http://localhost:8501`

### Instalação Rápida

```bash
# Criar ambiente virtual (opcional)
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
.\venv\Scripts\activate  # Windows

# Instalar dependências
pip install streamlit pandas plotly folium matplotlib

# Executar
streamlit run app.py
```

## 🌐 Deploy na Nuvem

### Opção 1: Streamlit Community Cloud (Recomendado)

1. Faça push do código para um repositório GitHub
2. Acesse [share.streamlit.io](https://share.streamlit.io/)
3. Conecte sua conta GitHub
4. Selecione o repositório e branch
5. Clique em "Deploy"

### Opção 2: Hugging Face Spaces

1. Crie uma conta em [Hugging Face](https://huggingface.co/)
2. Crie um novo Space do tipo Streamlit
3. Faça upload dos arquivos ou conecte com GitHub

## 📁 Estrutura do Projeto

```
analise-localizacao-cd/
│
├── app.py                 # Aplicação principal Streamlit
├── requirements.txt       # Dependências do projeto
├── README.md             # Este arquivo
└── assets/               # (Opcional) Imagens e arquivos estáticos
    └── favicon.ico
```

## 📊 Fontes de Dados

- **IBGE** - Dados populacionais e econômicos
- **Ministério dos Transportes** - Dados de infraestrutura logística
- **Análise de mercado** - Dados imobiliários e operacionais
- **Geolocalização** - Coordenadas e distâncias entre cidades

## 🎨 Personalização

Para personalizar a análise para outras cidades:

1. Edite os dados em `load_data()` no arquivo `app.py`
2. Atualize as coordenadas no mapa
3. Ajuste as métricas conforme necessário

## 🤝 Contribuição

Contribuições são bem-vindas! Siga os passos:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Seu Nome - [Seu GitHub](https://github.com/seu-usuario)

## 🙋‍♂️ Suporte

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para:

- Abrir uma [issue](https://github.com/seu-usuario/analise-localizacao-cd/issues)
- Entrar em contato por email: seu.email@exemplo.com

---

⭐️ Se este projeto foi útil, deixe uma estrela no GitHub!