# 1S charging board
> A compact adapter board that lets standard RC chargers safely charge 1S batteries.

{jeste neco o tom co dela}  
It supports BT2.0/A30 and XT30 connectors.  
18650 batteries are also supported with XT30 to 18650 adapter.  

## Photos
### Main PCB
![Main PCB](Images/Main%20PCB.png)
### XT30 to 18650
![XT30 to 18650](Images/XT30%20to%2018650.png)

## Motivation
I have a great RC charger (ISDT D1) and it mesures internal resistance and capacity which is awesome!  
And there are a lot of 18650 cells of unknown condititon laying in my workshop, I would like to know if they are still good or of they belong to the trash.  
Also I love RC hobby. So why not to use a universal RC charger for RC and maker stuff.  
That's why there is as main PCB with XT30 and BT2.0 connectors. And a extension board for 18650

### Design constraints
- It should work with these battery types and connctors:
    - Modular design with BT2.0 on top and XT30 on the sides for modules.
    - XT30 - Main board
    - BT2.0 / A30 Main board
    - PH2.0 - future adapters if I need them
    - 18650 batteries - XT30 to 18650
- easy to use
- A fuse - 2A Polyfuze
- 6S MAX

## BOM
| Item                       | Qty | Price | Link                                                  |
| :------------------------- | :-- | :---- | :---------------------------------------------------- |
|                            |     |       |                                                       |
| BT2.0M                     | 6   | 4.83  | https://www.aliexpress.com/item/1005004465425088.html |
| 2A Polyfuse                | 1   | 0.51  | https://www.lcsc.com/product-detail/C960026.html      |
| XT60 - Power Input         | 1   | 0.59  | https://www.lcsc.com/product-detail/C98732.html       |
| 1x7P -  Balance input      | 1   | 0.54  | https://www.lcsc.com/product-detail/C144398.html      |
| 2x07 PinHeader             | 1   | 1.4   | https://www.lcsc.com/product-detail/C2897408.html     |
| XT30M                      | 6   | 1.72  | https://www.lcsc.com/product-detail/C431092.html      |
|                            |     |       |                                                       |
| XT30F                      | 6   | 1.92  | https://www.lcsc.com/product-detail/C2913282.html     |
| 18650 holder               | 6   | 7.52  | https://www.lcsc.com/product-detail/C2988620.html     |
| LCSC Shipping              |     | 11.2  |                                                       |
| PCB fabrication + shipping | 2   | 21.9  |                                                       |
|                            |     | 52.13 |                                                       |
