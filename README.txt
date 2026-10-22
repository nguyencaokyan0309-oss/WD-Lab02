ROSIE BEAUTY — HTML-ONLY E-COMMERCE | WD-Lab02 (Thiết Kế Web)
=============================================================
Sinh viên: Nguyễn Cao Kỳ Ân – MSSV 23110064 – Lớp 23TTH1
Chạy: bật Apache (XAMPP) rồi mở http://localhost/WD-Lab02/
Xem online (GitHub Pages): https://nguyencaokyan0309-oss.github.io/WD-Lab02/

Ngành hàng: MỸ PHẨM (khác ngành giày dép của StepUp Shoes mẫu).
Khách hàng mục tiêu: sinh viên và nhân viên văn phòng 18–30 tuổi.
3 nhóm hàng – 10 sản phẩm (mã SKU MP01–MP10):
  - Chăm sóc da:        MP01 Sữa rửa mặt, MP02 Toner, MP03 Serum Vitamin C, MP04 Kem dưỡng ẩm
  - Trang điểm:         MP05 Cushion, MP06 Son kem lì, MP07 Mascara, MP08 Bảng phấn mắt
  - Chống nắng & cơ thể: MP09 Kem chống nắng, MP10 Sữa dưỡng thể

5 trang HTML:
  index.html     Trang chủ: banner, menu, hero, 3 nhóm hàng, 10 card sản phẩm, chính sách demo
  chi-tiet.html  10 section id="MP01"…"MP10" (fragment), ảnh, giá, bảng thông số
  bang-gia.html  Bảng 10 sản phẩm: caption, colgroup, thead 2 tầng, 3 tbody, tfoot,
                 colspan (THÔNG SỐ, THÔNG TIN GIÁ, hàng tổng) và rowspan (nhóm sản phẩm)
  dat-hang.html  Form GET: text, email, tel, select/optgroup, number, radio, checkbox,
                 date, textarea; label for/id, name, required
  xac-nhan.html  Trang đích demo: KHÔNG lưu đơn hàng, giải thích các cặp name=value trên URL

images/mp01.png … mp10.png: 10 ảnh AI mô phỏng chụp sản phẩm ROSIE BEAUTY, tạo bằng imagegen. Phong cách bao bì đen, trắng, vàng lấy cảm hứng từ Chanel. Không phải ảnh sản phẩm Chanel chính hãng. Ảnh SVG cũ được giữ lại để đối chiếu.

KHÔNG dùng CSS, style=, <style>, <script> hay JavaScript.
Màu sắc/bố cục dùng thuộc tính HTML legacy (bgcolor, text, link, vlink, alink, width,
align, valign, nowrap, cellpadding, cellspacing, border, font color/size) — chỉ nhằm mục đích
học tập trước khi học CSS, không phải best practice hiện đại.
Số tiền tổng trong bảng giá được nhập thủ công; HTML không tự tính toán.
Toàn bộ giá, chính sách, hotline, email và địa chỉ đều là dữ liệu demo.

Công cụ hỗ trợ: trong quá trình làm bài, sinh viên có nhờ Claude (Anthropic) hỗ trợ
chỉnh sửa code HTML.
