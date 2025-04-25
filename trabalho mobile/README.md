# 🎬 App de Filmes com React Native (Expo)

Este é um aplicativo em React Native usando Expo que consome a API pública [OMDb](http://www.omdbapi.com/) para listar, buscar e exibir detalhes de filmes. Os usuários também podem favoritar filmes usando armazenamento local com AsyncStorage.

---

## 📱 Funcionalidades

- 🔍 Buscar filmes por palavra-chave
- 🎞️ Listar resultados em cards com título, pôster e ano
- 📄 Tela de detalhes com sinopse, elenco, diretor, etc.
- ❤️ Favoritar/desfavoritar filmes (armazenamento local)
- ⏳ Carregamento com `ActivityIndicator`
- ⚠️ Tratamento de erros com `axios` + `try/catch`

---

## 📦 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [Expo Router](https://expo.github.io/router/)
- [Axios](https://axios-http.com/)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/)
- [OMDb API](http://www.omdbapi.com/)

---

## 🚀 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/app-filmes-react-native.git
cd app-filmes-react-native
```

2. Instale as dependências:

```bash
npm install
# ou
yarn install
```

3. Adicione sua chave da API OMDb em `index.js` e `[id].js`:

```js
https://www.omdbapi.com/?apikey=SUA_API_KEY
```

> Você pode obter uma chave gratuita em [omdbapi.com/apikey.aspx](http://www.omdbapi.com/apikey.aspx)

4. Inicie o projeto:

```bash
npx expo start
```

---

## 📁 Estrutura de Pastas

```bash
.
├── app
│   ├── index.js              # Tela inicial com lista de filmes
│   ├── [id].js               # Tela de detalhes do filme
│   └── assets/
│       └── loading.json      # Animação Lottie (opcional)
├── components
│   └── MovieCard.js          # Componente de card de filme
├── constants/
├── README.md
├── package.json
└── ...
```

---

## ✨ Extras

- ✅ Suporte a animações com Lottie (em construção)
- ✅ Interface planejada para integração com `nativewind` ou `styled-components`
- ✅ Pronto para adicionar uma aba de "Favoritos"

---

## 📌 TODO

- [ ] Tela para visualizar somente os filmes favoritos
- [ ] Transições e animações com Lottie/Framer Motion
- [ ] Testes com Jest + Testing Library

---

## 📷 Screenshots

_(Adicione imagens aqui depois de testar no seu celular/emulador)_

---

## 🧑‍💻 Autor

Feito com 💙 por [Seu Nome](https://github.com/seu-usuario)

---

## 📝 Licença

Este projeto está sob a licença MIT.
