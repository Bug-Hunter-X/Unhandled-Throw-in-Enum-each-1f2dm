# Unhandled Throw in Elixir Enum.each

This example demonstrates a common error when using `Enum.each` with `throw` in Elixir.  The code attempts to iterate a list, throwing an exception when a specific condition is met. However, because the exception isn't caught, it terminates the execution before the final IO.puts statement is reached.  The solution showcases how to use a `try-catch` block to handle the thrown exception gracefully and achieve the intended behavior.  See the `bugSolution.ex` file for the corrected version.