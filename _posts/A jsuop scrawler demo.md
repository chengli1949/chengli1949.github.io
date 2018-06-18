#A Jsoup scrawler demo
###What we need
This project need Jsoup-1.8.1, Jfreechart-1.10.19 and Jcommon-1.0.23 to work.  
Jsuop is a open JAVA library for working with HTML.  
Jfreechart and Jcommon is libraries that helps us drawing gragh.
###How it works  
This demo grab data from [National Bureau of Statistics of the PRC 2016 annual report](http://www.stats.gov.cn/tjsj/tjbz/tjyqhdmhcxhfdm/).This report list all procince, city, county and village in China.We are going to grab these data and draw a gragh to show how many village in each province.  
Jsuop will help us get html file via web address, and all the other code analyze the html file to get village name and collect them into an arraylist.With that arraylist we can get the amount of village in each city of province in China, and darw a gragh to analyze result.  
### How run this demo ###
In order to run this demo, there are 3 major step you should follow:  
1. Download Jsoup-1.8.1, Jfreechart-1.10.19 and Jcommon-1.0.23.  
2. Refer these libraries in your JAVA project.  
3. Input the city index in your JAVA IDE console.
