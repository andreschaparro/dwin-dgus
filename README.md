# Pantallas DWIN DGUS

La pantalla utilizada es la `DMG10600T070_A5WTC`.

## T5L UI DGUS2 Kernel Upgrade

1. Formatear una tarjeta `microSD` de `16GB` en `FAT32 (4096 bytes de unidad de asignación)`.
2. Crear una carpeta con el nombre `DWIN_SET` dentro de la tarjeta `microSD`.
3. Descargar la última versión del `T5L UI DGUS2` del [sitio web del fabricante](https://www.dwin-global.com/kernel-upgrade/).
4. Descomprimir el archivo descargado.
5. Copiar los archivos `.INI` y `.BIN` a la carpeta `DWIN_SET`.
6. Apagar la pantalla.
7. Insertar la tarjeta `microSD` en la pantalla.
8. Encender la pantalla.
9. Esperar a que finalice el proceso de actualización.
10. Apagar la pantalla.
11. Retirar la tarjeta `microSD` de la pantalla.

## T5L OS Kernel Upgrade

1. Borrar el contenido de la carpeta `DWIN_SET` dentro de la tarjeta `microSD`.
2. Descargar la última versión del `T5L OS` para el `RTC SD2058` del [sitio web del fabricante](https://www.dwin-global.com/kernel-upgrade/).
3. Descomprimir el archivo descargado.
4. Copiar el archivo `.BIN` a la carpeta `DWIN_SET`.
5. Apagar la pantalla.
6. Insertar la tarjeta `microSD` en la pantalla.
7. Encender la pantalla.
8. Esperar a que finalice el proceso de actualización.
9. Apagar la pantalla.
10. Retirar la tarjeta `microSD` de la pantalla.

📝Utilizar el software [pyModSlave](https://sourceforge.net/projects/pymodslave/) para verificar la comunicación Modbus.

Autor: Ing. Andrés Chaparro
