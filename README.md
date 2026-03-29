#  Drip Store - Front-End

##  Descrição do Projeto
O **Drip Store** é uma aplicação web de e-commerce focada em moda urbana e streetwear. Este projeto corresponde à **camada front-end**, responsável pela interface do usuário, navegação, exibição de produtos e interação com a API do back-end.

O objetivo é proporcionar uma experiência de compra rápida, intuitiva e visualmente atraente, seguindo padrões modernos de design e usabilidade.

---

##  tecnologias utilizadas
- **Linguagens:** HTML5, CSS3, JavaScript (ES6+)
- **Frameworks / Bibliotecas:**  
  - React.js  
  - React Router  
  - Axios (para integração com o back-end)
- **Gerenciamento de Estado:** Redux / Context API (se aplicável)
- **Estilização:** CSS Modules / Styled Components / Tailwind CSS
- **Controle de Versão:** Git / GitHub
- **Ferramentas de Build:** Vite ou Create React App
- **Hospedagem:** Netlify / Vercel (opcional)

---

##  Funcionalidades
- Exibição de catálogo de produtos com filtros por categoria, preço e lançamentos
- Carrinho de compras dinâmico
- Sistema de cadastro/login de usuários (via API)
- Página de checkout e resumo do pedido
- Design responsivo para dispositivos móveis e desktops
- Navegação intuitiva com rotas protegidas para páginas privadas

---

##  Estrutura do Projeto
```

drip-store-frontend/
├─ public/                 # Arquivos estáticos
├─ src/
│  ├─ assets/              # Imagens, ícones e logos
│  ├─ components/          # Componentes reutilizáveis
│  ├─ pages/               # Páginas da aplicação
│  ├─ services/            # Serviços e integração com API
│  ├─ context/             # Context API ou Redux
│  ├─ styles/              # Arquivos CSS globais
│  └─ App.jsx
├─ package.json
├─ .gitignore
└─ README.md

````

---

##  Como Rodar o Projeto Localmente
1. Clone este repositório:
```bash
git clone https://github.com/seuusuario/drip-store-frontend.git
````

2. Acesse a pasta do projeto:

```bash
cd drip-store-frontend
```

3. Instale as dependências:

```bash
npm install
```

4. Inicie o servidor de desenvolvimento:

```bash
npm start
```

5. Abra no navegador:

```
http://localhost:3000
```

---

##  Contribuição

Contribuições são bem-vindas! Para colaborar:

1. Faça um fork deste repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Faça commit das alterações (`git commit -m "Adiciona nova feature"`)
4. Faça push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

---

##  Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---









