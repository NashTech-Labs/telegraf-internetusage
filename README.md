# telegraf-internetusage
this techhub will help  to collects data about the internet speed on the system. and store them in influx.we can also monitor through grafana
Clone Repositry and open power shell or cmd.use docker-compose up 
Open respective ports where Grafana run in my case 192...10:3000 
Add data souces influx with 192...10:8086 with default username and password as in configuration . and add panels
You will be able to see metric in grafana
![internetspeed](https://user-images.githubusercontent.com/76486190/201182858-28aeef54-70bf-4d03-a38b-a0338fb4cfff.png)
