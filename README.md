# DevCod - Site Institucional

Site institucional da DevCod, empresa especializada em desenvolvimento de software, aplicativos, servidores e hospedagem em nuvem GCP.

## Tecnologias Utilizadas

- HTML5
- CSS3 (com Flexbox e Grid)
- JavaScript puro (Vanilla JS)
- Font Awesome para ícones
- Design responsivo

## Estrutura do Projeto

```
site/
├── index.html          # Página principal
├── css/
│   └── style.css      # Estilos do site
├── js/
│   └── script.js      # Funcionalidades JavaScript
└── README.md          # Este arquivo
```

## Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/devcod-site.git
   cd devcod-site
   ```

2. Abra o arquivo `index.html` em qualquer navegador web moderno.

## Como Publicar no GitHub Pages

1. Crie um novo repositório no GitHub (ex: `devcod-site`)
2. Inicialize o repositório local e faça o push do código:
   ```bash
   git init
   git add .
   git commit -m "Primeiro commit"
   git branch -M main
   git remote add origin https://github.com/seu-usuario/devcod-site.git
   git push -u origin main
   ```
3. No GitHub, vá para as configurações do repositório (Settings)
4. Na seção "GitHub Pages", selecione o branch `main` e a pasta `/ (root)`
5. Clique em "Save"
6. Seu site estará disponível em: `https://seu-usuario.github.io/devcod-site`

## Personalização

- **Cores**: Edite as variáveis CSS no início do arquivo `css/style.css`
- **Conteúdo**: Atualize o arquivo `index.html` com suas informações
- **Formulário de Contato**: Atualize o JavaScript em `js/script.js` para enviar os dados para seu backend

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
