#Yeelight-Bulb-scenes

- pseudo code for the scenes used in the Android yeelight app (scenes taken for the yeelight color bulb) 
- this code is used for my Fibaro virtual devices (some color and mono bulbs)  (lua)
- for more information about the API, refer to [Yeelight WiFi Light Inter-Operation Specification](https://www.yeelight.com/en_US/developer)


Scenes for the Philips Hue equivalent from Xiaomi Corp. China
-

Sunrise
-
- simulate a natural and gentle sunrise in 15 minutes

{"method":"props","params":{"flowing":1}}
{"method":"props","params":{"flow_params":"3,1,50,1,16731392,1,360000,2,1700,10,540000,2,2700,100"}}

SunSet
-
- simulate a natural sunset and offering relaxing dimming to help you sleep in 10 minutes

{"method":"props","params":{"flowing":1}}
{"method":"props","params":{"flow_params":"3,2,50,2,2700,10,180000,2,1700,5,420000,1,16731136,1"}}

Romance
-
- romantic lights

{"method":"props","params":{"flowing":1}}
{"method":"props","params":{"flow_params":"0,1,4000,1,5838189,1,4000,1,6689834,1"}}

Night mode
-
{"method":"props","params":{"flowing":0}}
{"method":"props","params":{"color_mode":1}}
{"method":"props","params":{"rgb":16750848,"flowing":0,"bright":1}}

Home
-
{"method":"props","params":{"flowing":0}}
{"method":"props","params":{"color_mode":2}}
{"method":"props","params":{"ct":3200,"bright":80}}

Dating Night
--
{"method":"props","params":{"flowing":0}}
{"method":"props","params":{"color_mode":1}}
{"method":"props","params":{"rgb":16737792,"bright":50}}

Happy Birthday
-
{"method":"props","params":{"flowing":1}}
{"method":"props","params":{"flow_params":"0,1,1996,1,14438425,80,1996,1,14448670,80,1996,1,11153940,80"}}

Movie
-
{"method":"props","params":{"flowing":0}}
{"method":"props","params":{"color_mode":1}}
{"method":"props","params":{"rgb":1315890,"bright":50}}

Candle Flicker
-
{"method":"props","params":{"flowing":1}}
{"method":"props","params":{"flow_params":"0,0,800,2,2700,50,800,2,2700,30,1200,2,2700,80,800,2,2700,60,1200,2,2700,90,2400,2,2700,50,1200,2,2700,80,800,2,2700,60,400,2,2700,70"}}
