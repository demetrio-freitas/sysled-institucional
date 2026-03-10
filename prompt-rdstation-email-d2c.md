# Prompt para Claude — Criar Email no RD Station

Copie o prompt abaixo e cole no Claude (chrome/app):

---

```
Preciso da sua ajuda para criar um email marketing no RD Station. Vou te dar o conteúdo completo, a estrutura visual e as cores. Quero que você me guie passo a passo na montagem usando o editor drag-and-drop do RD Station.

## DADOS DO EMAIL

**Assunto:** A Indústria que Não Vende Direto Está Perdendo Margem — e Talvez Nem Saiba
**Preheader:** O modelo que funcionou por décadas está quebrado. A inadimplência do varejo bateu recorde e a margem da indústria encolhe. Mas existe uma saída.
**Remetente:** SYSLED
**Largura:** 600px

## PALETA DE CORES (usar exatamente estas)

- Azul escuro (fundo hero/CTA): #0F172A
- Azul profundo (títulos, links): #2B6CB0
- Azul médio: #3A8FD6
- Azul claro (destaques, stats): #5BB8F5
- Branco (fundo corpo): #FFFFFF
- Cinza claro (fundo cards): #F8FAFC
- Cinza texto: #475569
- Cinza escuro (títulos): #0F172A
- Background geral (fora do email): #F1F5F9

## FONTES

- Títulos: Trebuchet MS (fallback: Arial)
- Corpo: Arial, sans-serif
- Tamanho títulos: 20-22px, peso bold
- Tamanho corpo: 15px, line-height 1.8
- Tamanho pequeno (stats, footer): 11-13px

## ESTRUTURA DO EMAIL (de cima para baixo)

### 1. HEADER
- Fundo transparente (herda o cinza #F1F5F9)
- Texto "SYSLED" centralizado, 20px, bold, letter-spacing 3px, cor #0F172A
- Padding: 20px em cima, 16px embaixo

### 2. HERO (fundo escuro)
- Fundo: #0F172A (ou o gradiente mais próximo disponível)
- Border-radius topo: 16px (se o RD permitir)
- Padding: 48px lateral, 40px em cima e embaixo
- Pill/tag centralizada: texto "ESTRATÉGIA INDUSTRIAL", 11px, uppercase, cor #5BB8F5, fundo rgba semitransparente (ou #1E293B), border-radius 20px, padding 5px 16px
- Título: "A Indústria que Não Vende Direto Está Perdendo Margem — e Talvez Nem Saiba", 26px, bold, branco #FFFFFF, centralizado, line-height 1.2
- Meta: "7 minutos de leitura · Março 2026", 13px, cor rgba branco 40% (ou #8696A0), centralizado

### 3. CORPO — Seção 1 (fundo branco)
- Fundo: #FFFFFF
- Padding: 40px lateral

**Título:** "O modelo que funcionou por décadas está quebrado"
- 20px, bold, cor #0F172A

**Parágrafo 1:**
"Durante muito tempo, a lógica da indústria brasileira era simples: fabricar, vender para o distribuidor ou varejista, e esperar o pagamento. O varejo chegava ao consumidor final. A indústria ficava no seu canto."

**Parágrafo 2:**
"**Esse modelo está rachadando.** O varejo brasileiro perdeu força. Os varejistas aumentam a pressão: querem preços menores, prazo maior e mais flexibilidade. A margem que sobra para quem fabrica encolhe a cada negociação."

**Divisor:** linha gradiente azul centralizada, 60px de largura, 3px de altura (cores #5BB8F5 para #2B6CB0). Se não der pra fazer gradiente, use uma linha sólida #5BB8F5.

### 4. CORPO — Seção 2 (fundo branco)

**Título:** "A inadimplência chegou em níveis históricos"

**Parágrafo 1:**
"O Brasil encerrou 2025 com um **recorde histórico de inadimplência empresarial**. Milhões de empresas com dívidas negativadas, centenas de bilhões em débitos acumulados."

**Parágrafo 2:**
"Vender para o varejo com prazo de 60, 90 ou 120 dias, quando o varejista pode simplesmente não pagar, virou uma aposta cada vez mais arriscada. Com a Selic no maior nível em quase duas décadas, a cadeia inteira está pressionada."

**Divisor** (mesmo estilo)

### 5. CORPO — Seção 3 (fundo branco)

**Título:** "A saída: vender direto ao consumidor (D2C)"

**Parágrafo:**
"Enquanto algumas indústrias seguem dependentes do varejo tradicional, outras estão mudando de estratégia. O modelo D2C — Direct to Consumer — deixou de ser tendência e virou necessidade."

### 6. BARRA DE STATS (dentro do corpo branco)
- Bloco com fundo #0F172A, border-radius 14px
- Padding: 24px
- Label centralizado no topo: "NÚMEROS DO D2C NO BRASIL", 11px, uppercase, cor #5BB8F5, letter-spacing 2px
- 4 colunas lado a lado (empilham em mobile):

| Stat | Label | Descrição |
|------|-------|-----------|
| **R$3bi** | Faturamento D2C | 1º sem. 2025 |
| **+26%** | Crescimento | Ano a ano |
| **5%** | Penetração BR | (EUA = 15%) |
| **~50%** | Pix no D2C | Pagamento instantâneo |

- Números grandes: 22px, bold, cor #5BB8F5
- Labels: 10px, cor branco 50%

### 7. CORPO — 3 Vantagens (fundo branco)

**Título:** "Por que o D2C funciona para a indústria?"

3 cards empilhados verticalmente, cada um com:
- Fundo: #F8FAFC
- Border-radius: 12px
- Borda esquerda colorida (4px)
- Padding: 20px
- Margin-bottom: 16px

**Card 1:**
- Borda esquerda: #5BB8F5
- Título: "💰 Mais margem" (15px, bold, #0F172A)
- Texto: "O preço que o consumidor paga vai direto para quem fabricou, sem desconto para distribuidor ou varejista." (14px, #475569)

**Card 2:**
- Borda esquerda: #3A8FD6
- Título: "🎯 Mais controle"
- Texto: "A marca decide como, quando e para quem vende. Sem depender da prateleira de ninguém."

**Card 3:**
- Borda esquerda: #2B6CB0
- Título: "🛡️ Zero inadimplência do varejo"
- Texto: "O consumidor final paga no ato — com Pix, cartão, boleto. Acabou o risco de carregar crédito para um varejista endividado."

### 8. CORPO — Google + Barreira (fundo branco)

**Título:** "O Google já está do seu lado"

**Parágrafo:**
"O Google está integrando IA para conectar consumidores diretamente às marcas que fabricam o que procuram. Uma indústria com site e catálogo próprio pode aparecer na busca — sem marketplace, sem comissão. **Quem não tem canal próprio, simplesmente não aparece.**"

**Divisor**

**Título:** "O que falta para a sua indústria dar esse passo?"

**Parágrafo 1:**
"A principal barreira não é tecnológica — **é operacional**. Vender direto ao consumidor exige que produção, estoque, fiscal, financeiro e canais de venda funcionem como um único sistema."

**Parágrafo 2:**
"Uma indústria que tenta o D2C com sistemas desconectados vai travar antes de escalar. O gargalo não é a vontade de vender direto — é a estrutura que suporta essa venda."

### 9. CTA (dentro do corpo branco)
- Bloco com fundo #0F172A, border-radius 16px
- Padding: 40px 32px, centralizado

**Título:** "Da fábrica direto ao consumidor"
- 22px, bold, branco

**Subtítulo:**
"O SYSLED conecta produção, estoque, fiscal e canais de venda em um único sistema — para sua indústria escalar o D2C de verdade."
- 14px, cor branco 50%

**Botão:** "Agendar Demo Gratuita"
- Fundo branco #FFFFFF, texto #0F172A, bold, 14px
- Border-radius: 12px, padding 14px 36px
- Link: https://sysled.site/#contato

**Link secundário:** "Ler artigo completo no blog →"
- 13px, cor branco 40%, underline
- Link: https://sysled.site/blog-industria-d2c-margem

### 10. FOOTER (dentro do corpo branco, abaixo do CTA)
- Borda superior: 1px solid #E2E8F0
- Padding-top: 24px

**Selo SENAI:**
- Box com fundo #F8FAFC, borda #E2E8F0, border-radius 10px, padding 10px 20px, centralizado
- Linha 1: "★ PROJETO APROVADO" — 10px, bold, uppercase, cor #3A8FD6
- Linha 2: "SENAI Ceará" — 14px, bold, cor #0F172A

**Tagline:** "SYSLED — Plataforma IndTech para automação, logística e inteligência operacional. Do chão de fábrica à nuvem."
- 11px, cor #94A3B8, centralizado

**Links:** Site | Blog | Contato
- 11px, cor #2B6CB0
- Links: https://sysled.site | https://sysled.site/blog | https://sysled.site/#contato

**Copyright:** "© 2026 Sysled Ltda. Todos os direitos reservados."
- 10px, cor #CBD5E1

---

## REGRAS IMPORTANTES
1. NÃO usar cores laranja em nenhum lugar. Apenas a paleta azul informada.
2. O nome é "o SYSLED" (masculino). Nunca "a SYSLED".
3. Todos os links devem apontar para https://sysled.site/...
4. O email deve ser responsivo (empilhar em mobile).
5. Se o editor do RD Station não suportar algum estilo (como gradiente), usar a cor sólida mais próxima.

Me guie passo a passo na criação deste email no editor do RD Station.
```
