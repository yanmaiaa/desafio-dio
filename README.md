# Estrutura dos métodos em Java ⚡

[![Github Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yanmaiaa)
[![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yan-maia-b09546119/)
[![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yandamasceno01@gmail.com)
[![Medium Badge](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://yandamasceno01.medium.com/)
![Java Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)

## Você de fato entende o que acontece quando cria ou utiliza um método? Então vamos entender com um passo a passo rápido e fácil: 

Através de um método um objeto pode ter atributos modificados, interagir com outros objetos e assim por diante, por isso é importante que tenhamos um entendimento acerca da sua estrutura no momento em que iremos criar os nossos. Assim, seguindo o “fluxo”, quando utilizamos um método no java temos a seguinte estrutura ilustrada abaixo:

![image](https://user-images.githubusercontent.com/62847842/147023901-47c4cfb1-091c-4a24-8b3f-278c3727f00e.png)

Onde temos:

1. modificadorDeAcesso: É uma espécie de regra de visibilidade para que possamos acessar classes e membros de uma classe como atributos e métodos. Tendo posse disso, de forma rápida e objetiva, construí um diagrama que resume toda a explicação e ilustra melhor o que cada modificador permite no momento em que são utilizados, para que vocês usem de forma consciente:

![image](https://user-images.githubusercontent.com/62847842/147024036-e979ae37-68f5-45d6-ac5a-f7cbd8c2ad5b.png)

![image](https://user-images.githubusercontent.com/62847842/147024185-07dcb819-d49e-469b-b93b-61119a9a8657.png)

2. tipoDoRetorno: Refere-se ao tipo de dado que o método deve retornar. Pode ser qualquer tipo, incluindo o de classes construídas por nós. O que devemos lembrar, é que sempre que existir um tipo de retorno, o que fará com que o método esteja dentro dos conformes com base na sua sintaxe para executar o que precisa, é a palavra reservada “return”, que retornará um resultado para o método que o chamou. Porém, caso queiramos construir um método que não retorne nada, precisamos utilizar de forma obrigatória a palavra “void” no tipo de retorno, assim, estaremos dizendo para o método: “Olha método, eu não quero retornar um valor aqui”, porém, é importante saber que mesmo que não exista a necessidade de utilizar o “return”, o mesmo pode ser utilizado de forma opcional.
3. nomeDoMetodo: De forma prática e óbvia, é o nome dado ao método.
4. parametros: São variáveis que recebem um valor dos argumentos passados para um método no momento em que ele é chamado. Porém, se não houver parâmetros a serem passados o conteúdo dentro dos parênteses deve estar vazio, pois, quando precisamos passá-los, é importante lembrar que os parâmetros serão uma sequência de par que seria o tipo e um identificador sendo que, quando precisarmos passar mais de um, os separaremos por vírgula, assim como será mostrado abaixo:

![image](https://user-images.githubusercontent.com/62847842/147024249-39d5ce5d-a553-4ba6-916e-190ee82ed0ef.png)

Assim, finalizamos a nossa rápida abordagem acerca da estrutura de um método, que é tão utilizado no dia a dia de todo e qualquer programador. Mas aí nos perguntamos: “É só isso?”, bom…é só isso, porém existem outras questões que podem ser melhor aprofundadas envolvendo um método, mas como não é o objetivo desta nossa breve discussão, encerro por aqui e trarei ainda mais sobre o java e tudo o que venho aprendendo no meu dia a dia para que outras pessoas possam entender de forma facilitada.
