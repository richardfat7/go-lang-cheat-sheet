# Comments
// Line Comment
/* Block Comment */

# Data Types
bool (true / false)

uint8   (255 max)
uint16  (65,535 max)
uint32  (4.2 billion max)
uint64  (18,446 trillion max)
uint    alias for uint32
uintptr
byte    aslias for uint8

int8  (127 max)
int16 (32767 max)
int32 (2.1 billion max)
int64 (9,223 trillion max)
int   alias for int32
rune  alias for int32

float32 ex: 0.123456
float64 ex: 0.1e-5

complex64   ex: 12.34i
complex128 ex: 12.1e-5i

string

NaN
Array
Slice
Struct
Map
func


#functions

func add(x int, y int) int {
  return x + y
}


#bitwise

<< left shift (i.e. x2)
>> right shift (i.e. /2)
1<<2 = 100(bin) = 4
8>>2 = 10(bin) = 2
unbounded slices??


const (
  Big = 1<<100
  Small = Big>>99
)

# Loops
//
for i := 0; i < 10; i++ {
  fmt.Println($i)
}

// Equiv
i := 0;
for i < 10 {
  fmt.Println($i)
  i++
}

// For Each Loops
pow = []int{1, 2, 4, 8, 16, 32, 64, 128, 256}
for i, v := range pow {
  fmt.Printf("%d: %d\n", i, v)
}

// Switches
switch i {
  case 0:
    // do something
  default: f():
    // do something else
}


# Operators and assignment
 =
:=
+=
-=
++
--
+  Concat or addition, depending on context
&  Assign by reference (pointer)


# Checkings
<
>


# Common
fmt.Printf (debug)
fmt.Prinln (print a line with values)

#maps
m[key] = elem     insert of update
elem = m[key]     retreive an element
delete(m, key)    delete an element
elem, ok = m[key] test that a key is present

m := map[string]int {
  "item1" : 123,
  "item2" : 456,
}

#slices
p := []int{2, 3, 5, 7, 11, 13}
sliced := p[2:4]


