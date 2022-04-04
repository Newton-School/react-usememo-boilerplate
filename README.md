# Memoize Factorial

We have an app where we calculate factorial and display it
as we type in the input.
The factorial function here is a recursive one and it prints to console "factorialOf(n) called!" each time it is called.

But also we have a Increment button and a count which increments on clicking the button.

But more is also going behind the scenes as we see in console , we are re-calculating the factorial even though the input is same.

To solve this use useMemo hook.
