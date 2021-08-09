# Ứng dụng tra cứu đất

Dưới đây là danh sách tất cả các tính năng của ứng dụng tra cứu đất. Bên cạnh tính năng tra cứu thửa đất, ứng dụng còn cung cấp các loại bản đồ khác về tài nguyên, môi trường và khu/cụm công nghiệp.

## Bản đồ

Tất cả các bản đồ trong app đều có các tính năng sau:

### Giao diện bản đồ

<p>
    <img src='demo/common/map-screen-overview.jpg' width='222'>
    <img src='demo/common/map-screen-overview-2.jpg' width='222'>
</p>

### **(1)** Tiêu đề trang

Tiêu đề hiển thị vị trí hiện tại của viewport trên bản đồ, tùy vào loại bản đồ tiêu đề có thể dùng để hiển thị huyện, xã hoặc khu/cụm công nghiệp nếu là bản đồ công nghiệp

### **(2)** Nút quay lại trang chủ chọn bản đồ

### **(3)** Nút hiển thị popup/trang hiện chú thích bản đồ đó

<img src='demo/common/legend.jpg' width='222'>

### **(4)** Nút mở trang tìm kiếm nâng cao

Trang tìm kiểm nâng cao dùng để tìm [model](#8-Thực-thể-trên-bản-đồ-model) theo nhiều bộ lọc khác nhau, và nhảy tới vị trí của nó trên bản đồ

### **(5)** Nút hoán đổi basemap giữa street/satellite

<img src='demo/common/basemap-button.gif' width='222'>

### **(6)** Slider thay đổi độ trong suốt bản đồ đất

<img src='demo/common/opacity-slider.gif' width='222'>

### **(7)** Nút tùy chỉnh bản đồ

Ở một số bản đồ (thửa đất, công nghiệp), vị trí này sẽ hiện nút nhảy tới các vùng khác nhau trên bản đồ (xã, khu công nghiệp...),
ở một số bản đồ khác (như vài bản đồ môi trường), nút này dùng để [chọn renderer](#Chọn-WQI-để-hiển-thị-trên-bản-đồ) để hiển thị đồ hoạ icon theo các trường khác nhau trong dữ liệu.

### **(8)** Thực thể trên bản đồ (model)

Model là thông tin thực thể mà người dùng có thể xem trên bản đồ. Ở bản đồ đất, được gọi là thửa đất, bản đồ sinh trắc được gọi là điểm đo đạc sinh trắc hay bản đồ hầm đất là khu vực hầm đất.

Người dùng có thể chọn model trên bản đồ để hiển thị thêm thông tin. Nếu muốn tìm kiếm model theo nhiều bộ lọc, người dùng có thể dùng trang tìm kiếm nâng cao.

### **(9)** Snackbar

Snackbar dùng để hiển thị thông tin của model đó.

### **(10)** Hiện biên giới tỉnh Long An

<img src='demo/common/long-an-border.jpg' width='222'>

## Danh sách bản đồ

Hiện tại có 7 bản đồ:

* Bản đồ đất
    * [Bản đồ giá đất](#bản-đồ-giá-đất)
    * [Bản đồ khu cụm công nghiệp](#bản-đồ-khu-cụm-công-nghiệp)
* Bản đồ tài nguyên
    * [Bản đồ điểm giếng](#bản-đồ-điểm-giếng)
    * [Bản đồ hầm đất](#bản-đồ-hầm-đất)
* Bản đồ môi trường
    * [Bản đồ quan trắc nước](#bản-đồ-quan-trắc-nước)
    * [Bản đồ quan trắc không khí](#bản-đồ-quan-trắc-không-khí)
    * [Bản đồ trạm xử lý nước thải](#bản-đồ-trạm-xử-lý-nước-thải)

<img src='demo/common/home.jpg' width='222'>

## Bản đồ giá đất

Bản đồ giá đất dùng để tìm kiếm thửa đất ở các huyện/xã trong Long An và hiện thông tin chi tiết về các loại giá cũng như diện tích thửa đất đó.

### Tổng quan bản đồ

<p>
    <img src='demo/price/overview-1.jpg' width='222'>
    <img src='demo/price/overview-2.jpg' width='222'>
    <img src='demo/price/overview-3.jpg' width='222'>
</p>

### Xem thửa đất

<p>
    <img src='demo/price/view-1.jpg' width='222'>
    <img src='demo/price/view-2.jpg' width='222'>
    <img src='demo/price/view-1.gif' width='222'>
</p>

### Xem chi tiết giá đất

<p>
    <img src='demo/price/detail-1.jpg' width='222'>
    <img src='demo/price/detail-2.jpg' width='222'>
    <img src='demo/price/detail-3.jpg' width='222'>
</p>


### Trang chú thích danh mục đất

<p>
    <img src='demo/price/legend-1.jpg' width='222'>
    <img src='demo/price/legend-2.jpg' width='222'>
    <img src='demo/price/legend.gif' width='222'>
</p>

### Trang tìm kiếm thửa đất/xã

Người dùng có thể tìm kiếm theo huyện > xã > số tờ > số thửa để nhảy tới thửa đất đó

<p>
    <img src='demo/price/region-filter.gif' width='222'>
    <img src='demo/price/search.gif' width='222'>
</p>

## Bản đồ công nghiệp

Viết tắt:
- KCCN: Khu - cụm công nghiệp

### Tổng quan bản đồ

<p>
    <img src='demo/industry/overview-1.jpg' width='222'>
    <img src='demo/industry/overview-2.jpg' width='222'>
    <img src='demo/industry/overview-3.jpg' width='222'>
</p>

### Xem thửa đất công nghiệp

<p>
    <img src='demo/industry/view-1.jpg' width='222'>
    <img src='demo/industry/view-1.gif' width='222'>
</p>

### Popup chú thích icon KCCN/thửa đất

<img src='demo/industry/legend.jpg' width='222'>

### Trang tìm kiếm KCCN/thửa đất

Tìm kiếm nâng cao theo bộ lọc:
    - Tìm thửa đất theo quận > KCCN
    - Tìm kiếm tên cty/lô đất
    - Lọc trạng thái đã/chưa thuê
    - Lọc diện tính tối thiểu/tối đa
    - Nhảy tới bản đồ thửa đất trong bảng

<p>
    <img src='demo/industry/region-filter.gif' width='222'>
    <img src='demo/industry/search.gif' width='222'>
</p>

## Bản đồ điểm giếng

### Tổng quan bản đồ

<p>
    <img src='demo/well/overview-1.jpg' width='222'>
    <img src='demo/well/overview-2.jpg' width='222'>
    <img src='demo/well/overview-3.jpg' width='222'>
</p>

### Xem điểm giếng

<p>
    <img src='demo/well/view-1.jpg' width='222'>
    <img src='demo/well/view-1.gif' width='222'>
</p>

### Popup chú thích

<img src='demo/well/legend.jpg' width='222'>

### Trang tìm kiếm nâng cao

<img src='demo/well/search.gif' width='222'>

## Bản đồ hầm đất

### Tổng quan bản đồ

<p>
    <img src='demo/pit/overview-1.jpg' width='222'>
    <img src='demo/pit/overview-2.jpg' width='222'>
    <img src='demo/pit/overview-3.jpg' width='222'>
</p>

### Xem điểm hầm đất

<p>
    <img src='demo/pit/view-1.jpg' width='222'>
    <img src='demo/pit/view-1.gif' width='222'>
</p>

### Popup chú thích

<img src='demo/pit/legend.jpg' width='222'>

### Trang tìm kiếm nâng cao

<img src='demo/pit/search.gif' width='222'>

## Bản đồ quan trắc nước

### Tổng quan bản đồ

<p>
    <img src='demo/water/overview-1.jpg' width='222'>
    <img src='demo/water/overview-2.jpg' width='222'>
</p>

### Xem điểm quan trắc nước

<p>
    <img src='demo/water/view-1.jpg' width='222'>
    <img src='demo/water/view-1.gif' width='222'>
</p>

### Chọn WQI để hiển thị trên bản đồ

<p>
    <img src='demo/water/picker.jpg' width='222'>
    <img src='demo/water/picker-1.jpg' width='222'>
    <img src='demo/water/picker-2.jpg' width='222'>
</p>

### Popup chú thích

<img src='demo/water/legend.jpg' width='222'>

### Trang tìm kiếm nâng cao

<img src='demo/water/search.gif' width='222'>

## Bản đồ quan trắc không khí

### Tổng quan bản đồ

<p>
    <img src='demo/air/overview-1.jpg' width='222'>
    <img src='demo/air/overview-2.jpg' width='222'>
    <img src='demo/air/overview-3.jpg' width='222'>
</p>

### Xem điểm quan trắc không khí

<p>
    <img src='demo/air/view-1.jpg' width='222'>
    <img src='demo/air/view-2.jpg' width='222'>
    <img src='demo/air/view-1.gif' width='222'>
</p>

### Chọn AQI để hiển thị trên bản đồ

<p>
    <img src='demo/air/picker.jpg' width='222'>
    <img src='demo/air/picker-1.jpg' width='222'>
    <img src='demo/air/picker-2.jpg' width='222'>
</p>

### Popup chú thích

<img src='demo/air/legend.jpg' width='222'>

### Trang tìm kiếm nâng cao

<img src='demo/air/search.gif' width='222'>


## Bản đồ trạm xử lý nước thải

### Tổng quan bản đồ

<p>
    <img src='demo/treatment/overview-1.jpg' width='222'>
    <img src='demo/treatment/overview-2.jpg' width='222'>
</p>

### Xem trạm xử lý nước thải

<p>
    <img src='demo/treatment/view-1.jpg' width='222'>
    <img src='demo/treatment/view-1.gif' width='222'>
</p>

### Popup chú thích

<img src='demo/treatment/legend.jpg' width='222'>

### Trang tìm kiếm nâng cao

<p>
    <img src='demo/treatment/search-1.jpg' width='222'>
    <img src='demo/treatment/search.gif' width='222'>
</p>