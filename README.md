# Dự đoán tỷ lệ khách hàng rời đi

## Giới thiệu

Dự đoán tỷ lệ khách hàng rời đi là một vấn đề khó khăn và phổ biến đối với bất kỳ doanh nghiệp thương mại điện tử nào, nơi mà sự thành công phụ thuộc vào hành vi của khách hàng. Tỷ lệ khách hàng rời đi được định nghĩa là quá trình khách hàng chuyển từ dạng cao cấp xuống miễn phí hoặc ngừng sử dụng sản phẩm hoặc dịch vụ của doanh nghiệp. 

Dự đoán khả năng rời đi của người dùng trong thời gian đăng ký cho phép doanh nghiệp đưa ra các ưu đãi hoặc khuyến mãi đặc biệt, giúp ngăn chặn thiệt hại tài chính đáng kể.

## Sparkify Dataset

Sparkify là một dịch vụ nghe nhạc ảo, được Udacity tạo ra nhằm mô phỏng các bộ dữ liệu của các công ty như Spotify hoặc Pandora. Người dùng Sparkify có thể nghe nhạc miễn phí hoặc đăng ký gói cao cấp (premium) để phát nhạc không có quảng cáo.

- **Tập dữ liệu đầy đủ**: 26 triệu bản ghi từ 22,277 người dùng đã đăng ký.
- **Tập dữ liệu nhỏ**: 286,500 bản ghi từ 225 người dùng trong vòng hai tháng.

## Mục tiêu của dự án

Mục tiêu của dự án là xây dựng và huấn luyện một bộ phân loại nhị phân (binary classifier) có khả năng xác định chính xác những người dùng có khả năng hủy dịch vụ của Sparkify. Điều này sẽ giúp Sparkify cung cấp các ưu đãi đặc biệt cho những người có nguy cơ rời đi, từ đó giảm tỷ lệ rời bỏ.

Tuy nhiên, ta cũng cần tránh dự đoán sai đối với những người dùng trung thành, vì việc cung cấp các ưu đãi tốn kém và không cần thiết có thể gây thiệt hại cho công ty.

## Các bước thực hiện trong dự án

1. **Load & Data Cleaning**: Nạp dữ liệu và làm sạch dữ liệu để chuẩn bị cho các bước tiếp theo.
2. **Exploratory Data Analysis (EDA)**: Phân tích dữ liệu khám phá để hiểu rõ về cấu trúc và xu hướng trong dữ liệu.
3. **Feature Engineering**: Tạo ra các đặc trưng mới dựa trên dữ liệu đã có để cải thiện độ chính xác của mô hình.
4. **Modeling**: Xây dựng các mô hình dự đoán khác nhau để xác định mô hình nào hoạt động tốt nhất.
5. **Model Evaluation and Validation**: Đánh giá và xác thực các mô hình dựa trên các tiêu chí như độ chính xác, F1 score, Recall...

## Kết luận

Bằng cách xác định chính xác những người dùng có nguy cơ rời đi, Sparkify có thể cung cấp các ưu đãi đặc biệt nhằm giữ chân khách hàng và giảm thiểu tổn thất về tài chính.
