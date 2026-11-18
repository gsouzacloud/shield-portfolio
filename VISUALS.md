# Screenshots — Ananim Shield

[English](#english) · [Português](#português)

## English

**About the screenshots:** they are real captures of the production interface (November 2026). Client names, hostnames, IP addresses, users, e-mails and domains were replaced automatically at capture time by fictitious ones (e.g. `CLIENTE ALFA`, `app2.exemplo.com`, `usuario.1`, `10.20.x.x`); financial values are scrambled. Layout, features and workflows are exactly what runs in production.

How anonymization works: a script injected into the browser rewrites every visible text node, input, tooltip, SVG label and canvas chart label before the screenshot is taken, using a fixed dictionary of real → fictitious names plus pattern rules for IPs, e-mails, domains, user names and currency values. Each image was then reviewed manually and checked by a leak scanner before publishing. Because values are scrambled, totals on financial screens are not meant to add up.

`overview.png` is the main screen of the product, captured the same way.

| File | Screen |
|---|---|
| `docs/screenshots/shd-01-visao-geral.png` | Overview |
| `docs/screenshots/shd-02-cobertura.png` | Policies & published coverage |
| `docs/screenshots/shd-06-geolocalizacao.png` | Access & geolocation |
| `docs/screenshots/shd-05-excecoes.png` | Scoped exceptions |
| `docs/screenshots/shd-07-eventos.png` | Events |
| `docs/screenshots/shd-08-analytics.png` | Map & analytics |
| `docs/screenshots/shd-09-relatorios.png` | Reports |
| `docs/screenshots/shd-10-alertas.png` | Alerts |
| `docs/screenshots/shd-11-publicacoes.png` | Versioned publishing & rollback |
| `docs/screenshots/shd-12-auditoria.png` | Audit |

## Português

**Sobre as imagens:** são capturas reais da interface em produção (novembro/2026). Nomes de clientes, hostnames, IPs, usuários, e-mails e domínios foram substituídos automaticamente no momento da captura por nomes fictícios (ex.: `CLIENTE ALFA`, `app2.exemplo.com`, `usuario.1`, `10.20.x.x`); valores financeiros estão embaralhados. Layout, funcionalidades e fluxos são exatamente os que rodam em produção.

Como a anonimização funciona: um script injetado no navegador reescreve todo texto visível, campos, tooltips, rótulos SVG e rótulos de gráficos em canvas antes da captura, usando um dicionário fixo de nomes reais → fictícios e regras para IPs, e-mails, domínios, usuários e valores monetários. Cada imagem foi revisada manualmente e passou por um verificador de vazamento antes da publicação. Como os valores são embaralhados, os totais das telas financeiras não precisam fechar.

`overview.png` é a tela principal do produto, capturada da mesma forma.

| Arquivo | Tela |
|---|---|
| `docs/screenshots/shd-01-visao-geral.png` | Visão geral |
| `docs/screenshots/shd-02-cobertura.png` | Políticas e cobertura publicada |
| `docs/screenshots/shd-06-geolocalizacao.png` | Acesso e geolocalização |
| `docs/screenshots/shd-05-excecoes.png` | Exceções delimitadas |
| `docs/screenshots/shd-07-eventos.png` | Eventos |
| `docs/screenshots/shd-08-analytics.png` | Mapa e analytics |
| `docs/screenshots/shd-09-relatorios.png` | Relatórios |
| `docs/screenshots/shd-10-alertas.png` | Alertas |
| `docs/screenshots/shd-11-publicacoes.png` | Publicação versionada e rollback |
| `docs/screenshots/shd-12-auditoria.png` | Auditoria |
