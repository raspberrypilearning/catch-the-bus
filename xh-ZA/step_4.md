## Umvubu uyabhabha ukuya ebhasini

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Faka isprite esingumvubu esibhabhayo ukuya ebhasini.
</div>
<div>

![Umvubu uyabhabha ukuya ebhasini.](images/hippo-flies.png){:width="300px"}

</div>
</div>

### Nika uMvubu indawo yokuqala

--- task ---

Yongeza isprite so**Mvubu1** kwiprojekthi yakho.

Tshintsha **Ubungakanani** besprite so **Mvubu1**:

![Ipheyini yesprite, isprite uMvubu1, esinobungakanani obumiselwe ku- 50.](images/hippo-sprite-size.png)

--- /task ---

--- task ---

Tsala umvubu uye kwicala lasekhohlo eliphezulu kwiQonga.

![I-Spritr uMvubu1 kwicala eliphezulu lwasekholo eQongeni.](images/hippo-sprite-stage.png)

--- /task ---

--- task ---

Yongeza ikhowudi yokubeka umvubu kwindawo yayo yokuqala:

```blocks3
when flag clicked
go to x: [-200] y: [150] // icala eliphezulu lasekhohlo
```

**Ingcebiso:** Ulungelelaniso `x`{:class="block3motion"} no-`y`{:class="block3motion"} kwiblokhi `iya ku x: y:`{:class="block3motion"} lizakuba yile ndawo umvubu wakho ume kuyo, awudingi kuyixhaxhaza.

--- /task ---

### Yenza uMvubu uphaphazelise iimphiko zayo ibhabhe

--- task ---

Faka ikhowudi yokwenza umvubu ubhabhele ngakwi **Bhasi yeSixeko**:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+repeat [100] 
point towards (iBhasi YesiXeko v) // tshintsha usuka kwisalathisi se mausi
move [3] steps
next costume
+end
```

--- /task ---

--- task ---

**Uvavanyo:** Cofa kwiflegi eluhlaza ukuze ujonge ukuba umvubu ubhabhela ebhasini. Ungatshintsha inani kwibhloki `phinda`{:class="block3control"} ukuze umvubu ume kwindawo elungileyo.

--- /task ---

### Bonisa uphinde ufihle ibhasi

--- task ---

Yongeza iibhloki u`bonisa`{:class="block3looks"} kunye no`fihla`{:class="block3looks"}:

```blocks3
when flag clicked
go to x: [-200] y: [150] 
+ show
repeat [90] 
point towards (iBhasi YesiXeko v)
move [3] steps
next costume
end
+ hide
```

--- /task ---

--- task ---

**Uvavanyo:** Cofa kwiflegi eluhlaza. Umvubu uza kubhabha ungene ebhasini.

--- /task ---
