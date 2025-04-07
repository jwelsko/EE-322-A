# Lab 5
## CPE 322-A

Install the paho-mqtt library:
```bash
(venv) bdx@bdx-dev4:~/stevens/iot/lesson5$ pip3 install paho-mqtt
Collecting paho-mqtt
  Downloading paho_mqtt-2.1.0-py3-none-any.whl (67 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 67.2/67.2 KB 809.5 kB/s eta 0:00:00
Installing collected packages: paho-mqtt
Successfully installed paho-mqtt-2.1.0
```

Run the subcpu.py script:
```bash
(venv) bdx@bdx-dev4:~/stevens/iot/lesson5$ python3 subcpu.py
/home/bdx/stevens/iot/lesson5/subcpu.py:8: DeprecationWarning: Callback API version 1 is deprecated, update to latest version
  client = mqtt.Client(mqtt.CallbackAPIVersion.VERSION1)
Connected with result code 0
MyCPU 2025-04-07 10:01:08
MyCPU CPU Usage:   7.8 %
```

Run the pubcpu.py script:
```bash
(venv) bdx@bdx-dev4:~/stevens/iot/lesson5$ python3 pubcpu.py
/home/bdx/stevens/iot/lesson5/pubcpu.py:6: DeprecationWarning: Callback API version 1 is deprecated, update to latest version
  mqttc = mqtt.Client(mqtt.CallbackAPIVersion.VERSION1)
2025-04-07 10:01:08
CPU Usage:   7.8 %
2025-04-07 10:01:18
CPU Usage:   20.3 %
2025-04-07 10:01:28
CPU Usage:   18.0 %
```

In the above example, the pubcpu.py script publishes the CPU usage to the MQTT broker. The subcpu.py script subscribes to the CPU usage topic and prints the CPU usage to the console.


