Adapters for Bosch sensors in their "shuttle" format

https://www.bosch-sensortec.com/bst/support_tools/application_boards/overview_application_boards

Standard size: 20.32x43.18 ? 100 mil header like wide DIP28 package 



Shuttle fits into single CRUVI - use HS interface always this would allow variable VCCIO support and connection to all pins

List of known boards

|IC|COD|VDD|VDDIO|
|--|---|--|--|
|BMX160|011011000|1.7-3.6|1.2-3.6|
|BMI270+BMM150|110111000|1.6-3.3|1.6-3.3|
|BMI085||||
|BMF055||||

BMF055 is special it is SiP with Cortex MCU (SAMD20) also adds empty location and 1 more pins for SWD debug

Info links
https://www.mouser.de/datasheet/2/783/BST-BMF055-AN001-1509581.pdf

