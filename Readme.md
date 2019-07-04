## Fibertel

### Verificar niveles de Downstream y Upstream normales.
Podemos mirarlos visitando [dameunaip](http://dameunaip.com.ar) o [provisioning](http://provisioning.fibertel.com.ar/) ambos redirigen a la misma dirección ip (181.30.128.34).
#### Downstream Power Level
```
-10dBmV a + 10dBmV es aceptable para los módem.   
-7dBmV A + 7dBmV es el rango ideal y es también el rango especificado para módem de telefonía.   
Un técnico de instalación tendría como objetivo, por un valor cercano a al valor 0 dBmV
```
#### Downstream Signal to Noise Ratio (SNR)
```
Este número debe ser al menos mayor de +33 dB. Más alto es mejor.     
Cualquier valor por debajo de 33dB es probable que tenga transferencias lentas, problemas de conexiones, etc.
```
#### Upstream Power Level
```
El valor debe estar entre +35 a +49 dBmV
```

## Liberar un CableModem de Fibertel

1. Visitamos [Fibertel](http://dameunaip.com.ar).
2. Para obtener nuestros datos necesitamos ingresar primero con esta cuenta:
```
ID Componente: 258277559     
ID Cliente: 6432880
```
3. En el menú a la izquierda, le damos a Administrar o editando la URL en la barra de direcciónes agregando /auth/Administrar.xhtml [](http://dameunaip.com.ar/CVWebTecnico/auth/Administrar.xhtml).
4. Accedemos a [](http://dameunaip.com.ar/CVWebTecnico/auth/Administrar.xhtml)
(No te los van a dar si lo llamás)

id cliente: 53064376
id componente: 1017542027

http://provisioning.fibertel.com.ar/CVWebTecnico/auth/LiberarCM.xhtml
user:password service2:service
