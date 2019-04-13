# Design Patters

## Patters de Criação

**Usabilidade** - Normalmente utilizado para o controle fino das instâncias que são criadas. Um exemplo é se existe uma classe com id automático e alguém instânciá-la indevidamente, irá criar uma instância com endereço único inutilizável e, portanto, inútil. Com o pattern Factory é possível ter esse controle.
## Lista de Patterns

### Estruturais
* Decorator
* Proxy
* FlyWeigth
* Bridge
### Comportamental
* Template Method
* Visitor
* Command
* Strategy
* Chair of Responsability
* Mediator
* Momento
* Observer

**Patterns** | **Descrição**
:--------:|:-----
**Singleton** | É um pattern que restringe a instanciação de uma classe para uma única **(Single)** instância. É, normalmente, usado para a representação de configurações.
**Abstract Factory** | Descreve como resolver tais problemas: Encapsular criação de objetos num objeto de fábrica **(factory)**. O mesmo define uma interface **(Abstract Factory)** para a criação de objetos e implementar a interface.
**Builder** | Esse **pattern** permite a separação da construção de um objeto complexo da sua representação, de forma que mesmo processo de construção possa criar diferentes representações.
**Prototype** | Esse **pattern** permite a criação de novos objetos a partir de um modelo original ou protótipo que é clonado.
**Factory Method** | Esse **pattern** lida com o problema de criar objetos sem ter que especificar a classe exata do objeto a ser criado.
