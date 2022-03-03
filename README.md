# Machine_Learning
 
 - AI hoạt động như thế nào? 
 AI hoạt động bằng cách nhập một lượng lớn dữ liệu đào tạo được gắn nhãn, phân tích dữ liệu để tìm các mỗi tương quanvaf các mẫu, đồng thời sử dụng các mẫu này để đưa ra dự đoán về các trạng thái trong tương lai.
 
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
  
