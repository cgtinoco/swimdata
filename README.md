# Swimdata Insights CBDA

Aplicação React/Vite para visualização de dados de competições de natação a partir de JSONs estáticos gerados de bancos SQLite da CBDA.

## Comandos

```bash
npm install
npm run dev
npm run build
```

## Estrutura de dados

Os eventos ficam em:

```text
public/data/events/<id_evento>/
```

Exemplo:

```text
public/data/events/40671/
```

## Publicação

O projeto está pronto para GitHub + Netlify/Vercel.

Configuração Netlify:

```text
Build command: npm run build
Publish directory: dist
```
