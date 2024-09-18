---
layout: default
title: Explanation of How to Solve Problems
---

## Explanation of How to Solve Problems

We are going to solve problems from **Repetition with Ordering** to **Repetition with No Ordering**. Let’s go step by step, including examples.

### 1. **Repetition with Ordering**

This is the easiest type of problem. You are choosing items **with repetition allowed** (you can pick the same item more than once) and **the order matters** (which item comes first or second is important).

#### Formula:

If you have $$ n $$ options and you are choosing $$ r $$ items, the total number of ways is $$ n^r $$.

#### Example:

Let’s say you’re making a 3-digit security code, and you can choose any digit (0 to 9) for each position. How many different codes can you make?

You have 10 choices (0 to 9) for each digit, and you are choosing 3 digits:

$$
10 \times 10 \times 10 = 1000 \text{ possible codes}
$$

---

### 2. **No Repetition with Ordering**

Here, you are choosing items **without repetition** (you can’t pick the same item twice) and **the order still matters**.

#### Formula:

The formula is called a **permutation**, and it’s written as:

$$
P(n, r) = \frac{n!}{(n - r)!}
$$

Where $$ n! $$ (n factorial) means multiplying all the numbers from $$ n $$ down to 1.

#### Example:

You are selecting 3 kids to sit in 3 colored chairs (red, blue, and green). Once a child is assigned a chair, they can’t sit in another. How many ways can you assign them?

You have 3 choices for the first chair, 2 choices for the second chair, and 1 choice for the last:

$$
3 \times 2 \times 1 = 6 \text{ ways}
$$

---

### 3. **No Repetition with No Ordering**

In this case, you are choosing items **without repetition** (you can’t pick the same item twice), and **the order does not matter** (it doesn’t matter which item comes first).

#### Formula:

This is called a **combination**, and the formula is:

$$
C(n, r) = \frac{n!}{r!(n - r)!}
$$

#### Example:

You are selecting 2 fruits from a basket of 5 different fruits (apple, banana, cherry, orange, grape). How many ways can you choose 2 fruits if the order doesn’t matter?

You use the combination formula here:

$$
C(5, 2) = \frac{5!}{2!(5 - 2)!} = \frac{5 \times 4}{2 \times 1} = 10 \text{ combinations}
$$

---

### 4. **Repetition with No Ordering (Hardest)**

This is the trickiest type of problem. You are choosing items **with repetition allowed** (you can pick the same item more than once), but **the order doesn’t matter** (it doesn’t matter in which order you pick the items).

#### Formula:

For this, we use a different combination formula that counts how to choose $$ r $$ items from $$ n $$ types of items with repetition:

$$
C(n + r - 1, r) = \frac{(n + r - 1)!}{r!(n - 1)!}
$$

#### Example:

Imagine you’re at a candy store that has 4 types of candy (chocolate, gummy bears, licorice, and lollipops). You need to buy 6 candies, and you can get as many of each type as you want. How many ways can you do this?

Here, you’re choosing 6 candies from 4 types, and you can repeat types. The formula is:

$$
C(4 + 6 - 1, 6) = C(9, 6) = \frac{9!}{6!(9 - 6)!} = \frac{9 \times 8 \times 7}{3 \times 2 \times 1} = 84 \text{ ways}
$$

---

## Summary for the Kids:

- **Repetition with Ordering**: If you can repeat and the order matters, you multiply the number of choices for each spot.
- **No Repetition with Ordering**: If you can’t repeat and the order matters, you use the permutation formula.
- **No Repetition with No Ordering**: If you can’t repeat and the order doesn’t matter, you use the combination formula.
- **Repetition with No Ordering**: If you can repeat and the order doesn’t matter, you use the combination formula with repetition.

Each step gets trickier, but with practice, it becomes easier!

---

## The 10 Questions of This Week:

### 1. **Repetition with Ordering (Easy)**

You are buying 2 cupcakes, one for your mom and one for your dad. The bakery offers 3 types of cupcakes: chocolate, vanilla, and red velvet. How many different ways can you choose the cupcakes if the order (who gets which cupcake) matters and repetition of flavors is allowed?

---

### 2. **Repetition with Ordering (Easy)**

You are creating a 4-digit security code for your phone using the digits 0 to 9. How many possible security codes can you create if each digit can be used more than once and the order matters?

---

### 3. **Repetition with Ordering (Medium)**

You are organizing a 3-stage trivia competition. You have 4 trivia categories to choose from: sports, history, science, and music. How many different ways can you arrange the competition if you can repeat categories and the order of the stages matters?

---

### 4. **No Repetition with Ordering (Medium)**

You are assigning 3 children to sit in 3 different colored chairs: one red, one blue, and one yellow. How many ways can you assign the children to the chairs if no child can sit in more than one chair and the order matters?

---

### 5. **No Repetition with Ordering (Medium)**

You are selecting 4 employees from your team to give presentations at a conference. Each person will present in a different time slot (morning, noon, afternoon, evening). How many ways can you assign the employees to the slots if no one can present more than once and the order matters?

---

### 6. **No Repetition with No Ordering (Harder)**

You are organizing a group of 3 volunteers to help at an event from a pool of 8 people. How many different groups can you form if the order of selection doesn’t matter and no volunteer can be selected more than once?

---

### 7. **No Repetition with No Ordering (Harder)**

You are planning a dinner party and need to choose 5 dishes from a menu of 10 different dishes. How many different combinations of dishes can you choose if the order of selection doesn’t matter and no dish can be repeated?

---

### 8. **Repetition with No Ordering (Hardest)**

You are stocking your pantry with 6 items from a grocery store that sells 4 types of snacks: chips, cookies, pretzels, and crackers. How many different ways can you stock your pantry if the order doesn’t matter and you can choose more than one of each snack?

---

### 9. **Repetition with No Ordering (Hardest)**

You are distributing 8 identical books as prizes to 3 students in a class. How many different ways can you distribute the books if the order of distribution doesn’t matter and each student can receive any number of books, including none?

---

### 10. **Repetition with No Ordering (Hardest)**

You are putting together a bouquet using 5 different types of flowers. You need to select 10 flowers in total, and there’s no limit on how many of each type you can choose. How many different ways can you create the bouquet if the order of selection doesn’t matter?

---
