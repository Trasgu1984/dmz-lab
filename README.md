# DMZ Lab (Cisco Packet Tracer)

Laboratorio de ciberseguridad defensiva donde se configura una DMZ en Cisco Packet Tracer para:
- Aislar servicios críticos (DMZ)
- Controlar tráfico mediante ACLs
- Configurar NAT estático para publicar el servidor
- Exponer un servicio web de forma controlada desde la red externa

## Contenido del repositorio
- `DMZ_PROJECT.pka`: archivo final `.pka` del laboratorio
- `informe/Informe_DMZ_Laboratorio.md`: informe técnico con la configuración y validaciones
- `evidencias/`: capturas de pruebas (pings, acceso web, comandos show)
- `README.md`: explica brevemente el objetivo del laboratorio.

## Validaciones realizadas
- `ping` desde PC_Internal al router
- Acceso HTTP desde red externa al servidor publicado
- Bloqueo de comunicaciones iniciadas desde DMZ hacia LAN
- bloqueo ICMP desde PC_External a WAN/IP pública del servidor
- Verificación de ACLs y NAT mediante comandos `show`
