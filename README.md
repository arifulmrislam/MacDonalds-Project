## Monitoring, Controlling and Cost reducing: Energy, Water and Gas consumption
### IoT Solution by LoRaWAN for [***McDonald’s restaurants***](https://www.mcdonalds.ro/restaurante)
---
<div style="text-align: justify">We have been working on a proof of concept since last year. McDonald's was offered a way to reduce their energy consumption. They also consume other things like water, gas, etc. We installed the LoRaWAN network in one of their restaurants. We initially used five Eastron energy meters to collect different energy-related data and observe the average consumption over twenty-four hours. We set a threshold that if the energy consumption is more than the set limit, it will create a notification and send it by mail. By getting this notification, customers will be informed about their unnecessary consumption. They can save 15% to 20% on their total energy costs this way. We use the famous IoT platform Thingsboard and LoRaWAN based sensors. This year they approved our proof of concept, and we are now working with their other restaurants in Romania.</div><br>

<div style="text-align: justify">We split our project into two categories one is the hardware part, and the other is the software part. We work as a five-person team. One of my colleagues and I are working on the software part. We prepare the device configurations to connect with the lorawan gateway and send data to the network server. We use the chirpstack network server in this solution. The lorawan gateway sends data to the network server in encrypted mode. After receiving the payload, we write JavaScript code to decode the values as device documentation. When we get the correct values after decoding, we integrate the values into the application server which is thingsboard io. In thingsboard we will get all values in the device’s latest telemetry. From telemetry, we can redirect the values to the dashboard and create a beautiful dashboard for data visualization. Meanwhile, we can create a rule chain to process the values, like data aggregation, daily and monthly consumption and send an alarm to customers in a critical situation and so on.
</div> <br>
---
### Final Dashboard

<img src= "IMG/Mcdonalds dashboard.png" width=800>

---
### Project Agenda:

-	To monitor and control the Energy consumption,

- Indoor and Outdoor temperature and humidity, 

- People counting, 

- Water and Gas consumption. 
---

### Technologies:

`Famouse IoT platform (SaaS)` `ChirpStack Network server` `MQTT` `HTTP` `LoRaWAN network` `PostgreSQL (free and open-source relational database) `

### Hardware:

`Dragino rs485 to lorawan converter` `Eastron energy meter` `Mikrotik Gateway` `internet switch access port` `LoRa temperature sensor (Adeunis)` `Natural gas meter`
`Water meter (Bmeter)` `Tetrapolar circuit breaker` `current transformer`

---

### Restaurant plan:

<div style="text-align: justify">With the restaurant plan, it is easy for us to figure out where we will set all the devices. We need a strong Wi-Fi connection with no interruption. LoRaWAN networks cannot function without the internet. Also, we haven't any right to change their main design so we have to consider a lot of things with the existing design.<div><br>

<img src= "IMG/Restaurant plan.png" width=800>
  
  ---

🚩 Connect with me on social
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/ariful-islam-arif-2987b51a3/)
- Twitter: [Twitter](https://twitter.com/arifulislam301)
- Instagram: [Instagram](https://www.instagram.com/ariful_mr_islam/)

🔔 Subscribe to my YouTube channel: [YouTube](https://www.youtube.com/channel/UCED68cm6nHaAlAk0h9I3yAQ)
