## H2 Header     
#### H4 Sub-heading  


[YouTube](http://www.youtube.com)  
[Second .md file](SecondMarkdown.md)

![Image](tux.png)

![Image](http://4.bp.blogspot.com/-dlBBg9sSX2o/Tg0WIMZOc7I/AAAAAAAAANY/A7SJ1mea7zA/s1600/penguin+solo.JPG)
```C
float average_amount(float * amounts, int size)
{
        int sum = 0;
        int count;
        float avg =0;

        for(count = 0; count < size; count++)
        {
                sum = sum + *(amounts + count);
        }

	avg = (float)sum / count;

        printf("\nThe average amount is $%.2f\n", avg);

        return avg;
}
```
> this is a markdown block quote.

* Apples
* Oranges
* Grapes

1. first
2. Second
3. Third

Bold | Italicized | Strikethrough
--- | --- | ---
**Bold Text** | *Italicized text* | ~~Strikethrough Text~~
***
