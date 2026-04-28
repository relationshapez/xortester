# XOR Tester

XOR Tester is a single-file HTML flashcard-style practice tool for the XOR operation.

To run remotely:

- Access the tool at https://relationshapez.github.io/xortester/

## Files

- `index.html` — single-file HTML tool
- `README.md` — documentation for the HTML tool
- `LICENSE` — MIT License text

## Purpose

This tool is intended for classroom practice, quick review, or independent study. It gives students two numbers and asks them to compute the result of the XOR operation.

The interface is intentionally minimal and mobile-friendly so students can focus on the computation.

## How to Use

1. Read the two displayed numbers.
2. Compute their XOR result.
3. Type the answer into the answer box.
4. Press **Check** to see whether the answer is correct.
5. Press **Refresh** for a new problem.

The **Check** button remains inactive until an answer is entered.

## Base Selection

The tool starts in **Base-10**.

Use the **Base** input to change the display base to any base from **2** through **16**.

When the base is changed:

- the two problem numbers are converted to the selected base,
- the same underlying problem is preserved,
- the student's answer should be typed in the selected base.

For bases above 10, use the usual hexadecimal-style digits:

- `A` for 10
- `B` for 11
- `C` for 12
- `D` for 13
- `E` for 14
- `F` for 15

## Problem Size

Each generated number is at most two base-10 digits, so the original values are between **0** and **99**.

This keeps the binary calculations short enough for mental practice or quick written work.

## Feedback and Solution Display

After pressing **Check**, the tool shows whether the answer is correct or incorrect.

The answer box receives a thick outline:

- green when the entered answer is correct,
- red when the entered answer is incorrect.

The solution display shows:

- the two numbers in binary, aligned bit by bit,
- the binary XOR result,
- and the correct answer in the selected base when the selected base is not Base-2.

When the selected base is Base-2, the binary result already gives the answer.

## License

Copyright (c) 2026 Alan Miller.

This project is released under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the full license text.
