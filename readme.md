<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Adicione suas estatísticas no GitHub geradas dinamicamente em seus readmes!</p>

# Características

- [Cartão de estatísticas do GitHub](#cartão-de-estatísticas-do-github)
- [Pins extras do GitHub](#pins-extras-do-github)
- [Cartão de principais linguagens de programação](#cartão-de-principais-linguagens-de-programação)
- [Estatística semanal Wakatime](#estatística-semanal-wakatime)
- [Temas](#temas)
- [Personalização](#personalização)

# Cartão de estatísticas do GitHub

Copie e cole isso no seu conteúdo de remarcação e é isso. Simples!

Mude o valor de `?username=` para o seu nome de usuário no GitHub.

```md
[![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves)](https://github.com/Netinhoalves/github-readme-stats)
```

_Nota: As classificações são baseadas nas estatísticas do usuário, veja [src/calculateRank.js](../src/calculateRank.js)_

### Ocultando estatísticas específicas

Para ocultar estatísticas individualmente, você pode passar um parâmetro de consulta `?hide=` com valores separados por vírgula.

> Opções: `&hide=stars,commits,prs,issues,contribs`

```md
![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&hide=contribs,prs)
```

### Adicionando contagem de contribuições privadas à contagem total de commits

Adicione a contagem de todas as suas contribuições privadas à contagem total de confirmações usando o parâmetro de consulta `?count_private=true`.

_Nota: Se você estiver implantando este projeto, as contribuições privadas serão contadas por padrão; caso contrário, você precisará compartilhar suas contagens de contribuições privadas._

> Opções: `&count_private=true`

```md
![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&count_private=true)
```

### Exibindo ícones

Para habilitar ícones, basta utilizar o parâmetro `show_icons=true` na sua requisição, da seguinte forma:

```md
![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&show_icons=true)
```

### Temas

Com temas predefinidos, pode personalizar a aparência dos cartões sem precisar fazer nenhuma [configuração manual](#personalização).

Utilize o parâmetro `?theme=THEME_NAME`, da seguinte forma:

```md
![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&show_icons=true&theme=dark)
```

#### Todos os temas predefinidos :

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula
##
Visualize [todos o temas disponíveis](../themes/README.md) ou o [arquivo de configuração de tema](../themes/index.js)

### Personalização

Personalize a aparência do seu `Stats Card` ou `Repo Card` da maneira que desejar com os parâmetros de URL.

#### Opções comuns

- `title_color` - Cor do título do cartão _(hex color)_
- `text_color` - Cor de texto do conteúdo _(hex color)_
- `icon_color` - Cor dos ícones (se disponível) _(hex color)_
- `bg_color` - Cor de fundo do cartão _(hex color)_
- `hide_border` - Esconde a borda do cartão _(boleano)_
- `theme` - Nome do tema, escolha em [todos os temas disponíveis](../themes/README.md)
- `cache_seconds` - Defina o cabeçalho do cache manualmente _(min: 14400, max: 86400)_
- `locale` - defina o idioma no cartão _(por exemplo. cn, de, es, etc.)_

> Nota sobre o cache: Cartões de repositório tem um cache padrão de 30 minutos (1800 segundos), se o número a contagem de forks e contagem de estrelas é menor que 1 mil o padrão é 2 horas (7200 segundos). Note também que o cache é limitado a um mínimo de 30 minutos e um máximo de 24 horas.

#### Opções exclusivas do cartão de estatísticas:

- `hide` - Oculta itens específicos das estatísticas _(Valores separados por vírgulas)_
- `hide_title` - Ocultar o título _(boolean)_
- `hide_rank` - Ocultar a classificação _(boolean)_
- `show_icons` - Mostrar ícones _(boolean)_
- `include_all_commits` - Contabiliza todos os commits ao invés de apenas os atual ano _(boolean)_
- `count_private` - Contabiliza commits privados _(boolean)_
- `line_height` - Define a altura do espaçamento entre o texto _(number)_

#### Opções exclusivas do cartão de repositórios:

- `show_owner` - Exibir o nome da pessoa a quem o repositório pertence _(boolean)_

#### Opções exclusivas do cartão de linguagens:

- `hide` - Oculta linguagens específicas _(Valores separados por vírgulas)_
- `hide_title` - Oculta o título _(boolean)_
- `layout` - Alterna entre os dois layouts disponíveis `default` & `compact`
- `card_width` - Define a largura do cartão manualmente _(number)_

> :warning: **Importante:**
> Nomes de linguagens devem ser uma sequência escapada de URI, como específicado em [Codificação por cento](https://pt.wikipedia.org/wiki/Codificação_por_cento)
> (Ou seja: `c++` deve se tornar `c%2B%2B`, `jupyter notebook` deve se tornar `jupyter%20notebook`, etc.)

---

# Pins extras do GitHub

Os Pins extras do GitHub permitem fixar mais de 6 repositórios no seu perfil usando um perfil README.me do GitHub.

Uhu! Você não está mais limitado a 6 repositórios fixados.

### Utilização

Copie e cole esse código no seu README.md e altere os atributos.

Endpoint: `api/pin?username=Netinhoalves&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Netinhoalves&repo=github-readme-stats)](https://github.com/Netinhoalves/github-readme-stats)
```

### Demonstração

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Netinhoalves&repo=github-readme-stats)](https://github.com/Netinhoalves/github-readme-stats)

Utilize a variável [show_owner](#personalização) para incluir o nome de usuário do proprietária do repositório

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Netinhoalves&repo=github-readme-stats&show_owner=true)](https://github.com/Netinhoalves/github-readme-stats)

# Cartão de principais linguagens de programação

Exibe uma métrica de linguagens de programação mais usadas pelo usuário do GitHub.

_Nota: As principais linguagens de programação não fazem declarações sobre habilidades pessoais ou similares, é apenas uma figura-chave com base nas estatísticas do GitHub do usuário indicando a frequência com que cada uma foi utilizada._

### Utilização

Copie e cole esse código no seu README.md e altere os atributos.

Endpoint: `api/top-langs?username=Netinhoalves`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Netinhoalves)](https://github.com/Netinhoalves/github-readme-stats)
```

### Ocultar linguagens individualmente

Utilize o parâmetro `?hide=language1,language2` para ocultar linguagens específicas.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Netinhoalves&hide=javascript,html)](https://github.com/Netinhoalves/github-readme-stats)
```

### Layout de cartão de linguagens compacto

Utilize a opção `&layout=compact` para mudar o layout do cartão.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Netinhoalves&layout=compact)](https://github.com/Netinhoalves/github-readme-stats)
```

### Demonstração

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Netinhoalves)](https://github.com/Netinhoalves/github-readme-stats)

- Layout compacto

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Netinhoalves&layout=compact)](https://github.com/Netinhoalves/github-readme-stats)

# Estatística semanal Wakatime

Altere o valor de `?username=` para o seu username do Wakatime.

```md
[![Netinhoalves's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=Netinhoalves)](https://github.com/Netinhoalves/github-readme-stats)
```

### Demonstração

[![Netinhoalves's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=Netinhoalves)](https://github.com/Netinhoalves/github-readme-stats)

[![Netinhoalves's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=Netinhoalves&hide_progress=true)](https://github.com/Netinhoalves/github-readme-stats)

---



### Todas as demonstrações

- Padronizado

![NetinhoalvesNetinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves)

- Ocultando estatísticas específicas

![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&hide=contribs,issues)

- Mostrando ícones

!Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&hide=issues&show_icons=true)

- Incluir todos os commits

![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&include_all_commits=true)

- Temas

Escolha entre um dos [temas predefinidos](#temas)

![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api?username=Netinhoalves&show_icons=true&theme=radical)

- Personalizando o cartão de estatísticas

![Netinhoalves's GitHub stats](https://github-readme-stats.vercel.app/api/?username=Netinhoalves&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

- Customizando o cartão de repositório

![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=Netinhoalves&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

- Principais linguagens

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Netinhoalves)](https://github.com/Netinhoalves/github-readme-stats)

---
