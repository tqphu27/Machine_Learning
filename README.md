# Machine_Learning
 
 - AI hoạt động như thế nào? 
 AI hoạt động bằng cách nhập một lượng lớn dữ liệu đào tạo được gắn nhãn, phân tích dữ liệu để tìm các mỗi tương quan và các mẫu, đồng thời sử dụng các mẫu này để đưa ra dự đoán về các trạng thái trong tương lai.
 
- Phân nhóm dựa trên phương thưc học

1. Supervised Learning ( Học có giám sát)
  Là thuật toán dự đoán đầu ra của một dữ liệu mới dựa trên các cặp(data, label) đã biết từ trước.
  Thuật toán supervised learning chia thành hai loại chính:
  + Phân loại (Classification)
  + Regression(Hồi Quy)
2.  Unsupercised Learning (Học không giám sát)
  Không biết được outcome hay nhãn mà chỉ có dữ liệu đầu vào.
  
3. Semi-Supervised Learning
  Các bài toán khi chúng ta có một lượng lớn dữ liệu X nhưng chỉ một phần trong chúng được gán nhãn được gọi là Semi-Supervised Learning. Những bài toán thuộc nhóm này nằm giữa hai nhóm được nêu bên trên.
  Một ví dụ điển hình của nhóm này là chỉ có một phần ảnh hoặc văn bản được gán nhãn (ví dụ bức ảnh về người, động vật hoặc các văn bản khoa học, chính trị) và phần lớn các bức ảnh/văn bản khác chưa được gán nhãn được thu thập từ internet. Thực tế cho thấy rất nhiều các bài toán Machine Learning thuộc vào nhóm này vì việc thu thập dữ liệu có nhãn tốn rất nhiều thời gian và có chi phí cao. Rất nhiều loại dữ liệu thậm chí cần phải có chuyên gia mới gán nhãn được (ảnh y học chẳng hạn). Ngược lại, dữ liệu chưa có nhãn có thể được thu thập với chi phí thấp từ internet.
  4.  Reinforcement Learning (Học Củng Cố)
    Reinforcement learning là các bài toán giúp cho một hệ thống tự động xác định hành vi dựa trên hoàn cảnh để đạt được lợi ích cao nhất (maximizing the performance). Hiện tại, Reinforcement learning chủ yếu được áp dụng vào Lý Thuyết Trò Chơi (Game Theory), các thuật toán cần xác định nước đi tiếp theo để đạt được điểm số cao nhất.
    
 1. Linear Regression
  - Dạng 
 2. K-Means Clustering
   Elbow:
   +  Distortion: Trung bình cộng bình phương khoảng cách giữa tâm cụm đến các điểm còn lại.
 3. KNN 
 4. Gradient Descent
  Momentum
  + Dự đoán một điểm khởi tạo.
  + Cập nhật đến khi đạt được kết quả chấp nhận được.
  Nesterov accelerated gradient: đoán hướng đi trước trong tương lai.
  Biến thể của GD:
  + Batch Gradient Descent: Batch ở đây được hiểu là tất cả, tức khi cập nhậtchúng ta sử dụng tất cả các điểm dữ liệu   + Stochastic Gradient Descent: Trong thuật toán này, tại 1 thời điểm, ta chỉ tính đạo hàm của hàm mất mát dựa trên chỉ một điểm dữ liệu, rồi cập nhật dựa trên đạo hàm này.

5.  Perceptron Learning Algorithm: Cho hai class được gán nhãn, hãy tìm một đường phẳng sao cho toàn bộ các điểm thuộc class 1 nằm về 1 phía, toàn bộ các điểm thuộc class 2 nằm về phía còn lại của đường phẳng đó. Với giả định rằng tồn tại một đường phẳng như thế.
6.  Logistic Regression

# Kiến thức cần nhớ
1. Learning rate
 - Tốc độ học là một siêu tham số sử dụng trong việc huấn luyện các mạng nơ-ron. Giá trị của nó là một số dương, thường nằm trong khoảng 0 và 1. Tốc độ học kiểm soát tốc độ mô hình thay đổi các trọng số để phù hợp với bài toán. Tốc độ học lớn giúp mạng nơ ron huấn luyện nhanh hơn nhưng cũng có thể làm giảm độ chính xác.
2. Epochs
 - Một eppch được tính là khi chúng ta đưa tất cả dữ lệu trong tập train vào mạng neural network một lần.
3. Batch size
 - Batch  gradient descent: Dùng tất cả dữ liệu trong training set cho mỗi lần thực hiện bước tính đạo hàm.
 - Mini-batch gradient descent: Dùng một phần dữ liệu trong training set cho mỗi lần thực hiện bước tính đạo hàm.
 - Stochastic gradient descent: Chỉ dùng một dữ liệu trong training set cho mỗi lần thực hiện bước tính đạo hàm.
 - _Batch size: Là size trong mini-batch gradient descent, nghĩa là dùng bao nhiêu dữ liệu cho mỗi lần tính và cập nhật hệ số. _
  => Số lượng mẫu dữ liệu trong một lần huấn luyện.
 - Iterations là số lượng batchs cần để hoàn thành 1 epoch. 
4. Loss function
 - Là hàm mất mát, thể hiện một mối quan hệ giữa y*(là kết quả dự đoán của model) và y(là giá trị thực tế).
 - Dựa vào loss function, khi đó chúng ta có thể tính ra gradient descent để tối ưu loss function càng về gần 0 càng tốt.
 5. Activation- function
 - Hàm activation là hàm phi tuyến được áp dụng vào đầu ra của các nơ-ron trong tần ẩn của một mô hình mạng và được sử dụng làm input data cho tầng tiếp theo.
 - Nếu không có các activation functions, khả năng dự đoán của mạng neural sẽ bị giới hạn và giảm đi rất nhiều, sự kết hợp của các activation functions giữa các tầng ẩn là để giúp mô hình học được các quan hệ phi tuyến phức tạp tiềm ẩn trong dữ liệu.
 - Các activation function phải là nonlinear vì nếu không, nhiều layer hay một layer cũng là như nhau.
 
 6. Tại sao cần nhiều layer và nhiều node trong 1 hidden layer.
  - Trong neural network chúng ta cần nhiều để xử lý nhiều nhiệm vụ khác nhau, mỗi layer sẽ thực hiện một nhiệm vụ nào đó, output của tầng này sẽ là input của tầng sau. 
  - Cần nhiều node trong 1 hidden layer để việc học hiệu quả hơn. Giả sử đầu  

7. Overfiting, underfiting, good fitting
 - Overfitting xảy ra khi mô hình quá phức tạp để mô phỏng training, điều này xảy ra khi lượng dữ liệu training quá nhỏ trong khi độ phức tạp của mô hình quá cao.
 - Underefitting là mô hình không phù hợp với cả tập huấn luyện và cả tập test. Có thể là do mô hình chưa đủ phức tạp bao quát được tập dữ liệu.
 - 
# Các kỹ thuật cơ bản
**1. Vectorization**
 - Biểu diễn bài toán dưới dạng vector như vậy gọi là vectorization.
 - Nó không chỉ giúp code gọn lại mà  còn tăng tốc độ tính toán một cách đáng kể.
 - Nó có thể tính toán nhiều phép tính cùng một lúc.
 
**2. Mini-batch gradient descent** 
  - Batch  gradient descent: Dùng tất cả dữ liệu trong training set cho mỗi lần thực hiện bước tính đạo hàm.
 - Mini-batch gradient descent: Dùng một phần dữ liệu trong training set cho mỗi lần thực hiện bước tính đạo hàm.
 - Stochastic gradient descent: Chỉ dùng một dữ liệu trong training set cho mỗi lần thực hiện bước tính đạo hàm.

**3. Bias và variance**
 - Bias: nghĩa là độ lệch, biểu thị sự chênh lệch giữa giá trị trung bình mà mô hình dự đoán và giá trị thực tế của dữ liệu.
 - Variance: nghĩa là phương sai, biểu thị độ phân tán của các giá trị mà mô hình dự đoán so với giá trị thực tế.
 
 **4. Dropout**
  - Dropout với hệ số p nghĩa là trong quá trình train model, với mỗi lần thực hiện cập nhật hệ số trong gradient descent ta ngẫu nhiên loại bỏ p% số lượng node trong layer đấy, hay nói cách khác là giữ lạo (1-P%) node.
  
  **5. Batch normalization**
  - Batch normalization đưa dữ liệu về zero mean và chuẩn hóa variance trước khi đưa qua activation function nhờ đó giải quyết các vấn đề vanishing gradient hay exploding gradient.
  
