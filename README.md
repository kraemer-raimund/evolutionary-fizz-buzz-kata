# Evolutionary Fizz Buzz Kata

An evolutionary coding kata where the requirements are revealed incrementally.

## Evolutionary TDD Kata

*Make sure to reveal the requirements of the next version only after finishing the previous one.*

### Version 1 Requirements

<details>
<summary>Reveal</summary>

- Implement an API, driven by unit tests, that maps positive integers to strings according to the following rules:
  - If the number is divisible by 3, the API returns the word "Fizz" as result, otherwise the number itself as a string.
  - No modulo operator – imagine the language or platform does not support it (yet), or you haven't learned about it but need to solve the problem anyway.
  - Optional: If you're up for a challenge, implement the divisibility check using only bit shifting and addition/subtraction, no division and multiplication.

</details>

### Version 2 Requirements

<details>
<summary>Reveal</summary>

- You have unlocked the modulo operator!
- As usual, multiples of 5 should now be mapped to "Buzz", multiples of both 3 and 5 to "FizzBuzz". In general, unless stated otherwise, we always want to combine the outputs of the individual divisors from small to large (e.g., FizzBuzz, not BuzzFizz).

</details>

### Version 3 Requirements

<details>
<summary>Reveal</summary>

- Multiples of 7 should now be mapped to "Bizz" – except on Tuesdays, where we want to map it to "Tuez" instead.<br>
  *Note: We don't want to only be able to test it on Tuesdays, though!*

</details>

### Version 4 Requirements

<details>
<summary>Reveal</summary>

- Multiples of 11 become "Fuzz" – except on February 29th, where it becomes "Leapz" instead.
- The number 42 becomes "Univerz" – and no combinations are formed in case it is also a multiple.
- The number 420 is mapped to "Blaze", followed by the "regular" output for everything it is divisible by.

</details>

___

© 2023 Raimund Krämer - Use with attribution.

Links to third party sites are included for convenience only and I am not responsible for their contents.
