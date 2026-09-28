# Boundary Value Analysis – Login & Registration

## What is Boundary Value Analysis?

Boundary Value Analysis (BVA) is a black-box testing technique where we test values at the **boundary** and just **inside/outside** the allowed range.

It helps identify defects that may occur at the limits of input fields.

---

## 1. Age Field – Range 18 to 60

### Valid Range

**18–60**

| Test Value | Expected Result | Result |
| ---------: | --------------- | ------ |
|         17 | Invalid         | PASS   |
|         18 | Valid           | PASS   |
|         19 | Valid           | PASS   |
|         59 | Valid           | PASS   |
|         60 | Valid           | PASS   |
|         61 | Invalid         | PASS   |

### Boundary Values

* Minimum boundary = **18**
* Just below minimum = **17**
* Just above minimum = **19**
* Maximum boundary = **60**
* Just below maximum = **59**
* Just above maximum = **61**

---

## 2. Age Field – Range 8 to 20

### Valid Range

**8–20**

| Test Value | Expected Result | Result |
| ---------: | --------------- | ------ |
|          7 | Invalid         | PASS   |
|          8 | Valid           | PASS   |
|          9 | Valid           | PASS   |
|         19 | Valid           | PASS   |
|         20 | Valid           | PASS   |
|         21 | Invalid         | PASS   |

---

## 3. Password Length – Range 5 to 15 Characters

### Valid Range

**5–15 characters**

| Password Length | Expected Result |
| --------------: | --------------- |
|               4 | Invalid         |
|               5 | Valid           |
|               6 | Valid           |
|              14 | Valid           |
|              15 | Valid           |
|              16 | Invalid         |

### Conclusion

Boundary Value Analysis was used to test the minimum and maximum limits of input fields and values immediately outside those limits.
