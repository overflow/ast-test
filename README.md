# ast-test

## Evaluación Poblema II
### Query 1
      select tienda as productos from tiendas, productos where tiendas.tienda.id = tienda_id group by tienda ;

### Query 2
      select tienda from tiendas, productos where tiendas.tienda = tienda_id  group by tienda having count(producto) >= 15;
