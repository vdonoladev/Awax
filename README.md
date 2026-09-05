# Awax - Responsive Landing Page

Landing page moderna e responsiva desenvolvida para fins de estudo de estruturação semântica em **HTML5**, estilização avançada com **CSS3** e técnicas de **design responsivo** adaptadas para dispositivos móveis, tablets e desktops.

O layout foi baseado no conceito visual [Free Landing Page](https://www.behance.net/gallery/58301549/Free-Landing-Page), criado pelo designer [Alexander Bukin](https://www.behance.net/bagd).

## 📌 Seções da Página

- **Header / Navegação:** Barra de cabeçalho fixa com logotipo e menu responsivo (*mobile opener*).
- **Banner (Hero Slider):** Área de destaque com carrossel de chamadas principais, botões de call-to-action (CTA) e ponteiros de navegação.
- **About Us:** Apresentação da empresa/agência com texto institucional e imagem descritiva.
- **Services:** Grade de serviços oferecidos com ícones e resumos de entregáveis.
- **Our Projects:** Portfólio de trabalhos com categorias de filtro (Photos, Branding, Adverts, Development, Misc) e galeria de imagens interativa.
- **Our Team:** Carrossel apresentando membros da equipe, cargos e links para redes sociais.
- **Happy Clients:** Depoimentos e avaliações de clientes.
- **Companies:** Faixa institucional com logotipos de empresas parceiras.
- **Pricing Table:** Tabela de preços e planos com detalhamento de recursos inclusos.
- **Premium Features:** Área de benefícios adicionais com listas e recursos em destaque.
- **Some Facts:** Métricas e contadores de conquistas e projetos concluídos.
- **Social Share:** Barra de compartilhamento em redes sociais com contadores.
- **Contact Us & Map:** Formulário para envio de mensagens integrado com bloco de informações de endereço e localização física.
- **Footer:** Rodapé completo contendo links sociais, texto institucional e caixa de inscrição em newsletter.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica (`<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`).
- **CSS3:** Estilização com Flexbox/Grid, transições e media queries para responsividade.
- **Google Fonts:** Tipografia externa utilizando a família [Montserrat](https://fonts.google.com/specimen/Montserrat).
- **Assets Gráficos:** Imagens e ícones obtidos no [Pixabay](https://pixabay.com/pt/) e [Free Images](https://pt.freeimages.com/).

## 📁 Estrutura do Projeto

```plaintext
awax/
├── assets/
│   ├── css/
│   │   └── style.css           # Folha de estilos e media queries
│   └── images/                 # Ícones de interface e botões (menu, check, quote, redes)
├── media/                      # Imagens de conteúdo (banners, fotos de projetos, avatares)
├── index.html                  # Estrutura principal da página
└── README.md                   # Documentação do projeto
```

## 🚀 Como Executar

Por ser um projeto web puramente estático, você não precisa de servidores complexos ou gerenciadores de pacotes:

1. Clone o repositório:
```bash
git clone https://github.com/vdonoladev/Awax.git
```

2. Acesse o diretório do projeto:
```bash
cd Awax
```

3. Abra o arquivo `main.html` em seu navegador:
* Dê dois cliques diretamente no arquivo `main.html`, ou
* Use uma extensão como o **Live Server** no VS Code para recarregamento automático durante edições.

## 📱 Responsividade

A interface foi projetada para se ajustar dinamicamente a diferentes resoluções:

* **Mobile:** Menu colapsável com alternador (*menu-opener*), colunas empilhadas verticalmente e espaçamentos reduzidos.
* **Tablet:** Grades intermediárias para cards de serviços, preços e galeria de fotos.
* **Desktop:** Layout completo com alinhamentos em múltiplas colunas e carrosséis com largura expandida.

## 📄 Créditos e Licença

* **Design Original:** [Alexander Bukin](https://www.behance.net/bagd) via [Behance](https://www.behance.net/gallery/58301549/Free-Landing-Page).
* **Imagens:** [Pixabay](https://pixabay.com/pt/) e [Free Images](https://pt.freeimages.com/).
