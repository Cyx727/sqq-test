
## H2 Header
#### H4 Header
https://www.baidu.com

https://github.com/sqq-hub/sqq-test/edit/main/link.md


目录中的图像
![image](https://github.com/sqq-hub/sqq-test/blob/main/Img/productShow04.jpg)
web中的图像
![baidu] (http://www.baidu.com/img/bdllogo.gif "百度logo")
```C
int main()
{
   int a;
   a=10;
   printf("%d",a);
   while (!feof(fp_in))
	{
		initBuf();
		fgets(buf, MAX, fp_in);
		if (buf[0] == '@')
		{
			fprintf(fp_out, "%c", '\n');
			num++;
			i = 0;
			while (buf[i] != '*'&&buf[i] != '\0'&&buf[i] != '\n')
			{
				fprintf(fp_out, "%c", buf[i]);
				i++;
			}
			fprintf(fp_out, "%c", ' ');
		}
		else {
			i = 0;
			while (buf[i] == ' ') i++;
			while (buf[i] != '*'&&buf[i] != '\0'&&buf[i] != '\n')
			{
				fprintf(fp_out, "%c", buf[i]);
				i++;
			}
		}
   }
}
