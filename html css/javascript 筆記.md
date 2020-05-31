## javascript 筆記
<br/>
<pre>
	改用 === 、 !=== 取代 == 、!=
	因為== 、!= 會自動轉換資料型態，這樣可能會導致錯誤且不易除錯
</pre>
ex.

```javascript
	
	10 == '10'  //return true 自動轉換型態

	10 === '10' //return false
	10 === 10	//return true

```
