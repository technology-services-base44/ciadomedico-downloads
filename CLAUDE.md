# Cia do Médico — Downloads (Financeiro e Repasses de Convênios)

Repositório **público** só com a página de download (README + imagens) dos apps de Windows.
Os executáveis ficam nas **Releases** do GitHub, não no código.

- Financeiro: código em `../ciadomedico-financeiro`, tags `financeiro-vX.Y.Z`, arquivo `CiaDoMedico-Financeiro-vX.Y.Z.zip`.
- Repasses de Convênios: código em `../ciadomedico-repasses-convenios`, tags `convenios-vX.Y.Z`, arquivo `CiaDoMedico-Repasses-vX.Y.Z.zip`.

## Nova versão
1. Gerar o zip no repositório do app (ver o CLAUDE.md dele) e validar no Windows.
2. Criar a release com `gh release create <tag> <zip> --repo technology-services-base44/ciadomedico-downloads`, só com aprovação do usuário.
3. Atualizar no README a versão e o link do botão de download; trocar as imagens se a tela mudou.

## Cuidados
- É público: nada de segredos, URLs internas ou dados de clientes no README, nas imagens ou nas releases.
- Não apague releases antigas sem pedir.
