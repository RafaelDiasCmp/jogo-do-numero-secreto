# Jogo do Número Secreto 🎲

Este é um jogo interativo de lógica onde o jogador tenta adivinhar um número secreto gerado aleatoriamente. O jogo utiliza JavaScript para a lógica e a biblioteca `responsiveVoice.js` para narrar mensagens em voz alta, proporcionando uma experiência divertida e educativa.



<img src="Tela Inicial" alt="Tela Inicial do Jogo" width="800">


## 📝 Descrição do Projeto

O objetivo é adivinhar o número secreto em um intervalo de 1 a 10. O jogador recebe feedback visual e por áudio se o número secreto é maior ou menor que o chute, além de informações sobre o número de tentativas realizadas.

### Principais Funcionalidades

- **Gerador de Números Aleatórios**: Evita repetição ao longo das partidas.
- **Feedback Dinâmico**: Exibe mensagens na tela e utiliza narração para guiar o jogador.
- **Sistema de Tentativas**: Informa quantas vezes o jogador tentou antes de acertar.
- **Reinício do Jogo**: Gera um novo número secreto e reinicia o contador de tentativas.

---

## 🚀 Como Executar

### Pré-requisitos

- Um navegador moderno com suporte a JavaScript.
- Biblioteca `responsiveVoice.js` incluída no projeto.

### Passos para execução

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/jogo-numero-secreto.git

3. Abra o arquivo index.html no navegador.

4. Digite um número no campo de entrada e clique em "Verificar" para começar a jogar.

## 📂 Estrutura do Projeto

Abaixo está a organização dos arquivos e pastas do projeto:

```plaintext
├── index.html         # Estrutura HTML principal da aplicação
├── style.css          # Arquivo de estilos para a interface (opcional)
├── script.js          # Lógica principal do jogo em JavaScript
├── responsiveVoice.js # Biblioteca para síntese de voz
└── imagens/           # Pasta contendo as imagens do projeto
    ├── tela-inicial.png # Exemplo da tela inicial do jogo
    ├── feedback.png     # Exemplo de feedback ao jogador
```

## 📚 Conceitos Aplicados

- **Eventos de Entrada**: Captura e validação do número digitado pelo jogador.
- **Funções Modulares**: Código organizado e reutilizável.
- **Recursividade**: Garantia de números aleatórios únicos.
- **Integração com Biblioteca Externa**: Uso de `responsiveVoice` para síntese de voz.



