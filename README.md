# grid-css
Responsive Grid, criado com a feature do css3 **Grid Layout**

## Breakpoints (Media Queries)
* Phone = Até 599px;
* Tablet (Portrait and Landscape) = 600px até 1200px;
* Desktop = 1200px até 1800px;
* Big Desktop = 1800px ...

## Sintaxe
* Phone =  `col_p_*`
* Tablet (Portrait and Landscape) = `col_t_*`
* Desktop = `col_d_*`
* Big Desktop = `col_bd_*`

> `*` : Número de colunas 

## Como usar
1. Importe o css para o html;
2. Defina um elemento pai com a classe `grid`;
3. Adicione as classes nos elementos filhos de acordo com o breakpoint que você deseja

>Exemplo
```
<link rel="stylesheet" href="dist/grid.min.css">

<section class="grid">
    <div class="col_p_12 col_t_6">
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla velit deleniti accusamus quae.</span>
    </div>
</section>
```
