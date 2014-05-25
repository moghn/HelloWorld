echo off
cls
mode con cols=30 lines=15
title calc by ming
color 1b
:a
cls
set /p x= &&set /p w=  &&set /p y=  
set /a s=%x%%w%%y%
echo %x%%w%%y%=%s%
pause >nul
goto :a
