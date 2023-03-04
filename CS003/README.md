# Getting Started

### Reference Documentation

``` bash
mkdir CS002_VariablesConstantsIO
cd CS002_VariablesConstantsIO/
dotnet new console
code .
```

### Key 

``` bash
Toán tử	        Ý nghĩa               Ví dụ
+	              Phép cộng   	        a + b
-	              Phép trừ	            a - b
*	              Phép nhân	            a * b
/	              Phép chia	            a / b
%	        Phép chia lấy dư (modules)	a % b
```

### Thứ tự ưu tiên của các toán tử trong biểu thức
``` bash
Trong biểu thức, toán tử nào có độ ưu tiên cao hơn sẽ được tính trước.

Độ ưu tiên từ cao xuống thấp là: 1 trong ngoặc (), 2 số mũ - căn, 3 nhân hoặc chia * /, 4 cộng hoặc trừ + -

Khi độ ưu tiên ngang nhau, sẽ tính từ trái qua phải

```

### Toán tử gán trong C#
``` bash
Toán tử	Diễn tả	Ví dụ

=	Toán tử gán:
Gán biểu thức bên phải của = vào biến bên trái	
int x = 10 + 12;        // x bằng 22

+=	Toán tử công thêm:
Công thêm vào biến bên trái += giá trị bên phải	
int x = 10;
x += 2;                 // x bằng 12

-=	Toán tử trừ bớt:
Bớt đi giá trị biến bên trái của -= một lượng bằng biểu thức bên phải	
int c = 10;
c -= 3;                 // c = 7
               
*=	Toán tử nhân với:
a *= b tương đương a = a * b;	
int x = 2;
x *= 3;                 //x = 6

/=	Toán tử chia cho:
a / b tương đương a = a / b	
int a = 6;
a /= 2;                 // a = 3

%=	Toán tử gán module:
a %=b tương đương a = a % b;	
int a = 10;
a %= 3;                 // a = 1
```

### Toán tử tăng ++ và giảm -- trong C#
```bash
Nếu viết trước ++x thì toán tử ++ thi hành trước rồi mới áp dụng vào biểu thức, nếu viết sau dạng x++ thì biểu thức thi hành xong mới đến ++ (tương tự với --)
```
