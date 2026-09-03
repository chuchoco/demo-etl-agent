# Hướng dẫn

Nhiệm vụ của bạn là đổi định dạng lưu trữ chữ cái và điểm số tương ứng
trong game.

Hiện tại, chữ cái được lưu theo nhóm dựa trên điểm số, kiểu ánh xạ
một-nhiều:

- 1 điểm: "A", "E", "I", "O", "U", "L", "N", "R", "S", "T"
- 2 điểm: "D", "G"
- 3 điểm: "B", "C", "M", "P"
- 4 điểm: "F", "H", "V", "W", "Y"
- 5 điểm: "K"
- 8 điểm: "J", "X"
- 10 điểm: "Q", "Z"

Cần đổi sang lưu từng chữ cái riêng lẻ kèm điểm số của nó, kiểu ánh xạ
một-một.

- "a" đáng giá 1 điểm.
- "b" đáng giá 3 điểm.
- "c" đáng giá 3 điểm.
- "d" đáng giá 2 điểm.
- v.v.

Ngoài ra, team cũng quyết định đổi các chữ cái từ viết HOA sang viết
thường.

~~~~exercism/note
Nếu muốn xem cấu trúc dữ liệu cũ và cách nó cần thay đổi ra sao, xem các
ví dụ trong bộ test.
~~~~
