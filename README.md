<p align="center">
    <img src="https://raw.githubusercontent.com/training-center/sobre/master/img/logo/logo-circle.png" alt="Training Center Logo" width="90" heitgh="90">
</p>

# trainingcenter.io

> Site do Centro de Treinamento

<ul>
  <li><a href="https://ctgroups.herokuapp.com/" target="_blank" title="Entre no nosso grupo no Slack">Entre no nosso grupo no Slack</a></li>
  <li><a href="https://medium.com/trainingcenter/como-se-comportar-no-slack-do-training-center-a3715fb7c00f" target="_blank" title="Saiba como se comportar no nosso Slack">Saiba como se comportar no nosso Slack</a></li>
  <li><a href="https://twitter.com/trainingcentr" target="_blank" title="Siga-nos no Twitter">Siga-nos no Twitter</a></li>
  <li><a href="https://medium.com/trainingcenter" target="_blank" title="Leia nossos artigos no Medium">Leia nossos artigos no Medium</a></li>
</ul>

Esse site foi desenvolvido utilizando o Dunders: https://github.com/woliveiras/__s

## Como contribuir

Utilize a branch `dev` para enviar suas contribuições. Nenhum PR enviado para a `master` será aceito diretamente a não ser que seja um hotfix.

É necessário instalar o Ruby e o Jekyll em sua máquina, para isso você pode seguir [esse tutorial](jekyllrb.com).

Faça o download desse site utilizando o Git: 

```
git clone https://github.com/training-center/training-center.github.io.git
```

Acesse a pasta do site e execute a instalação das dependências:

```
cd training-center.github.io
bundle
```

Para subir um servidor local, utilize o comando:

```
bundle exec jekyll serve
```

Será disponibilizado o site na URL: `localhost:4000`

## Estrutura do site:

**assets**

Pasta onde devem ficar arquivos CSS, JS e imagens.

**_includes**

Partials do site

- **footer.html**
- **head.html**
- **header.html**
- **navigation-menu.html**
- **sessions.html**

Outros arquivos:

- arquivo de configuração do site: **_config.yml**
- arquivo de configuração de domínio: **CNAME**
