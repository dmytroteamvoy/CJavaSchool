Task: Arrow Builder



- Implement th interface [Arrow.java](main%2Fjava%2FArrow.java) that builds an arrow in the console based on the given direction and input length.
Implement a method that takes the arrow length as an input parameter and prints the arrow in the console.
From base to peak one side of the arrow decreases each line, and the second side decreases one time per two lines
The peak of the arrow can't be finished by more than one symbol `#`.
The bottom part(base) should contain only `#`
another area should be filled by `_`
You shouldn't use redundant symbols
argument of method `arrowLength` - should be multiple of two and greater or equal to 2 else trow appropriate exception.


- It it's too easy for you, implement both interfaces Arrow.java and AdvancedArrow.java
if `asymmetricLevel` is 3 it means the second side decreases one time per three lines
`arrowLength` should be multiple of `asymmetricLevel` 
other rules are same as in previous task.

Wrong examples:
```
__##_ // peak has more then one #
_####
#####
```

```
__#_ // length not multiple of two
_###
####

```




Variants:

1. Right Arrow (Left-biased): Build an arrow where the left side from base decreases on each row, and the right side from base decreases every two lines.
example for arrowLength = 6:
```
#_____
##____
###___
####__
#####_
######
####__
##____
```


2. Left Arrow (Right-biased): Build an arrow where the right side from base decreases on each row, and the left side from base decreases every two lines.
example for arrowLength = 6:
```
_____#
____##
___###
__####
_#####
######
__####
____##
```
3. Right Arrow (Left-biased): Build an arrow where the right side from base decreases on each row, and the left side from base decreases every two lines.
Example for arrowLength = 6:
```
##____
####__
######
#####_
####__
###___
##____
#_____
```
4. Left Arrow (Right-biased): Build an arrow where the left side from base decreases on each row, and the right side from base decreases every two lines.
example for arrowLength = 6:
```
____##
__####
######
_#####
__####
___###
____##
_____#
```
5. Up Arrow (Bottom-biased): Build an arrow where the left side from base decreases on each row, and the right side from base decreases every two lines.
example for arrowLength = 6:
```
_____#__
____##__
___####_
__#####_
_#######
########
```
6. Up Arrow (Bottom-biased): Build an arrow where the right side from base decreases on each row, and the left side from base decreases every two lines.
example for arrowLength = 6:
```
__#_____
__##____
_####___
_#####__
#######_
########
```
7. Down Arrow (Top-biased): Build an arrow where the left side from base decreases on each row, and the right side from base decreases every two lines.
example for arrowLength = 6:
```
########
#######_
_#####__
_####___
__##____
__#_____
```
8. Down Arrow (Top-biased): Build an arrow where the right side from base decreases on each row, and the left side from base decreases every two lines.
example for arrowLength = 6:
```
########
_#######
__#####_
___####_
____##__
_____#__
```