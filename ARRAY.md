ARRAY

DECLARATION 
```
DECLARE A : ARRAY [5] OF INTEGER
DECLARE B : ARRAY [10] OF REAL
DECLARE NAME : ARRAY [10] OF STRING
```
PSEUDO CODE
```
DECLARE A : ARRAY [0 : 4 ] OF INTEGER
FOR I := 0 TO 4
READ A[I]
END FOR 
FOR I := 0 TO 4
PRINT A[I]
END FOR

CODE 

    public static void main(String[] args) {

        int A[] = new int[5];
        int i;

        Scanner sc = new Scanner(System.in);

        for (i = 0; i <= 4; i++) {
            A[i] = sc.nextInt();
        }

        for (i = 0; i <= 4; i++) {
            System.out.println(A[i]);
        }
    }
```

FIND MAXIMUM IN ARRAY
```
PESUDO CODE

DECLARE A : ARRAY [5] OF INTEGER
DECLARE MAX : INTEGER
FOR I := 0 TO 4
READ A[I] 
END FOR 
SET MAX := A[0]
FOR I :=0 TO 4
IF A[I] > MAX THEN 
MAX := A[I]
END IF 
END FOR 
PRINT MAX

CODE

    public static void main(String[] args) {

        int A[] = new int[5];
        int i, max;

        Scanner sc = new Scanner(System.in);

        for (i = 0; i <= 4; i++) {
            A[i] = sc.nextInt();
        }

        max = A[0];

        for (i = 0; i <= 4; i++) {
            if (A[i] > max) {
                max = A[i];
            }
        }

        System.out.println(max);
    }
```
MULTI DIMENSIONAL ARRAY

DECLARATION
```
DECLARE X : ARRAY[2][2] OF INTEGER
OR
DECLARE X : ARRAY[0:1][0:1] OF INTEGER
OR 
INTEGER X[2][2]
```
PSEUDO CODE 
```
DECLARE X: ARRAY[2][2] OF INTEGER
DECLARE SUM : INTEGER
SUM := 0
FOR I := 0 TO 1
FOR J := 0 TO 1
READ X[I][J]
END FOR 
END FOR 
FOR I = 0 TO 1
FOR J = 0 TO 1
SUM := SUM+X[I][J]
END FOR 
END FOR 
PRINT SUM

CODE

    public static void main(String[] args) {

        int X[][] = new int[2][2];
        int i, j, sum;

        Scanner sc = new Scanner(System.in);

        sum = 0;

        for (i = 0; i <= 1; i++) {
            for (j = 0; j <= 1; j++) {
                X[i][j] = sc.nextInt();
            }
        }

        for (i = 0; i <= 1; i++) {
            for (j = 0; j <= 1; j++) {
                sum = sum + X[i][j];
            }
        }

        System.out.println(sum);
    }
```
FIND EVEN ODD
```
PSEUDO CODE 

DECLARE X : ARRAY[3][3] OF INTEGER
DECLARE EVEN : INTEGER
DECLARE ODD : INTEGER
SET ODD := 0
SET EVEN := 0
FOR I := O TO 2
FOR J := 0 TO 2
READ X[I][J]
END FOR 
END FOR 
FOR I = 0 TO 2
FOR J = 0 TO 2
IF X[I][J] MOD 2 == 0 THEN
INCREMENT EVEN
ELSE INCREMENT ODD 
END FOR 
END FOR 
PRINT EVEN 
PRINT ODD

CODE 

    public static void main(String[] args) {

        int X[][] = new int[3][3];
        int i, j, even, odd;

        Scanner sc = new Scanner(System.in);

        odd = 0;
        even = 0;

        for (i = 0; i <= 2; i++) {
            for (j = 0; j <= 2; j++) {
                X[i][j] = sc.nextInt();
            }
        }

        for (i = 0; i <= 2; i++) {
            for (j = 0; j <= 2; j++) {
                if (X[i][j] % 2 == 0) {
                    even++;
                } else {
                    odd++;
                }
            }
        }

        System.out.println(even);
        System.out.println(odd);
    }
```
ADDITON OF MATRIX
```
PSEUDO CODE 

DECLARE X : ARRAY [3][3] OF INTEGER
DECLARE Y : ARRAY [3][3] OF INTEGER
DECLARE Z : ARRAY [3][3] OF INTEGER

FOR I = 0 TO 2
FOR J = 0 TO 2
READ X[I][J]
READ Y[I][J]
END FOR 
END FOR 
FOR I = 0 TO 2
FOR J = 0 TO 2
Z[I][J] = X[I][J] + Y[I][J]
END FOR 
END FOR 
FOR I = 0 TO 2
FOR J = 0 TO 2
PRINT Z[I][J]
END FOR 
END FOR

CODE

    public static void main(String[] args) {

        int X[][] = new int[3][3];
        int Y[][] = new int[3][3];
        int Z[][] = new int[3][3];
        int i, j;

        Scanner sc = new Scanner(System.in);

        for (i = 0; i <= 2; i++) {
            for (j = 0; j <= 2; j++) {
                X[i][j] = sc.nextInt();
                Y[i][j] = sc.nextInt();
            }
        }

        for (i = 0; i <= 2; i++) {
            for (j = 0; j <= 2; j++) {
                Z[i][j] = X[i][j] + Y[i][j];
            }
        }

        for (i = 0; i <= 2; i++) {
            for (j = 0; j <= 2; j++) {
                System.out.println(Z[i][j]);
            }
        }
    }
```








