# Política de Privacidade — TinGroove

**Versão:** 1.0 · **Data:** [A PREENCHER NA PUBLICAÇÃO]  
**Publicador:** Jantonybit · **Store ID:** `9N8BSV9BGP95` (confirmar no Partner Center)

---

## Resumo

O TinGroove é um sequenciador de bateria que roda **inteiramente no seu computador**. Ele não
cria conta, não coleta dados pessoais, não envia telemetria, não exibe anúncios e não grava nem
transmite áudio. Os sons incluídos são gerados pelo próprio aplicativo.

## 1. Responsável

O aplicativo é publicado por **Jantonybit**. Esta política explica o que acontece com seus
arquivos e informações quando você usa o TinGroove. Os dados de compra são tratados pela
Microsoft Store, não pelo aplicativo.

## 2. Dados coletados

**Nenhum.** Não há cadastro, login, analytics, relatórios de falhas, identificadores de
publicidade, cookies, SDKs de terceiros nem envio de arquivos, texto ou áudio para servidores.
O aplicativo não contém compras dentro do app: o pagamento é único e processado pela Store.

## 3. Áudio e dispositivos

| Acesso | Para que serve | Para onde vai |
|---|---|---|
| Saída de áudio WASAPI (render-only, modo compartilhado) | Tocar o padrão que você montou | Somente para o dispositivo de saída escolhido |
| Entrada MIDI (`winmm`) | Receber notas, CC e MIDI Clock de um controlador ou DAW | Comandos locais; nada é enviado pela rede |

O TinGroove **não** acessa microfone, não faz loopback de reprodução, não captura o áudio de
outros aplicativos e não grava o som do sistema. Não há driver próprio nem instalação de driver.

## 4. Arquivos no seu computador

Ao contrário de um aplicativo clássico, o TinGroove **nunca grava dentro da pasta do
executável** (que é somente leitura no pacote da Store). Tudo o que é salvo fica em:

```
%LOCALAPPDATA%\TinGroove\config\
```

| Arquivo | Conteúdo |
|---|---|
| `ui.cfg` | Idioma, dispositivo de saída, preferências de MIDI, motor de som e opção de stems |
| `rhythm.cfg` | Seu padrão, barras, compasso, loop, durações, mix e mute/solo |
| `samples.cfg` | Instrumento, camada de velocity e caminho de cada WAV que você importou |
| `ritmo.mid` | Última exportação MIDI |
| `ritmo.wav` e `stems\*.wav` | Última exportação de áudio (quando você clica em EXPORT WAV) |

Para apagar seus dados, feche o aplicativo e remova essa pasta manualmente.

O aplicativo lê **apenas o arquivo WAV que você escolhe explicitamente** no gerenciador de
samples. O arquivo é lido no local original: não é copiado, modificado, renomeado ou enviado.
Se você apagar o WAV ou o mover, aquele slot volta ao som gerado pelo aplicativo.

> Use apenas sons que você tenha o direito de usar. Não redistribua samples de terceiros nem
> timbres de teclado gravados. O TinGroove não inclui nem hospeda esse tipo de arquivo.

## 5. Internet

O TinGroove não faz requisições de rede por conta própria. A única ação relacionada à internet
é abrir, mediante **clique explícito** no botão *More Apps From The Developer.*, a página do
publicador na Microsoft Store (com fallback para `apps.microsoft.com`). Suas configurações e
exportações nunca são enviadas.

## 6. Compartilhamento com terceiros

Não compartilhamos dados com terceiros. Não há redes de anúncios, analytics, nuvem nem
processadores de pagamento dentro do app. A Microsoft pode tratar informações relacionadas à
sua conta Microsoft e à compra conforme a política da Microsoft Store.

## 7. Crianças

O aplicativo não é direcionado a menores de 13 anos e não coleta informações de crianças.

## 8. Alterações

Se esta política mudar, a nova versão será publicada no mesmo endereço com a data atualizada.

## 9. Contato

Dúvidas ou solicitações relacionadas à privacidade devem ser registradas como `Issue` no
repositório do TinGroove no GitHub: **[CONFIRMAR URL — ex.:
https://github.com/Jantonybit/TinGroove/issues]**.

---

*TinGroove · Sound Designer by Jantonybit · Política de Privacidade v1.0*
