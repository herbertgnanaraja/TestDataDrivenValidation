# TestDataDrivenValidation
JSON, XML responses can be validated using datadriven approach
Following validations can be achieved

1.	Equal to
2.	* - any value in XML for asserted field
3.	*@ - case insensitive equal to 
4.	*$ - case insensitive contains
5.	** - contains
6.	*!  - not equal to 
7.	!! – field must not exist
8.	Text1#TEXT2#text3 – case insensitive any one matching
9.	Blank cell(field) will be skipped
10. Repeating elements in response suported
List of functions:
  1.	loadExcel( FileWithPath, SheetName, index )
  2.	assertXML(XMLString, TestcaseID, index )
  3.	assertJSON(JSONString, TestcaseID, index )
  4.	WriteToExcel( file, tab, text , row ,col )
  5.	AppendExcel( file, tab, text )
  6.	DateTime()
