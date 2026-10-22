# NexusAI — Landing Page

Landing page institucional da **NexusAI**, uma consultoria especializada em Inteligência Artificial.

## Descrição

Este projeto é uma página web estática single-page que apresenta os serviços de consultoria em IA da NexusAI. A página é totalmente responsiva e conta com design moderno, animações suaves e formulário de contato.

## Funcionalidades

- **Navegação fixa** com menu responsivo para dispositivos móveis
- **Seção Hero** com animações de orbs flutuantes e estatísticas da empresa
- **Seção de Serviços** com cards detalhando as áreas de atuação
- **Seção de Processo** explicando a metodologia de trabalho em 4 etapas
- **Seção Sobre** com métricas e diferenciais da empresa
- **Seção de Depoimentos** com cases de clientes
- **Formulário de Contato** para solicitação de diagnóstico gratuito
- **Barra de progresso de scroll** indicando a posição na página
- **Animações de reveal** ao scroll (IntersectionObserver)
- **Rodapé** com links de navegação e informações de contato

## Stack Tecnológica

- **HTML5** — estrutura da página
- **CSS3** — estilização com variáveis CSS, gradientes, blur e animações
- **JavaScript** (vanilla) — interatividade, animações de scroll e validação de formulário
- **Google Fonts** — fontes Inter e Syne

## Estrutura de Pastas

```
.
├── index.html              # Página principal (HTML, CSS e JS embutidos)
├── .github/
│   └── workflows/
│       └── static.yml      # Workflow para deploy no GitHub Pages
└── README.md               # Este arquivo
```

## Como Executar

Por se tratar de um arquivo HTML estático sem dependências externas, basta abrir o arquivo diretamente no navegador:

1. Clone o repositório:
   ```bash
   git clone https://github.com/rodrigosilvacio/claude-landingpage.git
   ```

2. Abra o arquivo `index.html` em qualquer navegador moderno.

Alternativamente, utilize qualquer servidor HTTP local. Exemplo com Python:

```bash
python3 -m http.server 8000
```

Em seguida, acesse `http://localhost:8000` no navegador.

## Deploy

O projeto está configurado para deploy automático no **GitHub Pages** através do workflow em `.github/workflows/static.yml`. A cada push na branch principal, o conteúdo é publicado automaticamente.

## Variáveis de Ambiente

Este projeto não requer variáveis de ambiente. Todo o conteúdo é estático e não depende de serviços externos configuráveis.

## Licença

Todos os direitos reservados © 2026 NexusAI Consultoria.
