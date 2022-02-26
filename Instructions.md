1. Add a new class to the project called `Foo`
2. Give it two *member variables*
  `int x;`
  `int y;`
3. Give it a *class method* called `sum()`
int sum() {
  return x + y;
}
4. Before you run the project, predict what value will be printed out. Then run the project and check  your prediction.
5. Add a new *class method* called `difference` which returns the difference between `x` and `y` in an object of class `Foo`. Test it out by calling difference in your `main()` method.
6. Create a new object `g` of class `Foo`. Set `x` to 16 and `y` to 33 in the object `g`, then call sum on `g`. Again,  predict what value will be printed and check your prediction.
7. Make a new method `same` in `Foo` which sets `x` to be equal to `y`. Call it before each of your calls to `sum`
and make sure you understand the output.

