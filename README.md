# 🎮 Sistema de Aluguel de Jogos

## 📝 Descrição
Sistema web para gerenciamento de aluguel de jogos, permitindo aos usuários alugar e devolver jogos de forma simples e intuitiva.

## ⚙️ Funcionalidades
- Visualização de jogos disponíveis
- Sistema de aluguel de jogos
- Sistema de devolução de jogos
- Interface interativa com feedback visual

## 🛠️ Tecnologias Utilizadas
- HTML
- CSS
- JavaScript

## 🎯 Como Usar
1. Clone o repositório:
```html
git clone https://github.com/seu-usuario/nome-do-repositorio
```

```markdown
2. Abra o arquivo `index.html` no seu navegador

3. Para alugar ou devolver um jogo:
   - Clique no botão "Alugar" para alugar um jogo
   - Clique no botão "Devolver" para devolver um jogo alugado

## 💻 Exemplo de Código
O sistema utiliza JavaScript para gerenciar o estado dos jogos:

```javascript
function alterarStatus(id) {
    let jogoSelecionado = document.getElementById(`game-${id}`)
    let imagem = jogoSelecionado.querySelector('.dashboard__item__img')
    let botao = jogoSelecionado.querySelector('.dashboard__item__button') 
    
    // Lógica para alternar entre alugar e devolver
}
```

## 🤝 Contribuição
Não necessário!
