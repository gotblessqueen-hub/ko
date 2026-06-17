Chào em, đây là file Markdown tổng hợp toàn bộ công thức Xác suất Thống kê dựa trên giáo trình em đã cung cấp.

Anh đã thiết kế phần Mục lục, phần Dấu hiệu nhận biết các dạng bài, và định dạng khoảng cách rộng rãi (bằng các thẻ ngắt dòng <br>) giữa các ý đúng như yêu cầu của em để em dễ dàng tra cứu trên máy tính hoặc in ra nhé.

TỔNG HỢP CÔNG THỨC XÁC SUẤT THỐNG KÊ (MÃ: XSTK_NEU)
MỤC LỤC
Phần 1: Dấu hiệu nhận biết các dạng bài tập

Phần 2: Công thức Thống kê mô tả

Phần 3: Công thức Xác suất cơ bản

Phần 4: Biến ngẫu nhiên và Phân phối xác suất

Phần 5: Các công thức Ước lượng tham số

Phần 6: Các công thức Kiểm định giả thuyết

Phần 7: Phân tích Phương sai (ANOVA) & Phi tham số

PHẦN 1: DẤU HIỆU NHẬN BIẾT CÁC DẠNG BÀI TẬP
Dạng đếm số kết cục, xác suất cổ điển: Đề bài thường có chữ "chọn ngẫu nhiên", "bốc ngẫu nhiên", "sắp xếp", "đồng chất đồng đều" từ một tập hợp cho trước. Dùng tổ hợp (C), chỉnh hợp (A), hoán vị (P).




Dạng Xác suất đầy đủ & Bayes: Đề bài thường chia làm 2 giai đoạn. Giai đoạn 1 có nhiều trường hợp (ví dụ: bốc từ 3 hộp khác nhau, có 3 máy sản xuất). Giai đoạn 2 là kết quả chung (ví dụ: bốc được phế phẩm). Nếu đề hỏi xác suất ngược lại kiểu "Biết đã bốc được phế phẩm, tính xác suất nó thuộc máy 1", đó chắc chắn là công thức Bayes.  
+1




Dạng Phân phối Nhị thức (Binomial): Đề bài có một phép thử được lặp lại chính xác n lần độc lập, xác suất thành công p không đổi qua các lần thử. Câu hỏi thường hỏi "Tính xác suất để có đúng x lần thành công".  





Dạng Phân phối Poisson: Đề cho số lượng mẫu n cực kì lớn, xác suất p cực kì nhỏ (hiếm gặp), hoặc cho sẵn số sự kiện trung bình λ xảy ra trong một khoảng thời gian/không gian nhất định (ví dụ: số cuộc gọi tới tổng đài trong 1 phút, số tai nạn giao thông).  
+1




Dạng Phân phối Chuẩn (Normal): Đề cho rõ "tuân theo luật phân phối Chuẩn", hoặc cho các thông số μ (trung bình) và σ 
2
  (phương sai). Luôn cần dùng thao tác chuẩn hóa Z=(X−μ)/σ và tra bảng hàm Laplace Φ(z).  
+1




Dạng Ước lượng khoảng: Đề bài chứa các từ khóa: "Với độ tin cậy 1−α", "Hãy ước lượng...", "Tìm khoảng tin cậy...", "Độ chính xác là...", "Cần điều tra thêm tối thiểu bao nhiêu...". Cần phân biệt rõ là ước lượng cho Trung bình (Mean), Phương sai (Variance) hay Tỉ lệ (Proportion).  
+2




Dạng Kiểm định giả thuyết: Đề bài chứa từ khóa: "Với mức ý nghĩa α", "Có ý kiến cho rằng...", "Hãy kiểm định...", "Có thể nói rằng... hay không?". Nếu hỏi chung chung (bằng/khác) là kiểm định 2 phía. Nếu chứa từ "nhiều hơn", "cao hơn", "vượt quá" là kiểm định phía phải. Nếu chứa từ "ít hơn", "thấp hơn" là kiểm định phía trái.  
+1

PHẦN 2: CÔNG THỨC THỐNG KÊ MÔ TẢ
Trung bình mẫu (Sample Mean):

x
ˉ
 = 
n
∑x 
i
​
 
​
 hoặc 
x
ˉ
 = 
∑w 
i
​
 
∑w 
i
​
 x 
i
​
 
​
 

(Áp dụng công thức thứ hai nếu có trọng số hoặc tần số w 
i
​
 ).  
+1




Phương sai mẫu hiệu chỉnh (Sample Variance):

s 
2
 = 
n−1
∑(x 
i
​
 − 
x
ˉ
 ) 
2
 
​
 

(Chú ý mẫu số là n−1, không phải N như tổng thể).  




Độ lệch chuẩn mẫu (Sample Standard Deviation):


s= 
s 
2
 

​
 
.  




Hệ số biến thiên (Coefficient of Variation):

CV= 
x
ˉ
 
s
​
 ×100%

(Dùng để so sánh độ phân tán của hai bộ dữ liệu khác đơn vị đo).  
+1




Giá trị chuẩn hóa (Z-score):


z 
i
​
 = 
s
x 
i
​
 − 
x
ˉ
 
​
 
.  




Hiệp phương sai mẫu (Sample Covariance):


Cov(X,Y)= 
n−1
∑(x 
i
​
 − 
x
ˉ
 )(y 
i
​
 − 
y
ˉ
​
 )
​
 = 
n−1
n
​
 ( 
x⋅y
​
 − 
x
ˉ
 ⋅ 
y
ˉ
​
 )
.  




Hệ số tương quan (Correlation Coefficient):


r 
X,Y
​
 = 
s 
X
​
 ⋅s 
Y
​
 
Cov(X,Y)
​
 
.  

PHẦN 3: CÔNG THỨC XÁC SUẤT CƠ BẢN
Định nghĩa cổ điển của xác suất:

P(A)= 
N
N 
A
​
 
​
 

(N 
A
​
  là số kết cục thuận lợi, N là tổng số kết cục có thể).  




Xác suất của biến cố đối lập:


P( 
A
 )=1−P(A)
.  




Công thức cộng xác suất (Biến cố tổng):

Trường hợp chung: 

P(A∪B)=P(A)+P(B)−P(A∩B)
.  

Nếu A và B xung khắc (A∩B=∅): 

P(A∪B)=P(A)+P(B)
.  




Công thức nhân xác suất (Biến cố tích):

Trường hợp chung: 

P(A∩B)=P(A)⋅P(B∣A)
.  

Nếu A và B độc lập: 

P(A∩B)=P(A)⋅P(B)
.  




Xác suất có điều kiện:


P(A∣B)= 
P(B)
P(A∩B)
​
 
.  




Công thức xác suất đầy đủ:

P(A)= 
i=1
∑
n
​
 P(H 
i
​
 )⋅P(A∣H 
i
​
 )

(Với H 
1
​
 ,H 
2
​
 ,…,H 
n
​
  là một nhóm đầy đủ các biến cố).  
+1




Công thức Bayes:


P(H 
i
​
 ∣A)= 
P(A)
P(H 
i
​
 )⋅P(A∣H 
i
​
 )
​
 
.  

PHẦN 4: BIẾN NGẪU NHIÊN VÀ PHÂN PHỐI XÁC SUẤT
Kỳ vọng (Expected Value):

Biến rời rạc: 

E(X)=∑x 
i
​
 p 
i
​
 
.  

Biến liên tục: 

E(X)=∫ 
−∞
+∞
​
 x⋅f(x)dx
.  




Phương sai (Variance):


V(X)=E(X 
2
 )−[E(X)] 
2
 
.  




Phân phối Nhị thức X∼B(n,p):

Hàm xác suất: 

P(X=x)=C 
n
x
​
 p 
x
 (1−p) 
n−x
 
.  

Đặc trưng: 

E(X)=np,V(X)=np(1−p)
.  




Phân phối Poisson X∼P(λ):

Hàm xác suất: 

P(X=x)=e 
−λ
  
x!
λ 
x
 
​
 
.  

Đặc trưng: 

E(X)=λ,V(X)=λ
.  




Phân phối Đều X∼U(a,b):

Mật độ xác suất: f(x)= 
b−a
1
​
  với x∈(a,b).  

Đặc trưng: 

E(X)= 
2
a+b
​
 ,V(X)= 
12
(b−a) 
2
 
​
 
.  




Phân phối Chuẩn X∼N(μ,σ 
2
 ):

Chuẩn hóa về Z∼N(0,1): 

Z= 
σ
X−μ
​
 
.  

Tính xác suất trong khoảng: 

P(a<X<b)=Φ( 
σ
b−μ
​
 )−Φ( 
σ
a−μ
​
 )
.  

PHẦN 5: CÁC CÔNG THỨC ƯỚC LƯỢNG THAM SỐ
Ước lượng Trung bình (μ) khi ĐÃ BIẾT phương sai σ 
2
 :

Khoảng tin cậy đối xứng: 

( 
x
ˉ
 −z 
α/2
​
  
n

​
 
σ
​
 ; 
x
ˉ
 +z 
α/2
​
  
n

​
 
σ
​
 )
.  

Xác định kích thước mẫu tối thiểu: 

n 
0
​
 ≥( 
ε 
0
​
 
z 
α/2
​
 σ
​
 ) 
2
 
.  




Ước lượng Trung bình (μ) khi CHƯA BIẾT phương sai σ 
2
  (dùng mẫu s):

Khoảng tin cậy đối xứng: 

( 
x
ˉ
 −t 
α/2
(n−1)
​
  
n

​
 
s
​
 ; 
x
ˉ
 +t 
α/2
(n−1)
​
  
n

​
 
s
​
 )
.  

Xác định kích thước mẫu tối thiểu: 

n 
0
​
 ≥ 

​
  
ε 
0
​
 
t 
α/2
(n−1)
​
 s
​
  

​
  
2
 
.  




Ước lượng Tỉ lệ (p) cho mẫu lớn (n≥100):

Khoảng tin cậy đối xứng: 

( 
p
^
​
 −z 
α/2
​
  
n
p
^
​
 (1− 
p
^
​
 )
​
 

​
 ; 
p
^
​
 +z 
α/2
​
  
n
p
^
​
 (1− 
p
^
​
 )
​
 

​
 )
.  

Xác định kích thước mẫu tối thiểu: 

n 
0
​
 ≥ 
ε 
0
2
​
 
p
^
​
 (1− 
p
^
​
 )z 
α/2
2
​
 
​
 
.  




Ước lượng Phương sai (σ 
2
 ):

Khoảng tin cậy hai phía: 

( 
χ 
α/2
2
​
 (n−1)
(n−1)s 
2
 
​
 ; 
χ 
1−α/2
2
​
 (n−1)
(n−1)s 
2
 
​
 )
.  

PHẦN 6: CÁC CÔNG THỨC KIỂM ĐỊNH GIẢ THUYẾT
Kiểm định Trung bình (μ) khi ĐÃ BIẾT σ 
2
 :

Tiêu chuẩn kiểm định:

Z 
qs
​
 = 
σ/ 
n

​
 
x
ˉ
 −μ 
0
​
 
​
 
Miền bác bỏ 2 phía: ∣Z 
qs
​
 ∣>[cite 
s
​
 tart]z 
α/2
​
 .  




Kiểm định Trung bình (μ) khi CHƯA BIẾT σ 
2
 :

Tiêu chuẩn kiểm định:

T 
qs
​
 = 
s/ 
n

​
 
x
ˉ
 −μ 
0
​
 
​
 
Miền bác bỏ 2 phía: ∣T 
qs
​
 ∣>[cite 
s
​
 tart]t 
α/2
(n−1)
​
 .  




Kiểm định Tỉ lệ (p) một tổng thể:

Tiêu chuẩn kiểm định:

Z 
qs
​
 = 
p 
0
​
 (1−p 
0
​
 )/n

​
 
p
^
​
 −p 
0
​
 
​
 
Miền bác bỏ 2 phía: ∣Z 
qs
​
 ∣>[cite 
s
​
 tart]z 
α/2
​
 .  




Kiểm định Phương sai (σ 
2
 ) một tổng thể:

Tiêu chuẩn kiểm định:

χ 
qs
2
​
 = 
σ 
0
2
​
 
(n−1)s 
2
 
​
 
Miền bác bỏ 2 phía: χ 
qs
2
​
 >χ 
α/2
2
​
 (n−1) hoặc χ 
qs
2
​
 <χ 
1−α/2
2
​
 (n−1).  




Kiểm định Trung bình hai tổng thể (Mẫu độc lập, n 
1
​
 ,n 
2
​
 >30):

Tiêu chuẩn kiểm định:

T 
qs
​
 = 
n 
1
​
 
s 
1
2
​
 
​
 + 
n 
2
​
 
s 
2
2
​
 
​
 

​
 
x
ˉ
  
1
​
 − 
x
ˉ
  
2
​
 
​
 
Miền bác bỏ 2 phía: ∣T 
qs
​
 ∣>[cite 
s
​
 tart]z 
α/2
​
 .  




Kiểm định Tỉ lệ hai tổng thể:

Tiêu chuẩn kiểm định:

Z 
qs
​
 = 
p
ˉ
​
 (1− 
p
ˉ
​
 )( 
n 
1
​
 
1
​
 + 
n 
2
​
 
1
​
 )

​
 
p
^
​
  
1
​
 − 
p
^
​
  
2
​
 
​
 
với  
p
ˉ
​
 = 
n 
1
​
 +n 
2
​
 
n 
1
​
  
p
^
​
  
1
​
 +n 
2
​
  
p
^
​
  
2
​
 
​
 

Miền bác bỏ 2 phía: ∣Z 
qs
​
 ∣>[cite 
s
​
 tart]z 
α/2
​
 .  




Kiểm định Phương sai hai tổng thể (Kiểm định Fisher):

Tiêu chuẩn kiểm định:

F 
qs
​
 = 
s 
2
2
​
 
s 
1
2
​
 
​
 
(Quy ước chọn s 
1
2
​
 >s 
2
2
​
 )

Miền bác bỏ (phía phải): F 
qs
​
 >f 
α
​
 (n 
1
​
 −1,n 
2
​
 −1).  

PHẦN 7: PHÂN TÍCH PHƯƠNG SAI (ANOVA) & PHI THAM SỐ
Kiểm định tính Chuẩn (Jarque-Bera):

Tiêu chuẩn:

JB=n[ 
6
a 
3
2
​
 
​
 + 
24
(a 
4
​
 −3) 
2
 
​
 ]
Bác bỏ H 
0
​
  (không phân phối chuẩn) nếu: JB>χ 
α
2
​
 (2).  




Kiểm định Tính độc lập (Chi-square test):

Tiêu chuẩn:

χ 
2
 =n 
i=1
∑
h
​
  
j=1
∑
k
​
  
n 
i
​
 m 
j
​
 
n 
ij
2
​
 
​
 −1
Bác bỏ H 
0
​
  (không độc lập) nếu: χ 
2
 >χ 
α
2
​
 ((h−1)(k−1)).  




Phân tích phương sai một nhân tố (One-way ANOVA):

Phương trình biến động: 

SST=SSB+SSW
.  

Bậc tự do (df): df 
SST
​
 =n−1, df 
SSB
​
 =k−1, df 
SSW
​
 =n−k.  

Thống kê Fisher: 

F= 
MSW
MSB
​
 = 
SSW/(n−k)
SSB/(k−1)
​
 
.  

Bác bỏ H 
0
​
  (có tác động) nếu: F>f 
α
​
 (k−1,n−k).  




Phân tích phương sai hai nhân tố không tương tác (Two-way ANOVA):

Phương trình biến động: 

SST=SSA+SSB+SSW
.  

Bậc tự do: df 
A
​
 =h−1, df 
B
​
 =k−1, df 
W
​
 =n−h−k+1.  

Kiểm định F cho từng nhân tố tương ứng: F 
A
​
 = 
MSW
MSA
​
  và F 
B
​
 = 
MSW
MSB
​
 .
