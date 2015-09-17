# proj_Management_python

- global변수 사용법
- raw_input() / print
- switch문이 없다. (Map으로 유사하게, 간단히 http://alnova2.tistory.com/21)
- class파일사용 (출처 : http://egloos.zum.com/rucaus/v/2424600)

```{.python}
>> ManagementSystem.py 에 BookMgr클래스가 존재
 
>> ex) using class
> instance_ManagementSystem = ManagementSystem.BookMgr() # load class instance
> instance_ManagementSystem.LoadXMLFromFile(filePath)    # using class function 

```
- l : LoadXMLFromFile()
	- file IO 파일IO
	- try, except, else 예외처리
	- parse() : from xml.dom.minidom import parse, parseString
	- global BooksDoc에 파일에서 불러온 데이터를 저장
	
- q : quit

- p : PrintDOMtoXML()
	- .toxml()
	
- _checkDocument() :  check data is None or not