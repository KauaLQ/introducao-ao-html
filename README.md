<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=e54e23&height=120&section=header"/>

# introducao-ao-html <img width='70' heigth='70' src="site/img/logo_HTML.png" />
#### Olá, _WebDev's_! Este é um repositório onde armazenei meus estudos iniciais sobre HTML, oferecidos pela residência em TIC ofertada pela UECE em parceria com o Instituto Atlântico. Neste repositório, você encontrará exemplos básicos e aplicações práticas que explorei durante o curso, desde a estruturação de páginas até o uso de tags mais comuns como cabeçalhos, listas, links, imagens e formulários.

#### Além disso, também incluí o resultado da primeira oficina prática do curso: uma página web desenvolvida puramente com HTML. Esta página reflete a aplicação dos conceitos fundamentais de marcação, hierarquia e organização de conteúdo, sem o uso de CSS ou JavaScript, permitindo focar exclusivamente na estruturação correta do HTML.

#### Sinta-se à vontade para explorar, estudar e contribuir!

#

#### HTML (HyperText Markup Language) é a linguagem base para a criação de páginas web. Ela estrutura o conteúdo de uma página, organizando textos, imagens, links e outros elementos. Ao contrário de linguagens de programação, o HTML é uma linguagem de marcação, ou seja, ele utiliza tags para identificar e descrever partes de um documento.

### Estrutura básica de uma página HTML
#### Uma página HTML é composta de várias tags que organizam o conteúdo. A estrutura básica inclui as seguintes partes:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
</head>
<body>
    <h1>Bem-vindo ao HTML!</h1>
    <p>Esta é a estrutura básica de uma página HTML.</p>
</body>
</html>
```
### Explicação:
- `<!DOCTYPE html>`: Define o documento como HTML5.
- `<html>`: Tag que engloba todo o conteúdo da página.
- `<head>`: Contém informações sobre a página, como codificação e título.
- `<meta charset="UTF-8">`: Define a codificação de caracteres para exibir corretamente acentos e símbolos.
- `<title>`: Define o título que aparece na aba do navegador.
- `<body>`: Onde o conteúdo visível da página é colocado (texto, imagens, links, etc.).

### Tags mais utilizadas
#### 1. Tags de Cabeçalho (`<h1>` a `<h6>`)
#### Utilizadas para criar títulos e subtítulos, onde `<h1>` é o título principal, e `<h6>` o menos importante.

#### Exemplo:

```html
<h1>Título Principal</h1>
<h2>Subtítulo</h2>
```

### 2. Parágrafos (`<p>`)
#### Utilizada para criar blocos de texto.

#### Exemplo:

```html
<p>Este é um parágrafo de exemplo.</p>
```

### 3. Links (`<a>`)
#### Utilizada para criar hyperlinks.

#### Exemplo:

```html
<a href="https://www.example.com">Visite o site</a>
```

### 4. Imagens (`<img>`)
#### Utilizada para exibir imagens.

#### Exemplo:

```html
<img src="imagem.jpg" alt="Descrição da imagem">
```

### 5. Listas
#### Existem dois tipos principais: ordenadas (`<ol>`) e não ordenadas (`<ul>`).

#### Exemplo de lista não ordenada:

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

#### Exemplo de lista ordenada:

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
</ol>
```

### 6. Div e Span
#### Tags de divisão (`<div>`) e de linha (`<span>`) são usadas para agrupar e estilizar blocos de conteúdo.

#### Exemplo:

```html
<div>
    <span>Texto dentro de uma span.</span>
</div>
```
### 7. Formulários (`<form>`)
#### A tag `<form>` é utilizada para criar formulários de entrada de dados, permitindo que os usuários enviem informações para um servidor. Dentro de um formulário, usamos vários elementos de entrada, como campos de texto, botões de envio, caixas de seleção, entre outros.

#### Exemplo básico de um formulário:

```html
<form action="/enviar" method="post">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <input type="submit" value="Enviar">
</form>
```

#### Explicação:
- `<form>`: Define o início do formulário. Os atributos principais são:
  - `action`: Define a URL para onde os dados serão enviados.
  - `method`: Define o método de envio, como GET ou POST.

- `<label>`: Cria uma etiqueta para o campo de entrada, associada ao campo pelo atributo `for`, que corresponde ao `id` do campo.

- `<input>`: Define os campos de entrada. Existem diferentes tipos de campos, como:
  - `type="text"`: Campo de texto simples.
  - `type="email"`: Campo específico para email.
  - `type="submit"`: Botão para enviar o formulário.

---

### _Gostou do meu perfil? Você pode saber mais sobre mim em:_ &nbsp;&nbsp;[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaualimaq/)
### _Ou me contatar através do:_ &nbsp;&nbsp;[![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:limakaua610@gmail.com)
### _Referência:_
[1] Slides do curso Desenvolvimento FullStack | Capacita Jovem Aula 03 e 04. Disponível em: https://view.genially.com/66ffe4752d5def7b8a9296b9/interactive-content-aula-03-04-html

[2] Repositório base. Disponível em: https://github.com/vaghenrique/capacita-Brasil-n2-n5
