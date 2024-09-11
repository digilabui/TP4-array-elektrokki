# Tugas Pendahuluan Modul 4

Nama : [Change Me]

NPM : [Change Me]


# 1. Jelaskan apa itu array dan jelaskan bagaimana cara untuk mengakses sebuah array 1D! (15 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

### Referensi :
- 
- 


# 2. Apa itu array 2D (multidimensi) dan bagaimana cara membuatnya? (10 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

### Referensi :
- 
- 


# 3. Sebutkan keuntungan dan kekurangan dari Array 1D dan Array 2D  (10 poin)

### Array 1D

| Keuntungan                                            | Kekurangan                                       |
|-------------------------------------------------------|--------------------------------------------------|
| Lorem ipsum dolor sit amet, consectetur adipiscing elit. | Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. |
| Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. | Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. |
| Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. | Velit esse cillum dolore eu fugiat nulla pariatur. |
| Curabitur pretium tincidunt lacus.                    | Excepteur sint occaecat cupidatat non proident. |

### Array 2D

| Keuntungan                                            | Kekurangan                                       |
|-------------------------------------------------------|--------------------------------------------------|
| Lorem ipsum dolor sit amet, consectetur adipiscing elit. | Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. |
| Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. | Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. |
| Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. | Velit esse cillum dolore eu fugiat nulla pariatur. |
| Curabitur pretium tincidunt lacus.                    | Excepteur sint occaecat cupidatat non proident. |

### Referensi :
- 
- 


# 4. Analisis Program (35 poin):

Analisislah program berikut dan jawablah pertanyaan dibawah.

```
#include <stdio.h>

int main (){
	int matrix[3][3] = {{1, 2, 3}, {1, 2, 3}, {1, 2, 3}};
	int i, j;
	printf("Before : \n");
	for(i = 0; i < 3; i++){
		for(j = 0; j < 3; j++){
			printf("%d", matrix[i][j]);
		}
		printf("\n");
	}
	
	printf("\nAfter : \n");
	for(i = 0; i < 3; i++){
		for(j = 0; j < 3; j++){
			matrix[i][j] = matrix[i][j] + matrix[i][j];
			printf("%d", matrix[i][j]);
		}
		printf("\n");
	}

    return 0;
}
```

**a. Apa yang dilakukan program tersebut? (5 Poin)**

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

**b. Ubahlah program tersebut menjadi diagonalnya saja yang dijumlah! (15 poin)**

```
Contoh Output :
223
143
126
```

**c. Kemudian ubahlah output program tersebut menjadi transpose (15 poin)**

```
Contoh Output :
211
242
336
```

**Note** : bagian b dan c digabung saja menjadi 1 program

### Referensi :
- 
- 


# 5. Pembuatan Program (30 poin):

Buatlah sebuah program yang mengenkripsi isi dari array berikut dengan melakukan shifting sebanyak 1 kali. Contoh shifting ```a --> b```, ```b --> c```, dst.
```
char hero[5][10] = {"gusion", "fanny", "yin", "johnson", "nana"};
```

*Output harus sesuai dengan format test case*

#### Test Case:

```
Hero 1: hvtjpo
Hero 2: gbooz
Hero 3: zjo
Hero 4: kpiotpo
Hero 5: obob
```



# Note
File yang dikumpulkan pada TP ini adalah :
- File .md ```Format Penamaan TP_ALPROG[NomorModul]_NamaLengkap_NPM.md```
- File .c (*Nomor 4 b dan c*) ```Format penamaan Nomor4.c```
- File .c (*Nomor 5*) ```Format penamaan Nomor5.c```
