# JoyaControl

Prototipo de gestión de joyas y piedras preciosas: compras con gastos repartidos por unidad,
inventario con código único por pieza, fabricación, ventas con abonos y cuentas por cobrar.

**Abrir:** https://camil1693.github.io/joyacontrol/

- Funciona en el navegador del celular o del computador, sin instalar nada.
- Trae datos de ejemplo inventados. Lo que cada persona registra se guarda solo en su propio
  navegador: nadie más lo ve y no se envía a ningún servidor.
- Los medios de pago (PayPal, Affirm, Mercado Pago, Addi, Bank of America, Bancolombia) son solo
  una etiqueta: no se conecta con ninguna entidad.

Este repositorio solo publica `index.html`. El código fuente, el contrato y las pruebas viven en la
carpeta del proyecto (`JoyaControl/`); para actualizar el sitio se ejecuta `node construir.mjs`
allí y se sube el `index.html` nuevo.
