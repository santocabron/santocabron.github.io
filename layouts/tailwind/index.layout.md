---
name: index
---
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>{{page.title}}</title>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <link rel="stylesheet" href="/stylesheets/stylesheet.css">
    <style>
      {{page.inline_styles}}
    </style>
  </head>
  <body>
    <header class="relative
      z-10
      pt-[120px]
      px-4
      md:pt-[130px]
      lg:pt-[160px]
      pb-[100px]
      bg-primary
      overflow-hidden">
      <div class="inner">
          <h1>Welcome to {{page.name}}</h1>
          <h2>{{page.description}}</h2>
      </div>
    </header>
      <div class="container">
        <div class="inner">
          {{{page.html}}}
        </div>
      </div>
  </body>
</html>
