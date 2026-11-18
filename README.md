# Etiquetas Niimbot

Página que imprime as etiquetas do app de Compras direto na Niimbot (B1), pelo Bluetooth ou USB do navegador (Chrome/Edge no computador).

- Os dados das etiquetas chegam no endereço (`#d=` JSON em base64url): não passam por servidor.
- Impressão: [NiimBlueLib](https://github.com/MultiMote/niimbluelib) 0.49.0 (MIT). Código de barras: JsBarcode 3.11.6.
- O iframe do Apps Script bloqueia o Bluetooth, por isso a página fica no GitHub Pages.
