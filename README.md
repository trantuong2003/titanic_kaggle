# titanic_kaggle
Titanic passengers survival rate analysis project using python and machine learning models.

Trong dự án này, tôi đã thực hiện đầy đủ các bước xử lý dữ liệu, phân tích dữ liệu, xây dựng và đánh giá mô hình để dự đoán khả năng sống sót của hành khách trên tàu Titanic.
Sau khi thử nghiệm nhiều mô hình khác nhau và tinh chỉnh siêu tham số, mô hình Voting Classifier (kết hợp Logistic Regression, Random Forest và XGBoost) cho kết quả tốt nhất với độ chính xác khoảng 84% và điểm Kaggle 0.79.
Các đặc trưng ảnh hưởng mạnh nhất đến khả năng sống sót là giới tính, hạng vé (Pclass), tuổi, giá vé, cùng với các đặc trưng được tạo thêm như Title và Family Size.
Kết quả cho thấy việc feature engineering và ensemble learning đóng vai trò quan trọng trong việc nâng cao hiệu suất mô hình.
Trong tương lai có thể mở rộng thêm các đặc trưng mới hoặc thử nghiệm mô hình stacking, deep learning để cải thiện kết quả.
