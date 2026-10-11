# CHEFGAMES - Rating 546

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-11T16:33:42.605Z  

```c_cpp

#include <iostream>
using namespace std;
int main() {
    int T;
    cin >> T;
    while (T--) {
        int N, X;
        cin >> N >> X;

        int pizza = (N * X + 3) / 4;

      cout << pizza << endl;
    }

    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/CHEFGAMES)