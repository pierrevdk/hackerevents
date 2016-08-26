### HackerEvents

#### Goals

The aim of this project is to provide:

* A list of upcoming events about software.
* A quick access to Call For Presentation pages.


#### Open to contribution

Feel free to add your events to the website. For that you just have to add a file in the folder corresponding to the event country.

The file format is pretty simple, see an example:

```yaml
name: FOSDEM' 17
start: 2017-02-04-10:00:00
end: 2017-02-05-18:00:00
place: ULB
address: Avenue Franklin Roosevelt 50 1050 Bruxelles
link: https://fosdem.org/
cfp: https://fosdem.org/2017/news/2016-07-20-call-for-participation/
```

To name the file simply follow this convention.
*start date*-*event name*.yml

Example: 20170204-fosdem.yml

Once your event added, the website will be rebuilt. 