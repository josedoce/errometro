# errometro


```html
<body>
<div class="errometro">
  <button onclick="dialog(content1)">open modal 1</button>
  <button onclick="dialog(content2)">open modal 2</button>
  <button onclick="dialog(content3)">open modal 3</button>
</div>
<script src="./script.js"></script>
<script>
  const av1 = new Aviso("Aviso 1", "conteudo da mensagem 1");
  const content1 = av1.content
  
  const av2 = new Aviso("Aviso 2", "conteudo da mensagem 2");
  const content2 = av2.content
  
  const av3 = new Aviso("Aviso 3", "conteudo da mensagem 3");
  const content3 = av3.content
</script>
</body>
```

