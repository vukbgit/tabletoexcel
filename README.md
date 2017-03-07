# tabletoexcel
create excel by javascript for table or json



###Install

    $ npm install table-to-excel

###Use
```bash
<script src='table-to-excel.js'></script>
var tableToExcel=new TableToExcel();
document.getElementById('button1').onclick=function(){
	
	tableToExcel.render("table");
	
};
document.getElementById('button2').onclick=function(){
	var arr=[
		['LastName','Sales','Country','Quarter'],
		['Smith','1675323242在34234','UK','Qtr 3'],
		['Johnson','14808','USA','Qtr 4']
	]
	tableToExcel.render(arr,[{text:"create",bg:"#000",color:"#fff"},{text:"createcreate",bg:"#ddd",color:"#fff"}]);
};
-------------------------or---------------------------
var TableToExcel = require('table-to-excel');
var tableToExcel=new TableToExcel();
.....

```
	

[github](https://github.com/ecofe/tabletoexcel)
