# Groei & Automatisering

Statische contenthub voor GitHub Pages over AI automatisering, sales automation, content automatisering, SEO automatisering, GEO en Google indexatie.

## Structuur

- `index.html` - homepage en hub
- `ai-automatisering/` - pillar page over AI automatisering voor MKB
- `sales-automation/` - sales automation checklist
- `content-automatisering/` - AI-content en marketing automation
- `seo-automatisering/` - SEO workflow, contentclusters en interne links
- `geo-ai-overviews/` - GEO en AI Overviews
- `google-indexatie/` - technische indexatiechecklist
- `kosten-ai-automatisering/` - kosten, ROI en terugverdientijd
- `n8n-make-zapier/` - vergelijking van workflowtools
- `blogs-uitbesteden/` - checklist voor SEO-content uitbesteden
- `contentcluster-voorbeeld/` - clusterstructuur, linkmatrix en anchors
- `bronnen/` - bronnen en verdiepende links
- `over/` - uitleg over de site
- `robots.txt`, `sitemap.xml`, `llms.txt` - crawlbaarheid en AI-readability

## Publiceren

De site is frameworkloos en kan direct via GitHub Pages gepubliceerd worden.

Aanname voor canonicals en sitemap:

```text
https://flowstatenl.github.io/Flowstate-link/
```

Als er een custom domein komt, vervang deze basis-URL in:

- alle `<link rel="canonical">` tags
- `sitemap.xml`
- `robots.txt`
- `llms.txt`

## Na livegang

1. Controleer dat alle URLs een 200-status geven.
2. Controleer dat `robots.txt` en `sitemap.xml` live bereikbaar zijn.
3. Dien de sitemap in via Google Search Console.
4. Inspecteer de belangrijkste URLs met URL-inspectie.
5. Werk bronnen en externe links periodiek bij.
