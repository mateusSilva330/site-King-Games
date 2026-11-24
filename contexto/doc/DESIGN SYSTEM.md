# **DESIGN SYSTEM — KING GAMES**

**Projeto:** Site Institucional King Games  
**Segmento:** Jogos e Tecnologias  
**Estilo visual:** Moderno  
**Tipografia dos títulos:** Orbitron  
**Tipografia dos textos:** Poppins

## **1\. Paleta de cores**

A paleta de cores seguirá exatamente a identidade visual definida pela empresa.

| Cor | Código HEX | Aplicação |
| ----- | ----- | ----- |
| Primária | `#10051F` | Fundo principal e cabeçalho |
| Secundária | `#D5A642` | Destaques, ícones e botões |
| Complementar | `#F5F1FA` | Textos e fundos claros |
| Roxo vibrante | `#9B35E8` | Botões, links e destaques |
| Roxo profundo | `#240D3A` | Cards, seções e superfícies |

**Regras de utilização:**

* O roxo escuro será a cor predominante do site.  
* O dourado será utilizado para destacar elementos importantes e representar a identidade da marca.  
* O roxo vibrante será utilizado em ações interativas.  
* O branco-lavanda será utilizado para textos e áreas de leitura.  
* O roxo profundo será utilizado para separar conteúdos e organizar os componentes.

Não serão introduzidas novas cores principais.

## **2\. Tipografia e hierarquia dos textos**

O sistema utilizará duas famílias tipográficas:

**Orbitron:** utilizada em títulos, chamadas principais e elementos de destaque.

**Poppins:** utilizada em parágrafos, descrições, menus, formulários e botões.

| Elemento | Fonte | Peso |
| ----- | ----- | ----- |
| Título principal | Orbitron | 700 |
| Títulos de seção | Orbitron | 600 |
| Subtítulos | Orbitron | 500 |
| Parágrafos | Poppins | 400 |
| Botões | Poppins | 600 |
| Menus | Poppins | 500 |
| Informações auxiliares | Poppins | 400 |

## **3\. Tamanhos dos títulos e parágrafos**

Os tamanhos serão padronizados para manter uma hierarquia visual consistente.

| Elemento | Desktop | Celular |
| ----- | ----- | ----- |
| H1 | 40 px | 28 px |
| H2 | 32 px | 24 px |
| H3 | 24 px | 20 px |
| H4 | 20 px | 18 px |
| Parágrafo | 16 px | 14 px |
| Texto auxiliar | 14 px | 12 px |
| Botões | 16 px | 14 px |

**Regras:**

* Utilizar Orbitron nos títulos.  
* Utilizar Poppins nos textos comuns.  
* Evitar textos muito pequenos.  
* Manter espaçamento adequado entre títulos e parágrafos.  
* Utilizar títulos curtos e objetivos.

## **4\. Estilo dos botões e seus estados**

Os botões terão formatos padronizados, bordas levemente arredondadas e áreas de clique confortáveis.

### **Botão primário**

* Fundo: `#D5A642`  
* Texto: `#10051F`  
* Fonte: Poppins semibold.  
* Altura: 48 px.  
* Borda arredondada: 8 px.

### **Botão secundário**

* Fundo: transparente.  
* Texto: `#F5F1FA`.  
* Borda: `#9B35E8`.  
* Altura: 48 px.

### **Botão de destaque**

* Fundo: `#9B35E8`.  
* Texto: `#F5F1FA`.  
* Altura: 48 px.

### **Estados dos botões**

| Estado | Comportamento |
| ----- | ----- |
| Normal | Aparência padrão |
| Hover | Destaque visual ao passar o mouse |
| Active | Aparência de botão pressionado |
| Focus | Contorno visível ao navegar pelo teclado |
| Disabled | Aparência reduzida e sem interação |

Os botões deverão apresentar transições suaves e manter contraste adequado.

## **5\. Estilo dos formulários**

Os formulários deverão apresentar campos simples, organizados e fáceis de preencher.

**Características:**

* Fundo dos campos: `#240D3A`.  
* Texto: `#F5F1FA`.  
* Borda: `#9B35E8`.  
* Altura dos campos: 48 px.  
* Bordas arredondadas: 8 px.  
* Fonte: Poppins.  
* Espaçamento entre campos: 16 px.

**Componentes:**

* Campo de nome.  
* Campo de e-mail.  
* Campo de telefone.  
* Campo de pesquisa.  
* Campo de mensagem.  
* Botão de envio.

**Estados dos formulários:**

* Normal: campo com borda padrão.  
* Focus: borda destacada.  
* Erro: mensagem explicativa abaixo do campo.  
* Sucesso: confirmação de envio.  
* Disabled: campo temporariamente indisponível.

## **6\. Cards e elementos reutilizáveis**

Os cards serão utilizados para organizar produtos, categorias, promoções e informações institucionais.

### **Card de produto**

* Imagem na parte superior.  
* Nome do produto.  
* Descrição resumida.  
* Preço.  
* Botão de visualizar detalhes.  
* Fundo `#240D3A`.  
* Bordas arredondadas de 12 px.

### **Card de categoria**

* Ícone ou imagem.  
* Nome da categoria.  
* Área clicável para acessar os produtos.

### **Card de promoção**

* Imagem do produto.  
* Identificação da oferta.  
* Preço promocional.  
* Botão para consultar a oferta.

### **Card institucional**

* Ícone ou imagem.  
* Título.  
* Texto explicativo.

Todos os cards deverão manter a mesma organização e proporção visual.

## **7\. Bordas, sombras e espaçamentos**

### **Bordas**

| Elemento | Configuração |
| ----- | ----- |
| Botões | 8 px |
| Cards | 12 px |
| Campos | 8 px |
| Imagens | 8 px |
| Containers | 12 px |

### **Sombras**

As sombras serão discretas, utilizadas para criar profundidade sem prejudicar a identidade visual.

Exemplo:

`box-shadow: 0 4px 16px rgba(0,0,0,0.25);`

### **Espaçamentos**

Será utilizada uma escala baseada em múltiplos de 4 px.

| Nome | Valor |
| ----- | ----- |
| XS | 4 px |
| SM | 8 px |
| MD | 16 px |
| LG | 24 px |
| XL | 32 px |
| XXL | 48 px |
| XXXL | 64 px |

## **8\. Regras de responsividade**

O site deverá funcionar em computadores, tablets e celulares.

| Dispositivo | Largura de referência | Organização |
| ----- | ----- | ----- |
| Celular | Até 767 px | Uma coluna |
| Tablet | 768 a 1023 px | Duas colunas |
| Desktop | A partir de 1024 px | Três ou mais colunas |

**Regras gerais:**

* Menu horizontal no computador.  
* Menu compacto no celular.  
* Imagens adaptáveis ao tamanho da tela.  
* Cards organizados conforme o espaço disponível.  
* Botões acessíveis em telas menores.  
* Textos com tamanhos adaptáveis.  
* Evitar rolagem horizontal.  
* Manter espaçamentos consistentes.

## **9\. Componentes reutilizáveis nas páginas**

Os componentes serão compartilhados para manter a padronização do site.

| Componente | Utilização |
| ----- | ----- |
| Header | Cabeçalho de todas as páginas |
| Footer | Rodapé de todas as páginas |
| Navigation | Menu de navegação |
| Logo | Identificação da King Games |
| Button | Ações e navegação |
| SearchBar | Pesquisa de produtos |
| ProductCard | Exibição dos produtos |
| CategoryCard | Exibição das categorias |
| PromotionCard | Exibição das ofertas |
| ContactForm | Formulário de contato |
| SocialLinks | Redes sociais |
| WhatsAppButton | Atendimento pelo WhatsApp |
| Breadcrumb | Indicação do caminho de navegação |

### **Distribuição dos componentes**

**Página inicial:**

* Header  
* Banner principal  
* CategoryCard  
* ProductCard  
* PromotionCard  
* Footer

**Página de produtos:**

* Header  
* SearchBar  
* CategoryCard  
* ProductCard  
* Footer

**Página de detalhes:**

* Header  
* Breadcrumb  
* Galeria de imagens  
* Informações do produto  
* WhatsAppButton  
* Footer

**Página de promoções:**

* Header  
* Banner promocional  
* PromotionCard  
* WhatsAppButton  
* Footer

**Página sobre nós:**

* Header  
* Apresentação institucional  
* Cards informativos  
* Footer

**Página de contato:**

* Header  
* ContactForm  
* SocialLinks  
* WhatsAppButton  
* Footer

## **10\. Implementação em CSS**

Para facilitar o desenvolvimento, as cores, fontes, espaçamentos e bordas serão organizados em variáveis CSS.

```
:root {
  /* Cores */
  --color-primary: #10051F;
  --color-secondary: #D5A642;
  --color-light: #F5F1FA;
  --color-purple: #9B35E8;
  --color-deep-purple: #240D3A;

  /* Tipografia */
  --font-heading: 'Orbitron', sans-serif;
  --font-body: 'Poppins', sans-serif;

  /* Tamanhos */
  --text-xs: 12px;
  --text-sm: 14px;
  --text-base: 16px;
  --text-lg: 20px;
  --text-xl: 24px;
  --text-2xl: 32px;
  --text-3xl: 40px;

  /* Espaçamentos */
  --space-1: 4px;
  --space-2: 8px;
  --space-3: 16px;
  --space-4: 24px;
  --space-5: 32px;
  --space-6: 48px;
  --space-7: 64px;

  /* Bordas */
  --radius-sm: 8px;
  --radius-md: 12px;

  /* Sombras */
  --shadow-card:
    0 4px 16px rgba(0, 0, 0, 0.25);
}

body {
  background: var(--color-primary);
  color: var(--color-light);
  font-family: var(--font-body);
}

h1, h2, h3, h4 {
  font-family: var(--font-heading);
}

button {
  font-family: var(--font-body);
  border-radius: var(--radius-sm);
  cursor: pointer;
}
```

## **11\. Considerações finais**

O Design System da King Games estabelece uma base de padronização para o desenvolvimento do site institucional.

A utilização das cores originais, das tipografias Orbitron e Poppins e dos componentes reutilizáveis permitirá manter uma identidade visual consistente em todas as páginas.

A documentação poderá ser utilizada como referência durante a criação dos protótipos no Figma e na implementação do site utilizando CSS ou Tailwind CSS.

**Resultado esperado:** um site moderno, organizado, responsivo e fiel à identidade visual da King Games.

