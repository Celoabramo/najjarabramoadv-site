# Najjar Abramo Sociedade de Advogados

Site institucional do escritório **Najjar Abramo Sociedade de Advogados**, especializado em assessoria jurídica empresarial, com unidades em São Paulo e Avaré (SP).

🌐 **Site no ar:** [najjarabramoadv.com.br](https://najjarabramoadv.com.br)

## Sobre o projeto

Site estático de várias páginas (Home, Áreas de Atuação, Dr. Marcelo e Contato), feito para apresentar o escritório e facilitar o contato por WhatsApp, e-mail e Instagram. Não usa banco de dados nem back-end.

## Tecnologias

- HTML5
- CSS3 (com Tailwind CSS via CDN)
- JavaScript puro (navegação entre páginas e animações ao rolar)
- Google Fonts

## Estrutura

```
najjarabramoadv-site/
├── README.md
└── SITE/
    ├── index.html
    ├── logo.png
    ├── escritorio.jpg
    ├── marcelo.jpg
    ├── favicon.ico
    ├── favicon-32.png
    ├── favicon-192.png
    └── apple-touch-icon.png
```

## Rodando localmente

Não precisa instalar nada. Clone o repositório e abra o arquivo no navegador:

```bash
git clone https://github.com/Celoabramo/najjarabramoadv-site.git
cd najjarabramoadv-site/SITE
# abra o index.html no navegador
```

## Deploy

O site é hospedado na **Netlify**, conectada a este repositório:

- **Branch:** `main`
- **Base directory:** `SITE`
- **Build command:** nenhum (site estático)

A cada `git push` na branch `main`, a Netlify publica a nova versão automaticamente.

## Como atualizar o site

```bash
git pull
# edite o SITE/index.html
git add .
git commit -m "Descreva a alteração"
git push
```

## Contato

📧 secretaria@najjarabramoadv.com.br
📸 [@najjarabramoadv](https://www.instagram.com/najjarabramoadv)

---

© Najjar Abramo Sociedade de Advogados. Todos os direitos reservados.
