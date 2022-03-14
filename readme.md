- Kiểu dữ liệu:

* Kiểu nguyên thủy(primitive): Number, String, Boolean, Underfined, Null
  // number: 1, 2, 100
  // string: hello world, xin chào, ....
  // boolean: true và false
  // underfined: khai báo ra mà không gán giá trị, giá trị không xác định
  // null: không có giá trị thì sẽ là null
* Kiểu non-primitive: Object, Function, Array....

- Khai báo biến với các từ khóa: var, let, const

* Var: có thể đổi giá trị và khai báo lại được
* Let: có thể đổi được giá trị nhưng không khai báo lại được
* Const: là 1 hằng số, không thể thay đổi giá trị, không khai báo lại được
* Hoisting: cách mà Javascript đưa phần khai báo biến lên đầu
  VD:
  console.log(a);
  var a = 3;
  // Hoisting sẽ hiểu là đưa phần khai báo var a lên đầu nên kết quả khi in a ra sẽ là underfined.
