# Teste
> ### Usando tabelas:
>
> > Alinhado à esquerda (padrão)
> > 
> >  -------Nome------- | -------Idade-------
> > ---|---
> > Maria | 18
> > João | 15
> > Joás | 19
> >
> > ---
> > 
> > Centralizado
> > -------Nome------- | -------Idade------- | ---------------------CPF---------------------
> > :---:|:---:|:---:
> > Maria | 18 | 000.000.000-00
> > João | 15 | 111.111.111-11
> > Joás | 19 | 222.222.222-22
> >
> > ---
> >
> > Alinhado à direita
> > -------Nome-------
> > ---:|
> > Maria
> > João
> > Joás
> 
> ### Listas:
>
> > * Frutas;
> >   1. Maçã;
> >   2. Banana;
> >   3. Melão;
> >   4. Abacate.
> > * Churrascos;
> > * Petiscos;
> > * Bebidas;
> >   1. Cervejas;
> >      1. Império;
> >      2. Heinekhen;
> >      3. Matuta.
> >   2. Sucos;
> >      1. Cajá;
> >      2. Laranja;
> >      3. Limão.
> >   3. Refrigerantes.
> >      1. Coca Cola Zero;
> >      2. Coca Cola Original;
> >      3. Fanta Uva;
> >      4. Fanta Laranja;
> >      5. Guaraná.


---
# Este sou eu:

![me](https://github.com/user-attachments/assets/0249a3da-0812-4819-9286-be73fd287f9c)

# Este é o meu repositório:

 [Meu repositório](https://github.com/joas-luna/Teste.git)

 # Inserindo código em Python:

```
class MetaMatriz(type):
    def __new__(metacls, name: str, bases: tuple[type, ...], attrs: dict[str, object]) -> type:
      return super()__new__(name, bases, attrs)
  
    def __call__(cls) -> object:
      return super()__call__(cls)


class Matriz(metaclass=MetaMatriz):
    def __new__(cls) -> object:
      return cls
  
    def __init__(self, nome: str, idade: int) -> None:
      self.__nome = nome
      self.__idade = idade
    
    @property
    def nome(self) -> str: return self.__nome
    
    @property
    def idade(self) -> int: return self.__idade
```

# Inserindo lista de tarefas:

- [ ] Comprar pão;
- [x] Comprar mortadela;
- [ ] Fazer massagem na minha esposa;
- [x] Fazer compras;
- [x] Caminhar;
- [ ] Se matar de estudar;
- [x] Se matar de trabalhar.
