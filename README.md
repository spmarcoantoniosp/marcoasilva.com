# marcoasilva.com

Website profissional de Marco Antonio da Silva — processos, serviços, produto e IA
em operações reguladas.

## Estrutura

- `index.html` — site completo, single-file e autocontido (fontes e imagens embutidas
  em base64, sem dependências externas).
- `CNAME` — domínio customizado do GitHub Pages (`marcoasilva.com`).
- `.nojekyll` — desliga o processamento Jekyll, servindo os arquivos como estão.
- `robots.txt` / `sitemap.xml` — SEO.

## Publicação

GitHub Pages serve a branch `main` a partir da raiz. Todo push em `main` republica
o site em poucos minutos.

Para atualizar:

```bash
cp "caminho/para/novo/index.html" index.html
git commit -am "Atualiza site"
git push
```

## DNS (GoDaddy)

| Tipo  | Nome | Valor             |
|-------|------|-------------------|
| A     | @    | 185.199.108.153   |
| A     | @    | 185.199.109.153   |
| A     | @    | 185.199.110.153   |
| A     | @    | 185.199.111.153   |
| CNAME | www  | USUARIO.github.io |
