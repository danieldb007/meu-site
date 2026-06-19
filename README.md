# meu-site

Portfólio pessoal de **Daniel Diederichsen de Brito** — desenvolvedor e gestor de projetos,
atuando na interseção entre tecnologia (IA, desenvolvimento web) e liderança (PMI Goiás).

Site estático de página única (HTML + [Tailwind CSS](https://tailwindcss.com/) e
[ícones Lucide](https://lucide.dev/) via CDN). Não há etapa de build.

🔗 Produção: <https://danieldbrito.com.br>

## Estrutura

| Arquivo             | Descrição                                                        |
| ------------------- | ---------------------------------------------------------------- |
| `index.html`        | Página única do portfólio.                                       |
| `favicon.svg`       | Favicon (iniciais "DB").                                         |
| `robots.txt`        | Regras para crawlers + referência ao sitemap.                    |
| `sitemap.xml`       | Mapa do site para mecanismos de busca.                           |
| `site.webmanifest`  | Manifesto PWA (nome, cores, ícones).                             |

## Rodar localmente

Por ser estático, basta abrir o `index.html` no navegador, ou servir a pasta:

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

## Publicar

Suba os arquivos da raiz para qualquer hospedagem estática (GitHub Pages, Netlify,
Vercel, etc.) apontando o domínio `danieldbrito.com.br` para ela.

## Assets pendentes (opcional)

- **`og-image.jpg`** (1200×630): imagem de pré-visualização para compartilhamento em
  redes sociais. As meta tags Open Graph/Twitter já apontam para `/og-image.jpg`;
  basta adicionar o arquivo na raiz.
- **`perfil.jpg`**: foto de perfil. Há uma tag `<img>` comentada na seção *hero* do
  `index.html` pronta para uso.
