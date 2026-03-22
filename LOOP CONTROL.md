
DO-WHILE LOOP
```
PSEUDO CODE

DECLARE X : INTEGER
SET I = 1
DO
PRINT I
INCREMENT I 
WHILE I <=10

CODE 

    public static void main(String[] args) {

        int x;
        int i = 1;

        do {
            System.out.println(i);
            i++;
        } while (i <= 10);
    }
```

WHILE LOOP
```
PSEUDO CODE

DECLARE i : INTEGER
SET i := 1
WHILE i <= 10
PRINT i
INCREMENT i 
END WHILE

CODE

    public static void main(String[] args) {

        int i = 1;

        while (i <= 10) {
            System.out.println(i);
            i++;
        }
    }
```

FOR LOOP
```
PSEUDO CODE

DECLARE i : INTEGER
DECLARE num : INTEGER
READ num
FOR i := 1 TO  10
PRINT i * num
END FOR

CODE

    public static void main(String[] args) {

        int i, num;

        Scanner sc = new Scanner(System.in);
        num = sc.nextInt();

        for (i = 1; i <= 10; i++) {
            System.out.println(i * num);
        }
    }
```

EXAMPLE

1. SUM THE SERIES 1+2+3+4+5------N
```
PSEUDO CODE 

DECLARE SUM : INTEGER
READ N
SUM := 0
FOR I := 1 TO N
SUM := SUM + I
END FOR 
PRINT SUM

CODE

    public static void main(String[] args) {

        int sum, n, i;

        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();

        sum = 0;

        for (i = 1; i <= n; i++) {
            sum = sum + i;
        }

        System.out.println(sum);
    }
```

2.  REVERSE NUMBER
```
PSEUDO CODE

DECLARE N : INTEGER
DECLARE R : INTEGER
DECLARE B : INTEGER
SET B := 0
READ N
WHILE N > 0
R = N MOD 10
B = B*10+R
N = N/10
END WHILE
PRINT B

CODE 

    public static void main(String[] args) {

        int n, r, b;

        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();

        b = 0;

        while (n > 0) {
            r = n % 10;
            b = b * 10 + r;
            n = n / 10;
        }

        System.out.println(b);
    }
```

3. PALINDROME
```
PSEUDO CODE

DECLARE N : INTEGER
DECLARE R : INTEGER
DECLARE B : INTEGER
DECLARE X : INTEGER

SET B := 0
READ N
SET X := N 
WHILE N > 0
R = N MOD 10
B = B * 10 + R
N = N \ 10
END WHILE
IF B == X THEN
PRINT "PALINDROME"
ELSE
PRINT "NOT PALINDROME"
END IF

CODE

    public static void main(String[] args) {

        int n, r, b, x;

        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();

        b = 0;
        x = n;

        while (n > 0) {
            r = n % 10;
            b = b * 10 + r;
            n = n / 10;
        }

        if (b == x) {
            System.out.println("PALINDROME");
        } else {
            System.out.println("NOT PALINDROME");
        }
    }
```

4. ARMS STROENG
```
PSEUDO CODE

DECLARE N : INTEGER
DECLARE R : INTEGER
DECLARE B : INTEGER
DECLARE X : INTEGER

SET B := 0
READ N
SET X := N
WHILE N > 0
R = N MOD 10
B = B + R * R * R
N = N / 10
END WHILE
IF B == X THEN
PRINT "ARMS STRONG"
ELSE PRINT "NOT ARMS STONG"
END IF

CODE

    public static void main(String[] args) {

        int n, r, b, x;

        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();

        b = 0;
        x = n;

        while (n > 0) {
            r = n % 10;
            b = b + r * r * r;
            n = n / 10;
        }

        if (b == x) {
            System.out.println("ARM STRONG");
        } else {
            System.out.println("NOT ARM STRONG");
        }
    }
```

5. COUNT ALL DIGIT OF A 12345
```
PSEUDO CODE

DECLARE N : INTEGER
DECLARE COUNT : INTEGER
READ N
SET COUNT := 0
WHILE N > 0
N = N / 10
INCREMENT COUNT 
END WHILE 
PRINT COUNT

CODE

    public static void main(String[] args) {

        int n, count;

        Scanner sc = new Scanner(System.in);
        n = sc.nextInt();

        count = 0;

        while (n > 0) {
            n = n / 10;
            count++;
        }

        System.out.println(count);
    }
```

6. TO COUNT HOW MANY TIMES DIGIT PRESENT IN A NUM
```
PSEUDO CODE 

DECLARE NUM : INTEGER
DECLARE COUNT : INTEGER
DECLARE R : INTEGER
DECLARE N : INTEGER

SET COUNT := 0
READ NUM
READ N
WHILE NUM > 0
R := NUM MOD 10
NUM = NUM / 10
IF N == R
INCREMENT COUNT 
END IF 
END WHILE
PRINT COUNT

CODE 

    public static void main(String[] args) {

        int num, count, r, n;

        Scanner sc = new Scanner(System.in);
        num = sc.nextInt();
        n = sc.nextInt();

        count = 0;

        while (num > 0) {
            r = num % 10;
            num = num / 10;

            if (n == r) {
                count++;
            }
        }

        System.out.println(count);
    }
```





























