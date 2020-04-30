## Unindo branches ##

### Passo a passo do rebase ###
### Estado inicial ###
> Com 2 branches `experiment` e `master` e commits a partir do `C2` criando `C3` e `C4` 
[![Banner](../.github/assets/entendendo-rebase-img1.png)](#)

### Durante o processo ###
> Diferente do merge ele coloca em linha ficando `C3'` ficando na frente do `C4`
[![Banner](../.github/assets/entendendo-rebase-img2.png)](#)

### Final do rebase ###
> E por fim tanto a branch `master` como `experiment` apontará para o mesmo commit `C3`
[![Banner](../.github/assets/entendendo-rebase-img3.png)](#)

### Pro ### 
* Evita commit extras
* Histórico linear
  
### Contra ###
* Perde a ordem cronológica