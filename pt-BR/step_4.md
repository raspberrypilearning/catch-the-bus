## O hipopótamo alcança o ônibus voando

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Você vai adicionar um ator hipopótamo que voa até o ônibus.
</div>
<div>

![O hipopótamo voando para o ônibus.] (Images/hippo-flies.png) {:width="300px"}

</div>
</div>

O ator**Hippo1** tem duas fantasias com asas em posições diferentes, para que uma animação possa ser feita do ator voando até o ônibus.

--- task ---

Adicione o ator**Hippo1** ao seu projeto.

Mude o **Tamanho** do ator**Hippo1**:

![O painel Ator para o ator Hippo1, com o tamanho 50.](images/hippo-sprite-size.png)

--- /task ---

--- task ---

Arraste o hipopótamo para o lado esquerdo superior do Palco.

![O ator Hippo1 no lado superior esquerdo do Palco.](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

Adicione o código para fazer o hipopótamo voltar à posição inicial:

```blocks3
when flag clicked
go to x: [-200] y: [150] // top left-hand side
```

**Dica:** As coordenadas `x`{:class="block3motion"} e `y`{:class="block3motion"} no bloco `go to x: y:`{:class="block3motion"} vão ser a posição atual do hipopótamo, assim você não precisa digitar elas.

--- /task ---

O hipopótamo voará em direção ao ônibus, batendo as asas.

Antes de começar a se mexer, o hipopótamo vai `apontar para`{: class = "block3motion"} o ônibus.

--- task ---

Adicione código para fazer a hipopótamo voar até o **Ônibus Cidade**:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+repeat [100] 
point towards (City Bus v) // change from mouse-pointer
move [3] steps
next costume
+end
```

--- /task ---

--- task ---

**Teste:** Clique na bandeira verde e veja se o hipopótamo voa em direção ao ônibus. Você pode alterar o número que está no bloco `repeat`{:class="block3control"} para fazer o hipopótamo parar no lugar certo.

--- /task ---

Agora, o hipopótamo vai entrar no ônibus.

--- task ---

Adicione os blocos `show`{:class="block3looks"} e `hide`{:class="block3looks"}:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+ show
repeat [90] 
point towards (City Bus v)
move [3] steps
next costume
end
+ hide
```

--- /task ---

--- task ---

**Teste:** Clique na bandeira verde. O hipopótamo vai voar e entrar no ônibus.

--- /task ---

--- save ---
