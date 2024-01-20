
Display no CSS

O que é a Propriedade Display?
A propriedade display em CSS determina o comportamento de um elemento em relação ao layout. Ela define como um elemento é renderizado na página, afetando seu modelo de caixa, empilhamento e interação com outros elementos.


Tipos de Displays Principais

1. Block

.box {
    display: block;
    background: #ff1395;
    height: 50px;
    width: 50px;
}


Características:

Ocupa 100% da largura do elemento pai.
Sempre ocupa toda a sua linha.
Altura definida de acordo com o conteúdo.
Pode-se definir height e width.
Pode-se definir valores de margin.


Inline

.box-2 {
    display: inline;
    background: yellow;
}


Características:

Elementos em linha.
Não permite alterar height e width.
Não pode-se definir valores de margin-top e margin-bottom.
Ganha comportamento de uma palavra.


3. Inline-Block

.box-3 {
    display: inline-block;
    background: blue;
}


Características:

Elementos em linha, porém com características do display block.
Altura e largura podem ser alteradas.


Escolhendo o Tipo de Display

Block: Use quando precisar de elementos que ocupem uma linha inteira, como divisões de layout (div), seções (section), parágrafos (p), títulos (h1, h2), entre outros.

Inline: Utilize para elementos em linha, como links (a), spans (span), texto em negrito (b), texto em itálico (i), etc.

Inline-Block: Ideal quando deseja combinar a natureza em linha com a capacidade de ajustar altura e largura, proporcionando flexibilidade de layout.

Escolha o tipo de display com base nas necessidades específicas do seu layout, permitindo a criação de designs mais eficientes e flexíveis. Experimente cada opção para entender como ela afeta o posicionamento e o comportamento dos elementos em sua página.