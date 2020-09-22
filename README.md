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

`dedit ~/.config/kwinrc`

Modifique el código.
* MagicLamp → Efecto de lámpara mágica
* PresentWindows → Efecto vista multiventana (Win+A)
* Wobbly → Efecto de ventana de gelatina

Cerrar sesión para aplicar cambios.

## Restablecer configuración por defecto

Ejecute el siguiente comando.

`rm ~/.config/kwinrc`

Cerrar sesión para aplicar cambios.
