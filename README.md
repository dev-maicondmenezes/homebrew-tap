# homebrew-tap

Tap do Homebrew para as ferramentas de [dev-maicondmenezes](https://github.com/dev-maicondmenezes).

## tyot

`tyot` (*Transcript YOuTube*) extrai metadados, capítulos e transcrição de
vídeos do YouTube para Markdown.

```bash
brew tap dev-maicondmenezes/tap
brew install tyot
man tyot
```

A formula é gerada automaticamente pelo GoReleaser a partir das releases de
[`transcript-tube-cli`](https://github.com/dev-maicondmenezes/transcript-tube-cli).
Não edite `Formula/tyot.rb` manualmente: a próxima release substitui o arquivo.

### Linuxbrew

A formula inclui binários para Linux `amd64` e `arm64`, além de macOS `amd64` e
`arm64`. Em Linux, instale o Homebrew conforme a
[documentação oficial](https://docs.brew.sh/Homebrew-on-Linux).
