# PageBar
一个jquery分页插件1111
```js
 var pager = $('#pager').pagebar({
                displayPageCount: 5,
                isWithSkipBtn: true,
                getTotalPages: function (data) {
                    return data.result.pageCount;
                },
                nextPage: function (data, pageIndex) {
                    console.log(data, pageIndex);
                } //点击当前页面回调函数，传入当前index
           });
```
