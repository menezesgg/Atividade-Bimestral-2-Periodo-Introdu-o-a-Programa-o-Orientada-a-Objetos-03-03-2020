# Atividade-Bimestral-2-Periodo-Introdu-o-a-Programa-o-Orientada-a-Objetos-03-03-2020
ATIVIDADE BIMESTRAL                                                                                         NOTA:
Disciplina: Introdução a Programação Orientada a Objetos
Nome do(a) Alexandre Menezes Gomes  Matrícula 201920003
Turma Data DS201N219 03/04/2020 Professor(a) Pabllo Borges Cardoso

INSTRUÇÕES
1. Este exercício é individual e com consulta;
2. Cada aluno deverá entregar o seu exercício evidamente preenchido e identificado, a falta de identificação acarretará a anulação;
3. Entender o exercício faz parte dele;
4. Todas as respostas devem ser fundamentadas no conteúdo da disciplina;
5. Utilizar este documento como gabarito de resposta;
6. O projeto referente aos exercícios práticos deve ser inseridos em um repositório online (Google Drive, Dropbox ou OneDrive) e compartilhados no e-mail pabllobc@gmail.com;
7. Respostas das questões objetivas devem ser encaminhadas para o e-mail pabllobc@gmail.com neste gabarito;
8. O nome do arquivo deve seguir o formato [nomedoalunocompleto-10032020.docx];
9. O mesmo nome do arquivo deve ser o do assunto do e-mail; 10. O início do trabalho e o prazo para o compartilhamento e o envio do e-mail será entre 18:30 até as 22:00.

ATIVIDADES 
Questão 01 – A história do Java começa em 1991, em San Hill Road empresa filiada a Sun (da qual hoje pertence a empresa Oracle), formado pelo time de engenheiros liderados por Patrick Naugthon, Sun Fellow e James Gosling. O grupo estava iniciando um projeto denominado Projeto Green, que consistia na criação de tecnologias modernas de software para empresas eletrônicas de consumo. A ideia principal era que os aparelhos eletrônicos se comunicassem entre si. Por exemplo, o caso de possuir um fogão, você poderia deixar assando sua comida e quando estivesse pronta iria enviar uma mensagem para o microondas ligar e após isso tocar o seu despertador, sendo algo do gênero. Com o tempo perceberam que não poderiam ficar presos aos sistemas operacionais, até porque os clientes não estavam interessados no tipo de processador que estavam utilizando, e sim na tecnologia. Portanto para o grupo criar uma versão do projeto para cada tipo de sistema era inviável, sendo assim, foi desenvolvido o sistema operacional GreenOS. Dada tamanha proporção que o Java tem hoje no cenário mundial é considerada à linguagem mais utilizada do momento, abaixo descreva o significado de cada uma das características da linguagem exemplificando para justificar sua resposta:
a) Portabilidade; No contexto da informática, a portabilidade de um programa de computador é a sua capacidade de ser compilado ou executado em diferentes arquiteturas(seja de hardware ou de software). O termo pode ser usado também para se referir a reescrita de um código fonte para uma outra linguagem de computador.
Java, por exemplo, é uma linguagem de programação portável já que basta compilar a aplicação uma vez apenas para que essa possa ser executada em qualquer plataforma que possua a respectiva máquina virtual Java (também conhecida por JVM). Não existe a necessidade de produzir uma versão compilada para cada sistema computacional em que se deseje executar a aplicação.
b) Interpretada; (o compilador pode executar os bytecodes do Java diretamente em qualquer máquina); É essa característica que faz com que os programas Java sejam independentes de plataforma, executando em qualquer sistema que possua uma JVM. Cada opcode tem o tamanho de um byte— daí o seu nome — e assim o número de diferentes códigos de operação está limitado a 256. Os 256 possíveis valores para códigos de operação não são todos utilizados. Na verdade, alguns dos códigos foram inclusive reservados para nunca serem implementados.
Um programador Java não precisa entender — e nem tomar conhecimento — dos bytecodes Java para ser proficiente na linguagem, da mesma forma que um programador de qualquer linguagem de alto nível compilada para linguagem de máquina não precisa conhecer a linguagem de montagem do computador hospedeiro para escrever bons programas naquela linguagem.

c) Independente de plataforma; O Java é compilado e independente de plataforma: Um programa escrito em Java precisa ser compilado antes de ser executado. O compilador traduz o código-fonte e gera arquivos objeto chamados arquivos de classe. Cada programa Java consiste da implementação de uma única classe. Depois de compilado, pode ser executado em qualquer plataforma onde exista um sistema de tempo de execução Java (runtime).

d) Case-sensitive: Significa que caracteres em caixa alta e em caixa baixa são tratados de modo diferente. Por exemplo, as palavras sum e SUM são consideradas diferentes. A linguagem Java é case-sensitive. 

e) Tipada (detecta os tipos de variáveis quando declaradas).  Linguagem fortemente tipada, resumindo, seria aquela em que os objetos/variáveis tem um tipo bem definido e que precisa ser informado no momento de sua declaração.
Um exemplo de linguagem que não é fortemente tipada é o PHP. Nela não é preciso definir o tipo das variáveis ao declará-las, e esse tipo pode ser alterado em tempo de execução. Assim, uma mesma variável pode receber valores numéricos, texto, booleanos, etc. 

Questão 02 – Na linguagem de programação Java, todas as classes descendem de uma Super Classe
chamada Object, assim “tudo” em Java é um objeto. Aponte a alternativa onde contém a CORRETA
assinatura do principal método de execução de uma classe, as outras alternativas justifique o que está errado na assinatura.
A) public static void Object(String [ ] args){ //Código }
//correto
B) private static void Main(String [ ] args){ /* Código */ }
// erro de semantica em “Main”, sendo o correto ‘main’.
C) private static void object(String [ ] entrada){ //Código }
// erro de semantica em “object”, sendo o correto ‘Object’.
D) public static void main(String [ ] entrada){ /* Código */}
//correta
Questão 03 – O Java é uma linguagem orientada a objetos e por isso, abaixo estão descritos os pilares da abstração. Descreva o conceito de cada um e justifique sua resposta exemplificando.
A) Acoplamento; Em engenharia de software, o acoplamento é uma métrica que define o grau de interdependência entre os elementos de um modulo. Poderíamos resumir em uma palavra: Dependência, ou seja, o acoplamento é o grau de dependência em que um artefato se relaciona com outro, considere um artefato como qualquer "coisa" que faça parte do produto final no ambiente de desenvolvimento (Um framework, um objeto, uma classe, etc). No contexto de classes, acoplamento refere-se ao modo como diferentes classes se conectam umas com as outras. 
B) Herança; A herança é um mecanismo da Orientação a Objeto que permite criar novas classes a partir de classes já existentes, aproveitando-se das características existentes na classe a ser estendida. Este mecanismo é muito interessante, pois promove um grande reuso e reaproveitamento de código existente.

C) Encapsulamento; Encapsulamento é a técnica que faz com que detalhes internos do funcionamento dos métodos de uma classe permaneçam ocultos para os objetos. Por conta dessa técnica, o conhecimento a respeito da implementação interna da classe é desnecessário do ponto de vista do objeto, uma vez que isso passa a ser responsabilidade dos métodos internos da classe. 
D) Polimorfismo; Polimorfismo significa "muitas formas", é o termo definido em linguagens orientadas a objeto, como por exemplo Java, C# e C++, que permite ao desenvolvedor usar o mesmo elemento de formas diferentes. Polimorfismo denota uma situação na qual um objeto pode se comportar de maneiras diferentes ao receber uma mensagem. No Polimorfismo temos dois tipos:
    • Polimorfismo Estático ou Sobrecarga
    • Polimorfismo Dinâmico ou Sobreposição



Questão 04 – Qual a razão de saber convenções de código, inúmeras razões, algumas delas: 
a) 80% do tempo programadores, deveriam estar focados em regras de negócio, entendimento, estudos e outros 20% programando, sendo que ainda faltaria tempo para melhora do código; 
b) Dificilmente um código será mantido“eternamente” pelo seu criador original; 
c) Códigos bem escritos, bem descritivos, bem anotados aumentam a produtividade, diminuem a quantidade de treinamentos, facilita a leitura e agrada visualmente;
d) Se você vende seu código como produto, você deve ter certeza que ele é um produto bem testado, empacotado para ser entregue e que faz o que promete, entregando valor ao seu cliente; d) Convenções padronizam métodos de usabilidade com boas práticas baseado no conhecimento e experiência de um corpo especializado na área; 
e) Para que as convenções funcionem corretamente no seu ambiente de trabalho é ideal que todos sigam as conformidades dos padrões. Todos, isso deve ser levado como uma regra. Utilizando as boas práticas da construção de objetos em Java, descreva as boas práticas para nomenclatura de:
 Classes, métodos e atributos, suas restrições e justifique sua resposta exemplificando.
As classes de programação são receitas de um objeto, aonde têm características e comportamentos, permitindo assim armazenar propriedades e métodos dentro dela. Para construir uma classe é preciso utilizar o pilar da abstração. Uma classe geralmente representa um substantivo, por exemplo: uma pessoa, um lugar, algo que seja “abstrato”.
Uma classe é um tipo definido pelo usuário que contém a “receita”, a especificação para os objetos, algo mais ou menos como o tipo inteiro contém o molde para as variáveis declaradas como inteiros. A classe envolve, associa, funções e dados, controlando o acesso a estes, defini-la implica em especificar os seus atributos (dados) e seus métodos (funções).
Um programa que utiliza uma interface controladora de um motor elétrico provavelmente definiria a classe motor. Os atributos desta classe seriam: temperatura, velocidade, tensão aplicada. Estes provavelmente seriam representados na classe por tipos como int ou float. Os métodos desta classe seriam funções para alterar a velocidade, ler a temperatura, etc.
    • Toda classe possui um nome;
    • Possuem visibilidade, exemplo: public, private, protected;
    • Possuem membros como: Características e Ações;
    • Para criar uma classe basta declarar a visibilidade + digitar a palavra reservada class + NomeDaClasse + abrir e fechar chaves { }.
Sintaxe básica para declaração de uma classe em Java:
public class Teste{
//ATRIBUTOS OU PROPRIEDADES
//MÉTODOS
}

Objetos (computacionais) são caracterizados por atributos e métodos. Atributos são as propriedades de um objeto. Métodos são as ações que um objeto pode realizar. Os objetos são características definidas pelas classes. Neles é permitido instanciar objetos da classe para inicializar os atributos e invocar os métodos.

Atributos são as características de um objeto, essas características também são conhecidas como variáveis, utilizando o exemplo dos cães, temos alguns atributos, tais como: cor, peso, altura e nome.
public class Cachorro{
public String nome;
public float peso;
public float altura;
public String cor;
}
Métodos são as ações que os objetos podem exercer quando solicitados, onde podem interagir e se comunicarem com outros objetos, utilizando o exemplo dos cães, temos alguns exemplos: latir, correr, pular.
Implementando a classe “Cachorro” além dos Atributos, agora com Métodos:
public class Cachorro{
public String nome;
public float peso;
public float altura;
public String cor;

void pular {
if (altura >= 80){
System.out.println(“Seu cachorro pula alto”);
 }
if(altura < 80 || altura >= 50{
 System.out.println(“Seu cachorro pula normalmente”)
 }
else{
System.out.println(“Seu cachorro pula baixo”)
}
}
}

Questão 05 – Utilizando da linguagem de programação Java construa uma aplicação que calcule a velocidade média (VM) segundo a observação dos exemplos abaixo, e para esta aplicação você deve utilizar obrigatoriamente a implementação do objeto JOptionPane para interação com o usuário. Como referência utiliza e fórmula abaixo:
Vm = ΔS/ΔT

#########  RESPOSTAS ##############


