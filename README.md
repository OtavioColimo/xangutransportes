# Xangu Transportes | Website

Site profissional da Xangu Transportes - Especialistas em transporte de cargas fechadas para todo o Brasil.

## 📋 Descrição

Este é um website responsivo e moderno desenvolvido para a empresa Xangu Transportes, especializada em transporte logístico de cargas fechadas (lotação) em carretas para todo o Brasil. O site foi construído com HTML, CSS (Tailwind CSS) e JavaScript vanilla.

## 🎯 Características Principais

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e dispositivos móveis
- **Interface Moderna**: Design elegante com paleta de cores profissional (azul marinho, laranja e branco)
- **Animações Suaves**: Transições e scroll reveal para melhor experiência do usuário
- **Menu Mobile**: Navegação adaptada para dispositivos menores
- **Botão Flutuante**: Link do WhatsApp sempre acessível
- **SEO Otimizado**: Meta tags e estrutura semântica

## 📂 Estrutura do Arquivo

O arquivo `index1.html` é um arquivo HTML completo e autocontido que contém:

- **Seções**: 
  - Header/Navegação
  - Hero Section (Seção principal)
  - Stats Bar (Estatísticas)
  - Diferenciais (Seis cards destacando diferenciais da empresa)
  - CTA/Contato (Call-to-action)
  - Footer (Rodapé)

- **Integração externa**:
  - Tailwind CSS (via CDN)
  - Google Fonts (Barlow Condensed e Barlow)

## 🚀 Como Usar

### 1. **Abrir no Navegador**
```bash
# Simplesmente abra o arquivo no seu navegador:
# - Windows: Clique duplo no arquivo index1.html
# - macOS/Linux: Clique duplo ou abra com seu navegador favorito
```

### 2. **Via Servidor Local**
Para melhor experiência com funcionalidades completas, abra com um servidor local:

**Com Python 3:**
```bash
python -m http.server 8000
# Acesse: http://localhost:8000
```

**Com Node.js (Live Server):**
```bash
npx live-server
```

**Com PHP:**
```bash
php -S localhost:8000
```

### 3. **Editar o Arquivo**
Abra o arquivo em um editor de texto:
- VS Code, Sublime Text, Atom, Notepad++, etc.
- Faça as alterações desejadas
- Salve (Ctrl+S / Cmd+S)
- Recarregue a página no navegador (F5)

## 🔧 Personalizações Comuns

### Alterar Número de WhatsApp
Procure por `5516991832629` no arquivo e substitua pelo seu número:
```html
https://wa.me/SEUNUMERO?text=Sua%20mensagem
```

### Modificar Cores
Localize a seção de configuração do Tailwind (linhas 17-30):
```javascript
colors: {
  navy:   { DEFAULT: '#0B1E3D', light: '#122548', dark: '#070F1F' },
  orange: { DEFAULT: '#F97316', hover: '#EA6C0A', ... },
  ...
}
```

### Editar Textos
Procure pelos textos principais como "Xangu Transportes" e substitua conforme necessário.

### Adicionar Novas Seções
1. Copie a estrutura de uma seção existente
2. Adapte o HTML mantendo as classes Tailwind
3. Adicione efeitos scroll-reveal com a classe `reveal`

## 🎨 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-----------|-----------|
| **HTML5** | Estrutura semântica do documento |
| **Tailwind CSS** | Framework CSS utilitário para styling |
| **JavaScript Vanilla** | Interatividade (menu mobile, scroll reveal, header scroll) |
| **Google Fonts** | Tipografia (Barlow e Barlow Condensed) |

## 📱 Responsividade

O site foi otimizado para:
- ✅ Smartphones (320px e acima)
- ✅ Tablets (768px e acima)
- ✅ Desktops (1024px e acima)

## 🔗 Links Importantes

- **WhatsApp**: +55 16 99183-2629
- **Instagram**: [@xangutransporte](https://www.instagram.com/xangutransporte/?hl=pt-br)

## 💡 Recursos Inclusos

### Funcionalidades JavaScript
1. **Scroll Reveal**: Elementos aparecem com animação ao scroll
2. **Mobile Menu**: Menu hamburger responsivo
3. **Header Dinâmico**: Fundo do header muda ao fazer scroll
4. **Smooth Scroll**: Navegação suave entre seções

### Componentes Visuais
- Badges de status (disponível agora, destaque, etc.)
- Cards com hover effect
- Botões com efeito de brilho
- Ícones SVG inline
- Padrões de fundo decorativos

## 📝 Observações Importantes

- O arquivo utiliza **CDN do Tailwind** - é necessário conexão com internet
- Todos os SVGs estão **inline** - a página é independente
- O arquivo é **totalmente responsivo** sem necessidade de breakpoints adicionais
- Compatível com navegadores modernos (Chrome, Firefox, Safari, Edge)

## 🚀 Deploy

Para colocar o site online:

1. **Via GitHub Pages**: 
   - Renomeie o arquivo para `index.html`
   - Faça push para a branch `main` ou `gh-pages`
   - Acione GitHub Pages nas configurações

2. **Via Hosting Tradicional**:
   - Upload via FTP (Filezilla, WinSCP, etc.)
   - Ou use painel de controle da sua hospedagem

3. **Via Vercel/Netlify**:
   - Conecte seu repositório Git
   - Deploy automático a cada push

## 📞 Suporte

Para edições, dúvidas ou melhorias, entre em contato com o desenvolvedor ou abra uma issue no repositório.

---

**Desenvolvido para Xangu Transportes** © 2019-2025  
Especialistas em transporte de cargas fechadas para todo o Brasil
