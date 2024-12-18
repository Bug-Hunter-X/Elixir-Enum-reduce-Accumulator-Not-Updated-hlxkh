# Elixir Enum.reduce Accumulator Issue

This repository demonstrates a subtle bug that can occur when using `Enum.reduce` in Elixir.  The issue arises from improperly handling the accumulator within the reducing function.  The provided code shows the incorrect implementation and its corrected version.

The bug involves an `if` statement within the `Enum.reduce` function. When the condition is false, the accumulator remains unchanged, resulting in incorrect summation.

This example highlights the importance of carefully considering all cases within the reducing function to ensure the accumulator is properly updated in every iteration.