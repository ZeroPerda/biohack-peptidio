style-guide.md

Direção Visual:

Vibe: "Apple Store de Laboratório". Minimalista, estéril, tecnológico e de alta confiança.

Iluminação: Bright/Daylight. Evite fundos escuros pesados; use o branco para transmitir higiene e pureza clínica.

Paleta de Cores (Tailwind Classes):

Primary (Identidade): teal-600 (#0D9488) - Baseado no logo da BIT Biotech . Use para cabeçalhos, bordas e ícones.

Secondary (Ação/Venda): emerald-500 (#10B981) - Use exclusivamente para botões de compra ("Comprar Agora", "Pix").

Accent (Detalhe): violet-500 (#8B5CF6) - Use para detalhes sutis ou badges de "Novidade", remetendo ao holográfico das embalagens .

Backgrounds:

Main: bg-white (Branco Puro).

Section: bg-slate-50 (Cinza Gelo muito sutil para separar blocos).

Text:

Headings: text-slate-900 (Quase preto, alto contraste).

Body: text-slate-600 (Cinza técnico, leitura confortável).

Tipografia (Google Fonts):

Headings (Display): "Space Grotesk" (Peso 600/700). Passa uma sensação moderna e biotecnológica.

Body (Leitura): "Inter" (Peso 400/500). Limpa, neutra e perfeita para mobile.

Numbers/Preços: "JetBrains Mono" ou "Roboto Mono". Use para exibir valores (ex: R$ 350,00) e dosagens (5mg), dando ar de dado técnico.

Elementos de UI:

Botões: rounded-full (Formato de pílula/cápsula). Sombra suave shadow-lg e efeito hover:scale-105.

Cards de Produto: bg-white, rounded-xl, border border-slate-100, shadow-md. Devem parecer fichas técnicas flutuando.

Imagens: Use fotos dos frascos com fundo recortado (transparente) ou sobre fundo branco infinito.

Regra de Ouro (Tech):

Framework: Use TailwindCSS via CDN (<script src="https://cdn.tailwindcss.com"></script>).

Responsividade: Mobile-First. Padding lateral generoso (px-6 ou px-8) em telas pequenas para o conteúdo não colar na borda.

Configuração Tailwind: Estenda a configuração de cores no script do head para usar os hexadecimais exatos se necessário.