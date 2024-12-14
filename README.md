# Página Pessoal - João Victor Fernandes Alves

Este repositório contém o código da minha página pessoal, onde compartilho informações sobre mim, meus hobbies, habilidades e projetos. A página também inclui um formulário de contato funcional para interações com visitantes.

## 📋 Funcionalidades
- **Menu de navegação:** Links para as seções "Início", "Sobre Mim", "Hobbies", "Projetos" e "Contato".
- **Formulário de contato:** Permite que os visitantes enviem mensagens, com a funcionalidade de envio (simulada) ao preencher os campos e clicar no botão.
- **Seções interativas:** Informações sobre mim, hobbies e projetos com imagens e descrições.

## 🎨 Design e Estilo
- **Layout responsivo:** A página se adapta a diferentes tamanhos de tela para garantir uma boa experiência de navegação em dispositivos móveis e desktop.
- **Imagens e ícones:** Utilização de imagens de fundo, imagens de perfil e ícones para melhorar a apresentação visual.
- **Cores e tipografia:** Estilo moderno com cores suaves e tipografia 'Montserrat' para um design limpo e agradável.

### Detalhes do CSS:
O estilo da página é baseado nas seguintes diretrizes:
- **Fundo:** A página possui uma imagem de fundo com efeito de gradiente.
- **Cabeçalho:** Um cabeçalho centralizado com sombra, exibindo um título principal e uma descrição.
- **Menu de navegação:** Links de navegação horizontais com efeito de hover para melhorar a interação.
- **Seções:** Cada seção (Sobre Mim, Hobbies, Projetos, Contato) é bem definida, com bordas arredondadas e sombras suaves.
- **Formulário de contato:** Campos de formulário com bordas arredondadas e botão de envio com efeito de hover.

## 💻 Tecnologias Utilizadas
- **HTML:** Estruturação do conteúdo e layout.
- **CSS:** Estilo e responsividade.
- **JavaScript:** Funcionalidade para o envio de formulários (simulado).
  
## 🚀 Como Usar

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. **Acesse o diretório do projeto:**
    ```bash
    cd seu-repositorio
    ```

3. **Abra o arquivo HTML em seu navegador:**
    Basta abrir o arquivo `index.html` no navegador de sua preferência.

## ✉️ Formulário de Contato
O formulário de contato possui campos para nome, e-mail e mensagem. Após preenchê-los, ao clicar no botão "Enviar", uma notificação de "Email enviado com sucesso!" será exibida, e os campos serão limpos.

### Exemplo do código JavaScript para o formulário:
```javascript
document.querySelector('.contato-form').addEventListener('submit', function(event) {
  event.preventDefault(); // Impede o envio real do formulário
  
  // Exibe a notificação
  alert('Email enviado com sucesso!');
  
  // Limpa os campos do formulário após o envio
  document.querySelector('.contato-form').reset();
});
