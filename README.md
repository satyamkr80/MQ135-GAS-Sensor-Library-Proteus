# MQ135 GAS Sensor Library for Proteus
![MQ135 Cover](https://user-images.githubusercontent.com/46389631/158180120-b73300f6-2fd1-4196-9330-287b75797e46.png)

## Introduction
**MQ135 Gas Sensor** is an industrial level sensor that is suitable for detecting NH3, NOx, Alcohol, Benzene, Smoke, CO2, etc. Mostly used for sensing smoke from a fire, this sensor is a critical part in Arduino projects that involve fire sensing and air quality measuring. One of the biggest advantages of using it is the relative ease at which it can be used. Thus, it is helpful to simulate it on Proteus when developing a circuit. This Github project will provide the necessary files to add the **MQ 135 Gas Sensor** to your Proteus project.

[Datasheet](https://www.olimex.com/Products/Components/Sensors/Gas/SNS-MQ135/resources/SNS-MQ135.pdf)

## How to Add the Library
1. First download the Github repository as a zip file. To do this, click on 'Code', then 'Download ZIP'. A zip file will be downloaded.
2. Extract the zip file by right clicking and *'Extract All' >> 'Extract'*.
3. Now go to the extract folder. There will be five files: **README.md**, **MQ135.LIB**, **MQ135.IDX**, **MQ135.hex** and **LICENSE**.
4. Go to *'C:\ProgramData\Labcenter Electronics\Proteus 8 Professional\LIBRARY'* folder. `NOTE: This folder might be hidden in the file system. In that case, check 'View' >> 'Hidden Items'.`
5. Copy the **MQ135.LIB** and **MQ135.MDX** files here.
6. Save the **MQ135.hex** file in a known location; probably your Proteus project folder.

## How to Use the Library
1. In Proteus, go to *'Component Mode'* and click on *'Pick from Library'*.
2. Search for **MQ135** and select the *'Gas Sensor'* listed.
3. Click *'Ok'* and add it to the canvas.
4. Double click on it or right click on the device >> select *'Edit Properties'*.
5. Under *'Program File'*, select the folder icon and locate the **MQ135.hex** file we saved earlier.
6. Select it and click *'Ok'*.
7. Click *'Ok'* to close the 'Properties window'.

> This library is shared under the GPL-3.0 License. For more information, read the [License](https://github.com/satyamkr80/MQ135-GAS-Sensor-Library-Proteus/blob/main/LICENSE).
=======
# MQ135-GAS-Sensor-Library-Proteus

A proteus library to simulate MQ135 Gas sensor.

