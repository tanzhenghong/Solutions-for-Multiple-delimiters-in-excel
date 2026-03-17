# Solutions-for-Multiple-delimiters-in-excel
This material is to indicate the solution to cover multiple delimiters in excel.

**For example**
=IF(ISERR(SEARCH(B$1,$A2)),"0",1) 

**it means that you look for the text in B1 inside cell A2.** 

**If you cannot find it, give me a "0". If  you find it, give me a "1"**

SEARCH(B$1,$A2) 

**Success: If found, it returns the position number (eg, if the word starts at the 5th character, it returns 5).**

**Failure: If NOT found, it throws an #VALUE!error.**

ISERR(...)

**An "Information" function that checks whether a cell or formula produces an error value. It returns TRUE if an error is found, and FALSE otherwise.**

**It returns TRUE if an error is found, and FALSE otherwise.**

IF(..., "0", 1)

**If ISERRis TRUE (Not Found), it outputs "0".**

**If ISERRis FALSE (Found), it outputs 1 .**
