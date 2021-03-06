**Personal information** <br>
*Name* :  *Nikita Trifonov* <br>
*Date of birth* : *25th February 2002* <br>
*Adress* : *37 Surganova, Minsk, Belarus* <br>
*Phone number* : *+375299064271* <br>
*Martial status* : *Single* <br>
*Email* : nikityshka.trifonov@gmail.com <br>
**Obgjective**<br>
Now my main goals are improve my knowlege in *html*, *css*, *JavaScript* and I am seeking employment with a company where I can use my ability to communicate with people and take advantage of my knowledge of English<br>
**Education**<br>
2nd year student of the faculty of ingormation technology and robotics of BNTU<br>
**Code examples**<br>
```// Set the full screen mode for the designer
var options = new Stimulsoft.Designer.StiDesignerOptions();
options.appearance.fullScreenMode = true;

// Create the report designer with specified options
var designer = new Stimulsoft.Designer.StiDesigner(options, "StiDesigner", false);

// Assign the onSaveReport event function
designer.onSaveReport = function (e) {
	var jsonStr = e.report.saveToJsonString();
	alert("Save to JSON string complete.")
}

// Assign the onCreateReport event function
designer.onCreateReport = function (e) {
	var ds = new Stimulsoft.System.Data.DataSet("Demo");
	ds.readJsonFile("../reports/Demo.json");
	e.report.regData("Demo", "Demo", ds);
	e.report.dictionary.synchronize();
}

// Assign the onPreviewReport event function
designer.onPreviewReport = function (e) {

}

// Assign the onExit event function
designer.onExit = function (e) {

}

// Create a new report instance
var report = new Stimulsoft.Report.StiReport();
// Load report from url
report.loadFile("../reports/SimpleList.mrt");
// Edit report template in the designer
designer.report = report;

// Show the report designer in the 'content' element
designer.renderHtml("content");
``` 
**English level**<br>
According to the [EfSet](https://www.efset.org/ru/) websie my English level is B1
