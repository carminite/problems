In his Introduction to Customer Service culminating project, [**carminite**](https://oj.paullee.dev/user/carminite) plans to use a revolutionary technique called "Chunk Loading" where only items in a region around a point is shown on a screen. He talks of saving computing power and creating less volatile games with this idea and, because he's actually *pretty* dumb, asks you to implement this idea. 

### Input Specification
The input will consist of one line with integers `X` and `Y`, `1 ≤ X, Y ≤ 20`, the map dimensions.
The next `Y` rows will have a string of `X` characters each.
The final row will have integers `A` and `B`, the 1-indexed coordinates of the chosen point on the map, and an integer `R`, `0 ≤ R ≤ X, Y`, the radius of the square of which chunks should be loaded (essentially a `2R+1` length square with (`A`, `B`) at the center).

### Output Specification
A visual representation of the loaded chunk region. Chunks outside the map are shown with character '.'.

### Sample Input
```
5 5
asdfh
qewru
ashsd
qeuye
awery
2 2 2
```

### Sample Output
```
.....
.asdf
.qewr
.ashs
.qeuy
```
