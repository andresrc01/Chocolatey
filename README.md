# Chocolatey
Programa Chocolatey

<h3>¿Que es chocolatey?</h3>
Chocolatey es un istalador de programas (.exe) para windows. La diferencia es que con este programa podemos instalar programas desde la linea de comandos powershell o desde la cmd.
Esta herramienta es de uso exclusivo de windows ya que viene a mejorar el sistema de instalacion que trae windows de manera muy eficaz y rapida. Con ayuda de la potencia de la powershell es capaz de instalar o actualizar un programa desde la consola.

<h3>Instalacion de chocolatey</h3>
Instalar chocolatey es muy sencillo ya que con un simple comando podremos instalarlo en el ordenador.
Siguiendo unos sencillos comandos de powershell lo prodremos instalar facilmente:
1.-Abrimos la powershell como administradores.
2.-Validamos las politicas de ejecución. Con el comando "Get-ExecutionPolicy" vemos en que estado estan y lo cambiamos a AllSigned con el comando "Set-ExecutionPlocy AllSigned".
3.-Acepatamos todas las politicas con la tecla "o"
4.-Copiamos el comando de instslacion y lo ejecutamos con la tecla intro y esperamos que se intale correctamente.
5.-Ya tenemos instalado chocolatey, simplemente poniendo el comando "choco" debemos ver la version que tenemos de chocolatey
Simplemente con la ejecucion de estos comandos en sus respectivas consolas y pulsando intro se instalaria de manera automatica la herramienta chocolatey.

(https://user-images.githubusercontent.com/94164319/170518578-8a59fa6e-fd64-49bd-89b4-82bf52967fb8.PNG)

<h3>Ejemplo de instalacion</h3>
Esta herramienta es muy sencilla y intuitiva y el comando para instalar las aplicaciones es tan facil como "choco install 'nombre_del_programa'". Este programa tambien nos proporciona un repositorio de nuevas herramientas que se pueden instalar con chocolatey y de que manera se instalan (Viene el comando a ejecutar).Como ejemplo, yo voy a instalar el programa CCleaner con el comando "choco install cccleaner"

(https://user-images.githubusercontent.com/94164319/170518157-be611f23-87ad-4f96-b2c8-5e4e4605dbad.PNG)





