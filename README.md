# 🔐 Bóveda: descargas

Gestor de contraseñas con **cifrado de extremo a extremo**. Este repositorio solo contiene los **instaladores oficiales** (el código fuente es privado).

## Descargar

| Sistema | Instalador |
|---|---|
| **Windows 10/11** (64 bits) | [⬇️ Boveda-Windows-x64-Setup.exe](https://github.com/morghullis/boveda-releases/releases/latest/download/Boveda-Windows-x64-Setup.exe) |
| **macOS 11+** (Apple Silicon e Intel) | [⬇️ Boveda-macOS.dmg](https://github.com/morghullis/boveda-releases/releases/latest/download/Boveda-macOS.dmg) |

Estos enlaces siempre apuntan a la **última versión**. Todas las versiones están en [Releases](https://github.com/morghullis/boveda-releases/releases).

Una vez instalada, **Bóveda se actualiza sola**: cuando hay una versión nueva aparece un aviso «Actualizar y reiniciar». Cada actualización está **firmada digitalmente** y la app rechaza cualquier paquete que no venga del autor.

## Instalar

### Windows
1. Ejecuta `Boveda-Windows-x64-Setup.exe`. No necesita permisos de administrador.
2. Si aparece **«Windows protegió su PC»**, pulsa **Más información → Ejecutar de todas formas**. Ocurre porque el instalador aún no tiene un certificado de firma de código de pago.

### macOS
1. Abre `Boveda-macOS.dmg` y arrastra **Boveda** a **Aplicaciones**.
2. La primera vez, si macOS dice que no puede verificar al desarrollador: **Ajustes del Sistema → Privacidad y seguridad → «Abrir igualmente»**.

## Usar la bóveda del equipo

Para compartir la misma información en varios equipos, en cada computadora:

1. Abre Bóveda y elige **«Ya uso Bóveda en otro dispositivo»**.
2. Escribe el **email** y la **contraseña maestra** de la bóveda del equipo.
3. Listo: los cambios se sincronizan automáticamente, cifrados, entre todos.

> La contraseña maestra nunca sale de tu equipo: el servidor solo guarda datos cifrados que no puede leer.
