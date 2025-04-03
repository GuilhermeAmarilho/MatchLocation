# 📍 Encontro Perfeito – Web App com Geolocalização e Favoritos

**Encontro Perfeito** é uma aplicação web PWA que ajuda o usuário a encontrar locais para encontros como **praças, bares e restaurantes** nas redondezas, utilizando a **API do Google Maps**, com suporte a **geolocalização**, **favoritos com localStorage** e **funcionalidade offline via Service Worker**.

---

## 🌐 Funcionalidades principais

- 🗺️ **Exibe locais próximos** com base na geolocalização do usuário
- 💾 Permite **favoritar estabelecimentos**, salvando dados no navegador
- 📋 Página dedicada para **listar e limpar favoritos**
- 🔌 **Funciona offline** graças ao Service Worker e cache inteligente
- 📱 Adaptado para **uso mobile e instalação como PWA**

---

## 📍 Como funciona

1. O usuário abre o app e escolhe um tipo de local (praça, bar, restaurante).
2. A API do Google Maps obtém a **localização atual** e mostra os locais mais próximos.
3. Ao clicar num marcador, exibe **nome, endereço e telefone**.
4. O usuário pode clicar em **"Quer favoritar esse local?"**, salvando no `localStorage`.
5. Em **favoritos.html**, todos os locais favoritos são listados em uma tabela, com opção de **limpar todos os dados**.

---

## 📦 Tecnologias usadas

- HTML5, CSS3, JavaScript
- 📍 Google Maps JavaScript API (com Places API)
- 🧠 `localStorage` para persistência de favoritos
- 💡 Service Worker para funcionamento offline
- 🧩 Progressive Web App (PWA) com `manifest.json`

---

> 🌐 *Um aplicativo web leve e útil para explorar os arredores, mesmo sem conexão com a internet!*
