[M2S04] Ex 5 - Tela de Bicicletas (Parte 2)

Desenvolver a tela de biciletas seguindo o padrão presente em: https://www.origamid.com/projetos/bikcraft/bicicletas.html

Para cada botão inserido de “mais sobre” relacionados a bicicleta, realizar uma ação de onclick no botão e chamar uma função no javascript.
A função deve receber qual o código da bicicleta selecionado e gerar um log no console contendo a seguinte informação:

‘Ir para a página da bicicileta ${nome_bicicleta}’



Para capturar o nome da bicicleta, deverá ter um array no javascript com o conteúdo abaixo e realizar busca via ID:

const bicicletas = [
{ id: 1, name: 'Nimbus Stark', price: 4999 },
{ id: 2, name: 'Magic Might', price: 2499 },
{ id: 3, name: 'Nebula Cosmic', price: 3999 },
]