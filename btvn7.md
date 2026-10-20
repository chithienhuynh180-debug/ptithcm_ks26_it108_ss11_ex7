# Bài: heading styles và auto toc

## Phần 1: Phân tích lỗi

1. các tiêu đề chỉ chỉnh tay (đổi cỡ chữ, in đậm, tô màu) nên word vẫn hiểu là normal. auto toc chỉ quét đoạn có gán heading 1, 2, 3 nên không thấy tiêu đề nào và mục lục rỗng.
2. mục lục thụt đầu dòng theo cấp heading. nếu 2.1.1 gán nhầm h2 thì nó ngang hàng với 2.1, không còn là mục con nên mục lục sai cấp.

## Phần 2: Sửa lỗi

3. các bước sửa:
   - bôi đen từng dòng, bấm ctrl + shift + N để xóa định dạng tay
   - dòng 1, 2, 3: ctrl + alt + 1 (heading 1)
   - dòng 1.1, 1.2, 2.1: ctrl + alt + 2 (heading 2)
   - dòng 2.1.1: ctrl + alt + 3 (heading 3)
   - references > table of contents > automatic table
4. không, mục lục sẽ không tự đổi số trang, vẫn ghi trang 2. cần bấm vào mục lục rồi bấm F9, chọn update entire table.