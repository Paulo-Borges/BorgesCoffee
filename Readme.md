# ☕ Borges Coffe - Cardápio Online

Um cardápio online simples e elegante desenvolvido em **HTML** e **CSS** puro, projetado para ser **responsivo** e de fácil leitura, especialmente em dispositivos móveis. Este projeto serve como uma vitrine digital para os produtos e horários de funcionamento da cafeteria **Borges Coffe**.

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando apenas as seguintes tecnologias fundamentais da web, o que o torna leve e rápido:

- **HTML5:** Estruturação semântica do conteúdo.
- **CSS3:** Estilização e layout responsivo (utilizando Grid Layout e Media Queries).

## ✨ Funcionalidades

- **Design Minimalista e Elegante:** Focado na experiência do usuário e na clareza do cardápio.
- **Responsividade:** O layout se adapta perfeitamente a diferentes tamanhos de tela, desde smartphones até monitores ultra-wide (com um breakpoint específico em $1970\text{px}$).
- **Estrutura Clara:** Separação nítida entre as seções de Lanches e Bebidas.
- **Informações Essenciais:** Apresenta o nome da cafeteria, horários de funcionamento e uma lista de produtos com preços e descrições.
- **Créditos:** Link direto para o GitHub do desenvolvedor no rodapé.

## 📁 Estrutura do Projeto

A aplicação é composta por dois arquivos principais:

.├── index.html # Estrutura e Conteúdo principal└── style.css # Estilos e Responsividade

## ⚙️ Instalação e Execução

Como o projeto é puramente estático (HTML e CSS), a execução é extremamente simples.

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
    ```
2.  **Navegue até o Diretório:**
    ```bash
    cd SEU_REPOSITORIO
    ```
3.  **Abra o Arquivo:**
    Basta dar um duplo clique no arquivo `index.html`. Ele será aberto automaticamente no seu navegador padrão.

## 🎨 Detalhes do Design (CSS)

O layout utiliza um sistema de **Grid** para organizar o nome do produto e seu preço na mesma linha, garantindo alinhamento e facilidade de leitura.

```css
/* Exemplo de Layout em Grid */
.detalhes-container {
  display: grid;
  /* Define duas colunas: a primeira (produto) ocupa 3/4 e a segunda (preço) 1/4 */
  grid-template-columns: 3fr 1fr;
}
As Media Queries garantem que o texto seja redimensionado para uma experiência de leitura ideal em telas muito grandes ($1970\text{px}$ e superior):CSS@media (min-width: 1970px) {
    .detalhes h1 {
        font-size: 30px;
    }
    .detalhes-container h2 {
        font-size: 20px; /* Aumenta o tamanho do título do produto */
    }
    /* ... outros ajustes de fonte ... */
}
👨‍💻 ContribuiçãoContribuições são bem-vindas! Se você tiver sugestões para melhorar o design, a responsividade ou a semântica do código, sinta-se à vontade para:Fazer um Fork do projeto.
Criar uma Branch para sua feature (git checkout -b feature/Inovacao).
Fazer o Commit das suas alterações (git commit -m 'feat: Adiciona Inovacao X').
Fazer o Push para a Branch (git push origin feature/Inovacao).
Abrir um Pull Request.
📝 Licença Este projeto está licenciado sob a Licença MIT.
🤝 Autor: Desenvolvido com ☕ e paixão por: Paulo Borges
```
