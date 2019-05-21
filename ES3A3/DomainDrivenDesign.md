# Aula 09/04/2019

## Domain Driven Design

### Glossário da aula passada
***
Palavras | Significado
---------|------------
Domínio | O negócio 
Modelo | Abstração do domínio com foco para pensar como ele funciona
Design | Criação dos artefatos para a resolução do problema

### Modelo em camadas

 User Interface|
:------------------------------------:|
Aplicação | 
Domínio | 
Infreaestrutura |

### Tijolos de construção **Domain Driven Design**

Termo | Explicação
:------:|--------
**Associação** | Normalmente é bidimencional (Tudo que vai volta) <br><br> No **Domain Driven Design** você pode expecificar o olhar (Tornar apenas unidimencional) <br><br>**Restição** - É feito colocado na associação (Entre os elementos)
**Entidade** Objeto de Referência | **Identificação** - Cada entidade de ser única<br><br>Levar em conta as características de cada elemento para caracterizar.<br><br>Vai existir por toda linha do tempo do software com um identificador único.
**Objecto de valor** | Existe pouco tempo durante o período do software.<br><br>Não é necessário utilizar identificadores únicos para ela. <br><br> É **mutável** - Os valores são atribuidos no momento da construção e apenas ter getters.
**Serviço** | Lida com operaçoes que não pertencem nem a uma **entidade** ou a um **objeto de valor**.


### Pacotes
***
* Organizar os pacotes pelos componentes os quais são compostos os componentes
* Quando um elemento existir em mais de um componente, é possível criar outros pacotes intermediários.

### Conceito de Agregado
***
* Várias estruturas relacionadas a uma entidade
* Abstrair um conjunto de elementos como um ( Objetos externos podem olhar o agregado como uma coisa só).
* Existe uma raiz de um agregado que é o ponto aonde pode ser visto por um objeto externo.
* Quando é criado um agregado deve ser criado um isolamento dentro do agregado sem ter nenhuma saída externa além da raíz do agregado.



## Notas
***
* Ligado a idéia de molarizar a aplicação. Um exemplo da separação é o modelo em camadas.

* **Variável de Instância** - Variável que não tem getter e setter.
* **Propriedade** - Uma característica do objeto.
* **UI Inteligente** - Colocar as regras de negócio dentro da parte do view. É um contraponto ao Domain Driven Design. É uma abordagem mais simples para uma aplicação.
* **Exclusão Lógica** - Inativação de um elemento.