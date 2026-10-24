# 📊 Classical Machine Learning: Theory & Implementation

Repository này tổng hợp toàn bộ lộ trình nghiên cứu nền tảng toán học, tài liệu lý thuyết và mã nguồn thực hành cài đặt các thuật toán Học máy kinh điển (Classical Machine Learning).

---

## 📂 Cấu trúc Repository

- **[Code/](./Code):** Chứa toàn bộ mã nguồn thực hành và đánh giá thuật toán bằng Python (Jupyter Notebooks).
- **[Slide/](./Slide):** Chứa slide bài giảng và tài liệu tổng hợp nền tảng toán học (PDF).

---

## 📌 Nội dung chi tiết các thư mục

### 1. [Slide - Nền tảng Toán học & Lý thuyết](./Slide)
Tài liệu tổng kết cơ sở toán học và cơ chế hoạt động của thuật toán:
- **Math Foundations:** Cơ sở giải tích đa biến (Gradients, Chain Rule), Đại số tuyến tính (Vectors, Matrices, Eigenvalues) và Xác suất thống kê cơ bản.
- **Hồi quy & Phân loại tuyến tính:** Cơ chế hàm mất mát MSE trong Linear Regression, hàm sigmoid và Binary Cross-Entropy trong Logistic Regression.
- **Support Vector Machine (SVM):** Khái niệm siêu phẳng tối ưu (Hyperplane), khoảng cách cực đại (Margin) và kỹ thuật Kernel Trick.
- **Cây quyết định & Học không giám sát:** Cấu trúc Decision Tree (Gini, Entropy), Ensemble Learning và thuật toán phân cụm K-Means.

### 2. [Code - Cài đặt Thuật toán](./Code)
Thực hành xây dựng và huấn luyện mô hình với Python & Scikit-learn:
- **Linear & Polynomial Regression:** Cài đặt hồi quy tuyến tính, tối ưu hóa qua Gradient Descent và mở rộng hồi quy đa thức cho dữ liệu phi tuyến tính.
- **Logistic Regression:** Cài đặt phân loại nhị phân, tính toán xác suất và đánh giá qua ma trận nhầm lẫn (Confusion Matrix, Precision, Recall, F1-score).
- **Support Vector Machine (SVM):** Khảo sát các dạng Kernel (Linear, RBF), tinh chỉnh các siêu tham số $C$ và $\gamma$.
- **Decision Tree & Random Forest:** Xây dựng mô hình cây quyết định và mô hình rừng ngẫu nhiên (Random Forest) với kỹ thuật Bagging để chống overfitting.

---

## 🛠️ Công nghệ & Công cụ sử dụng

- **Ngôn ngữ:** Python 3
- **Thư viện chính:** Scikit-learn, NumPy, Pandas
- **Trực quan hóa dữ liệu:** Matplotlib, Seaborn
- **Môi trường thực thi:** Jupyter Notebook / Google Colab
