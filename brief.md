# Brief do Projeto

## 1. Informações Principais
* **Nome da Empresa:** Biohack Peptídios
* **Indústria/Nicho:** [Ex: Saúde e Performance, Suplementação Avançada, Biohacking]
* **Localização:** [Ex: Goiânia, GO - Brasil]
* **Idioma:** Português (BR) - *Nota: O público final é brasileiro, buscando performance e saúde.*

## 2. Definição do Produto
* **O que estamos construindo?**
    * Uma landing page de alta conversão para um negócio de venda de peptídeos. O design deve ser mobile-first, rápido e transmitir autoridade científica e confiança.
* **Para quem é? (Público-Alvo)**
    * [Ex: Atletas, praticantes de musculação, pessoas buscando emagrecimento, longevidade e recuperação de lesões. Valorizam qualidade, pureza e atendimento ágil.]
* **Qual é o objetivo? (Call to Action)**
    * Objetivo Primário: Fazer o usuário clicar em "Comprar Agora" ou chamar no WhatsApp para orçamento.
    * Objetivo Secundário: Gerar confiança através de informações técnicas claras (pureza, origem) e depoimentos.

## 3. Requisitos da Stack Tecnológica (O Setup "Antigravidade")
* **Framework:** HTML5 Puro + JavaScript (ES6).
* **Estilização:** TailwindCSS (via CDN) para estilização rápida e consistência.
* **Backend:** Nenhum (Site Estático) OU Supabase (apenas se um banco de dados for estritamente necessário).
* **Deploy:** Google Stitch / Hospedagem Estática.
* **Restrições:** Sem etapas de build complexas (npm/yarn). Tudo deve rodar em um único `index.html` ou estrutura de pastas simples.

## 4. Visão Geral das Seções
A landing page precisa das seguintes seções específicas nesta ordem:

1. **Barra de Navegação (Navigation Bar):**
**Objetivo:** Fornecer acesso instantâneo às informações de contato e navegação sem poluição visual. Deve ser "Sticky" (sempre visível).

**Requisitos de Layout:**
* **Posição:** Fixa/Sticky no topo (`z-50`, `top-0`, `w-full`).
* **Fundo:** Branco ou cinza muito claro com uma sombra sutil (`shadow-md`) para separar do conteúdo.
* **Layout Desktop:**
    * **Esquerda:** Logo da Empresa (Imagem ou Texto em negrito).
    * **Centro:** Links (Início, Produtos/Catálogo, Benefícios, FAQ).
    * **Direita (Vital):** Um botão de CTA proeminente ("Falar com Especialista") E o ícone do WhatsApp clicável.
* **Layout Mobile:**
    * **Esquerda:** Logo.
    * **Direita:** Ícone do Menu Hambúrguer (Lógica Abrir/Fechar via JS simples) + Um botão de "WhatsApp/Telefone" para discagem instantânea.
    * **Estado do Menu:** Quando aberto, cobre a tela cheia ou desce com links grandes e fáceis de tocar.
    * **Nota:** Ao rolar a página, certifique-se de que a navbar não tenha "glitch" e reapareça suavemente.

**Detalhes de Interação:**
* **Efeitos Hover:** Sublinhado simples ou mudança de cor nos links.
* **Botão CTA:** Deve contrastar fortemente com o fundo (ex: Botão Verde/Laranja em nav Branca).
* **Prioridade Mobile:** No mobile, o ícone de "Chamar Agora" deve estar visível *fora* do menu hambúrguer. Não esconda o dinheiro dentro do menu.

**Conteúdo:**
* **Links:** Início, Catálogo, Sobre, Contato.
* **Texto do CTA:** "Orçamento Grátis" ou [Ícone do WhatsApp].

2. **Seção Hero (Capa):** Imagem de fundo de alta qualidade (remetendo a ciência/laboratório/fitness), manchete forte ("Peptídeos de Alta Pureza para Performance e Saúde"), e um botão "Sticky" de ação.
3. [cite_start]**Selos de Confiança / Prova Social:** "Pureza 99,65%", "Importado da Irlanda", "Laboratório Biotech Pharmaceutical"[cite: 33, 36].
4. **Grid de Produtos/Serviços:** 3 a 4 categorias principais com ícones/fotos (Ex: Emagrecimento, Recuperação, Ganho Muscular).
5. **Galeria/Detalhes:** Um slider ou grid mostrando os produtos reais (frascos, caixas).
6. **Sobre Nós:** Breve biografia para humanizar o negócio (foco em qualidade e importação segura).
7. **Formulário de Contato:** Um formulário simples para coletar informações do usuário.
8. **FAQ:** Uma seção de Perguntas Frequentes com dúvidas comuns (envio, forma de uso, armazenamento).
9. **Contato/Rodapé (Footer):** WhatsApp grande e visível, área de atendimento e um formulário simples.

## 5. Design & Vibe (Moodboard)
* **Estilo Visual:** DEFINIR ESTILO VISUAL PARA O SITE (Clean, Científico, Moderno).
* **Tipografia:** Cabeçalhos Sans-serif (Inter ou Roboto) para um toque moderno. (SINTA-SE LIVRE PARA PROCURAR MAIS FONTES SE QUISER).
* **Tom de Voz:** Profissional, científico, porém direto. Evite jargões corporativos vazios. Use palavras como "Pureza", "Resultado", "Performance".

"Requisitos adicionais: O site deve ser totalmente responsivo em Desktop, Tablet e Mobile.
[cite_start]Lembre-se de usar o mesmo esquema de cores do logo (Azul, Verde, Roxo conforme o logo da BIT Biotech [cite: 1]), e mantenha sempre um tamanho de fonte pequeno/adequado para Tablet e Mobile, para que não fique apertado na página."