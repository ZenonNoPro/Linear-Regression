giả nghịch đảo của một ma trận A:
	numpy.linalg.pinv(A)

X: ma trận dữ liệu đầu vào, mỗi hàng là 1 điểm dữ liệu

Y: ma trận kết quả thu được, mỗi hàng là 1 giá trị thu được tương ứng

W: nghiệm bài toán

W = pinv(A) * B
A = X.T * X
B = X.T * Y
