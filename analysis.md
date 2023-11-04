# Analysis

## Layer 1, Head 2

This head pays most attention to the MASK token. It is connected to itself and the CLS token strongly. The other values are not as strong and are more evenly distributed.

Example Sentences:
- I threw a small rock and it fell in the [MASK].
- I was walking down the [MASK] when I saw a dog.
- My [MASK] walked in the living room while talking on the phone.


## Layer 12, Head 9

This head follows a diagonal pattern along the matrix with relatively even scores.
Based on in which part of the sentence the MASK token is, more attention is paid to the period. For example, in the first sentence the diagonal was off around the period and in the third sentence the first three rows are connected to the period rather than to themselves.

Example Sentences:
- I threw a small rock and it fell in the [MASK].
- I was walking down the [MASK] when I saw a dog.
- My [MASK] walked in the living room while talking on the phone.