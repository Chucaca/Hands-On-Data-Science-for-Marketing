# Thuật toán đơn giản cho các vấn đề về MKT

Dữ liệu MKT là kết quả các hành động của khách hàng trong một nội dung cụ thể đối mặt với một môi trường cụ thể. Người làm MKT có thể ảnh hưởng một số khía cạnh đối với môi trường này. Mục tiêu của người làm data là cung cấp models ảnh hưởng đến việc đưa ra quyết định để có thể đưa đến những quyết định tối ưu một cách có điều kiện dựa trên models. Về cơ bản góc nhìn của khách hàng khác nhau phụ thuộc vào cái họ muốn và cần đối, nên sự khác nhau đối với từng đối tượng khách hàng cần được đưa vào models. Đối với bài toán MKT, ta đưa yếu tố khách hàng như là hàm mục tiêu để đưa ra quyết định. Ví dụ những quyết định về giá đối với khách hàng nhạy cảm với giá khác với khách hàng không quan tâm về giá.

Statistical modeling cho MKT bao gồm 3 thành phần:

* within unit behavior: điều kiện để unit xảy ra
* accross unit behavior: sự phần bổ của biến unit đến toàn bộ mẫu
* action: đưa ra quyết định gì?

Ví dụ:

Bài toán: khách hàng đưa ra quyết định mua sản phẩm giữa các loại sản phẩm khác nhau? Sản phẩm được cụ thể hóa bằng các vectors ảnh hưởng đến việc lựa chọn của khách hàng như là tính năng sp, giá và quảng cáo. Ta muốn dự đoán lựa chọn của khách hàng khi thay đổi biến Marketing mix hay product characteristics. Mục tiêu cuối cùng là thiết kế sản phẩm hoặc biến đổi marketing mix để tối ưu hóa lợi nhuận.

* Within-unit model là mô hình các lựa chọn có điều kiện dựa trên các biến quan sát được cho mỗi lựa chọn được đưa ra

![](../.gitbook/assets/image%20%282%29.png)

Nếu ta quan sát nhiều khách hàng khác nhau, sự khác nhau giữa các khách hàng khi ta không có nhiều thông tin về khách hàng có thể đưa khả năng mua hàng của từng khách hàng 







