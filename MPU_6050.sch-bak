EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 2 2
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Sensor_Motion:MPU-6050 U3
U 1 1 5FE2AE53
P 5450 3475
F 0 "U3" H 5875 4025 50  0000 C CNN
F 1 "MPU-6050" H 5775 2925 50  0000 C CNN
F 2 "Housings_DFN_QFN:QFN-24_4x4mm_Pitch0.5mm" H 5450 2675 50  0001 C CNN
F 3 "https://store.invensense.com/datasheets/invensense/MPU-6050_DataSheet_V3%204.pdf" H 5450 3325 50  0001 C CNN
	1    5450 3475
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C22
U 1 1 5FE2AF4B
P 7500 4000
F 0 "C22" H 7592 4046 50  0000 L CNN
F 1 "2.2nF" H 7592 3955 50  0000 L CNN
F 2 "Capacitors_SMD:C_0603" H 7500 4000 50  0001 C CNN
F 3 "~" H 7500 4000 50  0001 C CNN
	1    7500 4000
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C21
U 1 1 5FE2AFCE
P 6325 4000
F 0 "C21" H 6417 4046 50  0000 L CNN
F 1 "33nF" H 6417 3955 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 6325 4000 50  0001 C CNN
F 3 "~" H 6325 4000 50  0001 C CNN
	1    6325 4000
	1    0    0    -1  
$EndComp
Wire Wire Line
	6150 3775 6325 3775
Wire Wire Line
	6325 3775 6325 3900
$Comp
L power:GND #PWR0101
U 1 1 5FE2B070
P 6325 4525
F 0 "#PWR0101" H 6325 4275 50  0001 C CNN
F 1 "GND" H 6330 4352 50  0000 C CNN
F 2 "" H 6325 4525 50  0001 C CNN
F 3 "" H 6325 4525 50  0001 C CNN
	1    6325 4525
	1    0    0    -1  
$EndComp
Wire Wire Line
	5450 4175 5450 4375
Wire Wire Line
	5450 4375 6325 4375
Wire Wire Line
	6325 4375 6325 4525
Wire Wire Line
	6325 4100 6325 4175
Connection ~ 6325 4375
$Comp
L Device:C_Small C20
U 1 1 5FE2B293
P 4075 2500
F 0 "C20" H 4167 2546 50  0000 L CNN
F 1 "33nF" H 4167 2455 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 4075 2500 50  0001 C CNN
F 3 "~" H 4075 2500 50  0001 C CNN
	1    4075 2500
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR0102
U 1 1 5FE2B4D5
P 3675 2225
F 0 "#PWR0102" H 3675 2075 50  0001 C CNN
F 1 "+3.3V" H 3690 2398 50  0000 C CNN
F 2 "" H 3675 2225 50  0001 C CNN
F 3 "" H 3675 2225 50  0001 C CNN
	1    3675 2225
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C19
U 1 1 5FE2B593
P 3675 2500
F 0 "C19" H 3767 2546 50  0000 L CNN
F 1 "10nF" H 3767 2455 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 3675 2500 50  0001 C CNN
F 3 "~" H 3675 2500 50  0001 C CNN
	1    3675 2500
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0103
U 1 1 5FE2B737
P 3675 2675
F 0 "#PWR0103" H 3675 2425 50  0001 C CNN
F 1 "GND" H 3680 2502 50  0000 C CNN
F 2 "" H 3675 2675 50  0001 C CNN
F 3 "" H 3675 2675 50  0001 C CNN
	1    3675 2675
	1    0    0    -1  
$EndComp
Wire Wire Line
	3675 2225 3675 2325
Wire Wire Line
	3675 2325 4075 2325
Wire Wire Line
	4075 2325 4075 2400
Connection ~ 3675 2325
Wire Wire Line
	3675 2325 3675 2400
Wire Wire Line
	3675 2600 3675 2675
Wire Wire Line
	3675 2675 4075 2675
Wire Wire Line
	4075 2675 4075 2600
Connection ~ 3675 2675
Connection ~ 4075 2325
$Comp
L power:GND #PWR0104
U 1 1 5FE2D18A
P 4600 3825
F 0 "#PWR0104" H 4600 3575 50  0001 C CNN
F 1 "GND" H 4605 3652 50  0000 C CNN
F 2 "" H 4600 3825 50  0001 C CNN
F 3 "" H 4600 3825 50  0001 C CNN
	1    4600 3825
	1    0    0    -1  
$EndComp
Wire Wire Line
	4600 3825 4600 3775
Wire Wire Line
	4600 3775 4750 3775
Text GLabel 6150 3375 2    50   Input ~ 0
AUX_SDA
Text GLabel 6150 3475 2    50   Input ~ 0
AUX_SCL
Wire Wire Line
	4750 3675 4600 3675
Wire Wire Line
	4600 3675 4600 3775
Connection ~ 4600 3775
Text GLabel 6150 3175 2    50   Input ~ 0
INT
Text GLabel 4750 3175 0    50   Input ~ 0
SDA
Text HLabel 2425 1675 0    50   BiDi ~ 0
SDA
Text HLabel 2425 1800 0    50   BiDi ~ 0
SCL
Text HLabel 2425 2050 0    50   BiDi ~ 0
AUX_SDA
Text HLabel 2425 2175 0    50   BiDi ~ 0
AUX_SCL
Text HLabel 2425 2400 0    50   Output ~ 0
INT
Text GLabel 2425 1675 2    50   Input ~ 0
SDA
Text GLabel 2425 1800 2    50   Input ~ 0
SCL
Text GLabel 2425 2400 2    50   Input ~ 0
INT
Text GLabel 2425 2050 2    50   Input ~ 0
AUX_SDA
Text GLabel 2425 2175 2    50   Input ~ 0
AUX_SCL
Wire Notes Line
	1775 1475 1775 2625
Wire Notes Line
	1775 2625 3075 2625
Wire Notes Line
	3075 2625 3075 1475
Wire Notes Line
	3075 1475 1775 1475
Text Notes 1775 1450 0    50   ~ 0
Hierarchical Labels
Wire Wire Line
	4750 3375 4600 3375
Wire Wire Line
	4600 3375 4600 3675
Connection ~ 4600 3675
Text Notes 3375 3725 0    50   ~ 0
By pulling the AD0 pin low,\nthe I2C address of\nthe MPU_6050 is\neffectively: 0b1101000
Wire Wire Line
	4075 2325 4500 2325
$Comp
L Device:C_Small C23
U 1 1 5FE3C4EF
P 4500 2500
F 0 "C23" H 4592 2546 50  0000 L CNN
F 1 "33nF" H 4592 2455 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 4500 2500 50  0001 C CNN
F 3 "~" H 4500 2500 50  0001 C CNN
	1    4500 2500
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C24
U 1 1 5FE3C516
P 4900 2500
F 0 "C24" H 4992 2546 50  0000 L CNN
F 1 "33nF" H 4992 2455 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 4900 2500 50  0001 C CNN
F 3 "~" H 4900 2500 50  0001 C CNN
	1    4900 2500
	1    0    0    -1  
$EndComp
Wire Wire Line
	4500 2325 4500 2400
Connection ~ 4500 2325
Wire Wire Line
	4900 2325 4900 2400
Wire Wire Line
	4500 2325 4900 2325
Wire Wire Line
	4900 2600 4900 2675
Wire Wire Line
	4900 2675 4500 2675
Connection ~ 4075 2675
Wire Wire Line
	4500 2600 4500 2675
Connection ~ 4500 2675
Wire Wire Line
	4500 2675 4075 2675
Wire Wire Line
	4900 2325 5350 2325
Wire Wire Line
	5350 2325 5350 2775
Connection ~ 4900 2325
Wire Wire Line
	5350 2325 5550 2325
Wire Wire Line
	5550 2325 5550 2775
Connection ~ 5350 2325
Text Notes 4125 2200 0    50   ~ 0
The 3 33nF caps are equivalent to\nthe one 0.1uF cap that the manufacturer\nsuggests.
$Comp
L Device:C_Small C25
U 1 1 5FE40448
P 6750 4000
F 0 "C25" H 6842 4046 50  0000 L CNN
F 1 "33nF" H 6842 3955 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 6750 4000 50  0001 C CNN
F 3 "~" H 6750 4000 50  0001 C CNN
	1    6750 4000
	1    0    0    -1  
$EndComp
$Comp
L Device:C_Small C26
U 1 1 5FE4049E
P 7125 4000
F 0 "C26" H 7217 4046 50  0000 L CNN
F 1 "33nF" H 7217 3955 50  0000 L CNN
F 2 "Capacitors_SMD:C_0402" H 7125 4000 50  0001 C CNN
F 3 "~" H 7125 4000 50  0001 C CNN
	1    7125 4000
	1    0    0    -1  
$EndComp
Wire Wire Line
	7500 3675 7500 3900
Wire Wire Line
	6750 4100 6750 4175
Wire Wire Line
	6750 4175 6325 4175
Connection ~ 6325 4175
Wire Wire Line
	6325 4175 6325 4375
Wire Wire Line
	6750 4175 7125 4175
Wire Wire Line
	7125 4175 7125 4100
Connection ~ 6750 4175
Wire Wire Line
	7500 4100 7500 4175
Wire Wire Line
	7500 4175 7125 4175
Connection ~ 7125 4175
Wire Wire Line
	6150 3675 7500 3675
Wire Wire Line
	6325 3775 6750 3775
Wire Wire Line
	6750 3775 6750 3900
Connection ~ 6325 3775
Wire Wire Line
	7125 3900 7125 3775
Wire Wire Line
	7125 3775 6750 3775
Connection ~ 6750 3775
Text Notes 6600 4525 0    50   ~ 0
The 3 33nF caps are equivalent to\nthe one 0.1uF cap that the manufacturer\nsuggests.
Text GLabel 4750 3275 0    50   Input ~ 0
SCL
$EndSCHEMATC
