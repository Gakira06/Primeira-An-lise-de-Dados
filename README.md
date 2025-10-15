<img src="/img/Captura de tela 2025-10-14 170926.png" width="800"/>

# 📊 Dashboard Interativo de Análise de Salários

## 📖 Descrição do Projeto

Um dashboard web interativo construído em Python com a biblioteca Streamlit, projetado para a exploração e análise de dados salariais na área de tecnologia. O projeto ingere os dados utilizando a biblioteca Pandas para tratamento e manipulação, e apresenta as informações de forma visual e intuitiva através de gráficos dinâmicos gerados com Plotly.

A aplicação permite que o usuário filtre os dados por múltiplos critérios, como ano, nível de senioridade, tipo de contrato e tamanho da empresa, recalculando e atualizando as visualizações em tempo real. Este projeto demonstra habilidades práticas em todo o ciclo de vida de um projeto de dados, desde a manipulação e análise até a criação de uma ferramenta de visualização de dados (Data Viz) acessível e funcional.

> **Dica:** Para adicionar a imagem, tire um print do seu dashboard funcionando, adicione o arquivo ao seu repositório (em uma pasta `img`, por exemplo) e substitua `URL_DA_SUA_IMAGEM_AQUI.png` pelo nome do seu arquivo.

## 👨‍💻 Autor

- Gabriel Akira Borges Kiyohara

## 🌐 Links

- **Repositório GitHub:** https://github.com/Gakira06/Primeira-An-lise-de-Dados.git

## ⚙️ Tecnologias Utilizadas

### Linguagem & Bibliotecas Principais

- **Python**
- **Streamlit** (Framework para a criação do dashboard web)
- **Pandas** (Manipulação e análise de dados)
- **Plotly** (Criação de gráficos interativos)

## 🏗️ Arquitetura do Projeto

A aplicação foi desenvolvida como um script Python único (`app.py`) que é executado e servido pelo Streamlit.

- **Carregamento de Dados:** Os dados são carregados de um CSV hospedado remotamente usando `pandas.read_csv`.
- **Interface Interativa:** A barra lateral de filtros e os elementos do dashboard são criados com os componentes nativos do Streamlit.
- **Filtragem Dinâmica:** Os filtros selecionados pelo usuário são aplicados diretamente ao DataFrame do Pandas, que então serve de base para os gráficos.
- **Visualização de Dados:** Os gráficos (barras, histograma, pizza e mapa) são gerados pela biblioteca Plotly Express, que oferece alta interatividade.

## 🚀 Funcionalidades

- **Dashboard Interativo:** Interface web limpa e de fácil utilização para explorar os dados.
- **Filtros Múltiplos:** Filtre os dados por Ano, Senioridade, Tipo de Contrato e Tamanho da Empresa.
- **KPIs Dinâmicos:** Métricas chave como Salário Médio, Salário Máximo e Total de Registros são atualizadas em tempo real.
- **Gráficos Detalhados:**
  - Top 10 cargos por salário médio.
  - Distribuição de salários em um histograma.
  - Proporção dos tipos de trabalho (remoto, presencial, híbrido).
  - Mapa interativo com o salário médio de Cientistas de Dados por país.
- **Visualização de Dados Brutos:** Uma tabela exibe os dados filtrados para uma análise mais granular.

## 🔮 Roadmap / Futuras Melhorias

- Adicionar mais fontes de dados para enriquecer a análise.
- Implementar um modelo de Machine Learning para prever salários com base nas features.
- Criar novas visualizações, como séries temporais da evolução salarial.
- Adicionar uma aba de "insights", com conclusões automáticas geradas a partir dos filtros.
- Otimizar o carregamento de dados para datasets maiores.

## 🛠️ Como Rodar o Projeto Localmente

### Pré-requisitos

É necessário ter o Python (versão 3.8 ou superior) e o `pip` instalados em sua máquina.

### 1. Clone o repositório

```bash
git clone https://github.com/Gakira06/Primeira-An-lise-de-Dados.git
```

### 2. Navegue até o diretório do projeto

```bash
cd Primeira-An-lise-de-Dados
```

### 3. (Opcional, mas recomendado) Crie e ative um ambiente virtual

```bash
# Para Windows
python -m venv venv
.\venv\Scripts\activate

# Para macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

### 5. Execute a aplicação Streamlit

```bash
streamlit run app.py
```

### 6. Abra no navegador

O Streamlit abrirá automaticamente uma aba no seu navegador com o dashboard funcionando.

## 🤝 Como Contribuir

1. Faça um **fork** do projeto.
2. Crie uma branch para sua nova funcionalidade: `git checkout -b minha-feature`.
3. Faça **commit** das suas alterações: `git commit -m "feat: Adiciona nova funcionalidade"`.
4. Envie para a sua branch: `git push origin minha-feature`.
5. Abra um **Pull Request**.

## 📞 Contato

Gabriel Akira Borges Kiyohara

- **LinkedIn:** linkedin.com/in/gabriel-akira-kiyohara
- **GitHub:** @Gakira06

## 📄 Licença

Feito com ❤️ por Gabriel Akira Borges Kiyohara.

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
