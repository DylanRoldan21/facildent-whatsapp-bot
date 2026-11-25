# Facil Dent — Bot de WhatsApp

Bot de atención 24/7 por WhatsApp para la clínica dental Facil Dent. Responde consultas, agenda citas, muestra especialidades, ubicación y promociones, y deriva a una persona cuando hace falta. Opcionalmente usa IA (Claude) para respuestas más naturales.

## Tecnologías
JavaScript · Cloudflare Workers · Cloudflare KV · WhatsApp Cloud API (Meta) / 360dialog

## Despliegue
```bash
npm install
npx wrangler secret put WA_TOKEN
npx wrangler secret put VERIFY_TOKEN
npm run deploy
```
Las claves se configuran como secretos de Cloudflare; ninguna está en el código.

## Autor
Harvey Dylan Roldán Fernández — [GitHub](https://github.com/DylanRoldan21)
