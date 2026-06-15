<img width="131" height="48" alt="image" src="https://github.com/user-attachments/assets/3888df0f-b3e5-4f7c-a8cf-66a589feec4a" /># Logistics-Risk-Analytics
XÂY DỰNG HỆ THỐNG PHÂN TÍCH CHẬM TRỄ GIAO HÀNG VÀ DỰ ĐOÁN NGUY CƠ DELAY TRONG LOGISTICS
🚛 Cảnh Báo Sớm Rủi Ro Giao Hàng Trễ (Logistics Risk Analytics)

Dự án cuối kỳ: Xây dựng hệ thống phân tích hiệu suất và dự đoán nguy cơ delay trong chuỗi cung ứng logistics.

![Project Banner/Dashboard Image]([https://github.com/ThanhVien0311/Logistics-Risk-Analytics/blob/main/dashboard.png?raw=true])

📌 Giới Thiệu Dự Án (Project Overview)

Trong lĩnh vực Logistics hiện đại, việc đảm bảo thời gian giao hàng đúng hạn (On-Time Delivery) là yếu tố sống còn để duy trì uy tín và lợi thế cạnh tranh. Dự án này được phát triển nhằm giải quyết bài toán cốt lõi: Làm thế nào để không chỉ thống kê những đơn hàng đã trễ trong quá khứ, mà còn chủ động dự báo và giải quyết sớm các đơn hàng có nguy cơ trễ trong tương lai?

Chúng tôi tiếp cận bài toán bằng một luồng phân tích dữ liệu toàn diện (End-to-End Analytics Flow), kết hợp sức mạnh trực quan hóa của Business Intelligence và khả năng dự báo của Machine Learning.

🎯 Mục tiêu đã đạt được (Objectives)

Descriptive Analytics: Xây dựng kho dữ liệu (Data Warehouse) chuẩn Star Schema và các Dashboard tự động trên Power BI để giám sát toàn diện 9 KPI vận hành (Tuyến đường, Nhà cung cấp, Phương tiện, Độ chính xác ETA...).

Predictive Analytics: Phát triển và tinh chỉnh mô hình Học máy (XGBoost) để dự đoán xác suất trễ hẹn của từng lô hàng dựa trên các đặc trưng lịch sử và kế hoạch.

Prescriptive Analytics: Ứng dụng Explainable AI (SHAP) để giải thích nguyên nhân rủi ro cốt lõi và tích hợp chức năng What-If Analysis, hỗ trợ Điều phối viên đưa ra quyết định "cứu vãn" đơn hàng kịp thời thông qua Hệ thống Cảnh báo Sớm.

🛠️ Công Nghệ & Công Cụ (Tech Stack)

Business Intelligence: Power BI (Power Query, DAX Data Modeling, Data Visualization).

Machine Learning & Data Science: Python (Jupyter Notebook / Google Colab).

Libraries: pandas, numpy, scikit-learn (Logistic Regression, Decision Tree, Random Forest), xgboost, shap, matplotlib, seaborn.

🚀 Tính Năng Nổi Bật (Key Features)

1. Hệ Thống Dashboard Quản Trị (Power BI)

Executive Overview: Theo dõi On-Time Delivery Rate, Delayed Shipment Ratio và Logistics Stability Score.

Route Efficiency & Delay Hotspots: Xác định các "điểm đen" giao trễ trên bản đồ phân tích.

Supplier & Vehicle Performance: Đánh giá điểm tin cậy của từng đối tác và hiệu suất từng loại phương tiện.

2. Mô Hình Dự Báo Rủi Ro (Machine Learning)

Huấn luyện và tối ưu hóa siêu tham số (Hyperparameter Tuning bằng GridSearchCV) qua 4 mô hình khác nhau. Thuật toán XGBoost đạt hiệu suất tốt nhất (Đánh giá qua ROC-AUC, Accuracy, F1-Score) trong việc phân loại đơn hàng có nguy cơ trễ.

3. Trí Tuệ Nhân Tạo Có Thể Giải Thích (Explainable AI - SHAP)

Giải mã "hộp đen" Machine Learning, bóc tách và định lượng các yếu tố tác động mạnh nhất đến tỷ lệ giao trễ của từng đơn hàng cụ thể (VD: Thời gian ETA kế hoạch thiếu thực tế, Rủi ro từ loại xe).

![https://github.com/ThanhVien0311/Logistics-Risk-Analytics/blob/main/shap.png?raw=true])

4. Hệ Thống Cảnh Báo Sớm & What-If Analysis

Tự động tính toán Điểm Rủi Ro (Delivery Risk Score) và tích hợp trở lại Power BI tạo thành "Danh sách đen AI".

Mô phỏng các kịch bản can thiệp thực tế (Đổi loại xe tối ưu, Cấp thêm thời gian đệm) để đề xuất hướng hành động ngay lập tức cho nhân viên điều phối trước khi sự cố xảy ra.

📂 Cấu Trúc Repository

├── DA19_Logistics_BI_Dashboard.pbix      # File Power BI chứa Data Model, DAX và Dashboards
├── DA19_Logistics_ML_Prediction.ipynb    # Code Python chứa tiền xử lý, huấn luyện ML và SHAP
├── DA19_Logistics_AI_Risk_Data.csv       # Dữ liệu xuất ra từ mô hình AI (Cầu nối tích hợp lên Power BI)
├── BaoCaoNhom_DA19.pdf                          # File Báo cáo chi tiết của nhóm
└── README.md                                  # Tài liệu mô tả dự án


🎥 Video Demo Sản Phẩm

Xem video giới thiệu và demo chi tiết thao tác trên hệ thống tại đây:
👉 [[https://drive.google.com/file/d/1UwGuxPksoLSX0p_cLF2wDeHTBvAqEMPm/view?usp=sharing]]

👥 Nhóm Thực Hiện (Team Members)

[Nguyễn Thanh Viên] - [65134288]

[Huỳnh Thị Nhật Linh] - [65131699]

[Nguyễn Văn Tĩnh] - [65133671]

[Lê Thành Phát] - [65131428]

[Nguyễn Gia Khang] - [65131699]
