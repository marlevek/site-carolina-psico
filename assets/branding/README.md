# Branding

Arquivos recomendados para quando o logo e o favicon finais estiverem prontos:

- `logo-header.svg`
- `favicon.svg`
- `favicon-32x32.png`
- `favicon-16x16.png`
- `apple-touch-icon.png`

Onde plugar:

- Header: dentro do link `.brand-link` em `index.html`, usando a classe `brand-logo`
- Favicons: descomentar o bloco no `<head>` de `index.html`

Exemplo do logo no header:

```html
<img
  class="brand-logo"
  src="assets/branding/logo-header.svg"
  alt="Logo de Carolina Cunha Levek"
  width="56"
  height="56"
>
```

Observações:

- Preferir SVG para o logo principal
- Manter fundo transparente nos PNGs
- Salvar tudo em UTF-8 quando houver arquivos de texto auxiliares
- Se quiser, depois eu posso fazer a entrada final do logo e do favicon assim que os arquivos chegarem
