# Silent Failure of @apply with Undefined Tailwind Classes

This repository demonstrates a subtle issue with Tailwind CSS's `@apply` directive. When you use `@apply` with a class that doesn't exist in your Tailwind configuration, there's no error message, and the unknown class is simply ignored. This can lead to unexpected styling without any warning. 

The `bug.html` file shows the problem, and `bugSolution.html` shows how to prevent it using linters or careful class checking.