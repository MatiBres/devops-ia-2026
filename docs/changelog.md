## Hotfix de Producción - 25/08/2026
- **Responsable:** Luciano Bonafede
- **Problema detectado:** El sistema se encontraba en modo mantenimiento y con parámetros de réplicas incorrectos en producción.
- **Solución aplicada:** Se desactivó el modo mantenimiento, se estableció el ambiente en producción y se ajustaron las réplicas a 3 en el archivo app.yaml.

## Hotfix de Producción - 13/11/2026
- **Responsable:** Matias Bressan
- **Problema detectado:** El sistema se encontraba en ambiente desarrollo, con el modo mantenimiento activo y una sola réplica en producción.
- **Solución aplicada:** Se configuró el ambiente en produccion, se desactivó el modo mantenimiento y se ajustaron las réplicas a 3 en el archivo app.yaml.
