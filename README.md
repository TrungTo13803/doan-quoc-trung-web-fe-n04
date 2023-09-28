# web-fe-n04
## Yêu cầu
- File ảnh, svg, css thì cho vào folder assets. Tìm đúng folder riêng của từng loại file. Nếu có loại file mới thì tạo folder mới đặt tên theo tên loại file (vd: .docx)
- Viết đường dẫn đến file thì phải viết format như sau: ./assets/ten_folder/ten_file.duoi_file/. Nếu tạo ra folder khác ngoài folder assets thì viết tương tự. (vd: ./folder_A/folder_B/ten_file.abc/
- Đặt class và id có ý nghĩa. Ưu tiên đặt tên bằng tiếng Anh. Không đặt tên như: box-1, box-2,.... (Nếu có dùng chữ box thì phải đặt tên ví dụ như này: box-category (thể loại)).
- Ưu tiên đặt class chuẩn BEM - Block__element-modify -> tênclassthẻcha__tênthẻcon-đặcđiểmcủathẻcon. Vd: header__group-list-left (header = tên class thẻ cha; __group-list: tên thẻ con; -left: đặc điểm của thẻ con)
<div class="header">
  <div class="header__group-list-left">
    ...
  </div>
  <div class="header__group-list-right">
  ...
  </div>
</div>
