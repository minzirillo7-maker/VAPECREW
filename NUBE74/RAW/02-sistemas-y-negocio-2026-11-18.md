# RAW — Sistemas y negocio (notas de los documentos del proyecto, 18/11/2026)

Fuentes: docs del proyecto Vape Crew (consignacion-y-asistente-ia, crew-card-y-popup, analisis-perfumes, panel-admin-como-funciona, CONTEXTO VAPE CREW) y memoria del proyecto.

## Negocio
- Meta: facturar mínimo $4M por mes, estar en boliches de Mendoza, sumar otros productos por si prohíben los vapes.
- Dueños: Lolo y un socio (amigo). No quieren vender parte de la marca ni dividirla en tres.
- Base 30 días al 07/11: $1.680.300, 60 pedidos, ticket $28.005, margen bruto 47%, ganancia bruta $789.763. 77% de pedidos de 1 unidad.
- Ventas estancadas en 10/2026. Se sacaron los combos (11/2026): precio único por unidad. Solo promo BC 5K: 2 por $16.500 (suelto $10.000).
- Precios cargados 10/11: ICEKING / SWEETKING / TRIO / RABBEATS $26.500; EBC CREATE 40K $19.990; BC 5K $10.000; JOINONE 25K $23.990; ELFBAR 15K $19.900. Competencia amiga: ICEKING/TRIO $25.500, CREATE $17.000, RABBEATS $27.500.
- Promo UGC: ELFBAR CREATE 40K a $24.500 o 3x$20.000.
- Mayor: desde 10 unidades. Consignación a revendedores con niveles 10/15/20% de comisión según ventas de 30 días, piso 15% sobre costo.
- Pagos: MercadoPago alias vvpecrew, transferencia, efectivo solo si retira. Retiro: Barrio Olivos del Torreón / Barrio Paraíso 1, Maipú.
- WhatsApp ventas 2612152270. Canal de difusión de WhatsApp existente; quiere tarjeta con QR en cada pedido.
- Alguien de otra zona quiere sumar unos 400K para vender con la marca: en evaluación.
- Quiere promo para grupos de egresados.

## Perfumes
- Proveedor: Star Company (Paraguay, starcompany-py.com). 82 perfumes con costo real (USD × 1,13 × $1.660).
- Preventa de árabes con catálogo PDF y página oculta vapecrew.vercel.app/preventa-perfumes/.
- Quiere 20 perfumes de mujer (árabes y diseñador).
- Análisis 07/11: costo ~$28.000, venta ~$49.900, ganancia ~$20.400 por perfume. Escenarios mensuales: conservador 7 u. ($2,02M), base 18 ($2,56M), agresivo 39 ($3,60M). Para $4M con vapes como hoy: ~47 perfumes/mes.
- Plan: 20 unidades de 6 modelos (Khamrah, Khamrah Qahwa, Yara, Asad, Asad Bourbon, Bade'e Al Oud for Glory). Día 30: ≥15 vendidos reponer; 7–14 seguir; <7 liquidar.
- Solo originales, con factura y sobrerótulo en español con datos ANMAT del importador.
- Combo vape + perfume: $3.000 off.

## Sistemas
- Tienda: repo minzirillo7-maker/VAPECREW (main), Vercel, vapecrew.vercel.app. Fondo blanco desde 10/2026. Sin Linktree. Cartel +18 se saca.
- Panel: repo daaash, daaash.vercel.app. Ventas, stock, productos con foto, pedidos del día, cierre, perfumes, consignación, asistente IA (Gemini, con confirmación).
- Planilla CLAUDE CATALOGO: STOCK, MOVIMIENTOS, COMPRAS, EVENTOS, PERFUMES. Script "VAPE CREW ADMIN" versión 6.
- Reintentos automáticos en el panel y la tienda por pedidos colgados de Google (18/11).
- Analítica: eventos de sesión, vista de producto, carrito, pago, DM, búsquedas, pop-up.
- Pendiente técnico: og:image y favicon apuntan a una URL vieja del logo.

## CREW CARD
- Identificación por WhatsApp, nombre y apellido obligatorios. 3ª compra 10% off, 5ª 20% off, desde la 6ª vape gratis de 1K a 15K pitadas según stock. Usar premio reinicia ciclo.
- Pop-up: bienvenida $2.000 off al primer pedido; pop-up de perfumes para quien vuelve.

## Marketing
- Boliches: Wabi Fun Club (@wabifunclub) y Pura Producciones (@pura.producciones). Código por RRPP con comisión, combos de previa, beneficio para mesas. Sin sorteos.
- UGC pago: @agoss_sab, producto más fee fijo, sin guion rígido.
- Contenido hecho: carrusel "5 errores que están matando tu vape" (07/2026); carrusel CREW CARD "Cada pedido suma" (11/2026).
- Sticker pack: dos calcos de logo (blanco y azul) y tres personajes propuestos (alien verde, paquete plateado, robot violeta).

## Producción
- Logo real siempre. IA solo fondos y ambiente. Textos y logo se pegan después. Tildes revisadas. No estirar producto.
