# dorotech/.github

Repositório especial da organização **DoroTech** no GitHub. Ele guarda a página de apresentação exibida em [github.com/dorotech](https://github.com/dorotech).

> Este arquivo descreve o repositório e **não** aparece no perfil da organização. O conteúdo público está em [`profile/README.md`](profile/README.md).

## Estrutura

```
.github/
├── README.md              # Este arquivo (descrição do repositório)
└── profile/
    ├── README.md          # Página exibida no perfil da organização
    └── assets/
        ├── competencia-1.jpg … competencia-6.jpg
        └── mercado-1.jpg … mercado-6.jpg
```

## Como funciona

O GitHub exibe automaticamente o arquivo `profile/README.md` de um repositório público chamado `.github` na página da organização. Qualquer alteração enviada para a branch padrão (`master`) aparece no perfil logo após o push.

## Conteúdo do perfil

O texto segue o site institucional [dorotech.com.br](https://www.dorotech.com.br):

- Título e slogan
- Missão e valores
- Competências (grade com 6 imagens)
- Mercados (grade com 6 imagens)
- Contato e redes sociais

Ao mudar o site, revise o `profile/README.md` para manter os dois alinhados.

## Imagens

As fotos de competências e mercados vêm do site e foram padronizadas:

| Item | Padrão |
|---|---|
| Formato | JPG, qualidade ~82 |
| Proporção / tamanho | 3:2, 600×400 px (recorte centralizado) |
| Exibição no README | `width="180"` |
| Nomes | `competencia-N.jpg` e `mercado-N.jpg`, na ordem das células |

No README, as imagens usam a **URL absoluta** do GitHub:

```
https://raw.githubusercontent.com/dorotech/.github/master/profile/assets/<arquivo>
```

Caminhos relativos (`assets/...`) podem falhar na página da organização. Por isso, uma imagem nova só aparece no preview **depois do push**.

## Editando

1. Edite `profile/README.md` (e adicione imagens em `profile/assets/`, se precisar).
2. Faça commit e push na `master`.
3. Confira o resultado em [github.com/dorotech](https://github.com/dorotech).

> ⚠️ Este repositório é **público**. Não inclua dados financeiros, credenciais ou informações internas.
