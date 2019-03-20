# The Data

### Airline safety data

The raw data behind the story [Should Travelers Avoid Flying Airlines That Have Had Crashes in the Past?](http://fivethirtyeight.com/features/should-travelers-avoid-flying-airlines-that-have-had-crashes-in-the-past/)

| Header                   | Definition                               |
| ------------------------ | ---------------------------------------- |
| `airline`                | Airline (asterisk indicates that regional subsidiaries are included) |
| `avail_seat_km_per_week` | Available seat kilometers flown every week |
| `incidents_85_99`        | Total number of incidents, 1985–1999     |
| `fatal_accidents_85_99`  | Total number of fatal accidents, 1985–1999 |
| `fatalities_85_99`       | Total number of fatalities, 1985–1999    |
| `incidents_00_14`        | Total number of incidents, 2000–2014     |
| `fatal_accidents_00_14`  | Total number of fatal accidents, 2000–2014 |
| `fatalities_00_14`       | Total number of fatalities, 2000–2014    |

Source: [Aviation Safety Network](http://aviation-safety.net)

# The Project

#### *The goal of the project was to extract insights from the data and communicate these insights.*

I used [Jupyter Notebook](http://jupyter.org/) (the file called 'Airline Safety.ipynb' above is a Jupyter Notebook, which is rendered by GitHub so you can view it inside GitHub) with the following *Python* libraries: *[Pandas](https://pandas.pydata.org/), [Seaborn](https://seaborn.pydata.org/), [Matplotlib](https://matplotlib.org/), [NumPy](http://www.numpy.org/)*.



The most interesting observations I found were:

* By comparing the fatalities between 1985-1999, 2000-2014 and 1985-2014, it was clear that something really serious happened with most of the companies listed as the ones with the most number of fatalities during those periods. Many serious accidents were related to those numbers. ***You can see more details about this in the Jupyter Notebook ('Airline Safety.ipynb'). The main accidents that called my attention are also listed below.***
* The number of **incidents** reduced **42,53%**, comparing 1985-1999 to 2000-2014.
* The number of **fatal accidents** reduced **69,67%** comparing 1985-1999 to 2000-2014.
* The number of **fatalities** reduced **50,61%** comparing 1985-1999 to 2000-2014.

### The accidents that caught my eye (This is all in the Jupyter Notebook 'Airline Safety.ipynb')

#### Japan Airlines

**Japan Airlines only had 1 fatal accident, and it was the accident that had 520 fatalities. This one accident alone made Japan Airlines the third airline with most fatalities from 1985-2014.**

**By looking it up on google, I found out that it refers to Japan Airlines Flight 123.**

Read more about it: https://en.wikipedia.org/wiki/Japan_Airlines_Flight_123

It is also interesting to note that Japan Airlines only had 3 incidents in total, and they were all during 1985-1999. Nothing really happened during 2000-2014.

#### Malaysia Airlines

After doing some research:

* Malaysia Airlines Flight 2133 (34 fatalities)

Crashed due to pilot error on 15 September 1995, taking the lives of 32 of the 49 passengers and 2 of the 4 crew on board. 

Source: https://en.wikipedia.org/wiki/Malaysia_Airlines_Flight_2133 

* Malaysia Airlines Flight 370 (239 fatalities presumed)

The aircraft disappeared from air traffic controllers' radar screens at 01:22 MYT, but was still tracked on military radar as it deviated westwards from its planned flight path and crossed the Malay Peninsula, until it left the range at 02:22 while over the Andaman Sea, 200 nautical miles (370 km) north-west of Penang in north-western Malaysia. The aircraft was carrying 12 Malaysian crew members and 227 passengers from 15 nations.


**Interesting fact: With the loss of all 239 on board, Flight 370 is the second deadliest incident involving a Boeing 777 and the second deadliest incident in Malaysia Airlines' history, behind Flight 17(next one) in both categories.**

Source: https://en.wikipedia.org/wiki/Malaysia_Airlines_Flight_370

* Malaysia Airlines Flight 17 (298 fatalities)

Malaysia Airlines Flight 17 (MH17/MAS17)[a] was a scheduled passenger flight from Amsterdam to Kuala Lumpur that was shot down on 17 July 2014 while flying over eastern Ukraine, killing all 283 passengers and 15 crew on board.

Source: https://en.wikipedia.org/wiki/Malaysia_Airlines_Flight_17 

## Interesting Charts and Diagrams

### Incidents

![top_nincidents_85_14](top_nincidents_85_99.png)





![top_nincidents_00_14](top_nincidents_00_14.png)





![top_nincidents_85_14](top_nincidents_85_14.png)

### Fatal Accidents

![top_nfatalacc_85_99](top_nfatalacc_85_99.png)





![top_nfatalacc_00_14](top_nfatalacc_00_14.png)



![top_nfatalacc_85_14](top_nfatalacc_85_14.png)



### Fatalities

![top_nfatalities_85_99](top_nfatalities_85_99.png)



![top_nfatalities_00_14](top_nfatalities_00_14.png)



![top_nfatalities_85_14](top_nfatalities_85_14.png)



