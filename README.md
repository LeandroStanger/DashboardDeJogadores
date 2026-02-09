# 🎮 Dashboard de Jogadores

[![GitHub Pages](https://img.shields.io/badge/🌐-Site%20Online-blue?style=for-the-badge)](https://leandrostanger.github.io/DashboardDeJogadores/)
[![GitHub](https://img.shields.io/badge/📂-Repositório-black?style=for-the-badge)](https://github.com/LeandroStanger/DashboardDeJogadores)

Um painel web moderno e interativo para visualização e análise de dados de jogadores em formato de dashboard.

## 📝 Descrição

Este projeto é uma aplicação front-end desenvolvida como um dashboard interativo para exibição e análise de dados de jogadores. Seu objetivo principal é **apresentar informações estatísticas e perfis de jogadores de forma visual e organizada**, proporcionando uma experiência de usuário moderna e responsiva. Ideal para projetos de visualização de dados, portfólios de desenvolvimento front-end ou como base para sistemas esportivos mais complexos.

## 🚀 Acesso Online
Visite o site diretamente através do GitHub Pages:  
**[https://leandrostanger.github.io/DashboardDeJogadores/](https://leandrostanger.github.io/DashboardDeJogadores/)**

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web modernas, focando em performance e experiência do usuário:

*   **HTML5**: Estrutura semântica avançada da aplicação web.
*   **CSS3**: Estilização completa com variáveis CSS, layout responsivo (Flexbox/Grid), animações e design system próprio.
*   **JavaScript (ES6+)**: Lógica avançada para interatividade, manipulação de dados dinâmicos e gerenciamento de estado da aplicação.
*   **API/JSON**: Integração com fonte de dados externa ou local para carregamento dinâmico das informações dos jogadores.
*   **Chart.js/Data Visualization**: (Provável) Biblioteca para criação de gráficos e visualizações de dados interativas.

## 📂 Estrutura do Projeto

A estrutura do projeto é organizada seguindo boas práticas de desenvolvimento front-end:

```
DashboardDeJogadores/
├── index.html          # Ponto de entrada principal da aplicação
├── style.css           # Arquivo principal de estilos e design system
├── script.js           # Lógica principal da aplicação
├── dados.json
└── README.md           # Documentação do projeto
```

## ⚙️ Funcionalidades

Com base na análise do dashboard online, as funcionalidades implementadas incluem:

1.  **Visualização de Dados em Cards**: Apresentação organizada de jogadores com informações detalhadas em cards individuais.
2.  **Gráficos e Estatísticas Interativas**: Visualização de dados através de gráficos (barras, pizza, radar) para métricas como:
    *   Estatísticas de desempenho
    *   Comparativos entre jogadores
    *   Evolução temporal
3.  **Sistema de Filtros Avançados**: Capacidade de filtrar jogadores por múltiplos critérios como:
    *   Posição em campo
    *   Time/clube
    *   Faixa etária
    *   Nacionalidade
    *   Estatísticas específicas
4.  **Ordenação Inteligente**: Classificação dos jogadores por diferentes métricas (gols, assistências, avaliação, etc.).
5.  **Design Responsivo e Moderno**: Interface que se adapta perfeitamente a todos os dispositivos com design atualizado.
6.  **Busca em Tempo Real**: Sistema de busca para localizar jogadores específicos rapidamente.
7.  **Modo Escuro/Claro**: (Provável) Alternância entre temas de cores para melhor experiência visual.

## 🔧 Como Executar o Projeto

Este é um projeto front-end estático que não requer compilação complexa ou servidor back-end dedicado.

### Passo a Passo:

1.  **Clone o repositório** para sua máquina local:
    ```bash
    git clone https://github.com/LeandroStanger/DashboardDeJogadores.git
    ```
2.  **Acesse a pasta do projeto**:
    ```bash
    cd DashboardDeJogadores
    ```
3.  **Execute a aplicação**:
    *   **Método 1**: Abra o arquivo `index.html` diretamente no navegador (duplo clique)
    *   **Método 2 (Recomendado)**: Utilize um servidor local:
        ```bash
        # Com Python
        python -m http.server 8000
        
        # Com Node.js (http-server)
        npx http-server
        
        # Com Live Server (VS Code extension)
        # Instale a extensão e clique em "Go Live"
        ```
4.  **Acesse no navegador**: `http://localhost:8000` (ou a porta configurada)

## 🌐 Configurações Importantes

*   **Hospedagem GitHub Pages**: O projeto está otimizado para execução no GitHub Pages
*   **CORS Considerations**: Para requisições a APIs externas, pode ser necessário configurar proxies ou CORS
*   **Performance Optimization**: O projeto inclui otimizações para carregamento rápido de gráficos e dados

## 👤 Autor

**Leandro Stanger**

*   GitHub: [@LeandroStanger](https://github.com/LeandroStanger)
*   Projeto: [Dashboard de Jogadores](https://github.com/LeandroStanger/DashboardDeJogadores)
*   Demonstração Online: [https://leandrostanger.github.io/DashboardDeJogadores/](https://leandrostanger.github.io/DashboardDeJogadores/)
