## إعداد المبرمج نجم الدين شمس الدين 
* [واتس اب](https://wa.me/967715479737) 
* [فيسبوك](https://www.facebook.com/profile.php?id=100071127144290) 
* [حساب GitHub](https://github.com/najm-flutter) 
### Lecture on Matrices for Software Engineering

---

**1. Introduction to Matrices**
   - **English:** A matrix is a rectangular array of numbers, symbols, or expressions arranged in rows and columns.
   - **Arabic:** 
   المصفوفة هي ترتيب مستطيل من الأرقام أو الرموز أو التعبيرات يتم ترتيبه في صفوف وأعمدة.

**2. Matrix Notation**
   - **English:** Matrices are usually denoted by capital letters (e.g., A, B, C).
   - **Arabic:** عادةً ما يُشار إلى المصفوفات بالحروف الكبيرة (مثل A, B, C).

**3. Dimensions of a Matrix**
   - **English:** The size or dimension of a matrix is given by the number of rows (m) and the number of columns (n), denoted as m x n.
   - **Arabic:** 
   
   يتم تحديد حجم أو بُعد المصفوفة بعدد الصفوف (m) وعدد الأعمدة (n)، ويُشار إليها بـ m x n.

**4. Types of Matrices**
   - **English:** 
     - **Square Matrix:** A matrix with the same number of rows and columns (n x n).
     - **Arabic:** 

       - **المصفوفة المربعة:** مصفوفة لها نفس عدد الصفوف والأعمدة (n x n).
     - **Row Matrix:** A matrix with a single row (1 x n).
     - **Arabic:** 

       - **مصفوفة صف:** 
       مصفوفة تحتوي على صف واحد   
              (1xn)

     - **Column Matrix:** A matrix with a single column (m x 1).

     - **Arabic:** 

       - **مصفوفة عمود:** مصفوفة تحتوي على عمود واحد (m x 1).

     - **Zero Matrix:** A matrix in which all elements are zero.

     - **Arabic:** 


       - **المصفوفة الصفرية:** مصفوفة تحتوي جميع عناصرها على الصفر.

**5. Matrix Addition**
   - **English:** Two matrices of the same dimension can be added by adding their corresponding elements.
   - **Arabic:** يمكن جمع مصفوفتين من نفس البعد عن طريق جمع عناصرهما المقابلة.

**6. Matrix Subtraction**
   - **English:** Subtraction of matrices involves subtracting the corresponding elements of two matrices of the same dimension.
   - **Arabic:** طرح المصفوفات يتضمن طرح العناصر المقابلة لمصفوفتين من نفس البعد.

**7. Matrix Multiplication**
   - **English:** Matrix multiplication involves multiplying rows of the first matrix by columns of the second matrix. The result is a new matrix.
   - **Arabic:** ضرب المصفوفات يتضمن ضرب صفوف المصفوفة الأولى بأعمدة المصفوفة الثانية. الناتج هو مصفوفة جديدة.

**8. Properties of Matrix Multiplication**
   - **English:**
     - **Associative Property:** (AB)C = A(BC)
     - **Arabic:**
       - **الخاصية الترابطية:** (AB)C = A(BC)
     - **Distributive Property:** A(B + C) = AB + AC
     - **Arabic:**
       - **الخاصية التوزيعية:** A(B + C) = AB + AC
     - **Not Commutative:** AB ≠ BA (in general)
     - **Arabic:**
       - **ليست تبديلية:** AB ≠ BA (بشكل عام)

**9. Identity Matrix**
   - **English:** The identity matrix is a square matrix with 1s on the diagonal and 0s elsewhere. It acts as the multiplicative identity.
   - **Arabic:** المصفوفة الوحدة هي مصفوفة مربعة تحتوي على 1 في القطر الرئيسي و 0 في أماكن أخرى. تعمل كهوية في الضرب.

**10. Transpose of a Matrix**
   - **English:** The transpose of a matrix is obtained by swapping rows with columns.
   - **Arabic:** يمكن الحصول على المصفوفة المنقولة عن طريق تبديل الصفوف بالأعمدة.


**12. Applications of Matrices**
   - **English:** Matrices are used in computer graphics, cryptography, economics, and engineering to solve linear equations and perform transformations.
   - **Arabic:** تُستخدم المصفوفات في الرسومات الحاسوبية، علم التشفير، الاقتصاد، والهندسة لحل المعادلات الخطية وإجراء التحويلات.


### Lecture on Matrices for Software Engineering with Example Problems and Solutions

---

**1. Matrix Addition**
   - **Example Problem:**
     - **English:** Given matrices A and B, where A =  
       ```math
       \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}
       ```
       and B = 
       ```math
       \begin{pmatrix} 7 & 8 & 9 \\ 10 & 11 & 12 \end{pmatrix}
       ```
       , find A + B.
     - **Arabic:** 
     
     المعطى مصفوفتان A وB، حيث أن A = 
       ```math
       \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}
       ```
       و B = 
       ```math
       \begin{pmatrix} 7 & 8 & 9 \\ 10 & 11 & 12 \end{pmatrix}
       ```
       ، أوجد A + B.
   - **Solution:**
     - **English:** Add corresponding elements:  
       ```math
       A + B = \begin{pmatrix} 1+7 & 2+8 & 3+9 \\ 4+10 & 5+11 & 6+12 \end{pmatrix} = \begin{pmatrix} 8 & 10 & 12 \\ 14 & 16 & 18 \end{pmatrix}
       ```
     - **Arabic:** جمع العناصر المقابلة:  
       ```math
       A + B = \begin{pmatrix} 1+7 & 2+8 & 3+9 \\ 4+10 & 5+11 & 6+12 \end{pmatrix} = \begin{pmatrix} 8 & 10 & 12 \\ 14 & 16 & 18 \end{pmatrix}
       ```

**2. Matrix Subtraction**
   - **Example Problem:**
     - **English:** Given matrices C and D, where C = 
       ```math
       \begin{pmatrix} 9 & 8 & 7 \\ 6 & 5 & 4 \end{pmatrix}
       ```
       and D = 
       ```math
       \begin{pmatrix} 3 & 2 & 1 \\ 6 & 4 & 2 \end{pmatrix}
       ```
       , find C - D.
     - **Arabic:** 
     
     المعطى مصفوفتان C وD، حيث أن C = 
       ```math
       \begin{pmatrix} 9 & 8 & 7 \\ 6 & 5 & 4 \end{pmatrix}
       ```
       و D = 
       ```math
       \begin{pmatrix} 3 & 2 & 1 \\ 6 & 4 & 2 \end{pmatrix}
       ```
       ، أوجد C - D.
   - **Solution:**
     - **English:** Subtract corresponding elements:  
       ```math
       C - D = \begin{pmatrix} 9-3 & 8-2 & 7-1 \\ 6-6 & 5-4 & 4-2 \end{pmatrix} = \begin{pmatrix} 6 & 6 & 6 \\ 0 & 1 & 2 \end{pmatrix}
       ```
     - **Arabic:** طرح العناصر المقابلة:  
       ```math
       C - D = \begin{pmatrix} 9-3 & 8-2 & 7-1 \\ 6-6 & 5-4 & 4-2 \end{pmatrix} = \begin{pmatrix} 6 & 6 & 6 \\ 0 & 1 & 2 \end{pmatrix}
       ```

**3. Matrix Multiplication**
   - **Example Problem:**
     - **English:** Given matrices E = 
       ```math
       \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
       ```
        and F = 
       ```math
       \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix}
       ```
       , find the product EF.
     - **Arabic:** 
     
     المعطى مصفوفتان E و F، حيث أن E = 
       ```math
       \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}
       ```
       و F = 
       ```math
       \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix}
       ```
       ، أوجد حاصل الضرب EF.
   - **Solution:**
     - **English:** Multiply rows of E by columns of F:  
       ```math
       EF = \begin{pmatrix} 1 \cdot 5 + 2 \cdot 7 & 1 \cdot 6 + 2 \cdot 8 \\ 3 \cdot 5 + 4 \cdot 7 & 3 \cdot 6 + 4 \cdot 8 \end{pmatrix} = \begin{pmatrix} 19 & 22 \\ 43 & 50 \end{pmatrix}
       ```
     - **Arabic:**  
     
     ضرب صفوف E بأعمدة F:  
       ```math
       EF = \begin{pmatrix} 1 \cdot 5 + 2 \cdot 7 & 1 \cdot 6 + 2 \cdot 8 \\ 3 \cdot 5 + 4 \cdot 7 & 3 \cdot 6 + 4 \cdot 8 \end{pmatrix} = \begin{pmatrix} 19 & 22 \\ 43 & 50 \end{pmatrix}
       ```

**4. Transpose of a Matrix**
   - **Example Problem:**
     - **English:** Given matrix G = 
       ```math
       \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}
       ```
       , find the transpose G^T.
     - **Arabic:** 
     
     المعطى المصفوفة G = 
       ```math
       \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}
       ```
       ، أوجد المصفوفة المنقولة G^T.
   - **Solution:**
     - **English:** Swap rows and columns:  
       ```math
       G^T = \begin{pmatrix} 1 & 4 \\ 2 & 5 \\ 3 & 6 \end{pmatrix}
       ```
     - **Arabic:** تبديل الصفوف بالأعمدة:  
       ```math
       G^T = \begin{pmatrix} 1 & 4 \\ 2 & 5 \\ 3 & 6 \end{pmatrix}
       ```

**5. Identity Matrix**
   - **Example Problem:**
     - **English:** Find the identity matrix I of size 3x3.
     - **Arabic:**
     
      أوجد المصفوفة الوحدة I ذات الحجم 3x3.
   - **Solution:**
     - **English:** The identity matrix has 1s on the diagonal and 0s elsewhere:  
       ```math
       I = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}
       ```
     - **Arabic:** 
     
     المصفوفة الوحدة تحتوي على 1 في القطر و 0 في باقي الأماكن:  
       ```math
       I = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}
       ```

**6. Inverse of a Matrix**
   - **Example Problem:**
     - **English:** Given matrix H = 
       ```math
       \begin{pmatrix} 4 & 7 \\ 2 & 6 \end{pmatrix}
       ```
       , find the inverse H^(-1) if it exists.
     - **Arabic:** المعطى المصفوفة H = 
       ```math
       \begin{pmatrix} 4 & 7 \\ 2 & 6 \end{pmatrix}
       ```
       ، 
       
       أوجد المصفوفة العكسية H^(-1) إذا كانت موجودة.
   - **Solution:**
     - **English:** The inverse is given by:  
       ```math
       H^(-1) = \frac{1}{(4 \cdot 6 - 7 \cdot 2)} \begin{pmatrix} 6 & -7 \\ -2 & 4 \end{pmatrix} = \frac{1}{10} \begin{pmatrix} 6 & -7 \\ -2 & 4 \end{pmatrix} = \begin{pmatrix} 0.6 & -0.7 \\ -0.2 & 0.4 \end{pmatrix}
       ```
     - **Arabic:** العكسية تُحسب كالتالي:  
       ```math
       H^(-1) = \frac{1}{(4 \cdot 6 - 7 \cdot 2)} \begin{pmatrix} 6 & -7 \\ -2 & 4 \end{pmatrix} = \frac{1}{10} \begin{pmatrix} 6 & -7 \\ -2 & 4 \end{pmatrix} = \begin{pmatrix} 0.6 & -0.7 \\ -0.2 & 0.4 \end{pmatrix}
       ```

**7. Application in Solving Linear Equations**
   - **Example Problem:**
     - **English:** Solve the system of equations using matrix representation:  
       ```math
       2x + 3y = 5
       ``` 
       ```math
       4x + 6y = 10
       ```
     - **Arabic:**
      حل نظام المعادلات باستخدام تمثيل المصفوفات:  
       ```math
       2x + 3y = 5
       ``` 
       ```math
       4x + 6y = 10
       ```
   - **Solution:**
     - **English:** The system can be represented as AX = B, where  
       ```math
       A = \begin{pmatrix} 2 & 3 \\ 4 & 6 \end{pmatrix}
       ```
       , 
       ```math
       X = \begin{pmatrix} x \\ y \end{pmatrix}
       ```
       , 
       ```math
       B = \begin{pmatrix} 5 \\ 10 \end{pmatrix}
       ```
       .  
       However, since the determinant of A is zero, the system has no unique solution.
     - **Arabic:** 
     
     يمكن تمثيل النظام على شكل AX = B، حيث  
       ```math
       A = \begin{pmatrix} 2 & 3 \\ 4 & 6 \end{pmatrix}
       ```
       ، 
       ```math
       X = \begin{pmatrix} x \\ y \end{pmatrix}
       ```
       ، 
       ```math
       B = \begin{pmatrix} 5 \\ 10 \end{pmatrix}
       ```
       .  
       لكن نظرًا لأن محدد A يساوي صفرًا، فلا يوجد حل فريد للنظام.

---

