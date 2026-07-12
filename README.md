# Site Pessoal — Portfólio

Portfólio pessoal de **André Luiz**, desenvolvedor web em formação e criador de livros.

🌐 **Acesse:** [www.andreamorimdev.com.br](https://www.andreamorimdev.com.br)

## ✨ Destaques

- Design **glassmorphism** com tema escuro, gradientes e efeitos de fundo animados
- **Responsivo** (mobile-first) com menu hambúrguer em telas menores
- **Acessível**: `aria-expanded` no menu, suporte a `prefers-reduced-motion`
- **SEO**: meta description, Open Graph, canonical e favicon
- Animações de entrada com Intersection Observer

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — variáveis, grid/flexbox, animações e media queries
- **JavaScript (vanilla)** — sem frameworks ou dependências

## 📄 Seções

| Seção | Conteúdo |
|---|---|
| Início | Apresentação, estatísticas e chamadas para ação |
| Quem sou eu | Trajetória, redes sociais e projeto em destaque |
| Skills | Tecnologias: HTML5, CSS3, JavaScript, Git e GitHub |
| Educação | Certificações técnicas (Rocketseat) |
| Contato | Links para GitHub, LinkedIn, YouTube e Instagram |

## 🚀 Como rodar localmente

Não há build nem dependências — basta abrir o arquivo no navegador:

```bash
git clone https://github.com/andreamorim18/sitepessoal.git
cd sitepessoal
# abra o index.html no navegador, ou sirva com:
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## 📦 Hospedagem

Publicado no **GitHub Pages** com domínio personalizado configurado via `CNAME`.

## 🔒 Proteção do branch `main`

Como o site é publicado direto do `main`, recomenda-se proteger o branch contra force push e exclusão acidental:

1. No repositório, acesse **Settings → Branches → Add branch ruleset** (ou clique em **Protect this branch** no aviso do GitHub)
2. Nomeie a regra (ex.: `main`), defina o target como o branch `main` e ative **Enforcement status: Active**
3. Marque as regras **Restrict deletions** e **Block force pushes**
4. (Opcional) Ative **Require a pull request before merging** para que toda alteração passe por PR

## 📝 Licença

Distribuído sob a licença [MIT](LICENSE).
