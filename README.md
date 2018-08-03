# Seating-Layout-Sample

This project is sample app for Android it generates a dynamic layout for booking seats.


![seat layout sample](https://user-images.githubusercontent.com/24667361/43626651-787094d2-9710-11e8-97c2-0ceb4db5b719.gif)

To create the layout dynamically we need to pass specific syntax in string so the method could understand and process it. 

```java
String seats =        "_UUUUUUAAAAARRRR_/"
                    + "_________________/"
                    + "UU__AAAARRRRR__RR/"
                    + "UU__UUUAAAAAA__AA/"
                    + "AA__AAAAAAAAA__AA/"
                    + "AA__AARUUUURR__AA/"
                    + "UU__UUUA_RRRR__AA/"
                    + "AA__AAAA_RRAA__UU/"
                    + "AA__AARR_UUUU__RR/"
                    + "AA__UUAA_UURR__RR/"
                    + "_________________/"
                    + "UU_AAAAAAAUUUU_RR/"
                    + "RR_AAAAAAAAAAA_AA/"
                    + "AA_UUAAAAAUUUU_AA/"
                    + "AA_AAAAAAUUUUU_AA/"
                    + "_________________/";
```
As for this sample we have used 3 status for the seats :

> _ is for empty space
> U is for already booked seats
> R is for reserved seats
> A is for available seats

**You can customize this string according to your seats arrangement**

**Reserved seats VS Booked seats**
Both can't be booked but we are showing them with seperates colors cause the reserved seats can be available with time.

**Limitation:**
It's not recycling the views.

### About Me
Varun John
Sr. Android Developer
varunjohn1990@gmail.com
Follow me on Instagram [varunjohn1990](https://www.instagram.com/varun.john.1990/)
