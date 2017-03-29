# tabletoexcel
create excel by javascript for table or json



## Install

    $ npm install table-to-excel

## Use
```bash
1、
<script src='table-to-excel.js'></script>
var tableToExcel=new TableToExcel();
document.getElementById('button1').onclick=function(){
	
	tableToExcel.render("table");
	
};
document.getElementById('button2').onclick=function(){
	var arr = [
		['Name', 'Age', 'Sex', 'Country'],
		['ecofe', '18', 'male', 'china'],
		['alice', '3', 'female', 'china']
	]
	tableToExcel.render(arr,[{text:"title1",bg:"#333",color:"#fff"},{text:"title2",bg:"#ddd",color:"#333"}]);
};

2、
var TableToExcel = require('table-to-excel');
var tableToExcel=new TableToExcel();
.....

```




[github](https://github.com/ecofe/tabletoexcel)
