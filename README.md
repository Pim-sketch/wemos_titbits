# wemos_titbits
All kind of Wemos stuff
One thing that took me long to find was that updating a ThingSpeak channel makes use of port 80. If you then also define a webserver on port 80 you have a problem. Practical is to make the webserver use port 81, although I did not like the fact that one then has to type :81 in each address when trying to access the page.
