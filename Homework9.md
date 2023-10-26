## Homework 9

**1 Does sudoku.ts solve the puzzle ?**

Yes

**2 Which lines in sudoku.ts indicate that a solution is correct**

// finally, we check that the sudoku is the one that was originally deployed
let sudokuHash = this.sudokuHash.getAndAssertEquals();

    sudokuInstance
      .hash()
      .assertEquals(sudokuHash, 'sudoku matches the one committed on-chain');

    // all checks passed => the sudoku is solved!
    this.isSolved.set(Bool(true));

**3 Is it possible to submit a correct solution, but have the proof rejected as false ?**

If solution is correct then proof must be accepted as valid.

**4  If the prover altered the code, could they cheat and claim they had a solution, when in fact they didn't ?** 


If the prover has the ability to alter the code or the implementation of a zero-knowledge proof system, they could potentially cheat and claim they had a solution when they didn't. In any cryptographic protocol, the security and trustworthiness of the system depend on the correct and secure implementation of all components, including the zero-knowledge proof process.

However, the design and security of zero-knowledge proofs aim to minimize this risk. Zero-knowledge proofs are typically designed in a way that makes it extremely difficult for a dishonest prover to cheat without being detected. They rely on complex mathematical algorithms and cryptographic techniques to ensure the privacy and security of the information being proved.