### Questo file contiene una serie di _snippet_ (pezzetti) di codice utili per il tema di WordPress. Ogni snippet fa qualcosa di diverso (leggete il titolo all'inizio di ciascun snippet per capire a cosa serve)

###### Cancellare la scritta di Altervista che compare nel piede del sito. Il codice va messo all'inizio del file "style.css" (più o meno alla riga 56) del vostro tema

`.av-credit-link {
    visibility: hidden;
    display: none;
}`

###### Nascondere un qualsiasi elemento con i CSS. La classe "nascosto" andrà attribuita all'elemento, ad esempio così:

`<h1 class="nascosto">Non puoi vedermi.</h1>`

`.nascosto {
    visibility: hidden; /*non mostrare l'elemento nemmeno agli screen reader*/
    display: none; /*non mostrare l'elemento agli occhi di chi vede il sito*/
}`
