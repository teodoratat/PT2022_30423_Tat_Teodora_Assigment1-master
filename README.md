# Polynomial_Calculator
The main objective of this theme is the implementation of an application that performs various operations on some polynomials introduced by the user, such as addition, subtraction, multiplication and division of two polynomials, but also the derivation, respectively their integration.
![image](https://user-images.githubusercontent.com/79631600/226556187-be982666-a215-4801-993f-b525f62ae11b.png)
The GUI is made in JavaFX, and the implementation of the project I used regular expressions, ie a template string that describes the set of possible words that can be composed, following certain rules (I used patterns from regex).
For each addition, subtraction and multiplication operation, we performed 4 tests with JUnit, and for derivation and integration 6 tests each.
I tested the cases in which the polynomials received as input are not written in the classical form, they are subsequently processed by the program. I also tested that the operations work on polynomials of different degrees, as well as for constants, respectively for 0.
In the division operation, I have performed 5 tests but without the remainer shown. I also noticed that the division operation works both if the first polynomial has a higher degree than the
second, and in cases where the degree is lower, respectively in the case where the degrees are equal.
In derivation and integration, I noticed that both operations work, regardless of the form in which the polynomials are written, or their degree. Also, both the derivation and the integration of a constant give a correct result.
