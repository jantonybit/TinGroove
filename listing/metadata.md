# Metadados do listing — TinGroove (rascunho)

Rascunho para o Partner Center. Itens marcados como **CONFIRMAR** dependem de acesso ao
Partner Center ou de decisão sua; o resto foi extraído do código e do `README.md`.

## Identidade

| Campo | Valor |
|---|---|
| Título | `TinGroove` |
| Publicador | `Jantonybit` |
| Store ID | `9N8BSV9BGP95` — **CONFIRMAR** no Partner Center se o ID pertence a este produto |
| Assinatura do produto | *Sound Designer by Jantonybit* (visível na interface) |
| Preço | US$ 4,99 no lançamento / US$ 9,99 de tabela — pagamento único, sem assinatura |
| Versão | `1.0.0.0` (a definir no manifesto) |

## Listing pt-br

| Campo | Valor |
|---|---|
| Descrição curta | `Sequenciador de bateria com 14 instrumentos, MIDI, WAV e seus próprios samples.` (79/80) |
| Descrição longa | `listing/long-description.txt`, seção PT-BR |
| Categoria principal | Música |
| Categoria secundária | Utilitários / Produtividade |
| Faixa etária | Todos os públicos (Everyone) |
| Idiomas declarados | Português (Brasil), Inglês (Estados Unidos) |
| Palavras‑chave | `bateria`, `sequenciador`, `ritmo`, `midi`, `wav`, `samples`, `latim`, `drum machine` |
| URL da política de privacidade | `https://jantonybit.github.io/TinGroove/privacy-policy.html` |
| URL de suporte | `https://github.com/jantonybit/TinGroove/issues` |
| Novidades desta versão | `listing/release-notes.md` |
| Capturas de tela | A preparar: grid, configurações, gerenciador de samples, exportação |
| Assets | A preparar: StoreLogo 50×50, Square44x44, Square150x150, Wide310x150 |

## Listing en-us

| Campo | Valor |
|---|---|
| Title | `TinGroove` |
| Short description | `Drum sequencer with 14 instruments, MIDI/WAV export and your own samples.` (73/80) |
| Long description | `listing/long-description.txt`, seção EN |
| Category | Music / Productivity |
| Price | US$ 4,99 launch / US$ 9,99 list — one-time, no subscription |
| Age rating | Everyone |
| Keywords | `drum machine`, `sequencer`, `groove`, `midi`, `wav`, `samples`, `latin`, `beat` |
| Privacy policy URL | `https://jantonybit.github.io/TinGroove/privacy-policy.en.html` |
| Support URL | `https://github.com/jantonybit/TinGroove/issues` |

## Declaração de capacidades

| Capacidade | Justificativa |
|---|---|
| `runFullTrust` (restrita) | App Win32 clássico empacotado (Desktop Bridge): GDI, WASAPI e winmm. |
| `internetClient` | Necessária apenas para o fallback HTTPS do botão *More Apps From The Developer.*, acionado por clique. O app não faz requisições por conta própria. |
| `microphone` | **NÃO declarar.** O app é render-only: não captura microfone, loopback nem áudio do sistema. |

## Avisos para o formulário de conteúdo

- "Sons gerados pelo aplicativo; nenhum sample de terceiros incluído."
- O app lê arquivos WAV escolhidos explicitamente pelo usuário e grava configurações/exportações
  em `%LOCALAPPDATA%\TinGroove\config`. Não afirmar que "não acessa arquivos".
- Não prometer plugin: CLAP é apenas uma possibilidade futura. VST3/ASIO foram descartados por
  motivo de licenciamento.

## Pendências

- [ ] Confirmar Store ID e reserva do nome no Partner Center.
- [ ] Criar repositório público e GitHub Pages para a política de privacidade.
- [ ] Preparar capturas de tela e assets de ícone.
- [ ] Gerar manifesto e `.msix`; instalar e validar o checklist da seção 4 do `STORE_HANDOFF.md`.
