                   CONTROL STATEMENT

IF CONDITON
```
PSEUDO CODE

DECLARE X: INTEGER
READ X
IF X >= 5 THEN
PRINT "X is grater than or equal to 5"
END IF

CODE

    public static void main(String[] args) {

        int x;

        Scanner sc = new Scanner(System.in);
        x = sc.nextInt();

        if (x >= 5) {
            System.out.println("X is greater than or equal to 5");
        }
    }
```
IF-ELSE CONDITION
```
PSEUDO CODE

DECLARE X: INTEGER
READ X
IF X >= 5 THEN
PRINT "X is grater than or equal to 5"
ELSE
PRINT "x is less than 5"
END IF

CODE

    public static void main(String[] args) {

        int x;

        Scanner sc = new Scanner(System.in);
        x = sc.nextInt();

        if (x >= 5) {
            System.out.println("X is greater than or equal to 5");
        } else {
            System.out.println("X is less than 5");
        }
    }
```

IF-ELSE-IF LADDER
```
PSEUDO CODE

DECLARE a : INTEGER
DECLARE b : INTEGER
DECLARE c : INTEGER
DECLARE d : INTEGER

READ a,b,c,d
DECLARE PER : REAL
PER := (a+b+c+d)/4
IF PER >=90 THEN
PRINT "A"
ELSE IF PER >=80 THEN
PRINT "B"
ELSE IF PER>=70 THEN
PRINT "C"
ELSE
PRINT "FAIL"

CODE

    public static void main(String[] args) {

        int a, b, c, d;
        double per;

        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        b = sc.nextInt();
        c = sc.nextInt();
        d = sc.nextInt();

        per = (a + b + c + d) / 4.0;

        if (per >= 90) {
            System.out.println("A");
        } else if (per >= 80) {
            System.out.println("B");
        } else if (per >= 70) {
            System.out.println("C");
        } else {
            System.out.println("FAIL");
        }
    }
```

NESTED IF
```
PSEUDO CODE

DECLARE UID : STRING
DECLARE PASS : STRING
READ UID,PASS
IF UID == "TIT" THEN
IF PASS = "TIT" THEN
PRINT "WELCOME"
ELSE
PRINT "INVALID PASS"
ELSE
PRINT "INVALID UID"

CODE

    public static void main(String[] args) {

        String UID, PASS;

        Scanner sc = new Scanner(System.in);
        UID = sc.next();
        PASS = sc.next();

        if (UID.equals("TIT")) {
            if (PASS.equals("TIT")) {
                System.out.println("WELCOME");
            } else {
                System.out.println("INVALID PASS");
            }
        } else {
            System.out.println("INVALID UID");
        }
    }
```

CASE OF
```
PSEUDO CODE

READ VALUE
CASE OF VALUE
1 : PRINT "ONE"
2 : PRINT "TWO"
3 : PRINT "THREE"
OTHERWISE
PRINT 'WRONG"
END CASE

CODE

    public static void main(String[] args) {

        int value;

        Scanner sc = new Scanner(System.in);
        value = sc.nextInt();

        switch (value) {
            case 1:
                System.out.println("ONE");
                break;

            case 2:
                System.out.println("TWO");
                break;

            case 3:
                System.out.println("THREE");
                break;

            default:
                System.out.println("WRONG");
        }
    }
```
