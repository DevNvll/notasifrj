# notasifrj.js
Funções em JavaScript para o cálculo de notas do IFRJ.

Essa desgraça podia ser simples como as outras escolas mas nãããão, somos INSTITUTO FEDERAL, bora botar mv1 + (2*mv2)/3.

## Uso Básico

``<script src="algebra.min.js"></script>``

``<script src="notasifrj.min.js"></script>``

``<script>document.write(ifrj.mediaFinal(70, 65));</script>``

``<script>document.write(ifrj.quantoFalta(70));</script>``

## Métodos

### ifrj.mediaFinal(mv1, mv2);
Calcula a média final a partir das suas notas no MV1 e MV2.

### ifrj.quantoFalta(mv1);
Retorna a nota que você precisa tirar no MV2 para ter 60 de média final.

### ifrj.recuperacao(nota);
Retorna a nota que você precisa tirar na recuperação para ficar com média azul. Onde ``nota`` é a nota da prova que você ficou em recuperação.



## Disclaimer
O cálculo é referente ao Campus de Arraial do Cabo/RJ e não sei se é o mesmo para os demais.

Utilizei a biblioteca [algebra.js](http://algebra.js.org/) para facilitar minha vida, já que o JavaScript não tem nada pra resolver equações e expressões facilmente built-in e fazer com as ferramentas nativas iria ser um saco.

## Licensa

MIT
