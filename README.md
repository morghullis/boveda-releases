# 🔐 Bóveda

**[English](#english) · [Español](#español)**

| | Windows 10/11 (64-bit) | macOS 11+ (Apple Silicon & Intel) |
|---|---|---|
| ⬇️ | [**Boveda-Windows-x64-Setup.exe**](https://github.com/morghullis/boveda-releases/releases/latest/download/Boveda-Windows-x64-Setup.exe) | [**Boveda-macOS.dmg**](https://github.com/morghullis/boveda-releases/releases/latest/download/Boveda-macOS.dmg) |

These links always point to the **latest version** · Estos enlaces siempre apuntan a la **última versión** · [All releases / Todas las versiones](https://github.com/morghullis/boveda-releases/releases)

---

## English

Password manager with **end-to-end encryption**, built to store accounts, API keys and credentials organized by project. This repository only contains the **official installers** (the source code is private). The app is available in **English and Spanish**: it follows your system language and you can change it in *Settings → Language*.

Once installed, **Bóveda updates itself**: when a new version is out you'll see an “Update and restart” banner. Every update is **digitally signed**, and the app rejects any package that doesn't come from the author.

### Install

**Windows**
1. Run `Boveda-Windows-x64-Setup.exe`. No administrator rights needed.
2. If **“Windows protected your PC”** appears, click **More info → Run anyway**. This happens because the installer doesn't have a paid code-signing certificate yet.

**macOS**
1. Open `Boveda-macOS.dmg` and drag **Boveda** into **Applications**.
2. The first time, if macOS says it can't verify the developer: **System Settings → Privacy & Security → “Open Anyway”**.

### Reinstalling or switching computers

The desktop app saves an **automatic encrypted backup** after every change (in *Documents/Boveda*, or in the folder you pick in *Settings → Automatic backup*).

- **Uninstall and reinstall on the same computer:** your passwords stay (unless you tick “Delete the application data” when uninstalling on Windows). Just unlock with your master password.
- **New or reformatted computer:** install Bóveda and choose **“Restore from a backup”**. Pick your backup file and enter the master password. 👉 Tip: set the backup folder to **Google Drive, OneDrive, Dropbox or iCloud** so the backup survives a reformat and is ready on your new computer.

### Use the team vault

To share the same information across several computers, on each one:
1. Open Bóveda and choose **“I already use Bóveda on another device”**.
2. Enter the team vault's **email** and **master password**.
3. Done: changes sync automatically, encrypted, between everyone.

> The master password never leaves your computer: the server only stores encrypted data it cannot read.

---

## Español

Gestor de contraseñas con **cifrado de extremo a extremo**, pensado para guardar cuentas, API keys y credenciales organizadas por proyecto. Este repositorio solo contiene los **instaladores oficiales** (el código fuente es privado). La app está en **español e inglés**: usa el idioma de tu sistema y puedes cambiarlo en *Ajustes → Idioma*.

Una vez instalada, **Bóveda se actualiza sola**: cuando hay una versión nueva aparece un aviso «Actualizar y reiniciar». Cada actualización está **firmada digitalmente** y la app rechaza cualquier paquete que no venga del autor.

### Instalar

**Windows**
1. Ejecuta `Boveda-Windows-x64-Setup.exe`. No necesita permisos de administrador.
2. Si aparece **«Windows protegió su PC»**, pulsa **Más información → Ejecutar de todas formas**. Ocurre porque el instalador aún no tiene un certificado de firma de código de pago.

**macOS**
1. Abre `Boveda-macOS.dmg` y arrastra **Boveda** a **Aplicaciones**.
2. La primera vez, si macOS dice que no puede verificar al desarrollador: **Ajustes del Sistema → Privacidad y seguridad → «Abrir igualmente»**.

### Reinstalar o cambiar de computadora

La app de escritorio guarda una **copia cifrada automática** después de cada cambio (en *Documentos/Boveda*, o en la carpeta que elijas en *Ajustes → Copia automática*).

- **Desinstalar y volver a instalar en la misma PC:** tus contraseñas se conservan (salvo que en Windows marques «Eliminar los datos de aplicación» al desinstalar). Solo desbloquea con tu contraseña maestra.
- **PC nueva o formateada:** instala Bóveda y elige **«Restaurar desde una copia»**. Selecciona tu archivo de copia y escribe la contraseña maestra. 👉 Consejo: pon la carpeta de copias en **Google Drive, OneDrive, Dropbox o iCloud** para que la copia sobreviva a un formateo y esté lista en tu PC nueva.

### Usar la bóveda del equipo

Para compartir la misma información en varios equipos, en cada computadora:
1. Abre Bóveda y elige **«Ya uso Bóveda en otro dispositivo»**.
2. Escribe el **email** y la **contraseña maestra** de la bóveda del equipo.
3. Listo: los cambios se sincronizan automáticamente, cifrados, entre todos.

> La contraseña maestra nunca sale de tu equipo: el servidor solo guarda datos cifrados que no puede leer.
