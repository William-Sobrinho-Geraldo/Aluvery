# Aluvery App  

## Resumo 
Trata-se de um aplicativo para listar produtos de uma loja separados em categorias, também é possível realizar uma pesquisa na base de dados e encontrar um produto específico. 

## Detalhamento
Desenvolvido com o mais novo framework para criação de interfaces do google, o **Jetpack Compose**, o app Aluvery nasceu como uma forma de praticar os conceitos de criação de telas ensinados no curso de Jetpack Compose da Alura. Esse framework tem como objetivo tornar a criação de interfaces mais intuitiva e rápida, visto que desde a primeira versão do Android ainda é utilizado o método de criação de telas via XML.

Neste app é possível realizar filtro de busca dos produtos pelo nome ou pela descrição do produto. Adicionar novos produtos, cada um deles com nome, preço, descrição e uma imagem. Além disso, o app classifica os produtos em diferentes categorias para melhor apresentar um conjunto de produtos.

</br>

## Imagens do App

<div align="center"> 
<img src = "https://user-images.githubusercontent.com/111225477/225419430-b9c4e5c6-b959-40ff-a4e1-3caf1d5bb1b9.png" width = "200px" >
<img src = "https://user-images.githubusercontent.com/111225477/225419855-31768d45-03e2-4ae7-957d-92c586cb1bc2.png" width = "200px" >
<img src = "https://user-images.githubusercontent.com/111225477/225419433-05650e28-5660-4a38-bd53-2f3b5c94450a.png" width = "200px" >

</div>

</br>

## Conceitos praticados
- Utilização de composables de listas infinitas como [LazyColumn](https://developer.android.com/reference/kotlin/androidx/compose/foundation/lazy/package-summary?authuser=3#LazyColumn(androidx.compose.ui.Modifier,androidx.compose.foundation.lazy.LazyListState,androidx.compose.foundation.layout.PaddingValues,kotlin.Boolean,androidx.compose.foundation.layout.Arrangement.Vertical,androidx.compose.ui.Alignment.Horizontal,androidx.compose.foundation.gestures.FlingBehavior,kotlin.Boolean,kotlin.Function1)) e [LazyRow](https://developer.android.com/reference/kotlin/androidx/compose/foundation/lazy/package-summary?authuser=3#LazyRow(androidx.compose.ui.Modifier,androidx.compose.foundation.lazy.LazyListState,androidx.compose.foundation.layout.PaddingValues,kotlin.Boolean,androidx.compose.foundation.layout.Arrangement.Horizontal,androidx.compose.ui.Alignment.Vertical,androidx.compose.foundation.gestures.FlingBehavior,kotlin.Boolean,kotlin.Function1))
- Criação e reutilização do card de cada item
- Uso de [OutlinedTextField](https://developer.android.com/jetpack/compose/text?hl=pt-br) para filtrar produtos
- Uso de [StateHolders](https://developer.android.com/topic/architecture/ui-layer/stateholders?hl=pt-br) para gerenciar os estados dos composables
- Versões Stateless e Statefull da HomeScreen
- Utilização da biblioteca [Coil](https://github.com/coil-kt/coil) para download de imagens de forma assincrona
