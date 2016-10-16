<link id="linkstyle" rel="stylesheet" href="../foghorn.css">
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">

# Processing intro :  Coding Pirates DIKU



## Streg tegninger
Tast følgende eksempel ind:
```javascript
ellipse(200, 200, 150, 150);
ellipse(135, 125, 75, 75);
ellipse(260, 130, 75, 75);
```
### Eller prøv i stedet:
```javascript
rect(50,100,300,200);
ellipse(200,200,100,100);
rect(270,110,70,40);
rect(70,95,30,5);
```

### Eller:
``` javascript
triangle(200,150,250,280,150,280);
ellipse(200,115,70,70);

line(183,191,146,174);
line(217,191,254,174);
line(180,280,180,300);
line(220,280,220,300);
```

Prøv at tegne en bil:

![bil](pics/bil-streg.png)

# Farver
Farvelæg tegningerne med `fill`-kommandoen. Det handler om at
sætte `fill` ind det rigtige sted!
```javascript
fill(0,0,0);       // sort
fill(255,0,0);     // rød
fill(0,255,0);     // grøn
fill(0,0,255);     // blå
fill(255,255,0);   // gul
fill(255,255,255); // hvid
```

![bil](pics/bil-farvet.png) ![Mickey](pics/mickey_simpel.png)


### Prøv også kommandoen:
```javascript
  noStroke();
```

## Opgaver
* Kan du tegne en blomst?

![](pics/blomst.png)

* En pingvin?

![](pics/pingvin.png)

* Pikachu?

![](pics/pikachu.png)
