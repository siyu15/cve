SQL injection exists in the ibos office OA. Procedure

official website:http://www.ibos.com.cn/

version:4.5.5

Function points: Integrated office = "Recruitment management =" Background investigation = "Export
![WPS图片(2)](https://github.com/siyu15/cve/assets/98629324/3faeaeb4-ab68-4df2-b5b2-99e00202f667)

POC

Route: r=recruit/bgchecks/export&checkids=x

The injection parameter checkids exists

Successfully burst the database name by reporting an error injection

![WPS图片(1)](https://github.com/siyu15/cve/assets/98629324/f128452a-6f49-4d94-ae9d-d2951ec4fa92)
