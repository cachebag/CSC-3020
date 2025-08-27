You can only have one `public` class per file- that's essentially the name of your file or "class", although you could create multiple classes by way of making them private.

You may call classes individually. Consider:

```Java
public class Foo {
	public static void(String[] args) {
		System.out.println("Hello, World from Foo!");	
	}
}

class Bar {
	public static void(String[] args) {
		System.out.println("Hello, World from Bar!");
	}
}
```

Now you can run either:
```bash
java Foo
```
or
```bash
java Bar
```

