# JavaScripts - part 1

<hr>

## Operator : Toán tử
    
### Dấu so sánh == và ===
_ Toán tử == khi so sánh hai giá trị với nhau thì đâu tiên nó sẽ thực hiện chuyển đổi 
loại toán tử rồi sau đó mới so sánh.
_ Toán tử === khi so sánh thì chúng sẽ so sánh các giá trị cũng như kiểu dữ liệu của
các biến.

### 

<hr/>

## Prototypal Inheritance : Kế thừa nguyên mẫu
 - Gọi đến một thuộc tính của object con bằng object cha : khi cùng khởi tạo một object 
trong một object thì object cha có thể gọi đến thẳng thuộc tính con mà không cần gọi qua
object con khi thuộc tính object con có mà thuộc tính object cha không có.
```
let objectFather = {
    speaks: true,
    objectChild: {
        goes : false,
        eats : true,
        speaks: false
    }
}
console.log('objectFather : ' + objectFather.speaks);
```

### 