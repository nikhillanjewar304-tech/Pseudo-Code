PROCEDURES : DOESN'T RETURN VALUE 

DECLARATION 
```
PROCEDURES ADD(X : INTEGER, Y : INTEGER)
PRINT X+Y
END PROCEDURES

CALL ADD(12,3)
```
FUNCTION : RETURN VALUE

DECLARATION 
```
FUNCTION  ADD(X : INTEGER, Y : INTEGER)
RETURN INTEGER
RETURN X+Y
END FUNCTION
```
EXAMPLE PROCEDURE

FIND SIMPLE INTEREST
```
PSEUDO CODE 

PROCEDURE SIMINT(PA : INTEGER, ROI : REAL, NOY : REAL)
DECLARE SI : REAL
SI := (PA * ROI * NOY) / 100
PRINT SI
END PROCEDURE

CALL SIMINT(1000, 2.3, 1.2)

CODE 

    static void simint(int pa, double roi, double noy) {
        double si;
        si = (pa * roi * noy) / 100;
        System.out.println(si);
    }

    public static void main(String[] args) {
        simint(1000, 2.3, 1.2);
    }
```

FIND CUBE
```
PSEUDO CODE 

PROCEDURE CUBE(VALUE : INTEGER)
DECLARE ANS : INTEGER
ANS := VALUE * VALUE * VALUE
PRINT ANS
END PROCEDURE 

CALL CUBE(3)

CODE

    static void cube(int value) {
        int ans;
        ans = value * value * value;
        System.out.println(ans);
    }

    public static void main(String[] args) {
        cube(3);
    }
```
FIND TRIANGLE
```
PSEUDO CODE

PROCEDURE TRIANGLE(BASE : REAL, HEIGHT : REAL)
PRINT 0.5 * BASE * HEIGTH
END PROCEDURE

CALL TRIANGLE(5.1, 3.6)

CODE

    static void triangle(double base, double height) {
        System.out.println(0.5 * base * height);
    }

    public static void main(String[] args) {
        triangle(5.1, 3.6);
    }
```

FUNCTION EXAMPLE 

FIND SIMPLE INTREST
```
PSEUDO CODE 

FUNCTION SIMINT( PA : INTEGER, ROI : REAL, NOY : REAL) RETURN REAL
DECLARE SI : REAL
SI := (PA * ROI * NOY) / 100
RETURN SI
END FUNCTION 
PRINT CALL SIMINT(10, 3, 4)

CODE 

    static double simint(int pa, double roi, double noy) {
        double si;
        si = (pa * roi * noy) / 100;
        return si;
    }

    public static void main(String[] args) {
        System.out.println(simint(10, 3, 4));
    }
```

FIND CUBE
```
PSEUDO CODE 

FUNCTION CUBE (VALUE : INTEGER) RETURN INTEGER
RETURN VALUE * VALUE * VALUE
END FUNCTION
PRINT CALL CUBE(4)

CODE 

    static int cube(int value) {
        return value * value * value;
    }

    public static void main(String[] args) {
        System.out.println(cube(4));
    }
```
FIND ABSLUTE VALUE
```
PSEUDO CODE 

FUNCTION ABSVALUE (A: INTEGER) : INTEGER
IF A >= 0 THEN 
RETURN A 
ELSE
RETURN -A
END FUNCTION 
PRINT CALL ABSVALUE(5)

CODE

    static int absvalue(int a) {
        if (a >= 0) {
            return a;
        } else {
            return -a;
        }
    }

    public static void main(String[] args) {
        System.out.println(absvalue(5));
    }
```





















