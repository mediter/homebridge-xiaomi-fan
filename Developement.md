"get_prop" accepts any of the following as parameters to get the property value from the physical device

"angle_enable"
"buzzer"
"child_lock"
"led_b"
"natural_level"
"power"
"speed_level"

ZhiMiDCVariableFrequencyFan and ZhiMiNaturalWindFan supports the following property.
"humidity"
"temp_dec"

for ZhiMiDCVariableFrequencyFan,
"ac_power" instead of "power" for power state
"battery" for battery level

the following methods accepts "on" / "off" as parameters
"set_angle_enable"
"set_buzzer"
"set_child_lock"
"set_natural_level"
"set_power"
"set_speed_level"

"set_led_b" accepts: 2 / 1 / 0

2 off
1 dim
0 bright