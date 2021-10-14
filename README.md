# tp1-frameworks

## Teste de Performance 1 da disciplina Frameworks Front-End e Conexão com Back-End do bloco de Front-End


### Running the code
Clonar o repositório e abrir com o Live Server


### Questão 1
a. O MVVM é um modelo criado para aplicações web responderem mais rapidamente com a interação do usuário. Ele tem uma comunicação mais direta com a visão, não tendo a camada de Controle.

b. View, Data Binder, View-Model e Model

### Questão 2
No modelo MVC a camada de Visão(V) é a responsável por mostrar as informações ao usuário e comunica-se com a Controle(C), que é uma "intermediária". Esta recebe as ações do usuário, comunica-se com a camada Modelo(M), utiliza-se das regras de negócio que estão alocadas lá, e transformam os dados para jogar na camada V. O caminho inverso também: o usuário envia dados e a camada C transforma esses dados para serem persistidos camada M. No modelo MVVM, a camada de Visão(V) faz o mesmo papel do que no MVC, porém as decisões lógicas do que será exibido na tela estão na camada VM(View-Model). Não possui a camada C e possui uma camada chamada Data Binder para fazer a conexão das V's com suas respectivas VM's.

### Questão 3
Uma aplicação é reativa quando ela recebe algum tipo de dado ou mudança no estado da aplicação, consegue enviar essa mudança para toda a aplicação, faz uma renderização automática de acordo com essas informações e dão um feedback ao usuário sobre o que foi feito. Um exemplo é uma curtida em algum post do Facebook: o usuário curte e, logo em seguida, o contador de Likes aumenta sem precisar atualizar a página inteira.

### Questão 4
a. 'v-if'

b. 'v-show'. A diretiva 'v-if' é usada para renderizar um bloco de acordo com uma condição. O bloco só será renderizado se a expressão da diretiva retornar um valor verdadeiro. No caso do 'v-show' o bloco será renderizado de qualquer maneira, porém se a expressão retornar um valor falso, a diretiva usará o CSS para não mostrar o conteúdo utilizando a regra 'display: none;'.

### Questão 5
Usando o 'double moustache' englobando o nome da variável.

### Questão 6
a. É um DOM criado pelo Vue que pode alterar o HTML de forma mais rápida que o DOM do browser.

b. É, também, por conta do Loop de Eventos que as mudanças ocorrem em tempo real. Quando algum dado sofre alteração, o DOM virtual é renderizado novamente e esse alter ao DOM do browser na hora.

### Questão 7
Quando queremos fazer um loop e exibir uma lista de elementos.

### Questão 8
{{ coisa | tudoMinusculo }} onde tudoMinusculo é um filtro que transforma todas as letras em
letras minúsculas.

``
filters: {
 tudoMinusculo: function (coisa) {
 return valor.toLowerCase();
 }
}
``

### Questão 9
Abre precedente para alguém passar um script html e achar uma brecha no seu site.

### Questão 10
- Código deste repositório
