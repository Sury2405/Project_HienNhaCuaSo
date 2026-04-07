Decription: 
- Name: Website Hiên Nhà Của Sò
- Content: Web truyện chữ, truyện ngắn, đa thể loại
- Data: sử dụng My Sql
  + Truyện:
    . Id
    . Tên truyện: 1 truyện có 1 ảnh bìa, 1 truyện có nhiều chương, 1 truyện có nhiều thể loại, 1 truyện có 1 mô tả
    . Hình ảnh: 1 hình ảnh thuộc về 1 truyện
    . Thể loại: 1 thể loại có thể có nhiều truyện
    . Mô tả: 1 mô tả chỉ thuộc về 1 truyện
    . Chương: 1 chương thuộc về 1 truyện
    
  + Thể loại:
    . Id
    . Tên thể loại
    . Mô tả
    
  + Danh sách:
    . Id
    . Tên danh sách

  + Bảng xếp hạng:
    . Id
    . Tên bảng xếp hạng

  + User
    . Id
    . Tên user
    . Chức năng: admin, user
    . Email
    . Pass

- UI (front end): sử dụng ngôn ngữ react js, frame: react native, html, css
  + Trang chủ
    * Header: Logo Trang web, Trang chủ, truyện mới, danh sách truyện, thể loại, bảng xếp hạng, "Đăng ký/ Đăng nhập", Thông tin user
    * Center:
      . Truyện đề cử: đề cử ngẫu nhiên 10 truyện, hoặc để cử theo sở thích của đọc giả (lấy ngẫu nhiên theo: thể loại, top tuần, top tháng, top ngày).
      . Truyện mới nhất: 1 hàng ngang gồm có 10 truyện được đăng lên mới nhất (thời gian tính bằng giây), 1 dòng clik chuyển đến trang "truyện mới nhất"
        => Hiển thị: tên truyện, số chương, số lượt xem, thể loại, thẻ (new).
      . Truyện hot nhất: 1 hàng truyện gồm 10 truyện được đọc nhiều nhất (tính từ lúc tạo trang web đến hiện tại), 1 dòng click chuyển đến trang "truyện hot nhất",
        => Hiển thị: tên truyện, số chương, số lượt xem, thể loại
      . Top truyện
        => Ngày: lượt xem nhiều nhất trong ngày. Hiển thị: tên truyện, số lượt xem
        => Tuần: Lượt xem nhiều nhất trong tuần. Hiển thị: tên truyện, số lượt xem
        => Tháng: Lượt xem nhiều nhất trong tháng. Hiển thị: tên truyện, số lượt xem
      . Thể loại
        => Hiển thị tất cả các thể loại: khi click vào các thể loại nào sẽ chuyển đến trang chuyên về thể loại đó (trong trang đó sẽ có tất cả các truyện thuộc thể loại đó).
    *Footer:
      . Hiển thị: logo trang web, thông tin liên hệ

  
