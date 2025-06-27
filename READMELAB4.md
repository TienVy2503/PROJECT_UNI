Lab 4

Phân vùng là một quá trình chia ảnh thành nhiều vùng nhỏ hơn dựa trên các đặc tính chung của pixel :

Phân vùng theo Histogram: Dựa vào phân bố cường độ sáng của pixel để tìm ngưỡng phân chia.

- Otsu: Tìm ngưỡng tối ưu mà không đòi hỏi cả tri thức trước biết về mẫu và nền.

- Adaptive Thresholding: Chia ảnh thành nhiều vùng nhỏ hơn và tính ngưỡng riêng, đối với từng ảnh, để phân vùng chính xác hơn dưới ánh sáng khác nhau.

Phân vùng theo Region: Nhóm các pixel có cùng thuộc tính thành một vùng. Ví dụ thuật toán Watershed để tách các đối tượng dính liền. 

Biến đổi hình thái là các phép toán thay đổi hình dạng của đối tượng trong ảnh. Thường dùng cho ảnh nhị phân Dilation Giãn nở: Làm các đối tượng phình to ra, nối liền các phần bị đứt hoặc lấp đầy lỗ nhỏ:

- Dilation : hình ảnh phình to lớn của các đối tượng, có thể gắn kết các phần phá tan rồi hay lấp đầy các khe nhỏ.

- Erosion : hình ảnh rút gọn, loại bỏ có thể nhiễm hoặc làm tách các đối tượng kết nối.

- Opening : một tính năng hình ảnh kết hợp giảm rồi chúng được mở ra, điều dọn mất đối tượng xác định nhỏ hơn sẽ nằm ở frontal. 

- Closing : một tính năng hình ảnh kết hợp tăng rồi tinh chế, lấp đầy các lỗ nhỏ trong các đối tượng.
