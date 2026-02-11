# Método PAR — Landing Page (Link na Bio)

Este pacote já vem com:
- `index.html` (página pronta, responsiva)
- `assets/hero.webp` (foto do evento)
- `assets/eliane.webp` (foto de perfil)
- `assets/favicon.png`

## 1) Ajustes obrigatórios (2 minutos)
Abra o `index.html` e procure por `const CONFIG = { ... }`:

- `checkoutUrl`: link do seu checkout (Hotmart/Eduzz/Kiwify/Monetizze, etc.)
- `whatsappNumber`: seu WhatsApp no formato 55DDDNUMERO (ex.: 5511912345678)
- `offerEndsAt`: data/hora do fim da oferta (opcional)
- `showTimer`: true/false para exibir/ocultar o contador
- `privacyUrl` e `termsUrl`: se você tiver páginas de política/termos

## 2) Hospedar (mais simples)
### Opção A — Netlify (recomendado)
1. Acesse Netlify e crie uma conta
2. Arraste a pasta (ou o ZIP) para o painel (“Deploy manually”)
3. Pronto: copie a URL e cole no link da bio

### Opção B — GitHub Pages
1. Crie um repositório (ex.: `metodo-par`)
2. Envie os arquivos (index.html + assets/)
3. Settings → Pages → Deploy from branch (main / root)
4. Copie o link gerado

## 3) Personalizações rápidas
- Troque textos (títulos, bullets, bônus) direto no HTML
- Coloque depoimentos reais na seção “Resultados”
- Substitua imagens em `assets/` mantendo os nomes

Boa campanha.
