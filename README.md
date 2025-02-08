# Inefficient Enum.reduce in Elixir

This repository demonstrates an example of inefficient code using `Enum.reduce` in Elixir and provides a more efficient alternative using `Enum.filter` and `Enum.sum`.

The original code iterates through the entire list, even when an element does not satisfy the condition.  The improved solution filters the list first, which improves performance for larger lists.