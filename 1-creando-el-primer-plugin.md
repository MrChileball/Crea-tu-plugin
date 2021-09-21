
# Instalar eclipseIDE

para esta guia usaré eclipseIDE porque el programa que suelo usar y ya, si usas otro IDE para java bien por ti


descarga eclipseIDE (for java developers) desde su pagina oficial:
https://www.eclipse.org/downloads/packages/installer

instalalo y pues ya

1. crea un nuevo proyecto java y llamalo como quieres, por ejemplo **Start**
2. descarga el .jar oficial de spigot desde https://getbukkit.org o desde buildtools en la pagina oficial de spigot, cuando tengas que añadir una libreria ve a la pestaña "libraries" y selecciona **add external jar** te abrirá una pestaña de explorador de archivos y selecciona el .jar de spigot
3. una vez creado el proyecto da click derecho en el y crea un nuevo package con el siguiente formato

**com.(Tu NICK).(Proyecto)** esto es más que nada para mantener un orden.

en mi caso seria algo como **com.Chileball.Start**


## Creando el primer archivo .java

una vez creado tu area de trabajo con las dependencias respectivas y todo instalado tendrás que crear la clase o archivo .java principal el cual debe ir en el package que creaste antes, lo recomendable es ponerle de nombre Main para que se guarde como Main.java.

Automaticamente se te abrirá el archivo, para importar las librerias de spigot a este archivo tendras que añadir el sufijo **extends JavaPlugin** después de el public class Main, quedará algo así

`

public class Main extends JavaPlugin{
	
	public void onEnable() {
		
	}
	public void onDisable() {
		
		
	}
	
	
	
}

`

