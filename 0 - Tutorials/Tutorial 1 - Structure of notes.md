creation date: 2025-04-09 19:39
modification date: `$= dv.current().file.mtime`

# Tutorial 1 - Structure of notes

- Cấu trúc của tất cả các ghi chú sẽ được lưu trong thư mục từ 1 đến 6
	- 1 - Source Material
	- 2 - Tags
	- 3 - Indexes
	- 4 - Main Notes
	- 5 - Templates
	- 6 - undefined
- Từ đây từ note sẽ được sử dụng để thay thế cho ghi chú
- Mỗi thư mục sẽ chứa các note với chức năng khác nhau và sẽ được mô tả dưới đây:

## 3 - Indexes 

- Đây là cấp bậc cao nhất của note
- Tất cả các note sẽ được phân loại theo loại ngôn ngữ
- Ở cấp bậc này hiện tại sẽ có 4 loại:
	- English
	- French
	- German
	- Spanish

## 2 - Tags

- Đây là cấp bậc thứ 2 của mpte
- Tất cả các note sẽ được phân loại theo nguồn:
	- Tên sách
	- Tên phim
	- Tên kênh Podcast
	- Tên kênh Youtube
	- ...
- Những note ở cấp bậc này sẽ liên kết với các note ở nhóm 3 (ở trên) theo ngôn ngữ

## 1 - Source Material

- Đây là cấp thấp nhất của note
- Những ghi chú này sẽ dành cho các bài báo, những bài học trong sách, những tập phim, podcast, video và được phân loại sau đây:
	- Articles, Blogs: dành cho cái bài blog ngắn, báo, ...
	- attachments: dành riêng cho những hình ảnh, audio khi người dùng copy và paste. Tất cả sẽ được lưu tự động vào đây
	- Books: các ghi chú thuộc về sách
	- Dictionary: dành cho các từ vựng được lấy ra theo khuôn mẫu từ ChatGPT
	- Films: các ghi chú thuộc về phim
	- Other: không thuộc các loại trên
	- Podcasts: các ghi chú thuộc về podcast
	- Videos: các ghi chú thuộc về video trên youtube, ...

- Những ghi chú trong phần 1 - Source Material sẽ liên kết với nhóm 2 và thuộc về một nguồn chung. Ví dụ:
	- Những ghi chú bài 1, 2, 3, 4, ... (nhóm 1) sẽ thuộc trong 1 cuốn sách (nhóm 2)
	- Những ghi chú tập 1, 2, 3, 4, ... (nhóm 1) sẽ thuộc trong 1 bộ phim (nhóm 2)
	- Những ghi chú về podcast (nhóm 1) sẽ thuộc series cùng 1 tác giả hoặc 1 kênh trên youtube, spotify, ... (nhóm 2)

## 5 - undefined

- Tất cả các note mới tạo sẽ được thêm vào đây tự động và sẽ chờ người dùng phân loại khi hoàn thành
- Các note đang được thực hiện sẽ được lưu trữ tại đây cho đến khi xong và xếp vào trong các nhóm 1, 2, 3

## 4 - Main notes

- Sẽ có một vài note sinh ra trong quá trình làm việc vì vậy những note sẽ được lưu vào hàng chờ cho đến khi được chuyển vào nhóm 6 để thực hiện
- Nói cách khác, nhóm 4 chính là nhóm note chưa được thực hiện cho đến khi chuyển vào nhóm 6 để bắt đầu làm việc


![[Pasted image 20250409211441.png]]


# References