# Assignment2-komatineni
my second assignment.
# komatineni venkata sravani.
###### Ongole.

 Perhaps even more famous than its beautiful beaches are the local cattle and oxen in Ongole, Andhra Pradesh. One of the major **Zebu breeds of cattle**, the Ongole cows and bulls from this region are exported regularly, and have gone as far as North America, South America, and Europe.

But there’s more than just cows for you to see here. A beautiful, **albeit small coastal town**, Ongole has a long and interesting religious and spiritual history, dating back to 230 BCE. There are temples and inscriptions all over town proving its existence in ancient times. The **Mauryas** and the **Satavahanas** were the most prominent rulers of the region, and many of the temples and monuments that they built, still stand tall as a testament to their greatness.
    

***

## Directions from Maryville to Ongole
 
 1. Take a cab from Maryville to Kansas city
 2. Take a flight from kansas airport to Chicago airport
 3. From chicago take a flight to Doha Airport
 4. . From Doha take a flight to Hyderabad Airport
    1. from Hyderabad take a car to Ongole City

Items that can be brought to my favorite place.

- Credit and Debit Card
- Cash
- Cricket bat
- ball
- Cotton clothes

![MyImage](images/mrbean.jpg)

[Link to AboutMe](https://github.com/komatinenivs/Assignment2-komatineni/blob/6a98963ff6726b436f1467592a6fe622e0abcb8f/AboutMe.md)


| Food | Location | Money |
|:----:| :---: | :---:|
| Mysorepak| Ongole | $ 25 |
| Ismail Biryani | Ongole| $ 50 |
| pakodi | Santhapet| $ 20 |
| Samosa| Ongole| $ 10 |

***

## Quotes about life

>"You only live once, but if you do it right, once is enough.”  *Mae West*

>"There are only two ways to live your life. One is as though nothing is a miracle. The other is as though everything is a miracle.”  *Albert Einstein*

***

## Code Fencing

>This is easy to do if we go through all edges and add trapezoid areas bounded by each edge and x-axis. The area needs to be taken with sign so that the extra area will be reduced. 

[ Wiki link](https://www.wikihow.com/Calculate-the-Area-of-a-Polygon#:~:text=To%20find%20the%20area%20of%20a%20regular%20polygon%2C%20all%20you,is%20perpendicular%20to%20that%20side)

    double area(const vector<point>& fig) {  
        double res = 0;  
        for (unsigned i = 0; i < fig.size(); i++) {  
            point p = i ? fig[i - 1] : fig.back();  
            point q = fig[i];  
            res += (p.x - q.x) * (p.y + q.y);  
        }  
        return fabs(res) / 2;  
    }  

[link](https://cp-algorithms.com/geometry/area-of-simple-polygon.html)



