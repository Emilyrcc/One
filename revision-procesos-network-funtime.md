# Revisión de procesos de TI: Network Funtime

**Diagnóstico.** Con correo, ofimática y Slack en la nube, apenas se necesita infraestructura local; falla la gestión de equipos, cuentas y soporte, delegada informalmente en RR. HH. Los portátiles, baratos y dispares, llegan días tarde, sin inventario ni configuración estándar; las peticiones técnicas van por correo y no hay política de contraseñas ni recuperación de cuentas. Con poco presupuesto, priorizo el bajo coste.

1. **Inventario y etiquetado.** Etiquetar cada equipo y registrar serie, usuario y fecha de compra (hoja de cálculo o herramienta libre como Snipe-IT). *Justificación:* hoy una pérdida o un robo no se pueden auditar; el inventario permite detectarlos y planificar renovaciones.

2. **Catálogo estándar y reserva mínima.** TI compra un modelo homologado por perfil, compatible con Linux, y mantiene uno o dos en reserva. *Justificación:* lo barato suele salir caro; pocos modelos simplifican el soporte y la reserva elimina la espera, pues solo adelanta compras previstas.

3. **Identidad centralizada.** Usar el directorio de la suite en la nube (SSO, MFA y recuperación por autoservicio) y una cuenta local de administración con contraseña distinta en cada portátil. *Justificación:* evita reformatear por un olvido, y ante una baja o un robo se revoca todo a la vez.

4. **Contraseñas robustas y cifrado.** Exigir frases de paso, bloqueo automático y cifrado de disco, con claves de recuperación custodiadas por TI. *Justificación:* hoy se permiten contraseñas débiles y nada garantiza el cifrado; un robo podría exponer credenciales y datos.

5. **Aprovisionamiento automatizado.** Preparar instalaciones desatendidas (Kickstart, preseed) y scripts de configuración (p. ej., Ansible) para las distribuciones Linux aprobadas y demás sistemas. *Justificación:* sustituye la instalación manual por USB: cada equipo llega listo, seguro y registrado.

6. **Mesa de ayuda.** Centralizar las solicitudes técnicas en un gestor de tickets de código abierto o un formulario conectado a Slack. *Justificación:* libera a RR. HH., permite priorizar y deja trazabilidad.

7. **Altas y bajas estandarizadas.** Crear cuentas antes del primer día, sustituir la orientación individual por una guía y una sesión grupal breve y, en cada baja, recoger el equipo y revocar accesos. *Justificación:* ahorra horas de RR. HH. y evita equipos y cuentas sin control.

**Cierre.** Empezaría por las mejoras 1, 3 y 4, casi gratuitas y aplicables a la flota actual. En conjunto, hacen la TI auditable y segura con poca inversión.
