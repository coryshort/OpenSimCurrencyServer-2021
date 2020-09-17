# OpenSimCurrencyServer-907
For the new OpeSimulator 0.9.2.0.770+ DEV

DTL/NSL Money Server by Fumi.Iseki and NSL http://www.nsl.tuis.ac.jp , here is my test revision.

I have fixed or switched off all errors, warnings and messages.

Now you can experiment with new things without having old messages.

    This is currently being tested with:
    opensim-0.9.2.0 Dev - 770 target vs2019 prebuild 4.8
    Status works.

## copy:

copy addon-modules to addon-modules

copy bin to bin

copy helper to web (www/html/helper) - work in progress

    landtool.php works please insert the MySQL data in the landtool.php file. This landtool.php version is standalone.
    currency.php work in progress.

## Building:

### Linux: (Ubuntu 18.04 test server)

    ./runprebuild19.sh
    msbuild /p:Configuration=Release

### Windows: (Windows 10, Visual Studio 2019 Community)

    runprebuild19.bat
    start Visual studio with OpenSim.sln 
    or run compile.bat
    
Config: Robust, MoneyServer and OpenSim.

Start: 1. Robust, 2. MoneyServer, 3. OpenSim regions.

INFO: On Windows and Visual Studio, the Money Server only starts when mysql is running and config is set.