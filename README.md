# Imposter find Real Love
Construct Game Engine

## I.	Giới thiệu: 
Game dựa trên hình tượng nhân vật game Among Us – game từng thống trị thế giới giữa cuối năm 2020, kết hợp với trò chơi giải mê cung kinh điển.  Game Imposter Find Real Love sẽ mang đến làn gió mới cho các trò chơi giải mê cung mà chúng ta thường chỉ thấy và giải trên các tạp chí và các cuốn sách trò chơi. Tận dụng độ “hot” của Among Us và sự phát triển của công nghệ, game sẽ đưa người chơi đến với trải nghiệm giải mê cung vô cùng thú vị và sắc màu. Ngoài mục tiêu giải trí, game còn giúp người chơi luyện khả năng trí nhớ ngắn hạn về mô hình đường đi và tư duy tìm đường ngắn nhất để về đến đích. Game được tăng độ khó gấp nhiều lần khi người chơi không đoán được vị trí về đích ở đâu và buộc người chơi vừa đi vừa mò và phải nhớ đường đi. Hiện tại game mới phát hành nên khi mua game sẽ được tặng gamemposter Kill This Love.

## II.	Quy trình kỹ thuật: 

### 1.	Tổng quát:

*	Game engine: Construct 3.

*	Đồ hoạ: tự thiết kế hoàn toàn (trừ ảnh nền).

*	Âm thanh: Among Us Sound.

### 2.	Chi tiết: 

#### i.	Hình nền (Background):

*	Kích thước: 854 x 480 px (view), 1708 x 960 (layout game).

*	Thiết kế: ảnh sử dụng nguồn lấy từ google hình ảnh.

#### ii.	Các đối tượng trong trong trò chơi (Objects):

##### a.	Nhân vật trò chơi (Player):

*	Kích thước: 56 x 84 px.

*	Thiết kế: sử dụng ô vuông pixel (4 px) để vẽ.

*	Hiệu ứng: ảnh động (2 sprites).

*	Trạng thái: di chuyển và đứng yên.

*	Phương thức di chuyển: sử dụng 4 mũi tên trên bàn phím.

*	Phương thức tuỳ chọn: 5 màu sắc: đỏ (255,0,0), xanh lá (0,255,0), xanh dương (0,0,255), vàng (255,255,0), trắng (0,0,0)

##### b.	Trái tim (Heart):

*	Kích thước: 220 x 198 px.

*	Thiết kế: sử dụng ô vuông pixel (11 px) để vẽ.

*	Hiệu ứng: ảnh động (8 sprites).

*	Trạng thái: đứng yên.

*	Màu sắc: thay đổi từ đỏ sang hồng và ngược lại.

##### c.	Tường mê cung (Wall):

*	Kích thước: 6 x (?) px

*	Thiết kế: sử dụng ô vuông pixel (1 px) để vẽ.

*	Trạng thái: đứng yên.

*	Màu sắc: cyan đổ màu nhạt dần từ trong ra ngoài và đen.

##### d.	Thiên thạch (Meteorites):

*	Kích thước: 140 x 100 px.

*	Thiết kế: sử dụng ô vuông pixel (4 px) để vẽ.

*	Hiệu ứng: ảnh động (3 sprites).

*	Trạng thái: di chuyển ngẫu nhiên

### iii.	Mê cung (Map): (xem ở file)

## III.	Hướng dẫn sử dụng: 

  *	Dùng 4 phím mũi tên trên bàn phím để di chuyển nhân vật game.

  *	Dùng chuột trái để chọn các tuỳ chọn.

  *	Di chuyển nhân nhân vật vượt mê cung để về đến đích.

  *	Đến đích chạm vào được trái tim là hoàn thành thử thách.

  *	Trong quá trình di chuyển cần tránh những thiên thạch bay lơ lửng trong không gian.

  *	Trong quá trình chơi, nếu nhân vật chạm vào thiên thạch thì thử thách thất bại.

  *	Người chơi sẽ không biết vị trí đích nằm ở đâu và phải tự tìm được đích đến.

  *	Người chơi phải ghi nhớ những đoạn đã đi qua và tìm giải pháp đi hiệu quả nhất.

  *	Kết quả người chơi được so sánh dựa trên tiêu chí thời gian hoàn thành thử thách.

o	Một vài lưu ý khi chơi: cần giải quyết nhanh thử thách nhất có thể vì sau mỗi 40s sẽ xuất hiện thêm 1 thiên thạch trên màn hình, tường sẽ sáng và tối trong chu kì 1s, để chơi hiệu quả người chơi cần phải vận dụng khả năng ghi nhớ và khả năng tưởng tượng không gian 2 chiều tốt, nhân vật có 5 màu để tuỳ chọn và thay đổi trong phần Option, có hướng dẫn chơi ngắn gọn trong phần Tuturial.

## IV.	Mở rộng

Các bước thực thi tạo game:

  B1:	Chọn chủ đề game, nhân vật.

  B2:	Xác định phương thức chơi và giao diện chính.

  B3:	Chèn ảnh nền và điều chỉnh kích thước.

  B4:	Thiết kế tạo hình các nhân vật và đối tượng xuất hiện trong game.

  B5:	Tạo hiệu ứng ảnh động và gắn các hành vi cho đối tượng.

  B6:	Trang trí, xắp xếp các đối tượng trên cùng một layout.

  B7:	Lập trình các sự kiện diễn ra trong game (tạo câu lệnh điều khiển và điều kiện trong Event sheet).

  B8:	Tạo thêm các layout (menu, gameover,…).

  B9:	Thêm các button, hệ thống tính điểm, thời gian.

  B10:	Chèn nhạc, hiệu ứng âm thanh.


var copyright = require('update-copyright');
copyright('Copyright (c) 2029 by ');
