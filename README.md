# C-Program-for-2D-array
```
#include <stdio.h>

int main() {
  
    int arr[3][2] = { { 0, 1 }, { 2, 3 }, { 4, 5 } };

    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 2; j++) {
            printf("arr[%d][%d]: %d    ", i, j, arr[i][j]);
        }
          printf("\n");
    }
    return 0;
}
```
