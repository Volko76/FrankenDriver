
FrankenDriver (https://github.com/arutar/FrankenDriver) is a pure SCAM

You absolutly do not need to pay for his drivers, here is how to install the officials drivers :
- download the official drivers on the NVIDIA website : https://www.nvidia.com/fr-fr/geforce/drivers/   (do not use the automatic search, search manually)
- Unzip the .exe (with 7zip for exemple https://www.7-zip.org/a/7z2401-x64.exe)
- Use DDU to remove any rest of old NVIDIA driver : https://www.guru3d.com/download/display-driver-uninstaller-download/ (launch it in Safemode, it's recommanded)  RECOMMANDED but can work without
- Go to device manager, then right click on your graphic card (normally displayed as "microsoft graphical adapater"), then choose "update", then "search on my machine", then "choose in the list of driver available in my pc", then "disk", then "browse", go in the unzipped folder of the driver, then in the Display.Driver folder and select "nv_dispig.inf", then press "OK"
- Wait until it fetch all the possible GPUs and then select "1660 ti with Max-Q Design" and install it.
- Now we will redo but to install the 3060(or your gpu) laptop (cause 3060m are mobile chips) driver : Once install, go to device manager, then right click on your graphic card (normally displayed as "microsoft graphical adapater"), then choose "update", then "search on my machine", then "choose in the list of driver available in my pc", then "disk", then "browse", go in the unzipped folder of the driver, then in the Display.Driver folder and select "nv_dispig.inf", then press "OK"
- Now select the first "3060 Laptop" of the list, install it and you're done

It's based on this tutorial : https://www.youtube.com/watch?v=rmH431-OjZ4
