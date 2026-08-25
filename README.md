# Portfólio — João Monteiro

Site pessoal de portfólio para vagas em **dados, engenharia, machine learning e IoT**.
Página única, estática e sem dependências de build — apenas `index.html`
(HTML + CSS + um canvas de telemetria em JavaScript puro), com tema claro/escuro
e tipografia IBM Plex.

🔗 **Projetos em destaque:** [Plataforma RF 5G](https://github.com/JoaoMonteiroUNESP/feg-unesp-5g-rf-platform) ·
[Monitor do Condutor](https://github.com/JoaoMonteiroUNESP/monitor-do-condutor) ·
[Dashboard BASF](https://github.com/JoaoMonteiroUNESP/dashboard-financeiro-basf) ·
[CasaOS](https://github.com/JoaoMonteiroUNESP/casaos-demo) ·
[Nos Labirintos do Eu](https://nos-labirintos-do-eu.vercel.app)

## Rodar localmente

Por ser estático, basta abrir o `index.html` no navegador — ou servir a pasta:

```bash
python -m http.server 8000
```

## Deploy (Vercel)

1. Em [vercel.com/new](https://vercel.com/new), importe o repositório `portfolio`.
2. Framework Preset: **Other** (nenhum build necessário — é estático).
3. Deixe *Build Command* e *Output Directory* em branco e clique **Deploy**.

O site fica disponível em `https://portfolio-<sufixo>.vercel.app`, com opção de
domínio próprio depois.

---

Feito por João Guilherme de Castro Monteiro.
