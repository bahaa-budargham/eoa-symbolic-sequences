# EOA Symbolic Sequences

This repository contains a series of deterministic symbolic sequences generated from single English letter names using the EOA recursive operator under a particular limiting constant ratio (LCR). The sequences are not random; they are the output of a fixed deterministic process.

We begin with the letter 'a' at LCR ≈ 3.14.

## Sequence 1: Letter 'a', LCR ≈ 3.14

### Properties

- **Letter:** a
- **LCR:** ≈ 3.141593223578 (the limiting growth ratio matches π to six decimal places, 3.141593, without claiming exact equality)
- **Alphabet:** 16 distinct letters (permuted by a fixed 1–1 substitution for staged disclosure)
- **Factor complexity:** sublinear on the released initial segment; consistent with zero topological entropy
- **Released initial segment:** first 6,260 letters (cumulative through term 8)
- **Full scale:** the 24th term alone contains approximately 3.86 × 10¹¹ letters

## Files

- `eoa_a_LCR3.14_symbolic_sequence_6260.txt` — the 6,260-letter sequence as plain text.
- `eoa_a_LCR3.14_symbolic_sequence_technical_note.pdf` — 4-page technical note describing the observations and open questions.
- `checksum.txt` — SHA-256 checksum of `eoa_a_LCR3.14_symbolic_sequence_6260.txt` for verification.

## Full Sequence (6260 letters)

The full sequence is provided in `eoa_a_LCR3.14_symbolic_sequence_6260.txt`. A short excerpt is shown below for reference:
gzhlvzggjzyihjgheqvzgzhlvzhlvbjzgyhzizygjzbjzhlvgjzehjdzzgheqvzgzhlvzggjzyihjgheqvzggjzyihjgheqvygpzajukbjzgzhlvyhzgjzzgizyzgyhzzhlvbjzgygpzajukbjzggjzyihjgheqvzhlvbjzgehjgjzbjzdzgzgzhlvgjzehjdzzgheqvzgzhlvzggjzyihjgheqvzgzhlvzhlvbjzgyhzizygjzbjzhlvgjzehjdzzgheqvzgzhlvzhlvbjzgyhzizygjzbjzhlvgjzehjdzzgheqvyhzzhlvpzzgzaabjuvzbygpzajukbjzgzhlvzggjzyihjgheqvyhzgjzzgzhlvbjzgzgzhlvizyzgyhzzgzhlvyhzgjzzgzggjzyihjgheqvygpzajukbjzgzhlvyhzzhlvpzzgzaabjuvzbygpzajukbjzgzhlvzhlvbjzgyhzizygjzbjzhlvgjzehjdzzgh


## Observations

- Factor complexity on the released initial segment grows sublinearly up to k = 537. Beyond that point the counts plateau and then decrease, which is a finite-length artifact: in a word of length 6,260 every factor of length ≥ 700 is unique.
- The transition matrix is highly non-uniform. The most frequent letter pairs are e → a (365), y → e (286), e → i (207), i → g (207), and g → h (207). A small number of pairs dominate.
- The recurrent factor `zgzhlv` occurs 172 times. There are 30 distinct return words to `zgzhlv` and 41 distinct return words to the single letter `z`. The most frequent return words to `z` are `g` (267), `hlv` (113), `ggj` (92), and `hlvbj` (76).

## Collaboration

The original mapping and the full operator are withheld under the EOA staged disclosure policy. They can be made available to qualified researchers under a signed collaboration agreement.

We welcome collaboration from symbolic dynamicists, combinatorists on words, and researchers in formal languages and automata theory.

Contact: Bahaa Budargham, bdarghamneurolabs@gmail.com

## License

This dataset is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See `LICENSE` for details.

## DOI

https://doi.org/10.5281/zenodo.22882603
