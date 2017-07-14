
# HtmlToPdf 

#### 将HMTL元素转成pdf文件，并且保留原图片的像素真实比例

- demo

    ***请查看1.html***
    
```javascript
    var htmltopdf = new htmlToPDF();
    //生成多个pdf文件
    var arr = [document.getElementById('x'),document.getElementById('y')]
    //savePDF支持传入元素数组也支持传入单个元素。
    htmltopdf.savePDF(arr);
```

---

ps：

- htmltopdf依赖于jquery
- htmltopdf 引用了htmltocanvas和jsPDF,已经集成两个js文件在htmltopdf中，无需再次引用

