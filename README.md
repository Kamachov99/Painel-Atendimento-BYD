# Painel de Atendimento ao Cliente — Concessionária BYD

Um painel digital interativo e dinâmico desenvolvido para acompanhamento em tempo real do status de manutenção e serviços de veículos em uma concessionária fictícia da **BYD**. 

O painel exibe serviços **Em Execução** e **Finalizados**, possui área central destinada à reprodução contínua de vídeos institucionais/promocionais e conta com um resumo dos últimos atendimentos na parte inferior.

---

## 🚀 Tecnologias Utilizadas

* **HTML5**: Estruturação semântica da aplicação.
* **CSS3**: Estilização moderna com CSS Grid, Flexbox, variáveis nativas e animações.
* **JavaScript (ES6+)**: Lógica do painel, manipulação de DOM, persistência local e controle de mídia.
* **Bootstrap 5 & Bootstrap Icons**: Grid responsivo, tipografia e ícones de interface.
* **jQuery & Owl Carousel 2**: Biblioteca e plugin para a criação do carrossel interativo de vídeos.
* **Chat GPT & Google Gemini**: Auxílio da IA para algumas funcionalidades mais complexas e estrutura do Design do site com CSS.

---

## 📁 Estrutura do Projeto

Como a aplicação funciona **100% no lado do cliente (Client-Side)** e não utiliza banco de dados externo ou arquivos CSV, **é fundamental manter a estrutura de pastas e arquivos exatamente como descrita abaixo** após realizar o download ou clone do repositório:

```text
byd-service-panel/
│
├── index.html          # Arquivo principal do painel (PainelAtendimentoV6.html)
├── BYD-Logo.png        # Logo da BYD exibida na área central
└── videos/             # Pasta contendo os vídeos promocionais
    ├── video1.mp4
    ├── video2.mp4
    ├── video3.mp4
    ├── video4.mp4
    ├── video5.mp4
    ├── video6.mp4
    ├── video7.mp4
    └── video8.mp4
```

> **⚠️ IMPORTANTE:** Para que os vídeos e o logotipo sejam carregados corretamente, certifique-se de baixar todo o repositório completo e manter o arquivo `.html` no mesmo diretório em que está localizada a pasta `videos/` e a imagem `BYD-Logo.png`.

---

## ⚙️ Funcionalidades

* **Gerenciamento de Serviços Fictícios:**
  * Botão **"Novo serviço"**: Gera ordens de serviço aleatórias com dados verossímeis (cliente, modelo BYD, placa no padrão Mercosul, tipo de serviço, cor e horário de entrada).
  * Botão **"Finalizar serviço"**: Move o atendimento da coluna *Em execução* para *Finalizados*, registrando o horário de conclusão.
* **Carrossel de Vídeos em Loop:**
  * Carrossel automático que avança para o próximo vídeo assim que o vídeo atual finaliza a reprodução.
* **Rolagem Automática (Auto-Scroll):**
  * As listas de serviços rolam automaticamente quando o número de itens excede o tamanho do painel, pausando o movimento ao passar o ponteiro do mouse ou focar nos itens.
* **Resumo em Tempo Real:**
  * Exibição em destaque do último serviço iniciado e do último serviço concluído.
* **Persistência de Dados via LocalStorage:**
  * Os dados dos atendimentos permanecem salvos no navegador mesmo ao recarregar a página.
* **Limpeza de Dados:**
  * Botão discreto no rodapé para apagar todo o histórico de atendimentos e reiniciar a aplicação.

---

## 🛠️ Como Executar o Projeto

1. **Baixar o repositório:**
   * Clique em **Code** > **Download ZIP** no GitHub e extraia os arquivos no seu computador, **OU** clone o repositório via terminal:
     ```bash
     git clone https://github.com/seu-usuario/seu-repositorio.git
     ```
2. **Navegar até a pasta do projeto:**
   * Certifique-se de que a estrutura das pastas `videos/` e das imagens está preservada.
3. **Abrir no navegador:**
   * Dê um duplo clique no arquivo `.html` (ex: `index.html` ou `PainelAtendimentoV6.html`) para abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox, Brave, Safari).
   * Não é necessária a instalação de servidores locais (como Node.js, Apache ou Live Server), pois todas as dependências externas de CSS/JS são carregadas via CDN.

---

## 📌 Observações

* Os vídeos e logotipos utilizados são apenas para fins de demonstração acadêmica e de portfólio, simulando a experiência de atendimento em uma concessionária BYD.
# Painel-Atendimento-BYD
Projeto de um Painel de Atendimento fictício para estudo, da matéria Algoritmos e Lógica de Progrmação do 1º Semestre de ADS pela Fatec Carapicuíba.
