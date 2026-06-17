MỤC LỤC      
Bài 1 — Thống kê mô tả            
Bài 2 — Biến cố và Xác suất        
Bài 3 — Biến ngẫu nhiên rời rạc       
Bài 4 — Biến ngẫu nhiên liên tục       
Bài 5 — Mẫu ngẫu nhiên       
Bài 6 — Ước lượng tham số     
Bài 7 — Kiểm định tham số        
Bài 8 — Kiểm định phi tham số    
Bài 9 — Phân tích phương sai    
Từ điển thuật ngữ Anh - Việt
PHẦN 1: DẤU HIỆU NHẬN BIẾT CÁC DẠNG BÀI TẬP         
Dạng đếm số kết cục, xác suất cổ điển:       
Đề bài thường có chữ "chọn ngẫu nhiên", "bốc ngẫu nhiên", "sắp xếp", "đồng chất đồng đều" từ một tập hợp cho trước. Dùng tổ hợp ($C$), chỉnh hợp ($A$), hoán vị ($P$).       
Dạng Xác suất đầy đủ & Bayes: Đề bài thường chia làm 2 giai đoạn. Giai đoạn 1 có nhiều trường hợp (ví dụ: bốc từ 3 hộp khác nhau, có 3 máy sản xuất). Giai đoạn 2 là kết quả chung (ví dụ: bốc được phế phẩm). Nếu đề hỏi xác suất ngược lại kiểu "Biết đã bốc được phế phẩm, tính xác suất nó thuộc máy 1", đó chắc chắn là công thức Bayes.        
Dạng Phân phối Nhị thức (Binomial): Đề bài có một phép thử được lặp lại chính xác $n$ lần độc lập, xác suất thành công $p$ không đổi qua các lần thử. Câu hỏi thường hỏi "Tính xác suất để có đúng $x$ lần thành công".          
Dạng Phân phối Poisson: Đề cho số lượng mẫu $n$ cực kì lớn, xác suất $p$ cực kì nhỏ (hiếm gặp), hoặc cho sẵn số sự kiện trung bình $\lambda$ xảy ra trong một khoảng thời gian/không gian nhất định (ví dụ: số cuộc gọi tới tổng đài trong 1 phút, số tai nạn giao thông).                
Dạng Phân phối Chuẩn (Normal): Đề cho rõ "tuân theo luật phân phối Chuẩn", hoặc cho các thông số $\mu$ (trung bình) và $\sigma^2$ (phương sai). Luôn cần dùng thao tác chuẩn hóa $Z = (X - \mu)/\sigma$ và tra bảng hàm Laplace $\Phi(z)$.  
Dạng Ước lượng khoảng: Đề bài chứa các từ khóa: "Với độ tin cậy $1-\alpha$", "Hãy ước lượng...", "Tìm khoảng tin cậy...", "Độ chính xác là...", "Cần điều tra thêm tối thiểu bao nhiêu...". Cần phân biệt rõ là ước lượng cho Trung bình (Mean), Phương sai (Variance) hay Tỉ lệ (Proportion).         
Dạng Kiểm định giả thuyết: Đề bài chứa từ khóa: "Với mức ý nghĩa $\alpha$", "Có ý kiến cho rằng...", "Hãy kiểm định...", "Có thể nói rằng... hay không?". Nếu hỏi chung chung (bằng/khác) là kiểm định 2 phía. Nếu chứa từ "nhiều hơn", "cao hơn", "vượt quá" là kiểm định phía phải. Nếu chứa từ "ít hơn", "thấp hơn" là kiểm định phía trái.      

Bài 1 — Thống kê mô tả       
1.1 Các khái niệm cơ bản       
Thống kê (Statistics) là môn học gồm 4 bước:          

Thu thập dữ liệu                                 
Xử lý dữ liệu         
Trình bày, biểu diễn dữ liệu                                                            
Phân tích và suy diễn thông tin                                       
                 
Hai nhánh chính:    
          
Thống kê mô tả (Descriptive Statistics) — sắp xếp, tóm tắt, trình bày dữ liệu                 
Thống kê suy diễn (Inferential Statistics) — dự đoán, kiểm chứng, kết luận tổng quát                 
Cầu nối giữa hai nhánh là Lý thuyết xác suất (Probability Theory)         

Tổng thể và Mẫu:                                         
                 
Tổng thể (Population) — toàn bộ đối tượng cần nghiên cứu; kích thước N, có thể vô hạn                 
Giá trị tính từ tổng thể gọi là tham số (parameter)             
Mẫu (Sample) — tập con rút ra từ tổng thể; kích thước n, hữu hạn                  
Giá trị tính từ mẫu gọi là thống kê (statistic)   

Cấu trúc dữ liệu truyền thống: gồm Quan sát (Observation) — Biến (Variable) — Giá trị (Value)                  
                 
Phân loại biến:                        

Định tính (Qualitative): không đo được bằng số                   
Định danh (Nominal): ví dụ tên, địa chỉ, ngành học                                                           
Thứ bậc (Ordinal): có thứ tự, ví dụ xếp hạng, cỡ giày                  
Nhị phân (Binary): chỉ có 2 giá trị, ví dụ Đúng/Sai, Nam/Nữ                 
Định lượng (Quantitative): đo được bằng số, có đơn vị                                             
Rời rạc (Discrete): đếm được, ví dụ số buổi học, tuổi                                          
Liên tục (Continuous): đo lường được, ví dụ thời gian, cân nặng                          

Thang đo Likert: dùng trong bảng hỏi đánh giá, thường 5 bậc (1=Rất không đồng ý → 5=Rất đồng ý) hoặc 7 bậc                


1.2 Bảng biểu và Đồ thị
Bảng tần số (Frequency table) — đếm số lần xuất hiện của mỗi giá trị        
Bảng tần suất (Relative frequency) — tần số chia tổng, tức là tỷ lệ phần trăm                                  
Bảng tần suất tích lũy — cộng dồn tần suất từ đầu đến mỗi giá trị               
Đồ thị tròn (Pie chart) — dùng cho biến định tính                 
Đồ thị cột (Column chart / Bar chart) — dùng cho biến định tính hoặc rời rạc 
Đồ thị phân phối giá trị (Histogram) — dùng cho biến liên tục, các cột liền nhau                                           
Đồ thị rải điểm (Scatter plot) — thể hiện mối quan hệ giữa hai biến định lượng                 

Hình dạng phân phối:                             

Đối xứng, dạng chuông (Symmetrical) — phân phối chuẩn lý tưởng                 
Lệch trái / lệch âm (Negatively skewed / Left skewed) — đuôi kéo về bên trái                 
Lệch phải / lệch dương (Positively skewed / Right skewed) — đuôi kéo về bên phải                                             


1.3 Thống kê mô tả bằng số                  
Nhóm xu thế trung tâm (Central tendency)            
Trung bình (Mean) — tổng tất cả giá trị chia cho số quan sát; dùng cho biến định lượng                                 
Trung bình có trọng số (Weighted mean) — mỗi giá trị nhân với trọng số tương ứng rồi chia tổng trọng số                  
Trung vị (Median) — giá trị đứng giữa khi sắp xếp từ nhỏ đến lớn                   
Nếu n lẻ: lấy giá trị ở vị trí (n+1)/2                                    
Nếu n chẵn: trung bình cộng 2 giá trị giữa                                         
Mốt (Mode) — giá trị xuất hiện nhiều nhất (ít nhất 2 lần)            
Các vị trí (Quantiles)             
Tứ phân vị (Quartile): Q1, Q2, Q3 chia dữ liệu thành 4 phần bằng nhau; Q2 chính là trung vị                    
Bách phân vị (Percentile): P1 đến P99 chia dữ liệu thành 100 phần bằng nhau                    
Hàm Excel: QUARTILE.EXC / QUARTILE.INC, PERCENTILE.EXC / PERCENTILE.INC                    
Nhóm đo độ phân tán (Dispersion)                
Khoảng biến thiên (Range) — giá trị lớn nhất trừ giá trị nhỏ nhất; đơn giản nhất nhưng dễ bị ảnh hưởng bởi ngoại lai     
Phương sai (Variance) — trung bình bình phương độ lệch so với trung bình; đơn vị là bình phương đơn vị gốc                 
Phương sai tổng thể: chia cho N          
Phương sai mẫu: chia cho (n-1)                                    
Excel: VAR.P (tổng thể), VAR.S (mẫu)        
Độ lệch chuẩn (Standard Deviation) — căn bậc hai của phương sai; cùng đơn vị với dữ liệu                
Excel: STDEV.P (tổng thể), STDEV.S (mẫu)                   
Hệ số biến thiên (Coefficient of Variation, CV) — độ lệch chuẩn chia trung bình nhân 100%; đơn vị là %, dùng để so sánh độ phân tán giữa các biến có đơn vị khác nhau            
Khoảng tứ phân vị (Interquartile Range, IQR) — IQR = Q3 trừ Q1; ít bị ảnh hưởng bởi ngoại lai    
Giá trị ngoại lai (Outlier): nằm ngoài khoảng [Q1 - 1,5×IQR ; Q3 + 1,5×IQR]     
Giá trị chuẩn hóa (Z-score) — (giá trị - trung bình) chia độ lệch chuẩn; dùng để so sánh giữa các thang đo khác nhau       
Nhóm hình dáng phân phối                                        
Hệ số bất đối xứng (Skewness) — đo mức độ lệch trái hoặc phải                    
Skewness > 0: lệch phải (đuôi phải)                                         
Skewness < 0: lệch trái (đuôi trái)                           
Excel: SKEW(data)                    
Hệ số nhọn (Kurtosis) — đo mức độ nhọn hay bẹt của phân phối so với phân phối chuẩn        
Excel: KURT(data)                      
Nhóm đo độ liên hệ         
Hiệp phương sai (Covariance) — đo chiều hướng biến động chung của hai biến; Excel: COVARIANCE.P / COVARIANCE.S             
Hệ số tương quan (Correlation coefficient, r) — đo mức độ liên hệ tuyến tính giữa hai biến                           
Nằm trong đoạn [-1; 1]                          
r gần 0: tương quan yếu                                       
r gần 1 hoặc -1: tương quan mạnh                   
r > 0: tương quan dương (cùng chiều)                 
r < 0: tương quan âm (ngược chiều)                                         
Excel: CORREL(data)                            


Bài 2 — Biến cố và Xác suất          
2.1 Phép thử và Biến cố                     
Phép thử (Experiment) — thực hiện một nhóm điều kiện để quan sát một hiện tượng                                  
Kết cục (Outcome) — hiện tượng có thể xảy ra trong phép thử                         
Kết cục sơ cấp (Basic outcome) — kết cục không thể chia nhỏ hơn                 
Không gian mẫu (Sample space, S) — tập hợp tất cả kết cục sơ cấp                         
Biến cố (Event) — tập con của không gian mẫu                                   

Phân loại biến cố:                     

Biến cố chắc chắn (Certain event) — luôn xảy ra, xác suất = 1                  
Biến cố không thể có (Impossible event) — không bao giờ xảy ra, xác suất = 0                 
Biến cố ngẫu nhiên (Random event) — có thể xảy ra hoặc không, xác suất trong khoảng (0;1)                      
Biến cố đối lập (Complement) — hai biến cố loại trừ nhau và bao phủ hết không gian mẫu            


2.2 Xác suất của biến cố                     
Xác suất (Probability) — con số đặc trưng cho khả năng xảy ra của biến cố, từ 0 đến 1                   
Xác suất của biến cố đối lập A-bar = 1 trừ xác suất của A                              

Định nghĩa cổ điển: xác suất = (số kết cục thuận lợi) chia (tổng số kết cục), áp dụng khi các kết cục có khả năng xảy ra đều nhau                               
                 
Định nghĩa thống kê: khi số phép thử đủ lớn, xác suất xấp xỉ bằng tần suất xuất hiện biến cố                    
                                 
Hai nguyên lý thực hành:
                    
Nguyên lý xác suất lớn: xác suất rất lớn → thực tế coi như biến cố đó sẽ xảy ra                
Nguyên lý xác suất nhỏ: xác suất rất nhỏ → thực tế coi như biến cố đó sẽ không xảy ra  

Xác suất có điều kiện (Conditional probability): P(A|B) — xác suất của A khi biết B đã xảy ra      


2.3 Các công thức xác suất     
Biến cố đối lập: P(A-bar) = 1 - P(A)       
Biến cố tích (Intersection): xảy ra cả A và B đồng thời — P(A và B)       
Biến cố tổng (Union): xảy ra ít nhất một trong A hoặc B — P(A hoặc B) = P(A) + P(B) - P(A và B)    
Hai biến cố xung khắc (Mutually exclusive): không thể xảy ra cùng lúc → P(A và B) = 0, nên P(A hoặc B) = P(A) + P(B)      
Hai biến cố độc lập (Independent): xảy ra của A không ảnh hưởng đến B → P(A và B) = P(A) × P(B)      
Công thức nhân xác suất (tổng quát): P(A và B) = P(A) × P(B|A)    
Công thức xác suất đầy đủ: khi có hệ đầy đủ các giả thuyết H1, H2, ..., Hn thì xác suất của A bằng tổng P(Hi) × P(A|Hi)    
Công thức Bayes: tính xác suất ngược — biết kết quả, suy ra giả thuyết nào có khả năng xảy ra cao nhất     
Công thức Bernoulli: tính xác suất có đúng k thành công trong n phép thử độc lập, mỗi phép có xác suất thành công p       
    

Bài 3 — Biến ngẫu nhiên rời rạc       
Khái niệm      
Biến ngẫu nhiên (Random variable) — biến nhận giá trị số tùy theo kết cục phép thử                  
Biến ngẫu nhiên rời rạc (Discrete random variable) — nhận hữu hạn hoặc đếm được các giá trị           
Bảng phân phối xác suất (Probability distribution table) — liệt kê tất cả giá trị và xác suất tương ứng; tổng xác suất = 1     
Các đặc trưng số       
Kỳ vọng (Expected value / Mean, E[X] hay mu) — trung bình có trọng số là xác suất; đo xu thế trung tâm       
Phương sai (Variance, D[X] hay sigma^2) — đo độ phân tán quanh kỳ vọng              
Độ lệch chuẩn (Standard deviation, sigma) — căn bậc hai của phương sai         
Một số phân phối rời rạc thường gặp        
Phân phối Bernoulli — phép thử chỉ có 2 kết quả: thành công (p) hoặc thất bại (1-p)       
Phân phối nhị thức (Binomial distribution) — số lần thành công trong n phép thử Bernoulli độc lập; ký hiệu B(n, p)      
Phân phối Poisson — số sự kiện xảy ra trong một khoảng thời gian hoặc không gian cố định; phù hợp khi n lớn, p nhỏ, trung bình lambda = n×p
             

Bài 4 — Biến ngẫu nhiên liên tục        
Khái niệm        
Biến ngẫu nhiên liên tục (Continuous random variable) — nhận vô số giá trị trong một khoảng      
Xác suất tại một điểm cụ thể = 0; chỉ tính xác suất trên một khoảng     
Hàm mật độ xác suất (Probability density function, PDF) — mô tả phân phối; diện tích dưới đường cong = 1      
Hàm phân phối tích lũy (Cumulative distribution function, CDF) — xác suất để biến nhỏ hơn hoặc bằng một giá trị    
Phân phối chuẩn (Normal distribution)      
Còn gọi là phân phối Gauss, hình dạng chuông đối xứng   
Hoàn toàn xác định bởi hai tham số: trung bình (mu) và độ lệch chuẩn (sigma)   
Phân phối chuẩn tắc (Standard normal): trung bình = 0, độ lệch chuẩn = 1; ký hiệu Z       
Chuẩn hóa để đưa về phân phối chuẩn tắc: Z = (X - mu) / sigma      
Quy tắc 68-95-99,7: khoảng 1 độ lệch chuẩn chứa 68%, 2 độ lệch chuẩn chứa 95%, 3 độ lệch chuẩn chứa 99,7% dữ liệu   
Kiểm tra chuẩn: dùng biểu đồ Q-Q plot hoặc kiểm định Shapiro-Wilk, Kolmogorov-Smirnov                          
Phân phối chuẩn tắc — các giá trị hay dùng                
z = 1,645 ứng với xác suất một phía 95% (dùng khi độ tin cậy 90%)                       
z = 1,96 ứng với xác suất hai phía 95% (dùng khi độ tin cậy 95%)                  
z = 2,576 ứng với xác suất hai phía 99%                
Các phân phối liên tục khác                 
Phân phối t (t-distribution / Student's t) — giống chuẩn nhưng đuôi dày hơn; dùng khi mẫu nhỏ hoặc không biết phương sai tổng thể; tham số là bậc tự do (df)    
Phân phối Chi-bình phương (Chi-squared) — dùng để kiểm định phương sai và kiểm định phi tham số                
Phân phối F (F-distribution / Fisher) — dùng để so sánh phương sai hai tổng thể và phân tích phương sai                  


Bài 5 — Mẫu ngẫu nhiên                      
Khái niệm                     
Mẫu ngẫu nhiên (Random sample) — mẫu được chọn sao cho mỗi phần tử có cơ hội bằng nhau      
Thống kê mẫu (Sample statistic) — giá trị tính từ mẫu dùng để ước lượng tham số tổng thể                               
Phân phối mẫu (Sampling distribution) — phân phối của một thống kê mẫu qua nhiều lần lấy mẫu                      
Định lý giới hạn trung tâm (Central Limit Theorem, CLT)                   
Khi cỡ mẫu n đủ lớn (thường n ≥ 30), phân phối của trung bình mẫu xấp xỉ phân phối chuẩn bất kể phân phối tổng thể ban đầu là gì                            
Trung bình của phân phối mẫu bằng trung bình tổng thể (mu)                 
Độ lệch chuẩn của phân phối mẫu (sai số chuẩn / Standard Error) = sigma chia căn n                     
Sai số chuẩn (Standard Error)                                       
Đo độ biến động của trung bình mẫu giữa các lần lấy mẫu khác nhau                 
Cỡ mẫu càng lớn thì sai số chuẩn càng nhỏ, ước lượng càng chính xác                 

          
Bài 6 — Ước lượng tham số            
Khái niệm     
Ước lượng điểm (Point estimation) — dùng một giá trị duy nhất của mẫu để ước lượng tham số                                 
Ước lượng khoảng (Interval estimation) — cho ra một khoảng giá trị có khả năng chứa tham số thật                   
Độ tin cậy (Confidence level) — xác suất để khoảng tin cậy chứa tham số thật; thường dùng 95%               
Mức ý nghĩa (Significance level, alpha) = 1 - độ tin cậy; thường alpha = 0,05         
Sai số ước lượng (Margin of error, epsilon) — nửa độ dài khoảng tin cậy
Độ dài khoảng tin cậy I = 2 × epsilon                  
Ước lượng trung bình (mu)         
Khoảng tin cậy đối xứng: (x-bar - epsilon ; x-bar + epsilon)                                           
Khoảng tin cậy tối thiểu: mu > x-bar - epsilon (cận dưới)                 
Khoảng tin cậy tối đa: mu < x-bar + epsilon (cận trên)                 
Khi biết phương sai tổng thể hoặc n >= 30: dùng phân phối chuẩn Z, epsilon = z × (sigma / căn n)       
Khi không biết phương sai và n nhỏ: dùng phân phối t với bậc tự do df = n-1, epsilon = t × (s / căn n)     
Ước lượng tỷ lệ (p)                                                                             
Tần suất mẫu f = m/n (m là số phần tử có thuộc tính cần quan tâm)                   
epsilon = z × căn[f(1-f)/n]                           
Khoảng đối xứng: f - epsilon < p < f + epsilon            
Ước lượng phương sai (sigma^2)  
Dùng phân phối Chi-bình phương với bậc tự do df = n-1    
Khoảng tin cậy không đối xứng    
Xác định cỡ mẫu cần thiết   
Muốn đạt sai số epsilon với độ tin cậy cho trước, tính ngược ra n tối thiểu    
Cỡ mẫu tăng thì sai số giảm theo tỷ lệ: giảm sai số 1/k lần thì cần tăng cỡ mẫu k^2 lần     

   
Bài 7 — Kiểm định tham số        
Khái niệm chung        
Kiểm định giả thuyết (Hypothesis testing) — quy trình dùng dữ liệu mẫu để quyết định chấp nhận hay bác bỏ một giả thuyết về tổng thể          
Giả thuyết không (Null hypothesis, H0) — giả thuyết đang được kiểm định, thường là "không có sự khác biệt" hoặc bằng một giá trị cụ thể        
Giả thuyết thay thế (Alternative hypothesis, H1) — điều ta muốn chứng minh       
Mức ý nghĩa alpha — xác suất bác bỏ H0 khi H0 đúng (sai lầm loại 1); thường = 0,05      
P-value — xác suất thu được kết quả ít nhất "cực đoan" như vậy nếu H0 đúng; P-value < alpha thì bác bỏ H0     
       
Quy tắc so sánh:   

So sánh thống kê kiểm định với giá trị tới hạn: nếu thống kê vượt giới hạn → bác bỏ H0         
Hoặc so sánh P-value với alpha: P-value < alpha → bác bỏ H0         

Phân loại kiểm định:  

Kiểm định một phía (One-tail test): H1 dạng "lớn hơn" hoặc "nhỏ hơn"    
Kiểm định hai phía (Two-tail test): H1 dạng "khác"       
Kiểm định trung bình một tổng thể           
Biết phương sai hoặc n lớn: dùng kiểm định Z         
Không biết phương sai, n nhỏ, phân phối chuẩn: dùng kiểm định t (bậc tự do df = n-1)         
Kiểm định trung bình hai tổng thể          
Hai mẫu độc lập (Independent samples): so sánh trung bình của hai nhóm không liên quan          
Phương sai bằng nhau (t-Test Equal Variance) — dùng khi F-test không bác bỏ phương sai bằng nhau        
Phương sai khác nhau (t-Test Unequal Variance / Welch's t-test)       
Hai mẫu ghép cặp (Paired samples / t-Test Paired): mỗi quan sát nhóm 1 tương ứng một quan sát nhóm 2 (đo trước-sau, cùng đối tượng); thể hiện qua hệ số tương quan Pearson khác 0     
Kiểm định tỷ lệ         
Một tỷ lệ: so sánh tỷ lệ mẫu với giá trị chuẩn; dùng kiểm định Z        
Hai tỷ lệ: so sánh tỷ lệ của hai nhóm        
Kiểm định phương sai        
Một phương sai: dùng phân phối Chi-bình phương      
Hai phương sai (F-test): so sánh phương sai của hai tổng thể; F = phương sai lớn hơn chia phương sai nhỏ hơn; thường làm   trước kiểm định t để biết nên dùng loại t-test nào                  


Bài 8 — Kiểm định phi tham số         
Khái niệm     
Kiểm định phi tham số (Non-parametric test) — không cần giả định phân phối của tổng thể là phân phối chuẩn         
Dùng khi mẫu nhỏ, dữ liệu không tuân theo phân phối chuẩn, hoặc dữ liệu định tính/thứ bậc         
Các kiểm định phổ biến            
Kiểm định Chi-bình phương về tính độc lập (Chi-squared test of independence) — kiểm tra xem hai biến định tính có độc lập với nhau không          
Lập bảng chéo (Contingency table / Cross-tabulation)      
Thống kê Chi-bình phương = tổng [(quan sát - kỳ vọng)^2 / kỳ vọng]      
Bậc tự do = (số hàng - 1) × (số cột - 1)      
Kiểm định Chi-bình phương về phân phối (Goodness of fit test) — kiểm tra dữ liệu có tuân theo một phân phối lý thuyết không      
Kiểm định dấu (Sign test) — kiểm định trung vị, thay thế cho t-test khi vi phạm chuẩn     
Kiểm định Mann-Whitney (Mann-Whitney U test) — thay thế cho t-test hai mẫu độc lập không chuẩn     
Kiểm định Wilcoxon (Wilcoxon signed-rank test) — thay thế cho t-test ghép cặp không chuẩn        
Kiểm định Kruskal-Wallis — thay thế cho ANOVA một chiều không chuẩn     


Bài 9 — Phân tích phương sai         
Khái niệm        
Phân tích phương sai (Analysis of Variance, ANOVA) — kiểm định xem trung bình của từ 3 nhóm trở lên có bằng nhau không     
Thay vì làm nhiều t-test (dễ tăng sai số), ANOVA so sánh tất cả nhóm cùng một lúc       
Giả thuyết H0: trung bình tất cả các nhóm bằng nhau; H1: có ít nhất một nhóm khác        
ANOVA một chiều (One-way ANOVA)    
Chỉ có một nhân tố (factor) chia các nhóm          
Phân tách tổng phương sai thành:       
Phương sai giữa các nhóm (Between groups) — do sự khác biệt giữa các nhóm     
Phương sai trong các nhóm (Within groups / Error) — do ngẫu nhiên trong mỗi nhóm     
Thống kê kiểm định F = phương sai giữa nhóm chia phương sai trong nhóm           
F lớn → sự khác biệt giữa nhóm lớn hơn ngẫu nhiên → bác bỏ H0             
Bảng ANOVA trong Excel: Data → Data Analysis → ANOVA Single Factor  
Kiểm định sau ANOVA (Post-hoc test)                                 
Khi ANOVA bác bỏ H0, cần xác định cụ thể nhóm nào khác nhóm nào   
Các phương pháp phổ biến: Tukey, Bonferroni, LSD                
Điều kiện áp dụng ANOVA                            
Các nhóm được lấy mẫu ngẫu nhiên độc lập 
Phân phối trong mỗi nhóm xấp xỉ chuẩn    
Phương sai các nhóm bằng nhau (kiểm định bằng Levene's test hoặc Bartlett's test)       


Từ điển thuật ngữ Anh - Việt
Tiếng Anh
Tiếng Việt
Statistics
Thống kê
Probability
Xác suất
Descriptive Statistics
Thống kê mô tả
Inferential Statistics
Thống kê suy diễn
Population
Tổng thể
Sample
Mẫu
Parameter
Tham số (của tổng thể)
Statistic
Thống kê (của mẫu)
Observation
Quan sát
Variable
Biến
Qualitative
Định tính
Quantitative
Định lượng
Nominal
Định danh
Ordinal
Thứ bậc
Binary
Nhị phân
Discrete
Rời rạc
Continuous
Liên tục
Frequency
Tần số
Relative frequency
Tần suất
Pie chart
Đồ thị tròn
Bar chart / Column chart
Đồ thị cột
Histogram
Đồ thị phân phối giá trị (liên tục)
Scatter plot
Đồ thị rải điểm
Symmetrical
Đối xứng
Skewed
Lệch
Mean
Trung bình
Weighted mean
Trung bình có trọng số
Median
Trung vị
Mode
Mốt
Quartile
Tứ phân vị
Percentile
Bách phân vị
Range
Khoảng biến thiên
Variance
Phương sai
Standard Deviation
Độ lệch chuẩn
Coefficient of Variation
Hệ số biến thiên
Interquartile Range (IQR)
Khoảng tứ phân vị
Outlier
Giá trị ngoại lai
Z-score
Giá trị chuẩn hóa
Skewness
Hệ số bất đối xứng
Kurtosis
Hệ số nhọn
Covariance
Hiệp phương sai
Correlation coefficient
Hệ số tương quan
Experiment
Phép thử
Outcome
Kết cục
Sample space
Không gian mẫu
Event
Biến cố
Certain event
Biến cố chắc chắn
Impossible event
Biến cố không thể có
Random event
Biến cố ngẫu nhiên
Complement
Biến cố đối lập
Mutually exclusive
Xung khắc
Independent events
Biến cố độc lập
Conditional probability
Xác suất có điều kiện
Bayes' theorem
Công thức Bayes
Bernoulli formula
Công thức Bernoulli
Random variable
Biến ngẫu nhiên
Expected value
Kỳ vọng
Probability distribution
Phân phối xác suất
Binomial distribution
Phân phối nhị thức
Poisson distribution
Phân phối Poisson
Normal distribution
Phân phối chuẩn
Standard normal
Phân phối chuẩn tắc
t-distribution
Phân phối t (Student)
Chi-squared distribution
Phân phối Chi-bình phương
F-distribution
Phân phối F
Central Limit Theorem
Định lý giới hạn trung tâm
Standard Error
Sai số chuẩn
Point estimation
Ước lượng điểm
Interval estimation
Ước lượng khoảng
Confidence level
Độ tin cậy
Confidence interval
Khoảng tin cậy
Significance level (alpha)
Mức ý nghĩa
Margin of error
Sai số ước lượng
Hypothesis testing
Kiểm định giả thuyết
Null hypothesis (H0)
Giả thuyết không
Alternative hypothesis (H1)
Giả thuyết thay thế
P-value
Giá trị P (xác suất quan sát được)
One-tail test
Kiểm định một phía
Two-tail test
Kiểm định hai phía
Degrees of freedom (df)
Bậc tự do
t-Test Paired
Kiểm định t ghép cặp
t-Test Equal Variance
Kiểm định t phương sai bằng nhau
t-Test Unequal Variance
Kiểm định t phương sai khác nhau
F-test
Kiểm định F (so sánh phương sai)
Non-parametric test
Kiểm định phi tham số
Chi-squared test
Kiểm định Chi-bình phương
Contingency table
Bảng chéo / Bảng tần số hai chiều
Goodness of fit
Kiểm định phù hợp phân phối
Mann-Whitney test
Kiểm định Mann-Whitney
Wilcoxon test
Kiểm định Wilcoxon
ANOVA
Phân tích phương sai
One-way ANOVA
Phân tích phương sai một chiều
Factor
Nhân tố
Between groups
Giữa các nhóm
Within groups
Trong các nhóm
Post-hoc test
Kiểm định sau ANOVA
Homogeneity
Tính đồng đều


