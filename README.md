
## H2 Header
#### H4 Header
https://www.baidu.com

https://github.com/sqq-hub/sqq-test/edit/main/link.md


目录中的图像/<br>
![image](https://github.com/sqq-hub/sqq-test/blob/main/Img/productShow04.jpg)
web中的图像/<br>
![] (https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E5%9B%BE%E7%89%87%20%E5%94%AF%E7%BE%8E%20%E6%84%8F%E5%A2%83&hs=2&pn=2&spn=0&di=118470&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&ie=utf-8&oe=utf-8&cl=2&lm=-1&cs=3440747717%2C4105191895&os=3374918274%2C3152010848&simid=3290335413%2C218172676&adpicid=0&lpn=0&ln=30&fr=ala&fm=&sme=&cg=&bdtype=0&oriquery=%E5%9B%BE%E7%89%87%20%E5%94%AF%E7%BE%8E%20%E6%84%8F%E5%A2%83&objurl=https%3A%2F%2Fgimg2.baidu.com%2Fimage_search%2Fsrc%3Dhttp%3A%2F%2Fimage.biaobaiju.com%2Fuploads%2F20180111%2F03%2F1515614305-obUAmquLCQ.jpg%26refer%3Dhttp%3A%2F%2Fimage.biaobaiju.com%26app%3D2002%26size%3Df9999%2C10000%26q%3Da80%26n%3D0%26g%3D0n%26fmt%3Djpeg%3Fsec%3D1620007716%26t%3D45f0c1f38ed4a062133a69c2ee7fa3ab&fromurl=ippr_z2C%24qAzdH3FAzdH3Fojgojg_z%26e3Bf5257_z%26e3Bv54AzdH3FzAzdH3Fqdb0nmmna9_z%26e3Bip4&gsm=2&islist=&querylist=)
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
