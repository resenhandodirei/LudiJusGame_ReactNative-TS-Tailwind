# LudiJusGame
LudiJus é uma aplicação web simples desenvolvida em React e TypeScript com Tailwind CSS para estilização. O objetivo é criar uma experiência interativa de quiz onde os usuários podem responder perguntas e ver sua pontuação final.

## Funcionalidades
- **Tela de Perguntas**: Exibe perguntas com opções de resposta.
- **Interatividade**: O usuário pode selecionar uma resposta e passar para a próxima pergunta.
- **Cálculo de Pontuação**: Ao final do quiz, a pontuação é calculada com base nas respostas corretas.
- **Tela de Resultados**: Exibe a pontuação final e permite reiniciar o quiz.

## Tecnologias Utilizadas
- **React**: Biblioteca para construção da interface do usuário.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Tailwind CSS**: Framework de CSS para estilização rápida e responsiva.

## Estrutura do Projeto

```
/LudiJus
  /src
    /components
      QuestionCard.tsx
      ResultScreen.tsx
    /screens
      QuizScreen.tsx
      ResultScreen.tsx
    /utils
      questions.ts
    App.tsx
  /public
    index.html
  tailwind.config.js
```

### Componentes
- **QuestionCard.tsx**: Componente para exibir a pergunta e as opções de resposta.
- **ResultScreen.tsx**: Componente para exibir a pontuação final e permitir reiniciar o quiz.

### Telas
- **QuizScreen.tsx**: Tela principal que gerencia a exibição das perguntas e a coleta de respostas.
- **ResultScreen.tsx**: Tela final que exibe o resultado do quiz.

### Utilitários
- **questions.ts**: Arquivo contendo as perguntas e respostas do quiz.

## Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/ludi-jus.git
   cd ludi-jus
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o projeto:
   ```bash
   npm start
   ```

4. Acesse o aplicativo em seu navegador no endereço `http://localhost:3000`.

## Configuração do Tailwind CSS
Certifique-se de que o arquivo `tailwind.config.js` está configurado corretamente:

```js
module.exports = {
  content: [
    './src/**/*.{js,jsx,ts,tsx}',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

## Como Contribuir
1. Fork o repositório.
2. Crie uma nova branch:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça suas alterações e comite:
   ```bash
   git commit -m 'Adiciona minha feature'
   ```
4. Envie para a branch principal:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## Autor
Larissa Martins Correa

---

Esse projeto foi desenvolvido como parte do aprendizado em desenvolvimento web com React e TypeScript. Qualquer feedback ou sugestão é bem-vindo!

