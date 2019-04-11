# Design Patters

## Patters de Criação

**Usabilidade** - Normalmente utilizado para o controle fino das instâncias que são criadas. Um exemplo é se existe uma classe com id automático e alguém instânciá-la indevidamente, irá criar uma instância com endereço único inutilizável e, portanto, inútil. Com o pattern Factory é possível ter esse controle.



Padrão | Explicação
:-----:|:-----------
**Abstract Factory** | Permite que um programador usuário crie objetos sem especificar suas classes concretas.
**Factory Method** |Define uma interface para criação de objetos, mas deixa as subclasses decidirem quais classes instanciarem.
 