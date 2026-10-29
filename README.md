Recommended for Visual Studio Code

Toàn bộ đoạn code cài đặt pyldpc:
python -m venv env
.\env\Scripts\Activate.ps1
pip install numpy scipy matplotlib setuptools pyldpc
pip install pyldpc
pip install scikit-commpy

(pip install --upgrade pyldpc)

(Nếu xuất hiện lỗi trong quá trình cài đặt, hãy thử lệnh khác:
pip install --no-build-isolation pyldpc
pip install numpy setup tools matplotlib
pip install setuptools matplotlib
)

Chú thích:
1. Cài đặt numpy và setuptools: mhập lệnh: pip install numpy setuptools matplotlib

2. Cài đặt pyldpc: nhập lệnh: pip install pyldpc

3. Kiểm tra cài đặt thành công: nhập lệnh: python -c "import pyldpc; print('Cài đặt thành công')"

4.Tạo môi trường ảo env, nhập lệnh: python -m venv env
(Đợi khoảng 5–10 giây,
Khi màn hình hiện lại dòng PS ví dụ như C:\Users\ADMIN> mà không báo lỗi đỏ nghĩa là đã tạo
thành công thư mục env).

5.Kích hoạt môi trường ảo, nhập lệnh: .\env\Scripts\Activate.ps1

6. Cài đặt scikit-commpy cho kênh Rayleigh, QPSK và bộ giải mã Min-Sum: pip install scikit-commpy


NOTE:
1. Môi trường "env" nên chọn vào chung thư mục lưu file code
2. Ảnh sẽ được lưu vào file tổng của Visual Studio Code
3. Chạy các biểu đồ sẽ tốn thời gian (nếu chạy file run_all_experiments.py sẽ lâu hơn)
4. Các bảng theo yêu cầu sẽ hiện lên phần "terminal" khi thực hiện chạy code mô phỏng
5. Kiểm tra các thư viện đã cài: python -m pip list
6. Xác nhận môi trường hiện tại hoạt động bình thường: 
python -c "import numpy, scipy, matplotlib, pyldpc; print('Tất cả các thư viện cần thiết cho đồ án đã được tải thành công)"
