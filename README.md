# Google Playstore Case Study:Phân tích các APP trên Google Playstore
**Mô tả ngắn gọn:** Một phân tích các APP trên Google Play để hiểu rõ hơn về các yếu tố ảnh hưởng đến sự phổ biến của 1 số ứng dụng trên google playstore

## Giới Thiệu

Mục đích của dự án: Dự án này nhằm phân tích các APP trên Google Play Store. Mục tiêu là tìm hiểu các yếu tố ảnh hưởng đến sự phổ biến và hiệu suất của các ứng dụng này, từ đó đưa ra các khuyến nghị giúp cải thiện trải nghiệm người dùng và tối ưu hóa hiệu suất ứng dụng.


Mục tiêu:

Hiểu rõ hơn về các yếu tố ảnh hưởng đến đánh giá và số lượt cài đặt của ứng dụng.

Xác định mối quan hệ giữa kích thước ứng dụng, tần suất cập nhật và độ phổ biến của ứng dụng.

Dữ Liệu:

Nguồn Dữ Liệu: Dữ liệu được thu thập từ Google Play Store và bao gồm các thuộc tính sau:

App: Tên ứng dụng

Category: Thể loại ứng dụng

Rating: Đánh giá trung bình của ứng dụng

Reviews: Số lượng đánh giá

Size: Kích thước của ứng dụng (tính bằng KB)

Installs: Số lượt cài đặt

Type: Loại ứng dụng (Miễn phí hoặc Trả phí)

Price: Giá của ứng dụng (nếu có)

Content Rating: Xếp hạng nội dung

Genres: Thể loại chi tiết

Last Updated: Ngày cập nhật cuối cùng

Current Ver: Phiên bản hiện tại

Android Ver: Phiên bản Android yêu cầu

Các bước làm:

-Bước 1: Xử lý và làm sạch dữ liệu:

Xử lý giá trị thiếu

Xử lý các giá trị không chính xác

-Bước 2: Kiểm tra lại dữ liệu có ý nghĩa(có bị sai về cấu trúc dữ liệu hay sai về bối cảnh hay không)
(Xếp hạng nằm trong khoảng từ 1 đến 5 cho tất cả các ứng dụng.
Số lượt đánh giá nhỏ hơn hoặc bằng số lượt cài đặt.
Ứng dụng miễn phí không được có giá lớn hơn 0)

-Bước 3: Vẽ dashboard và phân tích bằng các biểu đồ

Kết Quả

Các kết quả chính sẽ được trình bày dưới dạng biểu đồ và bảng, bao gồm:

Ảnh hưởng của việc trả phí tới lượt cài đặt

Phân bố đánh giá ứng dụng, lượt tải,kích thước

Mối quan hệ giữa kích thước ứng dụng và đánh giá của người dùng

Ảnh hưởng của xếp hạng nội dung đến số lượt cài đặt

Ảnh hưởng của xếp hạng nội dung,giá app, nhận xét của người dùng đến số lượt cài đặt

Tìm ra các insight:

Price:  các ứng dụng trả phí có giá từ 1 đến 8 chiếm 72.2% (app trả phí), tập trung chủ yếu từ 2.5 đến 5 là 50%.

(Phần lớn các ứng dụng thuộc loại đánh giá "Everyone" hơn 6000 ứng dụng , cho thấy rằng hầu hết các ứng dụng đều phù hợp với mọi lứa tuổi.
Số lượng ứng dụng trong các loại đánh giá khác như "Teen", "Everyone 10+", "Mature 17+", và "Adults only 18+" ít hơn nhiều so với "Everyone"(từ 1000 đổ xuống).)

(Phiên bản phổ biến nhất:Android Ver

4.1 and up: Đây là phiên bản phổ biến nhất, với số lượng ứng dụng khoảng 1750.
4.0.3 and up: Xếp thứ hai với số lượng ứng dụng khoảng 1300.
4.0 and up: Xếp thứ ba với số lượng ứng dụng khoảng 1100.
Varies with device: Có khoảng 900 ứng dụng không yêu cầu phiên bản cụ thể mà phụ thuộc vào thiết bị.)

![image](https://github.com/tienhoang87/project/assets/172392038/a1866133-50d3-46cd-90b7-40112355939b)

(Số lượt cài đặt cao nhất: Tháng 6 và 7, chủ yếu từ loại đánh giá Everyone.
Số lượt cài đặt thấp nhất: Các tháng còn lại trong năm, với sự đa dạng trong loại đánh giá nội dung.
Loại đánh giá nội dung phổ biến nhất: Everyone, chiếm phần lớn số lượt cài đặt trong hầu hết các tháng.)

(Xu hướng điểm đánh giá:

Điểm đánh giá trung bình có xu hướng tăng từ tháng 1 đến tháng 8, sau đó giảm nhẹ vào tháng 9 và tháng 10, và tăng trở lại vào tháng 11 và 12.

Nhận xét chi tiết:
Biến động rõ ràng: Điểm đánh giá trung bình có sự biến động rõ ràng theo tháng. Các tháng đầu năm và cuối năm có sự giảm nhẹ, trong khi các tháng giữa năm có xu hướng tăng dần.

Đỉnh điểm vào tháng 8: Điểm đánh giá cao nhất vào tháng 8 (~4.28), cho thấy sự ưa thích hoặc hài lòng cao nhất của người dùng trong khoảng thời gian này.

Sự giảm sút vào tháng 9: Điểm đánh giá giảm đáng kể vào tháng 9 (~4.05), có thể là dấu hiệu của sự không hài lòng hoặc vấn đề phát sinh trong thời gian này.

Cảm nhận và đề xuất:
Tăng cường chất lượng dịch vụ trong tháng 9: Các vấn đề cần được xem xét và cải thiện để nâng cao điểm đánh giá trung bình.
Duy trì sự ổn định vào các tháng cuối năm: Đảm bảo không có sự giảm sút đột ngột trong điểm đánh giá và cố gắng duy trì hoặc tăng điểm đánh giá.)
