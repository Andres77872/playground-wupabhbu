# Welcome!

This Java template lets you get started quickly with a simple one-page playground.

```java runnable
// { autofold
public class Main {

public static void main(String[] args) {
// }

  fibonacci(10);

//{ autofold
}

public int void fibonacci(int val){
  if(val==0){
    System.out.println(0);
    return 0;
  }else if(val==1){
    System.out.println(1);
    return(1);
  }else{
    System.out.println(val+fibonacci(val+1));
  }
  
}

}
//}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Java template](https://tech.io/select-repo/385)
