# Logic From Numbers, Add And Mull

**True : Even Numbers**

**False: Odd Numbers**

**NOT : NUM + 1**
-  1 + 1 -> 2 ; True
-  2 + 1 -> 3 ; False

**OR : NUM1 * NUM2**
-  1 * 1 -> 1 ; False
-  1 * 2 -> 2 ; True
-  2 * 1 -> 2 ; True
-  2 * 2 -> 4 ; True

**XOR : NOT(NUM1 + NUM2)**
- 1+ 1 + 1 -> 3 ; False
- 1+ 1 + 2 -> 4 ; True
- 1+ 2 + 1 -> 4 ; True
- 1+ 2 + 2 -> 5 ; False

**EQUIVALENCE : NUM1 + NUM2**
-  1 + 1 -> 2 ; True
-  1 + 2 -> 3 ; False
-  2 + 1 -> 3 ; False
-  2 + 2 -> 4 ; True

**AND : (NUM1 + NUM2) + (NUM1 * NUM2)**
-  (1 + 1) + (1 * 1) -> 3 ; False
-  (1 + 2) + (1 * 2) -> 5 ; False
-  (2 + 1) + (2 * 1) -> 5 ; False
-  (2 + 2) + (2 * 2) -> 8 ; True

**IMPLIES : (OR (1+ NUM1) NUM2)**
- (1 => 1) -> 2 * 1 -> 2 ; True
- (1 => 2) -> 2 * 2 -> 4 ; True
- (2 => 1) -> 3 * 1 -> 3 ; False
- (2 => 2) -> 3 * 2 -> 6 ; True
