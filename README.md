# Princípios SOLID

- [Single responsability principle (Princípo da responsabilidade única)](#single-responsability-principle-princípo-da-responsabilidade-única)
- [Open-closed principle (Princípio aberto-fechado)](#open-closed-principle-princípio-aberto-fechado)
- [Liskov substitution priciple (Princípio da sobstituição de Liskov)](#liskov-substitution-priciple-princípio-da-sobstituição-de-liskov)
- [Interface segregation principle (Princípio da segragação da interface)](#interface-segregation-principle-princípio-da-segragação-da-interface)
- [Dependency inversion principle (Princício da inversão de dependência)](#dependency-inversion-principle-princício-da-inversão-de-dependência)


## Single responsability principle (Princípo da responsabilidade única)

O pricípio da responsabilidade única define que uma classe deve ser especializada em uma única tarefa e, portanto, ter apenas um motívo para se modificada.

Seguindo esse princípio, as classes se tornam mais coesas, possuem baixo acoplamento, melhor usabilidade, e mais fáceis de testar.

## Open-closed principle (Princípio aberto-fechado)

O princípio aberto-fechado define que as classes devem ser fechadas para modificação e abertas para extensão. Dessa forma quando há a necessidade de adicionar novas funcionalidades ou comportamentos diferentes, a classe não deve ser modificada e sim extendida com a nova lógica.

Seguindo esse princípio os problemas (bugs) decorrentes das atualizações ficam restritos e possuem menor potencial de causar danos ao sistema.

## Liskov substitution priciple (Princípio da sobstituição de Liskov)

O princípio da sobstituição de Liskov define que uma classe pai e suas subclasses devem ser intercambeáveis sem alteração no comportamento e resultado.

Seguindo esse princípio o código se torna mais confiável e com menos comportamentos inesperados.

## Interface segregation principle (Princípio da segragação da interface)

O princípio da segragação da interface define que uma classe não deve implementar um método que não seja necessário para sua funcionalidade. Isso se dá pela utilização de interfaces com escopos mais reduzidos e delimitados à tarefas mais específicas.

Seguir esse princípio permite manter o escopo de uma classe de forma melhor delimitada, favorecendo a utilização dos princípios acima.

## Dependency inversion principle (Princício da inversão de dependência)

O princípio da inversão de dependência define que as classes devem depedender de interfaces e não de classes concretas.

Depender de classes concretas implica em um maior acoplamento do código e alterações em uma classe podem implicar em alterações na outro ferindo o princípio de resposabilidade única.
