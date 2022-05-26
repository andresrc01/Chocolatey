# Chocolatey
Programa Chocolatey

<h3>¿Que es chocolatey?</h3>
Chocolatey es un istalador de programas (.exe) para windows. La diferencia es que con este programa podemos instalar programas desde la linea de comandos powershell o desde la cmd.
Esta herramienta es de uso exclusivo de windows ya que viene a mejorar el sistema de instalacion que trae windows de manera muy eficaz y rapida. Con ayuda de la potencia de la powershell es capaz de instalar o actualizar un programa desde la consola.

<h3>Instalacion de chocolatey</h3>
Instalar chocolatey es muy sencillo ya que con un simple comando podremos instalarlo en el ordenador.
Solo hay que poner el siguiente comando en POWERSHELL: Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object
System.Net.Webclient).Downloadstring('https://chocolatey.org/install.ps1'))

En cambio, si estamos en cmd, el comando seria: @"%SystemRoot*\System32\WindowsPowerShell\v1.@\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.Webclient).Downloadstring('https://chocolatey.org/install.ps1°))"&&SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

Simplemente con la ejecucion de estos comandos en sus respectivas consolas y pulsando intro se instalaria de manera automatica la herramienta chocolatey.




