# Defibrillators
(python)
```.py

import sys
import math

# the longtitude and the latitude are both float, 
# we also replace the comma "," with a dot "."
lon = float(input().replace(",","."))
lat = float(input().replace(",","."))
n = int(input())
nearestPoint = -1
dif = ""
for i in range(n):
    defib = input()
    _, name, _, _, lond, latd = defib.split(";") # the defib is split by ";" to create separation
    lond, latd = float(lond.replace(",",".")), float(latd.replace(",",".")) # replacing the comma with a dot
    # distance equation to find the distance that the user is from each defib
    x = (lond -lon ) * math.cos((lat + latd)/2) 
    y = latd - lat
    d = ((x*x+y*y)**0.5) * 6371
    # checking if the distance is less than the nearest defit or point
    if d<nearestPoint or nearestPoint == -1:
        dif = name
        nearestPoint = d
# print the nearest defit when foud
print(dif)

```
(Javascript) - this code is from anatol (Styled JavaScript)

```.js


// replacing the comma with a dot to make make it float
// the first Longt and Lat
const LongtA = parseFloat(readline().replace(",",".")); 
const LatA = parseFloat(readline().replace(",","."));
const N = parseInt(readline());
let DEFIB = []; // creating a store for our array
let destination = Infinity; // keeping the destination infinity because we want it to not have limits
let Npoint = -1;
let x = 0; // x cordinate
let y = 0; // y cordinate
let d = 0; // d cordinate
// the second Longt and Lat
let LongtB = 0; 
let LatB = 0;

for (let i = 0; i < N; i++) { // this loop will continue until the nearest defibrillator
    DEFIB[i] = readline().split(";"); // split the defib according to the ";" so that we have separate data
    DEFIB[i][4] = parseFloat(DEFIB[i][4].replace(",",".")) 
    DEFIB[i][5] = parseFloat(DEFIB[i][5].replace(",","."))

    // this section calculates the math to find the nearest defib by using cos and then 
    // squaring the outcome which then is multiplied by 6371.
    // this is for distance
    LongtB = DEFIB[i][4];
    LatB = DEFIB[i][5];
    x = (LongtB - LongtA) * Math.cos((LatA + LatB)/2);
    y = LatB - LatA;
    d = Math.sqrt(Math.pow(x, 2) + Math.pow(y, 2)) * 6371;
    // checking if the distance is less than the destination
    // if yes then, then the destination is shifted to the d and the nearest defit is found
    if (d < destination){
        destination = d;
        Npoint = i
    }
    printErr('${i}: ${x}, ${y}. ${d}, ${destination}, ${Npoint}');

}
print(DEFIB[Npoint][1])

```

# Chuck Norris

```js
var MESSAGE = readline(); // read the lines or the message

var res = ""; // defining this variable hold a
var pre = -1;

for (var i = 0; i < MESSAGE.length; i++) {

    for (var j = 6; j >= 0; j--) {
        // conerting the text into binary
        var bit = MESSAGE.charCodeAt(i) >> j & 1;
        if (bit !== pre) {
                // checking if the text is not equal to pre which is negative 1
            if (-1 !== pre) {
                res+= " ";
            }
            // assing res to hold 1 as 0 and 0 as 00
            res+= 1 == bit ? "0 " : "00 ";
            pre = bit;
        }
        res+= "0";
    }
}
print(res);


```
