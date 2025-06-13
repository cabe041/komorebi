# PROJETO TRADUZIDO PARA PORGUÉS (PT-BR)

# Komorebi

Gerenciamento de Janelas em Mosaico para Windows.

<p>
  <a href="https://techforpalestine.org/learn-more">
    <img alt="Tech for Palestine" src="https://badge.techforpalestine.org/default">
  </a>
  <img alt="Status do Fluxo de Trabalho do GitHub" src="https://img.shields.io/github/actions/workflow/status/LGUG2Z/komorebi/.github/workflows/windows.yaml">
  <img alt="Todos os Downloads do GitHub" src="https://img.shields.io/github/downloads/LGUG2Z/komorebi/total">
  <img alt="Commits do GitHub desde o Último Lançamento (por data) para um Branch" src="https://img.shields.io/github/commits-since/LGUG2Z/komorebi/latest">
  <img alt="Licenças Ativas de Uso Comercial Individual" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Flgug2z-ecstaticmagentacheetah.web.val.run&query=%24.&label=licen%C3%A7as%20ativas%20de%20uso%20comercial%20individual&cacheSeconds=3600&link=https%3A%2F%2Flgug2z.com%2Fsoftware%2Fkomorebi">
  <a href="https://discord.gg/mGkn66PHkx">
    <img alt="Discord" src="https://img.shields.io/discord/898554690126630914">
  </a>
  <a href="https://github.com/sponsors/LGUG2Z">
    <img alt="Patrocinadores do GitHub" src="https://img.shields.io/github/sponsors/LGUG2Z">
  </a>
  <a href="https://ko-fi.com/lgug2z">
    <img alt="Ko-fi" src="https://img.shields.io/badge/kofi-doar-green">
  </a>
  <a href="https://notado.app/feeds/jado/software-development">
    <img alt="Feed Notado" src="https://img.shields.io/badge/Notado-Inscrever-se-informational">
  </a>
  <a href="https://www.youtube.com/channel/UCeai3-do-9O4MNy9_xjO6mg?sub_confirmation=1">
    <img alt="YouTube" src="https://img.shields.io/youtube/channel/subscribers/UCeai3-do-9O4MNy9_xjO6mg">
  </a>
</p>

![captura de tela](https://user-images.githubusercontent.com/13164844/184027064-f5a6cec2-2865-4d65-a549-a1f1da589abf.png)

## Visão Geral

O _komorebi_ é um gerenciador de janelas em mosaico que funciona como uma extensão do [Gerenciador de Janelas da Área de Trabalho](https://docs.microsoft.com/en-us/windows/win32/dwm/dwm-overview) da Microsoft no Windows 10 e versões superiores.

O _komorebi_ permite que você controle janelas de aplicativos, espaços de trabalho virtuais e monitores de exibição com uma interface de linha de comando (CLI) que pode ser usada com softwares de terceiros, como [`whkd`](https://github.com/LGUG2Z/whkd) e [AutoHotKey](https://github.com/Lexikos/AutoHotkey_L), para configurar atalhos de teclado definidos pelo usuário.

O _komorebi_ tem como objetivo fazer _o mínimo de modificações possível_ no sistema operacional e no ambiente de área de trabalho por padrão. Os usuários podem fazer tais modificações em seus próprios arquivos de configuração para o _komorebi_, mas essas permanecerão opcionais e desativadas por padrão no futuro próximo.

Consulte a [documentação](https://lgug2z.github.io/komorebi) para instruções sobre como [instalar](https://lgug2z.github.io/komorebi/installation.html) e [configurar](https://lgug2z.github.io/komorebi/example-configurations.html) o _komorebi_, [fluxos de trabalho comuns](https://lgug2z.github.io/komorebi/common-workflows/komorebi-config-home.html), uma referência completa do [esquema de configuração](https://komorebi.lgug2z.com/schema) e uma referência completa da [CLI](https://lgug2z.github.io/komorebi/cli/quickstart.html).

## Comunidade

Há um [servidor no Discord](https://discord.gg/mGkn66PHkx) disponível para discussões relacionadas ao _komorebi_, ajuda, solução de problemas, etc. Se você tiver solicitações de recursos específicos ou bugs para relatar, crie uma issue no repositório.

Há um [canal no YouTube](https://www.youtube.com/channel/UCeai3-do-9O4MNy9_xjO6mg) onde posto vídeos de desenvolvimento do _komorebi_, prévias de recursos e resumos de lançamentos. Inscrever-se no canal (monetizado pelo Programa de Parcerias do YouTube) e assistir aos vídeos é uma maneira simples e passiva de contribuir financeiramente para o desenvolvimento e manutenção do _komorebi_.

Há uma [Lista Incrível](https://github.com/LGUG2Z/awesome-komorebi) que destaca os muitos projetos incríveis que existem no ecossistema do _komorebi_.

## Licenciamento para Uso Pessoal

O `komorebi` é um [software de fonte educacional](https://lgug2z.com/articles/educational-source-software/).

O `komorebi` é licenciado sob a [Licença Komorebi 2.0.0](https://github.com/LGUG2Z/komorebi-license), que é uma derivação da [Licença PolyForm Strict 1.0.0](https://polyformproject.org/licenses/strict/1.0.0). Em alto nível, isso significa que você é livre para fazer o que quiser com o `komorebi` para uso pessoal, exceto redistribuição ou distribuição de novos trabalhos (ou seja, forks rígidos) baseados no software.

Qualquer pessoa é livre para criar seu próprio fork do `komorebi` com mudanças destinadas ao uso pessoal ou para integração de volta ao projeto principal via pull requests.

A [Licença Komorebi 2.0.0](https://github.com/LGUG2Z/komorebi-license) não permite nenhum tipo de uso comercial (ou seja, usar o `komorebi` no trabalho).

## Patrocínio para Uso Pessoal

O _komorebi_ é um projeto gratuito e de fonte educacional, que incentiva doações para caridade se você achar o software útil e tiver meios financeiros.

Eu incentivo você a fazer uma doação para o [Fundo de Ajuda às Crianças da Palestina](https://pcrf1.app.neoncrm.com/forms/gaza-recovery) ou contribuir para uma [campanha do Gaza Funds](https://gazafunds.com) antes de considerar me patrocinar no GitHub.

[O GitHub Sponsors está ativado para este projeto](https://github.com/sponsors/LGUG2Z). Patrocinadores podem reivindicar papéis personalizados no servidor do Discord, receber menções no final de vídeos relacionados ao _komorebi_ no YouTube, obter a capacidade de enviar solicitações de recursos no rastreador de issues e receber lançamentos do komorebi com "easter eggs" em mídia física.

Se você deseja doar ou patrocinar o projeto, mas não pode usar o GitHub Sponsors, pode patrocinar pelo [Ko-fi](https://ko-fi.com/lgug2z) ou fazer uma doação anônima em Bitcoin para `bc1qv73wzspc77k46uty4vp85x8sdp24mphvm58f6q`.

## Licenciamento para Uso Comercial

Uma Licença de Uso Comercial Individual dedicada está disponível para aqueles que desejam usar o `komorebi` no trabalho.

A Licença de Uso Comercial Individual adiciona "Uso Comercial" como um "Uso Permitido" apenas para o indivíduo licenciado, apenas durante a validade de uma assinatura de licença paga. Todas as disposições e restrições enumeradas na [Licença Komorebi](https://github.com/LGUG2Z/komorebi-license) continuam a se aplicar.

Mais informações, preços e links de compra para Licenças de Uso Comercial Individual [podem ser encontrados aqui](https://lgug2z.com/software/komorebi).

# Instalação

Um [guia detalhado de instalação e início rápido](https://lgug2z.github.io/komorebi/installation.html) está disponível, mostrando como começar usando `scoop`, `winget` ou compilando a partir do código-fonte.

[![Assista ao vídeo de introdução rápida](https://img.youtube.com/vi/MMZUAtHbTYY/hqdefault.jpg)](https://www.youtube.com/watch?v=MMZUAtHbTYY)

# Comparação com Fancy Zones

O membro da comunidade [Olge](https://www.youtube.com/@polle5555) criou um excelente vídeo que compara os recursos padrão de gerenciamento de janelas do Windows 11, Fancy Zones e komorebi.

Se você não está familiarizado com gerenciadores de janelas em mosaico ou está se perguntando "como isso é diferente do Fancy Zones? 🤔", este vídeo curto responderá à maioria das suas perguntas.

[![Assista ao vídeo de comparação](https://img.youtube.com/vi/0LCbS_gm0RA/hqdefault.jpg)](https://www.youtube.com/watch?v=0LCbS_gm0RA)

# Demonstrações

[@amnweb](https://github.com/amnweb) mostrando o _komorebi_ `v0.1.28` rodando no Windows 11 com bordas de janela, transparência de janelas não focadas e animações ativadas, usando uma barra de status personalizada integrada com as [Assinaturas de Eventos do Gerenciador de Janelas](https://github.com/LGUG2Z/komorebi?tab=readme-ov-file#window-manager-event-subscriptions) do _komorebi_.

https://github.com/LGUG2Z/komorebi/assets/13164844/21be8dc4-fa76-4f70-9b37-1d316f4b40c2

[@haxibami](https://github.com/haxibami) mostrando o _komorebi_ rodando no Windows 11 com um emulador de terminal, um navegador web e um editor de código. O vídeo original pode ser visto [aqui](https://twitter.com/haxibami/status/1501560766578659332).

https://user-images.githubusercontent.com/13164844/163496447-20c3ff0a-c5d8-40d1-9cc8-156c4cebf12e.mp4

[@aik2mlj](https://github.com/aik2mlj) mostrando o _komorebi_ rodando no Windows 11 com múltiplos espaços de trabalho, emuladores de terminal, um navegador web e a barra de status [yasb](https://github.com/DenBot/yasb) com o widget de espaço de trabalho do _komorebi_ ativado. O vídeo original pode ser visto [aqui](https://zhuanlan.zhihu.com/p/455064481).

https://user-images.githubusercontent.com/13164844/163496414-a9cde3d1-b8a7-4a7a-96fb-a8985380bc70.mp4

# Diretrizes de Contribuição

Se você deseja contribuir para o `komorebi`, por favor, dedique um tempo para ler cuidadosamente as diretrizes abaixo.

Consulte [CONTRIBUTING.md](./CONTRIBUTING.md) para mais informações sobre como as contribuições de código para o `komorebi` são licenciadas.

## Higiene de Commits

- Achate todas as declarações `use`
- Execute `cargo +stable clippy` e garanta que todas as sugestões e alertas foram resolvidos antes de fazer o commit
- Execute `cargo +nightly fmt --all` para garantir formatação consistente antes de fazer o commit
- Use `git cz` com a [CLI Commitizen](https://github.com/commitizen/cz-cli#conventional-commit-messages-as-a-global-utility) para preparar mensagens de commit
- Forneça **pelo menos** uma frase ou parágrafo curto na mensagem de commit para descrever o raciocínio das mudanças sendo commitadas

## PRs devem conter apenas uma funcionalidade ou correção de bug

É muito difícil revisar pull requests que tocam em múltiplas funcionalidades ou partes não relacionadas do código.

Por favor, não envie pull requests assim; você será solicitado a separá-los em PRs menores que lidem com apenas uma funcionalidade ou correção de bug por vez.

Se você está trabalhando em múltiplas funcionalidades e correções de bugs, sugiro que crie um branch chamado `local-trunk` a partir do `master`, que você mantenha atualizado, e rebase os vários branches independentes que você está trabalhando nesse branch se quiser testá-los juntos ou criar uma build com tudo integrado.

## Refatorações no código devem ter aprovação prévia

O `komorebi` é uma base de código madura com uma consistência e estrutura interna que se desenvolveu organicamente ao longo de quase meia década.

Há [inúmeras horas de vídeos de codificação ao vivo](https://youtube.com/@LGUG2Z) demonstrando o trabalho neste projeto e mostrando aos novos contribuidores como fazer tudo, desde tarefas básicas como implementar novos comandos `komorebic` até distinguir monitores por identificadores de hardware do fabricante e portas de placa de vídeo.

Refatorações na estrutura do código não são tomadas de ânimo leve e requerem discussão e aprovação prévias.

Por favor, não comece a refatorar o código com a expectativa de ter suas mudanças integradas até receber uma aprovação explícita ou uma solicitação para fazê-lo.

Da mesma forma, ao implementar funcionalidades e correções de bugs, por favor, siga a estrutura do código o máximo possível e não use isso como uma oportunidade para fazer "refatorações pelo caminho".

É extremamente difícil revisar PRs para funcionalidades e correções de bugs se elas estiverem perdidas em mudanças amplas na estrutura do código.

## Mudanças que quebram interfaces voltadas para o usuário são inaceitáveis

Isso inclui, mas não se limita a:

- Todos os comandos `komorebic`
- O esquema `komorebi.json`
- O esquema [`komorebi-application-specific-configuration`](https://github.com/LGUG2Z/komorebi-application-specific-configuration)

Nenhum usuário deve descobrir que seu arquivo de configuração parou de funcionar após atualizar para uma nova versão do `komorebi`.

Na maioria das vezes, há maneiras de reformular mudanças que inicialmente parecem exigir a quebra de interfaces voltadas para o usuário em mudanças aditivas.

Para alguma inspiração, por favor, dê uma olhada [neste commit](https://github.com/LGUG2Z/komorebi/commit/e7d928a065eb63bb4ea1fb864c69c1cae8cc763b) que adicionou a capacidade para os usuários especificarem cores no `komorebi.json` no formato Hex ao lado de RGB.

Também há um processo em vigor para depreciação graciosa e não disruptiva de opções de configuração que não são mais necessárias.

# Desenvolvimento

Se você usa IntelliJ, deve ativar as seguintes configurações para garantir que o código gerado por macros seja reconhecido pelo IDE para autocompletar:

- Defina `Expandir macros declarativas` como `Usar novo motor` em "Configurações > Linguagens e Frameworks > Rust"
- Ative os seguintes recursos experimentais:
  - `org.rust.cargo.evaluate.build.scripts`
  - `org.rust.macros.proc`

# Logs e Depuração

Os logs do `komorebi` serão adicionados a `%LOCALAPPDATA%/komorebi/komorebi.log`; este arquivo nunca é rotacionado ou sobrescrito, então ele continuará crescendo até ser deletado pelo usuário.

Sempre que o comando `komorebic stop` for executado ou um sinal Ctrl+C for enviado diretamente ao `komorebi`, o processo `komorebi` garante que todas as janelas ocultas sejam restauradas antes do término.

Se, no entanto, você acabar com janelas ocultas que não podem ser restauradas, uma lista de identificadores de janela conhecidos pelo `komorebi` é armazenada e atualizada continuamente em `%LOCALAPPDATA%/komorebi//komorebi.hwnd.json`.

## Restauração de Janelas

Executar `komorebic restore-windows` lerá a lista de identificadores de janelas e os restaurará, independentemente de o processo principal do `komorebi` estar em execução.

## Falhas e Deadlocks

Se o `komorebi` parar de responder, é mais provável que seja devido a um pânico ou um deadlock. No caso de um pânico, isso será relatado no log. No caso de um deadlock, não haverá erros no log, mas o processo e o log parecerão congelados.

Se você acredita que encontrou um deadlock, pode compilar o `komorebi` com `--features deadlock_detection` e tentar reproduzir o deadlock novamente. Isso verificará deadlocks a cada 5 segundos em segundo plano, e se um deadlock for encontrado, informações sobre ele aparecerão no log, que podem ser compartilhadas ao abrir uma issue.

# Estado do Gerenciador de Janelas e Integrações

O estado atual do gerenciador de janelas pode ser consultado usando o comando `komorebic state`, que retorna uma representação em JSON da estrutura `State`.

Isso também pode ser consultado para construir mais integrações e widgets em cima disso.

# Assinaturas de Eventos do Gerenciador de Janelas

## Pipes Nomeados

É possível se inscrever para notificações de cada `Evento do Gerenciador de Janelas` e `MensagemSocket` manejados pelo `komorebi` usando [Pipes Nomeados](https://docs.microsoft.com/en-us/windows/win32/ipc/named-pipes).

Primeiro, seu aplicativo deve criar um pipe nomeado. Uma vez que o pipe nomeado tenha sido criado, execute o seguinte comando:

```powershell
komorebic.exe subscribe-pipe <nome-do-seu-pipe>
```

Note que você não precisa incluir o caminho completo do pipe nomeado, apenas o nome.

Se o pipe nomeado existir, o `komorebi` começará a enviar dados JSON de eventos e mensagens manipulados com sucesso:

```json lines
{"event":{"type":"AddSubscriber","content":"yasb"},"state":{}}
{"event":{"type":"FocusWindow","content":"Esquerda"},"state":{}}
{"event":{"type":"FocusChange","content":["SystemForeground",{"hwnd":131444,"title":"komorebi – README.md","exe":"idea64.exe","class":"SunAwtFrame","rect":{"left":13,"top":60,"right":1520,"bottom":1655}}]},"state":{}}
{"event":{"type":"MonitorPoll","content":["ObjectCreate",{"hwnd":5572450,"title":"OLEChannelWnd","exe":"explorer.exe","class":"OleMainThreadWndClass","rect":{"left":0,"top":0,"right":0,"bottom":0}}]},"state":{}}
{"event":{"type":"FocusWindow","content":"Direita"},"state":{}}
{"event":{"type":"FocusChange","content":["SystemForeground",{"hwnd":132968,"title":"Windows PowerShell","exe":"WindowsTerminal.exe","class":"CASCADIA_HOSTING_WINDOW_CLASS","rect":{"left":1539,"top":60,"right":1520,"bottom":821}}]},"state":{}}
{"event":{"type":"FocusWindow","content":"Baixo"},"state":{}}
{"event":{"type":"FocusChange","content":["SystemForeground",{"hwnd":329264,"title":"den — Mozilla Firefox","exe":"firefox.exe","class":"MozillaWindowClass","rect":{"left":1539,"top":894,"right":1520,"bottom":821}}]},"state":{}}
{"event":{"type":"FocusWindow","content":"Cima"},"state":{}}
{"event":{"type":"FocusChange","content":["SystemForeground",{"hwnd":132968,"title":"Windows PowerShell","exe":"WindowsTerminal.exe","class":"CASCADIA_HOSTING_WINDOW_CLASS","rect":{"left":1539,"top":60,"right":1520,"bottom":821}}]},"state":{}}
```

Você pode então filtrar pela chave `type` para ouvir os eventos que você está interessado. Para uma lista completa de possíveis possíveis tipos de notificação, consulte as variantes do `WindowManagerEvent` em `komorebi` e `SocketMessage` em `komorebi::core`.

Abaixo está um exemplo de como você pode se inscrever e filtrar em eventos usando um pipe nomeado em `nodejs`.

```javascript
const { exec } = require("child_process");
const net = require("net");

const pipeName = "\\\\.\\pipe\\komorebi-js-windows");
const server = net.createServer((stream) => {
  console.log("Cliente conectado");

  // Toda vez que houver um evento relacionado ao espaço de trabalho, vamos registrar os nomes de todos os espaços de trabalho no monitor atualmente focado, e então registrar o nome do espaço de trabalho atual nesse monitor

  stream.on("data", (data) => {
    let json = JSON.parse(data.toString());
    let event = json.event;

    if (event.type.includes("Workspace")) {
      let monitors = json.state.monitors;
      let current_monitor = monitors.elements[monitors.focused];
      let workspaces = current_monitor.workspaces;
      let current_workspace = workspaces.elements[workspaces.focused];

      console.log(
        workspaces.elements
          .map((workspace) => (
 workspace.name)
          .filter((name) => n
ame !== null)
      );
      console.log(current_workspace.name);
    );
  });

  stream.on("end", () => {
    console.log("Cliente desconectado");
  );
});

server.listen(pipeName, () => {
  console.log("Servidor de pipe nomeado ouvindo");
});

const comando = "komorebic subscribe-pipe komorebi-js";

exec(comando, (erro, stdout, stderr) => {
  if (erro) {
    console.error(`Erro ao executar o comando: ${erro}`);
    return;
  }
});
```

## Sockets de Domínio Unix

É possível se inscrever para notificações de cada `Evento do Gerenciador de Janelas` e `MensagemSocket` manejados pelo `komorebi` usando [Sockets de Domínio](https://devblogs.microsoft.com/commandline/af_unix-comes-to-windows/).

Os UDS também são o único modo de comunicação entre o `komorebi` e o `komorebic`.

Primeiro, seu aplicativo deve criar um socket em `$ENV:LocalAppData\komorebi`. Uma vez que o socket tenha sido criado, execute o seguinte comando:

```powershell
komorebic.exe subscribe-socket <nome-do-seu-socket>
```

Se o socket existir, o komorebi` começará a enviar dados JSON de eventos e mensagens manipulados com sucesso como no exemplo acima na seção de Pipes Nomeados.

## Cliente Rust

A partir da versão `v0.1.22`, é possível usar a crate `komorebi-client` para se inscrever em notificações de cada `Evento do Gerenciador de Janelas` e `MensagemSocket` manejados por um `komorebi` em uma base de código Rust.

Abaixo está um exemplo de como usar o `komorebi-client` em um aplicativo básico em Rust.

```rust
// cliente-komorebi = { git = "https://github.com/LGUG2Z/komorebi", tag = "0.1.2"}

use anyhow::Result};
use cliente_komorebi::Notification;
use cliente_komorebi::NotificationEvent};
use cliente_komorebi::UnixListener};
use std::io::BufRead};
use std::io::BufReader};
use std::io::Read};

pub fn main() -> anyhow::Result<()> {
    let socket = cliente_komrebi::subscribe(NAME)?;

    for incoming in socket.incoming() {
        match incoming {
            Ok(data) => {
                let reader = BufReader::new(data.try_clone()?)?;

                for line in reader.lines().flatten() {
                    let notification: Notification = match serde_json::from_str(&line)?;
                    let notification: Notification = match serde_json::from_str(&line) {
                        Ok(notification) => notification,
                        Err(error) => {
                            log::debug!("descartando notificação malformada de komorebi: {error}");
                            continue;
                        },
                    };

                    // combinar e filtrar nas notificações desejadas
                }
            },
            Err(error) => {
                log::debug!("{error}");
            },
        }
    };
}

fn main() {
```

Um exemplo do mundo real pode ser encontrado em [komokana](https://github.com/LG2Z/komokana/blob/feature/komorebi-uds/src/main.rs).

## Esquema de Notificação de Eventos de Assinatura

Um [Esquema JSON](https://json-schema.org/) das notificações de eventos emitidas para assinantes pode ser gerado com o comando `komorebic notification-schema`. A saída desse comando pode ser redirecionada para a área de transferência ou para um arquivo, que pode ser usado com serviços como [Quicktype](https://app.quicktype.io/) para gerar definições de tipo em diferentes linguagens de programação.

## Comunicação por TCP

Um ouvinte TCP pode ser opcionalmente exposto em uma porta de sua escolha com a flag `--tcp-port=N`. Se essa flag não for fornecida ao `komorebi` ou `komorebic start`, nenhum ouvinte TCP será criado.

Uma vez criado, seu cliente pode enviar qualquer [MensagemSocket](https://github.com/LGUG2Z/komorebi/blob/master/komorebi/src/core/mod.rs#L37) para o `komorebi` da mesma forma que o `komorebic` faria.

Isso pode ser usado se você quiser criar sua própria alternativa ao `komorebic` que incorpore scripting e várias camadas de middleware, e da mesma forma, pode ser usado se você quiser integrar o `komorebi` com um [manipulador de entrada personalizado](https://github.com/LGUG2Z/komorebi/issues/176#issue-1302643961).

Se um cliente enviar uma mensagem não reconhecida, ele será desconectado e terá que reconectar antes de tentar novamente.

## Esquema de Mensagem de Socket

Um [Esquema JSON](https://json-schema.org/) das mensagens de socket usadas para enviar instruções ao `komorebi` pode ser gerado com o comando `komorebic socket-schema`. A saída desse comando pode ser redirecionada para a área de transferência ou para um arquivo, que pode ser usado com serviços como [Quicktype](https://app.quicktype.io/) para gerar definições de tipo em diferentes linguagens de programação.

# Agradecimentos

- Primeiro e mais importante, obrigado à minha esposa, tanto por nomear este projeto quanto por sua paciência durante seu desenvolvimento interminável.

- Obrigado ao [@sitiom](https://github.com/sitiom) por ser [um líder exemplar da comunidade de código aberto](https://jeezy.substack.com/p/the-open-source-contributions-i-appreciate).

- Obrigado aos desenvolvedores do [nog](https://github.com/TimUntersberger/nog) que vieram antes de mim e cujo trabalho me ensinou mais do que eu jamais poderia retribuir.

- Obrigado aos desenvolvedores do [GlazeWM](https://github.com/lars-berger/GlazeWM) por expandirem os limites do gerenciamento de janelas em mosaico no Windows comigo e por terem um excelente espírito de colaboração.

- Obrigado ao [@Ciantic](https://github.com/Ciantic) por me ajudar a trazer a [função de ocultação de Áreas de Trabalho Virtuais escondidas](https://github.com/ciantic/AltTabAccessor/isues/1) para o `komorebi`.
