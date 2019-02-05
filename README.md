# Installation
This mod saves the Model name of the vehicle in your database so you can use it outside of FiveM/Gta

1. Copy esx_vehicleshop into resources

2. add `start esx_vehicleshop` in your server.cfg

3. Add a column to your database in the table `owned_vehicles`
`ALTER TABLE owned_vehicles
ADD modelname VARCHAR(150);
`

This resources is need to use my admin panel.
