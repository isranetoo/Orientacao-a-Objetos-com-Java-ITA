#  Pergunta 1
    É um método especial de uma classe Java que
    tem o mesmo nome da classe, cuja execução se dá imediatamente após a
    instanciação de um objeto da classe, com o objetivo de alocar memória e iniciar
    as suas variáveis de instância. Como é chamado esse método especial? 
[Na sua resposta, por limitação do presente ambiente de correção automática, coloque obrigatoriamente apenas a primeira letra em maiúscula; o restante deverá estar em minúscula!]

* Contrutor

# Pergunta 2
    Uma classe que tem um método abstrato não precisa ser declarada como abstrata. Verdadeiro/V ou Falso/F?

* Falso

# Pergunta 3
    Uma classe abstrata pode não ter nenhum método abstrato.

* Verdadeiro

# Pergunta 4
    O código abaixo compilará corretamente (indique apenas e exatamente  V ou Verdadeiro ou Sim – F 
    ou Falso ou Não; e não deve justificar).
 Obs. : se você escrever as iniciais da sua resposta em 
    minúsculas (v ou verdadeiro ou sim – f ou falso ou não), o sistema não entenderá e marcará como 
    errado, mesmo se for a resposta certa! [Supondo que o trecho representado por "..." compila corretamente] 
  
    public abstract class X {...}
    public class Teste{
        public static void main (String[] args) {
          X x = new X();
        }
    }

* Falso

# Pergunta 5
    O código abaixo compilará corretamente 
   [supondo que o trecho representado por "..." compila corretamente]:


    class Teste{
       public void metodo (int i) {...}   
       protected void metodo (double x) {...}
    }

* Verdadeiro

# Pergunta 6
    O código abaixo compilará corretamente (indique apenas e exatamente V ou Verdadeiro ou Sim – F ou 
    Falso ou Não; e não deve justificar). Obs. : se você escrever as iniciais da sua resposta em 
    minúsculas (v ou verdadeiro ou sim – f ou falso ou não), o sistema não entenderá e marcará como 
    errado, mesmo se for a resposta certa!
 [Supondo que o trecho representado por "..." compila corretamente]

    class Teste{
       public int metodo ( ) {...}   
       protected double metodo ( ) {...}
    }

* Falso

# Pergunta 7
    É um mecanismo existente no paradigma orientado a objetos que permite a reutilização da estrutura e do
    comportamento de uma classe ao se definir novas classes; é conhecido também
    como relacionamento "é um"; a classe que herda o comportamento é
    chamada de subclasse e a que definiu o comportamento, superclasse. Qual é o nome
    desse mecanismo?

* Herança 

# Pergunta 8
    Apresente como é em Java a assinatura do método correspondente à primeira mensagem que aparece no 
    trecho do exemplo abaixo [se você vislumbrar mais de uma assinatura possível, apresente apenas 
    uma delas!][A assinatura de método em Java tem um formato que não segue a sintaxe do Java;
 a sintaxe é a de assinatura de método, que poderá ser usada ao se avaliar programas em C# ou Python, por exemplo!]:
    
    . . .
    Ponto ponto1 = new Ponto( );
    Ponto ponto3 = new Ponto( );
    . . .
    if (ponto1.igual(ponto3))
      ponto3.mover(5,10);
    . . .

* boolean igual(Ponto outroPonto)

#  Pergunta 9
    Os dados e operações de um objeto que são visíveis externamente compreendem seu/sua ____________________.

    * Interface


    * Método


    * Sobrecarga


    * Sobreposição

* Interface

# Pergunta 10
    O princípio de ______________________ permite queobjetos que pertencem a  diferentes  
    classes respondam de forma distinta a mensagens
    idênticas. 
[Na sua resposta, por limitação do presente ambiente de correção automática, coloque 
    obrigatoriamente apenas a primeira letra em maiúscula; o restante deverá estar em minúscula!]
* Polimorfismo

# Pergunta 11
    A principal diretriz convencionada para atributos de objetos é que todas as variáveis 
    de  instância devem ser declaradas ____________________.



    * Públicas


    * Protegidas


    * Privadas
* Privadas
