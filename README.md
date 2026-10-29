# Teleprompter V2.1

Teleprompter gratuito, responsivo e **open source**, criado com HTML, CSS e JavaScript puro. Foi projetado para facilitar a leitura de roteiros em gravações, apresentações e produção de conteúdo, tanto no celular quanto no computador.

**Sem instalação, conta, framework ou backend.** Basta abrir o arquivo `index.html` em um navegador moderno.

## Funcionalidades

- **Rolagem automática** com 10 níveis de velocidade e ajustes durante a leitura.
- **Modo espelhado** para uso com acessórios de teleprompter.
- **Tipografia configurável:** tamanho da fonte, espaçamento, largura e alinhamento.
- **Contagem regressiva 3–2–1** antes do início.
- **Guia de foco**, barra de progresso e controles flutuantes.
- **Gestos no celular:** um toque para pausar/continuar, dois toques para mostrar/ocultar controles e arraste para reposicionar.
- **Bloqueio de controles** durante a leitura.
- **Importação e exportação de roteiros `.txt`**.
- **Salvamento automático** do roteiro, das preferências e da posição no navegador.
- Suporte a **tela cheia** e à **Screen Wake Lock API**, quando disponíveis no navegador.

## Como usar

1. Abra `index.html` no navegador ou visite a versão hospedada, quando configurada no GitHub Pages.
2. Digite ou cole um roteiro. Se preferir, clique em **Importar .txt**.
3. Configure a velocidade de leitura, o tamanho do texto e demais preferências.
4. Clique em **Iniciar leitura**. Durante a leitura, você pode pausar, ajustar a velocidade ou reposicionar o texto.

### Atalhos de teclado

| Tecla | Ação |
| --- | --- |
| `Espaço` | Pausar / continuar |
| `↑` | Aumentar a velocidade |
| `↓` | Diminuir a velocidade |
| `Home` | Voltar ao início do roteiro |
| `Esc` | Sair do modo de leitura (quando desbloqueado) |
| `L` | Bloquear / desbloquear controles |

## Executar localmente

Não é necessário instalar dependências ou iniciar um servidor. Clone este repositório ou baixe o código-fonte e abra `index.html` diretamente.

```bash
git clone https://github.com/lukasmonken/teleprompter-web.git
cd teleprompter-web
```

> O endereço do clone acima funcionará após a criação do repositório público com esse nome.

## Publicar no GitHub Pages

Na página do repositório, acesse **Settings → Pages**. Em **Build and deployment**, selecione **Deploy from a branch**; escolha a branch `main`, a pasta `/ (root)` e salve. Depois da publicação, o projeto deverá ficar disponível em:

`https://lukasmonken.github.io/teleprompter-web/`

A publicação depende de habilitar o GitHub Pages; o endereço acima não é uma demonstração já ativa.

## Privacidade e armazenamento

Este projeto é uma aplicação estática e não possui conta, backend ou chamadas de rede no código fornecido. O conteúdo dos roteiros e as preferências são armazenados com `localStorage` **no navegador e dispositivo em uso**, não em uma conta online. Se você limpar os dados do site ou trocar de navegador/dispositivo, poderá perder o roteiro salvo. Exporte seus roteiros para `.txt` como cópia de segurança.

As funções de tela cheia e de manter a tela ativa dependem do suporte e das permissões de cada navegador. Em dispositivos móveis, alguns navegadores podem limitar essas funções.

## Tecnologia

- HTML5
- CSS3
- JavaScript (Vanilla)
- Web APIs: `localStorage`, `FileReader`, `requestAnimationFrame`, Fullscreen API e Screen Wake Lock API

## Contribuições

Sugestões, issues e pull requests são bem-vindos. Veja [CONTRIBUTING.md](CONTRIBUTING.md) para um guia rápido de contribuições.

## Licença

Distribuído sob a [licença MIT](LICENSE). © 2026 lukasmonken.

---

## English

**Teleprompter V2.1** is a free, responsive, open-source web teleprompter built with vanilla HTML, CSS and JavaScript. It works directly in a modern browser, with no installation, account, dependencies or backend.

**Features:** adjustable auto-scroll speed, mirror mode, font size and line spacing controls, countdown, focus guide, progress bar, touch gestures, script import/export (`.txt`), autosave using browser `localStorage`, optional fullscreen and screen wake lock (depending on browser support).

**Getting started:** open `index.html`, paste or import your script, adjust the settings, and select **Iniciar leitura** (Start reading). This version's interface is in Portuguese.

**Privacy:** scripts are stored locally in your browser, not synced to the cloud. Export `.txt` backups to avoid data loss.

**License:** [MIT](LICENSE). Contributions via GitHub issues and pull requests are welcome.