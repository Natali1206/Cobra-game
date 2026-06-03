# 🐍 Snake Game

Uma implementação moderna do clássico **Snake Game**, desenvolvida utilizando apenas **HTML5, CSS3 e JavaScript Vanilla**, sem bibliotecas ou dependências externas.

O projeto foi criado com foco em simplicidade, desempenho, responsividade e organização de código, funcionando diretamente no navegador sem necessidade de instalação ou configuração adicional.

---

## 🎮 Demonstração

O objetivo do jogo é controlar a cobra, coletar alimentos espalhados pelo mapa e alcançar a maior pontuação possível sem colidir com as paredes ou com o próprio corpo.

### Controles

| Tecla | Ação                |
| ----- | ------------------- |
| ⬆️    | Mover para cima     |
| ⬇️    | Mover para baixo    |
| ⬅️    | Mover para esquerda |
| ➡️    | Mover para direita  |

---

# ✨ Funcionalidades

* ✅ Controle completo por teclado
* ✅ Movimentação fluida da cobra
* ✅ Geração aleatória de comida
* ✅ Crescimento progressivo da cobra
* ✅ Sistema de pontuação em tempo real
* ✅ Sistema de recorde (High Score)
* ✅ Persistência do recorde utilizando Local Storage
* ✅ Detecção de colisão com bordas
* ✅ Detecção de colisão com o próprio corpo
* ✅ Tela de Game Over
* ✅ Reinício da partida sem recarregar a página
* ✅ Layout responsivo
* ✅ Interface moderna e intuitiva
* ✅ Código comentado e organizado

---

# 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido exclusivamente com tecnologias nativas da web:

* HTML5
* CSS3
* JavaScript (ES6+)
* Canvas API
* Local Storage

Nenhuma biblioteca ou framework externo foi utilizado.

---

# 📂 Estrutura do Projeto

```text
snake-game/
│
├── snake.html
└── README.md
```

Todo o projeto está contido em um único arquivo HTML:

* Estrutura → HTML
* Estilização → CSS interno
* Lógica do jogo → JavaScript interno

---

# 🚀 Como Executar

### Método 1 — Download

1. Faça o download do arquivo `snake.html`
2. Abra o arquivo em qualquer navegador moderno:

   * Google Chrome
   * Microsoft Edge
   * Firefox
   * Opera
   * Safari

Pronto! O jogo iniciará automaticamente.

### Método 2 — Clonar Repositório

```bash
git clone https://github.com/seu-usuario/snake-game.git
```

Depois:

```bash
cd snake-game
```

Abra:

```bash
snake.html
```

---

# 🎯 Mecânicas do Jogo

## Alimentação

Sempre que a cobra consumir um alimento:

* A pontuação aumenta.
* O corpo da cobra cresce.
* Um novo alimento é gerado aleatoriamente.

## Colisões

O jogo termina quando:

* A cobra atinge uma parede.
* A cobra colide com seu próprio corpo.

## Recorde

O melhor resultado obtido é armazenado localmente através do navegador utilizando:

```javascript
localStorage
```

Assim, o recorde permanece salvo mesmo após fechar a página.

---

# 🎨 Interface

O design foi desenvolvido com foco em:

* Legibilidade
* Contraste visual
* Experiência do usuário
* Responsividade
* Aparência moderna

Características visuais:

* Tema escuro moderno
* Painel de pontuação
* Destaque para a cabeça da cobra
* Área de jogo centralizada
* Overlay de Game Over

---

# 📱 Responsividade

O jogo adapta-se automaticamente a diferentes tamanhos de tela:

* 💻 Desktop
* 💻 Notebook
* 📱 Smartphones
* 📱 Tablets

---

# ⚡ Desempenho

O projeto foi desenvolvido visando:

* Baixo consumo de recursos
* Carregamento instantâneo
* Execução totalmente local
* Ausência de requisições externas
* Compatibilidade com navegadores modernos

---

# 🔒 Dependências

Nenhuma.

O projeto é totalmente independente e executa localmente sem:

* Frameworks
* Bibliotecas
* APIs externas
* Banco de dados
* Backend
* Servidores

---

# 🔮 Melhorias Futuras

Possíveis evoluções para próximas versões:

* Controles por toque (Swipe)
* Sistema de níveis
* Obstáculos dinâmicos
* Efeitos sonoros
* Música de fundo
* Ranking local
* Modos de dificuldade
* Animações avançadas
* Power-ups especiais
* Modo infinito

---

# 📸 Screenshot

Adicione uma captura de tela do jogo aqui:

```md
![Snake Game Screenshot](./assets/screenshot.png)
```

---

# 🤝 Contribuições

Contribuições são sempre bem-vindas.

Caso encontre bugs ou tenha sugestões de melhorias:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature

```bash
git checkout -b minha-feature
```

3. Faça commit das alterações

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

4. Envie para sua branch

```bash
git push origin minha-feature
```

5. Abra um Pull Request

---

# 📄 Licença

Este projeto está licenciado sob a licença MIT.

Sinta-se livre para utilizar, modificar e distribuir.

---

## 👨‍💻 Autor

Desenvolvido como uma recriação moderna do clássico Snake Game utilizando tecnologias web nativas.

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório.
