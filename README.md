# Haskell Sort Bug

This repository demonstrates an unexpected behavior in Haskell's `sort` function. The `sort` function in Data.List does not modify the original list. However, under certain circumstances (especially when dealing with mutable data structures or state), unexpected modifications might appear.