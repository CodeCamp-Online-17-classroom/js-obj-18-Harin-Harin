# js-lab-64
### Lab64 Object: Guess Result3
บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร    
ผลลัพท์ คือ John เพราะ console.log(this.name) this = user กลายเป็น console.log(user.name)   
          value ของ user.name = 'John'

```JavaScript
let user = {
  name: 'John',
  sayHi: function () {
    console.log(this.name);
  }
};

(user.sayHi)(); // *
```
