# Silveira & Cassales — Website Institucional

> **Projeto Simulado** | VIII Semana do Estagiário EAJCS 2026

Um website profissional e elegante para o escritório jurídico **Silveira & Cassales**, especializado em litígios complexos, consultoria estratégica e conformidade regulatória.

---

## 📋 Sobre o Projeto

Este é um website institucional desenvolvido como atividade prática da **VIII Semana do Estagiário** da EAJCS 2026. O site apresenta:

- 🎯 **Identidade visual refinada** com paleta de cores inspirada no branding oficial
- 📱 **Design responsivo** para desktop, tablet e dispositivos móveis
- ⚖️ **Apresentação das áreas de prática** jurídica
- 👥 **Equipe de estagiários** com especialidades definidas
- ✨ **Interface elegante** com tipografia sofisticada

---

## 🎨 Design & Paleta de Cores

| Elemento | Cor | Código |
|----------|------|--------|
| Primária | Azul Marinho | `#1a2847` |
| Destaque | Dourado | `#c9a961` |
| Fundo Claro | Creme | `#faf9f7` |
| Fundo Secundário | Bege | `#f5f3f0` |
| Texto | Cinza Escuro | `#2c2c2c` |

### Tipografia

- **Títulos & Cabeçalhos**: Cormorant Garamond (serif elegante)
- **Corpo de Texto**: Lora (serif legível)
- **Navegação & UI**: Cormorant Garamond (uppercase)

---

## 🏗️ Estrutura do Site

```
Silveira & Cassales
├── Header
│   ├── Logo (SC)
│   ├── Título Principal
│   ├── Subtitle & Tagline
│   └── Navegação
├── Seção: Sobre o Escritório
│   └── Apresentação institucional
├── Seção: Áreas de Prática
│   ├── Litígios Cíveis
│   ├── Direito Trabalhista
│   ├── Direito Tributário
│   ├── Contencioso Cível Geral
│   ├── Direito do Consumidor
│   └── Insolvência e Falência
├── Seção: Nossa Equipe
│   ├── 7 Estagiários em Direito
│   ├── Especialidades definidas
│   └── Fotos profissionais
└── Footer
    ├── Informações de Contato
    ├── Direitos Autorais
    └── Crédito do Projeto
```

---

## 👥 Equipe

| Nome | Especialidade | Função |
|------|----------------|--------|
| **Flávia Nunes** | Direito Trabalhista | Estagiária em Direito |
| **João Nardin** | Direito Tributário | Estagiário em Direito |
| **Isadora Zotz** | Contencioso Cível | Estagiária em Direito |
| **Wesley Ribeiro** | Direito do Consumidor | Estagiário em Direito |
| **Nathany Silveira** | Direito Trabalhista | Estagiária em Direito |
| **Maria Cassales** | Direito do Consumidor | Estagiária em Direito |
| **Gabriely Calesso** | Insolvência & Falência | Estagiária em Direito |

---

## 🚀 Como Usar

### 1. Visualizar Localmente

Basta abrir o arquivo `index.html` no navegador:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### 2. Adicionar Fotos da Equipe

Para que as fotos apareçam no site:

1. **Prepare as imagens** (recomendado: 400px × 500px)
2. **Renomeie** com os seguintes nomes:
   - `flavia.jpg`
   - `joao.jpg`
   - `isadora.jpg`
   - `wesley.jpg`
   - `nathany.jpg`
   - `maria.jpg`
   - `gabriely.jpg`

3. **Coloque na mesma pasta** do arquivo `index.html`
4. **Pronto!** As fotos aparecerão automaticamente

### 3. Adicionar o Logo

O logo já está configurado como um placeholder "SC". Para usar o logo real:

1. Renomeie a imagem para: `logo.jpg`
2. Coloque na mesma pasta do `index.html`
3. Altere a linha no código de:
   ```html
   <img src="logo .jpg" alt="Logo Advocacia" class="logo">
   ```
   Para:
   ```html
   <img src="logo.jpg" alt="Logo Silveira & Cassales" class="logo">
   ```

---

## 🌐 Hospedagem Online

### Opção 1: GitHub Pages (Recomendado)

1. Faça um **commit** no repositório
2. Vá em **Settings → Pages**
3. Selecione **Main branch** como fonte
4. Seu site estará em: `https://seu-usuario.github.io/SITE-SILVEIROS-EQUIPE2`

### Opção 2: Netlify (Alternativa Rápida)

1. Acesse [Netlify.com](https://netlify.com)
2. Conecte seu repositório GitHub
3. Deploy automático — pronto!

### Opção 3: Vercel

1. Acesse [Vercel.com](https://vercel.com)
2. Importe seu repositório GitHub
3. Deploy com um clique

---

## 📱 Responsividade

O site foi desenvolvido com **mobile-first approach** e funciona perfeitamente em:

- 📱 **Dispositivos Móveis** (até 480px)
- 📱 **Tablets** (480px a 768px)
- 💻 **Desktop** (acima de 768px)

**Breakpoints implementados:**
- `@media (max-width: 768px)` — Ajustes para tablet
- `@media (max-width: 480px)` — Otimizações para mobile

---

## 🛠️ Personalização

### Mudar o Nome do Escritório

Procure por `Silveira & Cassales` no arquivo `index.html` e substitua pelo nome desejado. Ocorrências:
- Linha ~510 (Header)
- Linha ~660 (Footer)
- Título da página (tag `<title>`)

### Alterar Cores

Edite as variáveis CSS no `<style>`:

```css
:root {
    --primary: #1a2847;      /* Cor primária (azul) */
    --accent: #c9a961;       /* Cor de destaque (dourado) */
    --light-bg: #f5f3f0;     /* Fundo claro */
    --cream: #faf9f7;        /* Fundo principal */
    --text: #2c2c2c;         /* Texto */
    --text-light: #5a5a5a;   /* Texto secundário */
    --border: #e8e4df;       /* Bordas */
}
```

### Modificar Áreas de Prática

Edite a seção `#pratica` (linha ~541):

```html
<div class="area-card">
    <h3>Sua Área</h3>
    <p>Descrição da área de prática...</p>
</div>
```

---

## 📊 Otimização

### Compactar Imagens

Antes de usar as fotos, comprima-as para melhorar a velocidade do site:

- [TinyPNG.com](https://tinypng.com) — Excelente compressor
- [Imgbot.ai](https://imgbot.ai) — Otimização automática
- [Squoosh.app](https://squoosh.app) — Editor online Google

**Recomendação**: Manter imagens entre 50-150KB

---

## 🎯 Funcionalidades Implementadas

✅ Navigation com hover animado  
✅ Cards com efeitos visuais ao hover  
✅ Grid responsivo para equipe (4+3 containers)  
✅ Seções com backgrounds alternados  
✅ Footer integrado com contato  
✅ Tipografia elegante e profissional  
✅ Scroll comportado (smooth scroll)  
✅ Compatibilidade com todos os navegadores modernos  

---

## 📄 Arquivos do Projeto

```
SITE-SILVEIROS-EQUIPE2/
├── index.html              ← Arquivo principal do site
├── README.md               ← Documentação (este arquivo)
├── flavia.jpg              ← Fotos da equipe (a adicionar)
├── joao.jpg
├── isadora.jpg
├── wesley.jpg
├── nathany.jpg
├── maria.jpg
├── gabriely.jpg
└── logo.jpg                ← Logo do escritório (a adicionar)
```

---

## 🔗 Links Úteis

- **GitHub Pages**: [pages.github.com](https://pages.github.com)
- **Fonte Cormorant Garamond**: [Google Fonts](https://fonts.google.com/specimen/Cormorant+Garamond)
- **Fonte Lora**: [Google Fonts](https://fonts.google.com/specimen/Lora)
- **Netlify Deploy**: [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel Deploy**: [vercel.com](https://vercel.com)

---

## 📝 Notas de Desenvolvimento

### Versão Atual
- **v1.0** — Lançamento inicial
- **Data**: Setembro 2026
- **Status**: Simulação Acadêmica

### Compatibilidade
- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)

### Próximas Melhorias (Sugestões)
- [ ] Formulário de contato funcional
- [ ] Integração com Google Maps
- [ ] Blog/Artigos jurídicos
- [ ] Galeria de casos de sucesso
- [ ] Integração com CMS
- [ ] Dark mode
- [ ] Multi-idioma (PT/EN)

---

## 👨‍💼 Autores

**Equipe de Estágio — EAJCS 2026**

- Flávia Nunes
- João Nardin
- Isadora Zotz
- Wesley Ribeiro
- Nathany Silveira
- Maria Cassales
- Gabriele Calesso

**Orientação Acadêmica**: VIII Semana do Estagiário — EAJCS

---

## 📜 Licença

Este projeto é uma **simulação acadêmica** desenvolvida exclusivamente para fins educacionais na EAJCS 2026. Todos os direitos reservados.

---

## ❓ Dúvidas?

Para dúvidas sobre:
- **Código HTML/CSS**: Verifique os comentários dentro do arquivo `index.html`
- **Hospedagem**: Consulte os guias em [GitHub Pages](https://pages.github.com), [Netlify](https://netlify.com) ou [Vercel](https://vercel.com)
- **Tipografia**: As fontes estão carregadas via [Google Fonts](https://fonts.google.com)

---

**Última atualização**: Setembro 2026  
**Projeto**: Simulação Acadêmica EAJCS 2026  
**Status**: ✅ Completo e pronto para apresentação
