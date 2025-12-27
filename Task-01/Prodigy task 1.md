## ***Task-01: Test Cases for Simple Calculator Applications***

## ***Addition – Test Cases***

### **Test Case Id:**

### TC\_001

**Test Description:**

    Verify addition of two positive numbers

 **Precondition:**

 Calculator application is opened

**Test Steps:**

1. Enter 2  
2. Click `+`  
3. Enter 3  
4. Click `=`

**Expected Result:** Result should be **5**

### 

### **Test Case Id:**

### TC\_002

**Test Description:**

     Verify addition of two negative numbers

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter \-4  
2. Click `+`  
3. Enter \-6  
4. Click `=`

**Expected Result:** Result should be **\-10**

### 

### **Test Case Id:**

### TC\_003

**Test Description:** 

   Verify addition of decimal numbers

 **Precondition:**

 Calculator application is opened

**Test Steps:**

1. Enter 2.5  
2. Click `+`  
3. Enter 1.5  
4. Click `=`

**Expected Result:** Result should be **4.0**

---

## **Subtraction – Test Cases**

### **Test Case Id:**

### TC\_004

**Test Description:**

      Verify subtraction of two positive numbers

**Precondition:**

Calculator application is opened

**Test Steps:**

1. Enter 1  
2. Click `-`  
3. Enter 4  
4. Click `=`

**Expected Result:** Result should be **6\.**

### **Test Case Id:**

### TC\_005

**Test Description:** 

   Verify subtraction resulting in negative value

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter 3  
2. Click `-`  
3. Enter 8  
4. Click `=`

**Expected Result:** Result should be **\-5**

---

## **Multiplication – Test Cases**

### 

### **Test Case Id:**

### TC\_006

**Test Description:** 

     Verify multiplication of two numbers

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter 6  
2. Click `*`  
3. Enter 7  
4. Click `=`

**Expected Result:** Result should be **42**

**Test Case Id:**

TC\_007

**Test Description:** 

       Verify multiplication with zero

 **Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter 9  
2. Click `*`  
3. Enter 0  
4. Click `=`

**Expected Result:** Result should be **0**

### **Test Case Id:**

### TC\_008

**Test Description:** 

    Verify multiplication of decimal numbers

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter 2.5  
2. Click `*`  
3. Enter 4  
4. Click `=`

**Expected Result:** Result should be **10**

---

**Division – Test Cases**

### **Test Case Id:**

### TC\_009

**Test Description:**

       Verify division of two positive numbers

**Precondition:** 

Calculator application is opened

**Test Steps:**

1\. Enter 20  
2\. Click /  
3\. Enter 4  
4\. Click \=

**Expected Result:** Result should be **5**

### 

### **Test Case Id:**

### TC\_010

**Test Description:**

      Verify division resulting in decimal value

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter 7  
2. Click `/`  
3. Enter 2  
4. Click `=`

**Expected Result:** Result should be **3.5**

### **Test Case Id:**

### TC\_011

**Test Description:** 

     Verify division by zero  
 

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter 8  
2. Click `/`  
3. Enter 0  
4. Click `=`

**Expected Result:** Error message should be displayed (e.g., *“Cannot divide by zero”*)

---

## **BODMAS – Test Case**

### **Test Case Id:**

### TC\_012

**Test Description:** 

       Verify calculator follows BODMAS rule

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter `2 + 3 * 4`  
2. Click `=`

**Expected Result:** Result should be **14**

---

## **Invalid Input – Test Cases**

### **Test Case ID:**

### TC\_013

**Test Description:** 

      Verify behavior for non-numeric input

**Precondition:**

 Calculator application is opened

**Test Steps:**

1. Enter `a`  
2. Click `+`  
3. Enter `5`  
4. Click `=`

**Expected Result:** Error message should be displayed

### **Test Case Id:**

### TC\_014

**Test Description:** 

Verify behavior for special characters

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Enter `@`  
2. Click `+`  
3. Enter `#`  
4. Click `=`

**Expected Result:** Error message should be displayed

**Test Case Id:**

TC\_015

**Test Description:** 

Verify behavior when no input is provided

**Precondition:** 

Calculator application is opened

**Test Steps:**

1. Click `=` without entering any value

**Expected Result:** No result or validation message should be shown

