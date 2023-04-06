Interfaces em Java

   * As interfaces em Java são uma poderosa ferramenta de programação que permitem a definição de contratos ou especificações de comportamento que as classes devem implementar. Elas são usadas para definir um conjunto de métodos que uma classe deve implementar, sem fornecer uma implementação concreta desses métodos. Isso permite que as classes sejam flexíveis e intercambiáveis, possibilitando a criação de código modular e extensível em Java.

O que é uma Interface?

  * Uma interface em Java é uma coleção de métodos abstratos, constantes (variáveis estáticas final) e métodos default (a partir do Java 8), que podem ser implementados por várias classes. As interfaces são semelhantes a classes abstratas, mas diferem na medida em que não podem ter implementação concreta de métodos. Elas são usadas para definir contratos, ou seja, especificações de comportamento que as classes que implementam a interface devem seguir.

    As interfaces são definidas usando a palavra-chave interface no Java e podem ser implementadas por qualquer classe que deseje cumprir o contrato definido pela interface. Uma classe pode implementar várias interfaces, o que permite a criação de código reutilizável em diferentes contextos.


Por que usar Interfaces?

    As interfaces são amplamente utilizadas em Java por várias razões:

   1. Definição de Contratos: As interfaces permitem a definição clara de contratos ou especificações de comportamento que as classes devem seguir. Isso permite a padronização e organização do código, garantindo que as classes implementadoras cumpram as obrigações definidas pela interface.

   2. Flexibilidade e Extensibilidade: As interfaces permitem que as classes sejam flexíveis e intercambiáveis. Uma classe pode implementar várias interfaces, o que possibilita a adição de diferentes comportamentos em uma única classe, sem a necessidade de herança múltipla, que não é permitida em Java.

   3. Reutilização de Código: As interfaces permitem a criação de código reutilizável. Uma vez que uma interface é definida, várias classes podem implementá-la, tornando o código mais modular e permitindo a reutilização de implementações em diferentes contextos.

   4. Polimorfismo: O uso de interfaces permite o polimorfismo em Java. Isso significa que objetos de diferentes classes que implementam a mesma interface podem ser tratados de forma uniforme, permitindo a substituição de objetos em tempo de execução e tornando o código mais flexível.

   5. Evolução do Código: As interfaces permitem a evolução do código de forma mais fácil. Se novos comportamentos precisarem ser adicionados, basta criar uma nova interface e implementá-la nas classes apropriadas, sem afetar o código existente. Isso ajuda a manter o código mais limpo e evita a quebra de compatibilidade.


Como usar Interfaces em Java?
    Para usar uma interface em Java, você precisa seguir os seguintes passos:

   * Definir uma Interface: Use a palavra-chave interface para definir uma nova interface. Você pode definir métodos abstratos, constantes e métodos default na interface. No repositório você encontra os exemplos práticos.






