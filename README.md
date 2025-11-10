## 🖥️ Visão Geral do Projeto

Este projeto foi desenvolvido como parte do **"Ford `<Enter>`"**
(curso de Programação Front-end da **Ford** em parceria com o **SENAI
CIMATEC**). O site apresenta um **portal completo da Ford**, com foco em
navegação dinâmica, interatividade, comparação de veículos e,
crucialmente, na **conformidade com a Lei Geral de Proteção de Dados
(LGPD)** no formulário de contato.

O projeto é composto por **três páginas principais**, integradas entre
si e complementadas por scripts que adicionam funcionalidades dinâmicas,
como **carrossel automático de imagens**, **comparador de veículos** e
**formulário de contato com controle de consentimento LGPD**.

## 📑 Funcionalidades Implementadas

  ----------------------------------------------------------------------------
  Funcionalidade     Descrição          Status            Arquivo(s)
  ------------------ ------------------ ----------------- --------------------
  **Página Inicial   Exibe o carrossel  ✅ Completa       `index.html`,
  (Home)**           de imagens com                       `carousel.js`
                     botões de                            
                     navegação e                          
                     títulos clicáveis.                   

  **Página           Mostra os modelos  ✅ Completa       `lancamento.html`,
  Lançamento**       da Ford com vídeo                    `compare.js`
                     promocional e                        
                     opção de comparar                    
                     dois veículos                        
                     simultaneamente.                     

  **Página de        Contém formulário  ✅ Completa       `contato.html`,
  Contato (Foco      com validação de                     `form.js`
  LGPD)**            campos e                             
                     **controle de                        
                     envio** baseado na                   
                     aceitação dos                        
                     **Termos e                           
                     Condições                            
                     (LGPD)**.                            

  **Design           Layout ajustável a ✅ Completo       `style.css`,
  Responsivo**       diferentes                           `form.css`,
                     resoluções de tela                   `lancamento.css`
                     (desktop, tablet e                   
                     mobile).                             

  **Interatividade   Carrossel          ✅ Completo       `carousel.js`,
  com JavaScript**   automático, botões                   `compare.js`,
                     de navegação e                       `form.js`
                     comparação                           
                     dinâmica de                          
                     veículos.                            

  **Rodapé Social**  Ícones e links     ✅ Completo       Todos
                     para redes sociais                   
                     (Facebook,                           
                     YouTube,                             
                     Instagram).                          
  ----------------------------------------------------------------------------

## 🛠️ Tecnologias Utilizadas

-   **HTML5:** Estruturação semântica das páginas.
-   **CSS3:** Estilização, layout e responsividade.
-   **JavaScript:** Funcionalidades dinâmicas e interativas.
-   **Google Fonts e Material Icons:** Ícones e tipografia moderna.
-   **YouTube Embed:** Integração de vídeo promocional.

## 📂 Estrutura de Diretórios

    📁 projeto-ford
    │
    ├── index.html              # Página inicial (carrossel interativo)
    ├── lancamento.html         # Página de modelos e comparação de veículos
    ├── contato.html            # Página de formulário de contato (Com controle LGPD)
    │
    ├── js/
    │   ├── carousel.js         # Lógica do carrossel de imagens
    │   ├── compare.js          # Comparador de veículos
    │   └── form.js             # Processamento, validação e lógica LGPD do formulário
    │
    ├── css/
    │   ├── style.css
    │   ├── lancamento.css
    │   └── form.css
    │
    └── img/
        ... (Arquivos de Imagem)

## 🚀 Como Visualizar o Projeto

Você pode visualizar o projeto diretamente no GitHub Pages:

👉
**[https://erickrochanascimento.github.io/LGPD-SPRINT6/](https://erickrochanascimento.github.io/LGPD-SPRINT6/index.html)**

## 💡 Principais Aprendizados (Foco no Sprint LGPD)

Durante o desenvolvimento deste projeto foram aplicados e aprimorados
conceitos fundamentais de Front-End:

-   **Conformidade Legal (LGPD):** Implementação de um sistema de
    bloqueio do botão de envio (`bloquear` função em `form.js`) até que
    o usuário **aceite explicitamente** os Termos e Condições, simulando
    uma exigência legal de consentimento.
-   Organização modular de CSS e JavaScript.
-   Manipulação de DOM e eventos em JavaScript.
-   Criação de classes e métodos para controle dinâmico de conteúdo.
-   Uso de `setInterval`, `addEventListener` e métodos estáticos de
    classe.
-   Comparação de objetos e atualização de conteúdo dinâmico via DOM.

## 👤 Autor

**Erick Rocha Nascimento**
*   [LinkedIn](https://www.linkedin.com/in/erickrochanascimento)
*   [GitHub](https://github.com/ErickRochaNascimento)


