# 🚀 C++ PROGRAM SKELETON

---

## 🧱 1. **Preprocessor Directive**

```cpp
#include <iostream>
```

### What is this?

* This line tells the compiler to include a **header file** before actual compilation starts.
* `<iostream>` contains code for:

  * input (cin)
  * output (cout)
  * streams (files)

---

### Why needed?

Because functions like `cout` and `cin` are not a part of core C++ language; they are part of standard libraries.

---

### How it works internally?

* `#include` copies the content of the file and pastes it into your program before compilation.
* This process is called “Preprocessing”

---

---

## 🌍 2. Namespace Declaration

```cpp
using namespace std;
```

### Meaning:

* `std` is the standard namespace that contains many standard C++ components:

  * cout
  * cin
  * string
  * vector
  * maps etc.

### Without namespace:

you would write

```cpp
std::cout << "Hello";
```

By writing:

```cpp
using namespace std;
```

You can write:

```cpp
cout << "Hello";
```

---

### Why do we need `<std>`?

* C++ organizes functionality into "namespaces"
* Think like folders inside a big computer
* `std` is just a folder name

---

---

# 🏁 3. The Main Function

```cpp
int main()
```

### ✨ Why every program needs main()?

Because program execution always starts from **main()**
This is the “entry point”.

---

### Why return type `int`?

* `main()` returns an integer to the operating system
* `0` means successful execution

Example:

```cpp
return 0;
```

means everything OK

---

---

# 🧩 4. Function Body

```cpp
{
    // code goes here
}
```

This pair of braces defines the beginning and end of the function.

Everything inside `{ }` belongs to main function.

---

---

# 🖨 5. Output Statement

```cpp
cout << "Hello World";
```

### Explanation:

* `cout` = character output
* `<<` = output insertion operator

What happens?

* text goes from program → output stream → computer screen

---

### Example:

```cpp
cout << "My name is Soumya";
```

---

---

# 🎯 6. Return Statement

```cpp
return 0;
```

### Why return?

* It sends result back to OS
* `0` means success
* A non-zero value means error

If we remove `return 0`, the compiler AUTO inserts return 0 (in modern standards)

---

---

# 📌 Complete Skeleton (with comments)

```cpp
#include <iostream>    // library for input/output

using namespace std;   // so we can use cout directly

int main()             // starting point of program
{
    cout << "Hello World";   // print message on screen

    return 0;          // tell OS program finished correctly
}
```

---

---

# 🔥 Core Concepts You Learned

| Concept      | Meaning                 |
| ------------ | ----------------------- |
| preprocessor | runs before compilation |
| iostream     | input/output library    |
| namespace    | collection of names     |
| std          | standard namespace      |
| main()       | starting point          |
| cout         | print output            |
| return       | exit code               |

---

---

# ⭐ Why This Structure is Essential?

Because:
✔ defines library dependencies
✔ tells compiler where execution starts
✔ uses standard library
✔ outputs something
✔ ends program properly

---

---

# 🧠 Extra Notes (IMPORTANT)

### 🟦 C++ has 4 major building blocks:

* preprocessor
* headers
* main
* statements

### 🟦 Program without `#include`?

❌ cannot use input/output

### 🟦 Program without main()?

❌ won't run

---

---

# 💎 Short Mind Map

```
#include ---> gives cout, cin
std ---> library namespace
main() ---> program entry
cout ---> output printing
return ---> tells OS success
```
