# CE444-F2022-Lab6
Follows example from https://github.com/mjhea0/flaskr-tdd

## Pros of TDD
* Forces you to automate the testing process
* Brings everyone on the same page before implementation begins
* Gives a higher degree of confidenc at the time of deployment
* Testing Process is not rushed at the end of development like with traditional testing
* Fits well with the agile methodology

## Cons of TDD
* It's a slow process
    * You need to write tests even for trivial solutions and straightforward code.
* All team members must do it to work
    * If only some do, then it defeats the whole purpose of TDD, as additional testing will be required at the end of development anyways.
* Tests must be maintained when requirements change
    * Whenever requirements change, this means the code must change.
    * However, before writing code, tests are written first in TDD.
    * So this requires the tests to be re-written, then the actual new requirements can be coded in.
    * Takes a long time, wouldn't have had to re-write tests using traditional testing methods (since testing wouldn't have begun yet)