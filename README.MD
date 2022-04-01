    *  Object.defineProperty() : định nghĩa một thuộc tính mới trực tiếp trên mộđối tượng hoặc

- sửa đổi một thuộc tính hiện có trên một đối tượng và trả về đối tượng.
  Syntax:
  Object.defineProperty(obj, prop, descriptor)

* obj: Đối tượng để xác định thuộc tính.
* prop: Tên hoặc Biểu tượng của thuộc tính được xác định hoặc sửa đổi.
* descriptor: Bộ mô tả cho thuộc tính đang được xác định hoặc sửa đổi.

*\*\* HTML Audio/Video DOM Reference
*HTML Audio/Video Methods

- play() => Bắt đầu phát âm thanh / video
- pause() => Tạm dừng âm thanh / video hiện đang phát
  \*HTML Audio/Video Properties
- currentTime => Đặt hoặc trả về vị trí phát lại hiện tại trong âm thanh video (tính bằng giây)
- duration => Trả về thời lượng của âm thanh / video hiện tại (tính bằng giây)
  \*HTML Audio/Video Events
- pause => Kích hoạt khi âm thanh / video đã bị tạm dừng
- play => khi âm thanh / video đã được bắt đầu hoặc không còn bị tạm dừng
- timeupdate => Kích hoạt khi vị trí phát hiện tại đã thay đổi

\*\*\*Element.animate()

- Phương thức animate () của giao diện Phần tử là một phương thức phím tắt đtạo một Hoạt ảnh mới,
  áp dụng nó cho phần tử, sau đó phát hoạt ảnh. Nó trả về cá thể đối tượnAnimation đã tạo.
  Syntax:
  animate(keyframes, options)
- keyframes:
  Một mảng các đối tượng khung chính hoặc một đối tượng khung chính có thuộc tínlà
  các mảng giá trị để lặp lại. Xem Định dạng khung hình chính để biết thêm chtiết.
- options:
  Một số nguyên đại diện cho thời lượng của hoạt ảnh (tính bằng mili giây) hoặc
  Đối tượng chứa một hoặc nhiều thuộc tính thời gian được mô tả trong tham số tùchọn KeyframeEffect ()
