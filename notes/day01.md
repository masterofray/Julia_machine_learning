# Day 1 - 20240729

## Pages Covered
- Pages 1 to 23 [julia for beginners]

## Key Concepts
- Introduction to Julia with its high computing
- Julia as calculator
- Angle of Reach example

## Notes
- Julia is designed for high-performance numerical and scientific computing.
- Function like lambda

## Code Snippets
```julia
#= 
Imagine a start velocity v = 762.425 m/s and 
we want to know the angles for
the distances 8, 12, 16 and 25 km. 
We could write in the Julia REPL:
=#
v = 762.425;
grafitasi = 9.81;
x1 = 0.5*asin(grafitasi * 8000 / v^2);
x2 = 0.5*asin(grafitasi * 12000 / v^2);
x3 = 0.5*asin(grafitasi * 25000 / v^2);
print("Value is x1 = $x1, x2 = $x2, x3 = $x3.")
```