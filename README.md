# Battery charging/consume curcuit for Dehler 39, Frk. Jensen

## Start battery
Start battery is connected to motorgnd only if motor switch is connected.
It is charged solely by Alternator.

## House-bank
House-bank batteries are constantly connected to Motorgnd.
House-bank switch connects/disconnects the 'consumer' ground. I.e. all correctly
connected 'consumers' are powered only when House bank switch is on.
Diesel heater is one known consumer not using 'consumer ground'

House-bank can be charged in 3 ways: 
- From Alternator through start relay and DC/DC
- From Solar
- From Shore charger

Housebank DC/DC will start charging only if voltage on input is above 13.5
to ensure start battery gets fully charged first.

Solar is directly connected to one of the batteries, while shore charger is connected in the switchboard panel. DauerMinus is the same as MotorGnd

House-bank batteries are of type LiFePO4. Other batteries are old school lead 
batteries.

Ideally wires from house bank batteries should all be of same length and go to 
common junctions (plus and minus) before going to other places

## Thruster battery
Thruster battery is charged from housebank through a DC/DC
The threshold must be very low (13V or less maybe) to ensure it always gets
charged if needed - doesn't matter state of house bank

The total power consumed by thruser is considered neglible compared to the
house bank power available

The DC/DC can be isolated if that's easier to fit in.
