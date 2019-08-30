# Human
Testing


# C Sample

```c
#include <stdio.h>
int main(){
  printf("Testing.\n");
  return 0;
}
```

# Java Sample

```java
import java.lang.*;
public class Human{
	public static void main(String[]args){
  	System.out.println("Testinge.");
}
}
```

# Python Sample
```python
print "Testing."
```

# VBA "Convert to number" function is too inefficient, everyone please use this instead.
```VBA
Sub ConvertNo()

Application.ScreenUpdating = False

'Modify the range yourself lol
[A2:A200000].Select
With Selection
    .NumberFormat = "0"
    .Value = .Value
End With

Application.ScreenUpdating = True

End Sub
```
