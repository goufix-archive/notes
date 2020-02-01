# Orientação a Objetos com JAVA

## Classe vs Objeto

### Classe

Uma classe é um "boilerplate" de um objeto, usado para representar e criar objetos.

```Java
public class Pen() {
  private String model;
  private String color;
  private float lineSize;
  private int refil;
  private Bool isClosed;

  public scratch() {
    if(this.isClosed) {
      system.out.println("Não é possível riscar com a caneta tampada");
    } else {
      system.out.println("Rabiscado!");
    }
  }

  public close() {
    this.isClosed = true;
  }

}
```

### Objeto

Um objeto é uma instância de uma clase, pode representar qualquer coisa, seja ela lógica ou física.

```Java
Pen pen = new Pen();
pen.color = "Azul";
```

### Visibilidade

Indicam o nível de acesso aos componentes internos da classe.
`public, private, protected`

#### Publico

A classe atual e todas as outras classes podem usar.

#### Privado

Apenas a classe atual pode usar

#### Protegido

A classe atual e todas suas subclasses podem usar.

