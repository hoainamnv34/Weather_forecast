# Weather-forecast-using-LSTM-DecisionTree
Project dự báo thời tiết tại một địa điểm bằng cách sử dụng mô hình Long Short Term Memory và DecisionTree

### Các thư viện và ngôn ngữ được sử dụng:
* `Python 3.10`: toàn bộ project đều sử dụng ngôn ngữ lập trình Python
* `Numpy`: xử lý dữ liệu số, dữ liệu dạng mảng,...
* `Pandas`: làm việc với dữ liệu dạng bảng, cụ thể là `csv` 
* `Matplotlib` và `Seaborn`: trực quan hoá dữ liệu
* `MinMaxScaler` from sklearn.preprocessing: scale dữ liệu về khoảng nhỏ hơn trước khi bắt đầu huấn luyện
* `LabelEncoder` from sklearn.preprocessing để mã hóa các nhãn (labels) thành các số nguyên.
* `Keras` from Tensorflow : xây dựng mô hình học máy LSTM
* `confusion_matrix` from sklearn.metrics: tính ma trận nhầm lẫn (confusion matrix) để đánh giá hiệu suất của một mô hình
* `mean_absolute_error` và `BinaryAccuracy` from keras.metrics để đánh giá kết quả dự đoán của mô hình

### Cách sử dụng:
* Dữ liệu thô được lưu trữ trong folder `raw_data` dưới dạng `.csv`
* Chạy tất cả các ô trong file `Data_Preprocessing.ipynb`, dữ liệu đã xử lý sẽ được lưu vào folder `processed_data`dưới dạng `.csv`
* Sau khi đã xử lý xong dữ liệu, tiến hành huấn luyện mô hình bằng cách thực thi tất cả các ô trong file `DECISIONTREE.ipynb` và `LSTM.ipynb`. Mô hình sau khi huấn luyện sẽ được lưu vào folder `model` dưới dạng `.h5` với `val_loss` thấp nhất.
* Cũng trong file `DECISIONTREE.ipynb` và `LSTM.ipynb`, tiến hành load mô hình tốt nhất lên và đánh giá nó
* Nhóm đã lưu các đánh giá dưới dạng hình ảnh trong folder `image`

### Thông tin liên lạc:
* Email: hoainam.nv34@gmail.com
