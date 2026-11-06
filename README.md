# OnStudio para Claude

Consulta y administra tu estudio desde Claude con OnStudio. Incluye cuatro habilidades: operación diaria, cambios de horario, seguimiento de clientes y revisión del negocio.

## Conexión

El servidor remoto es `https://api.onstudio.ai/mcp/admin`. Conecta OnStudio mediante OAuth, inicia sesión como propietario o administrador activo y elige tu estudio. `Permitir cambios` inicia apagado. La conexión usa una sola organización; cada herramienta verifica los permisos y el acceso vigentes. Para elegir otra organización, inicia una conexión nueva.

Las consultas muestran horarios, planes y reportes. Los cambios admitidos requieren activar el permiso de escritura. Las herramientas comerciales pueden preparar compras de clases, planes y membresías para completarlas en las interfaces seguras de OnStudio o del proveedor de pago. Preparar una venta no significa que esté pagada. El catálogo no incluye el checkout de OnStudio Pro ni autorización mediante PIN de staff.

## Datos y permisos

Claude y el servidor de OnStudio intercambian por HTTPS los parámetros solicitados y los datos que tu cuenta puede consultar del estudio seleccionado. Según la consulta, los resultados pueden incluir clases, clientes y reportes del negocio. OAuth autoriza el acceso; no pegues contraseñas, tokens ni datos de tarjeta en el chat. Este paquete no incluye credenciales, un servidor local ni un ejecutor de código.

Puedes revisar o revocar la conexión desde Claude o desde las conexiones de OnStudio. La conservación y el tratamiento de los datos se describen en los avisos aplicables de OnStudio y Claude.

## Demostración

[Recorrido con datos sintéticos de Yoga Harmony](https://evidence.onstudio.fit/evidence/plugin-submissions/claude-yoga-harmony/codex-mcp-refresh-scope/1878b0a/onstudio-claude-yoga-harmony-walkthrough-cc5776f561.mp4?v=1878b0a-1793943577061). Muestra una conexión de solo lectura, consultas del calendario y catálogo, comparación de reportes, límites de cobertura y una solicitud fuera del alcance. No muestra datos de un estudio real.

## Ayuda y políticas

- [OnStudio](https://onstudio.mx)
- [Soporte](https://onstudio.mx/soporte)
- [Aviso de privacidad](https://onstudio.mx/privacidad)
- [Términos y condiciones](https://onstudio.mx/terminos-condiciones)

## Licencia

MIT cubre sólo los archivos de este paquete: habilidades, configuración, guía e icono. No cambia la licencia del backend ni del monorepo de OnStudio.
