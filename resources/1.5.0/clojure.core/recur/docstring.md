Evaluates the exprs in order, then, in parallel, rebindsthe bindings of the recursion point to the values of the exprs.Execution then jumps back to the recursion point, a loop or fn method.