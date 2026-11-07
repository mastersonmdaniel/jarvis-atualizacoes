# jarvis-atualizacoes

Canal de atualização automática do Jarvis instalado.

- `ultima.json`: versão mais recente, endereço do instalador e sha256.
- `Jarvis-<versão>-instalador.exe`: instalador (Git LFS), sem nenhum dado pessoal.

O Jarvis instalado confere o `ultima.json` ao abrir; se houver versão mais nova, baixa o instalador, confere o
sha256 e instala em silêncio. Publicado pelo `scripts/publicar_atualizacao.ps1 -GitHub` do projeto.
