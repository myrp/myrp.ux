<p align="center">
  <img width="200" src="./assets/img/logo.png" alt="Logo do myrp">
  <br>
</p>

## Resources
> Links úteis relacionados à UI e UX

### myrp
- [myrp Analytics](https://github.com/myrp/myrp.home/blob/master/Documentation/analytics.md#myrp-analytics) - GA, Amplitude, Hotjar, Pipz e InvisionApp.

## Framework de perguntas para entrevista
### Esquenta:
- Qual sua profissão?
- Você pode contar um pouco sobre seus hobbies?
- Com que frequência você usa a internet?
- Com que frequência você faz compras online?
- Com que frequência você utiliza o myrp?

### Sistema:
- Quais são os módulos que mais utiliza?
- Conte-nos quando foi a última vez que utilizou o myrp.
- De 0 a 10, que nota você daria ao myrp?

### Específica:
- Você sente alguma dificuldade ao utilizar a rotina de (NOME_DA_ROTINA)?
- Você tem alguma sugestão de melhoria da rotina de (NOME_DA_ROTINA) que acha válido compartilhar?

### Pontuação por Tema
- Facilidade	0-10
- Visual		0-10
- Agilidade	0-10

### Design Systems
- [Awesome Design Systems](https://github.com/alexpate/awesome-design-systems)

### Material Design
- [Web Fundamentals - Best practices for modern web development](https://developers.google.com/web/fundamentals/design-and-ux/ux-basics/)
- [Guidelines](https://material.io/archive/guidelines/) (old)
- [Guidelines](https://material.io/design) (new)
- [Material Icons](https://material.io/icons/)
- [Material Web Components](https://material-components-web.appspot.com/) (old) 
- [Material Web Components](https://material-components.github.io/material-components-web-catalog) (new)
- [Materialize](http://materializecss.com/)
- [Google Design](https://medium.com/google-design)

## Tools
> Ferramentas para os processos de UI e UX

### Fluxogramas
- [Whimsical](https://whimsical.co) - Flowchart, Wireframes e Sticky Notes

### Wireframes
- [Balsamiq](https://balsamiq.com) - Ferramenta para sketch e wireframe
- [Adobe XD](https://www.adobe.com/products/xd.html) - Ferramenta para wireframe e prototipação

### Feedback
- [InvisionApp](http://invisionapp.com) - Plataforma para criar protótipos interativos, whiteboards e coletar feedback
- [Gallery](https://gallery.io) - Plataforma colaborativa para compartilhar e organizar protótipos
- [Red Pen](https://redpen.io) - Ferramenta para compartilhar protótipos e coletar feedback via comentários
- [UsabilityHub](https://usabilityhub.com) - Ferramenta para compartilhar e validar protótipos
- [Optimal Workshop](https://www.optimalworkshop.com) - Ferramenta para compartilhar e validar protótipos
- [Maze](https://maze.design) - Ferramenta para compartilhar e validar protótipos interativos do InvisionApp

### Cores
- [Material Palette Generator](https://material.io/design/color/the-color-system.html#tools-for-picking-colors) - Paleta de cores do Material Design 2018
- [Material Color Tool 2014](https://material.io/tools/color) - Paleta de cores do Material Design 2014
- [Color Contrast Checker](https://webaim.org/resources/contrastchecker/) - Verifica o constrate entre duas cores de acordo com o [WCAG 2.0](https://www.w3.org/TR/WCAG20/)
- [Adobe Color CC](https://color.adobe.com/pt/create/color-wheel/) - Cria combinações de cores e color schemes

### Outros
- [Dropmark](http://dropmark.com) - Organizador de links e imagens em coleções
- [Dummi](http://dummi.io/) - Gerador de dados fake
- [unDraw](https://undraw.co/illustrations) - Ilustrações (MIT licensed)

## Férias

### Como atualizar o changelog?
- Abrir visual studio code em /erp/solutions/cdn
- Adicionar imagens e videos em /erp/solutions/cdn/myrp/static
- Alterar arquivo changelog.json em /erp/solutions/cdn/myrp/static
- Após fazer as alterações gerar o bundle utilizando `Atualizar.bat`

```
Exemplo arquivo de changelog.json:

[
  // Primeiro changelog
  {
    "validade": "01/01/0001", // Preecha com a validade de exibição
    "url": "?efetuandoLogin=1", // Preencha com parte da url onde o changelog deverá ser exibido, neste caso ao efetuar login
    "uf": "", // Preencha com o código da uf se o changelog for para uma uf específica
    "permissao": "", // Preecha com o código da permissão se o changelog for para uma permissão específica
    "itens": [
      {
        "arquivo": "/cdn/myrp/static/imagem.png", // Preencha com a url da imagem ou video do slide
        "url": "/financeiro/titulobeta", // Preencha com a url de redirecionamento ao clicar no botão "call to action" do slide
        "titulo": "", Preencha com o título do slide
        "texto": "", // Preencha com o texto do slide
        "textoBotao": "" // Preencha com o texto do botão "call to action" do slide
      }
    ]
  },
  // Outro changelog
  {
    "validade": "",
    "url": "",
    "uf": "",
    "permissao": "",
    "itens": [
      {
        "arquivo": "",
        "url": "",
        "titulo": "",
        "texto": "",
        "textoBotao": ""
      }
    ]
  }
]

Quando não tiver changelogs:
[]
```

### Como atualizar o financeiro?

- Abrir visual studio em /erp/solutions/financeiro
- Alterar arquivo views/titulobeta/index.cshtml

### Como atualizar a integração contábil?

- Abrir visual studio code em /integracaocontabil.frontend
- Após fazer as alterações gerar o bundle utilizando `Atualizar.bat`
