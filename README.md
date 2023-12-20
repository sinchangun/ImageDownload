# ImageDownload
![290708000-30cd91ac-4e89-4ff2-b614-c0b5f43db1c4](https://github.com/sinchangun/ImageDownload/assets/145514301/061bffa1-4f41-47a1-ad5d-bc7364872400)


![290708145-61e6b5e8-c169-4845-88f5-a7019408fee2](https://github.com/sinchangun/ImageDownload/assets/145514301/4264db8b-4e44-47bd-9e1d-dd4c95d6bdb6)


![290708867-9a7d163e-8559-49b6-983c-c5c51f5ba5c6](https://github.com/sinchangun/ImageDownload/assets/145514301/3929ed97-efa3-42f6-9bd0-1647a6023dd8)

# 아무 이미지나 우클릭 복사를 클릭한다.

# console.log 창에 변수를 생성 var har = { 복사한내용 } 이렇게 한다.

![290709012-24d0bda8-7cfa-49be-ab96-1340f0a586cf](https://github.com/sinchangun/ImageDownload/assets/145514301/5587fa74-527a-4825-a138-6f05a5df0f70)

![290709806-5165585a-5df2-4103-9c9e-9f70f5ea014c](https://github.com/sinchangun/ImageDownload/assets/145514301/7be29add-b92a-45b1-a2e4-e03a3accd109)

# download.js 안에 내용을 복사하여 console에 붙여 놓으면 이미지 주소가 일괄적으로 나타난다. 내용은 밑에있음

```
var imageUrls = [];
har.log.entries.forEach(function (entry) {
  if (entry.response.content.mimeType.indexOf("image/") !== 0) return;
  imageUrls.push(entry.request.url);
});
console.log(imageUrls.join('\n'));
```

# 주소 이미지를 다운

![290713210-15973efd-6544-4f35-b4c4-1c0e2ea0819a](https://github.com/sinchangun/ImageDownload/assets/145514301/09edebe8-d091-4a0c-8037-b72c6a2f8a2e)



