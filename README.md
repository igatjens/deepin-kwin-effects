# Video
[![Watch the video](https://img.youtube.com/vi/iOnPLH-uI1Y/hqdefault.jpg)](https://youtu.be/iOnPLH-uI1Y)

# Deepin win effects
Configuraciones de efectos de ventanas para Deepin 20

Efectos
* Ventana de gelatina
* Vista multiventana en cuadrícula (Win+A)
* Efecto de lampara mágica

## Procedimiento

Ejecute los siguientes comandos.

`wget https://raw.githubusercontent.com/igatjens/deepin-kwin-effects/master/2020-09-14%20Deepin%2020%201002/kwinrc`

`mv  kwinrc ~/.config/kwinrc`

`kwin --replace`

Active el efecto de lampara mágica en Centro de control→Personalización→General→Efecto al minimizar ventana

## Cambiar la configuración

Ejecute el siguiente comando.

`deepin-editor ~/.config/kwinrc`

Modifique el código.
* MagicLamp → Efecto de lámpara mágica
* PresentWindows → Efecto vista multiventana (Win+A)
* Wobbly → Efecto de ventana de gelatina

Aplique los cambios con el siguiente comando.

`kwin --replace`

También puede cerrar sesión para aplicar cambios.

## Restablecer configuración por defecto

Ejecute el siguiente comando.

`rm ~/.config/kwinrc`

Cerrar sesión para aplicar cambios.
