# char* pc="hello"而非const char* pc="hello"
## 改为char* pc=(char*)"hello",但是”hello”处于只读存储区，不能通过修改pc来修改值，故故存在隐患。
