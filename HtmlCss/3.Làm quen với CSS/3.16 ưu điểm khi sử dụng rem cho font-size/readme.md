Tại sao không sử dụng 10px thay cho 62.5%?
Chắc hẳn một số bạn sẽ nhận thấy,
nếu con số 62.5% chỉ để dễ dàng trong việc chuyển đổi rem sang px
thì tại sao chúng ta không làm như này:
html {
font-size: 10px;
}

Tại sao không làm luôn như này cho nhanh?
Qua bài học về các đơn vị, các bạn cần nhớ px là đơn vị tuyệt đối,
nó sẽ tương ứng với số px hiển thị trên màn hình của bạn
(phụ thuộc vào độ phân giải trong tùy chọn hiển thị của thiết bị).

Tức là, cho dù một người mắt kém,
họ cài đặt kích thước font chữ trên trình duyệt hoặc thiết bị
của họ lớn hơn bình thường,
với việc sử dụng font-size là px
thì chữ trên website của bạn vẫn sẽ giữ đúng kích thước px của nó,
và hiển thị bị nhỏ hơn so với mong muốn của người dùng.

Đối với rem, là đơn vị tương đối.
Mặc định font chữ của trình duyệt là 16px thì 62.5% sẽ ứng với 10px.
Nhưng nếu người dùng mắt kém, cần chữ to hơn,
họ set trình duyệt mặc định ở font chữ lớn hơn,
khi ấy chữ trên website của bạn cũng sẽ được lớn lên theo.
Vì khi ấy, 62.5% sẽ là 62.5% của kích thước font chữ mà người dùng cài đặt.

Công cụ chuyển đổi PX to REM
👉 https://nekocalc.com/px-to-rem-converter