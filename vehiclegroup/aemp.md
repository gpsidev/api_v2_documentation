Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/aemp?session_token=xxxx&vehicle=Truck240&vehicle_group=Delivery

This data adheres to the AEMP standard for formatting telematics data. 
See: http://docplayer.net/47523189-Aemp-telematics-data-standard-v1-0.html. 
This standard is often used by OEMs of heavy machinery. 
This endpoint will return data from all tracking devices in the AEMP format, not just OEM data.

NOTE: Because AEMP is a specific XML format, you cannot override the output formatting with a formatting qualifier
such as `/v2/vehiclegroup/aemp/json`. 

Example Response:
```xml
<?xml version="1.0"?>
<Fleet version="1.2" snapshotTime="2021-09-28T17:50:35+00:00" xmlns="http://schemas.aemp.org/fleet">
    <Equipment>
        <EquipmentHeader>
            <UnitInstallDateTime>2019-10-10T16:35:00+00:00</UnitInstallDateTime>
            <Make>Toyota</Make>
            <Model>Sienna</Model>
            <EquipmentID>5TDKK3DC4BS123422</EquipmentID>
            <SerialNumber>4572072000</SerialNumber>
        </EquipmentHeader>
        <Location datetime="2021-09-28T15:22:29+00:00">
            <Latitude>37.292291</Latitude>
            <Longitude>-121.7623408</Longitude>
            <Altitude>
                <Meters>0</Meters>
            </Altitude>
            <AltitudeUnits>meters</AltitudeUnits>
        </Location>
        <CumulativeOperatingHours datetime="2021-09-28T15:22:29+00:00">
            <Hour>PT13H28M30S</Hour>
        </CumulativeOperatingHours>
        <Distance datetime="2021-09-28T15:22:29+00:00">
            <OdometerUnits>miles</OdometerUnits>
            <Odometer>203928.3</Odometer>
        </Distance>
    </Equipment>
    <Equipment>
        <EquipmentHeader>
            <UnitInstallDateTime>2020-10-09T21:10:00+00:00</UnitInstallDateTime>
            <Make>GMC</Make>
            <Model>Yukon Denali</Model>
            <EquipmentID>1GKS1MEF3CR123457</EquipmentID>
            <SerialNumber>4674929000</SerialNumber>
        </EquipmentHeader>
        <Location datetime="2021-09-28T15:35:31+00:00">
            <Latitude>33.9196603</Latitude>
            <Longitude>-98.295121</Longitude>
            <Altitude>
                <Meters>0</Meters>
            </Altitude>
            <AltitudeUnits>meters</AltitudeUnits>
        </Location>
        <CumulativeOperatingHours datetime="2021-09-28T15:35:31+00:00">
            <Hour>P1DT7H2M3S</Hour>
        </CumulativeOperatingHours>
        <Distance datetime="2021-09-28T15:35:31+00:00">
            <OdometerUnits>miles</OdometerUnits>
            <Odometer>116503.2</Odometer>
        </Distance>
    </Equipment>
</Fleet>
```
    