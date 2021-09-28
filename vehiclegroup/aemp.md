Example Request:

https://api.gpsinsight.com/v2/vehiclegroup/aemp?session_token=xxxx&vehicle=Truck240&vehicle_group=Delivery

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
    