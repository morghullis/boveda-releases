# Política de privacidad de Bóveda · Bóveda Privacy Policy

_Última actualización / Last updated: 15 de noviembre de 2026_

[English below](#english)

## Español

Bóveda es un gestor de contraseñas y secretos con cifrado de extremo a extremo, desarrollado por Pedro Antonio Monzon («nosotros»).

### Qué datos tratamos

- **Tu bóveda** (contraseñas, claves de API, variables de entorno, notas y demás entradas) se cifra **en tu dispositivo** con AES-256-GCM, usando una clave derivada de tu contraseña maestra con Argon2id. Nunca vemos tu contraseña maestra ni el contenido de tu bóveda.
- **No recopilamos** datos personales, analíticas, identificadores de publicidad ni registros de uso. La app no contiene anuncios ni SDK de terceros de seguimiento.

### Dónde se guardan

- En el almacenamiento privado de la app en tu dispositivo, siempre cifrado.
- **Android:** si tienes activada la copia de seguridad de Google en tu teléfono, el sistema puede incluir la bóveda **cifrada** en esa copia para restaurarla al reinstalar. Google no puede leerla porque no tiene tu contraseña maestra. Puedes desactivarlo en los ajustes de copia de seguridad de Android.
- **Copias que tú exportas:** los archivos de copia (también cifrados) van donde tú decidas.

### Conexiones a internet

- **Comprobación de filtraciones (opcional, solo si la inicias tú en «Salud»):** se envían a [Have I Been Pwned](https://haveibeenpwned.com/Passwords) los **5 primeros caracteres del hash SHA-1** de cada contraseña (k-anonimato). Ni la contraseña ni su hash completo salen del dispositivo.
- **Sincronización en la nube (opcional, cuando esté disponible):** si la activas, se guardan en nuestro servidor tu correo electrónico (para la cuenta) y tus entradas **ya cifradas**. El servidor no puede descifrarlas.
- **Enlaces:** al abrir la web de una entrada, se abre en tu navegador.
- **Logotipos de servicios:** van incluidos en la app; nunca se descargan, así que nadie puede saber qué cuentas tienes.
- **Compartir:** el paquete cifrado lo envías tú por el canal que elijas (correo, chat, archivo) y el código por otro. No pasa por nuestros servidores y sin el código es ilegible.

### Permisos en Android

- **Cámara (opcional):** solo para escanear el código QR de la verificación en dos pasos cuando tú lo pides. La imagen se procesa en el teléfono y no se guarda ni se envía.
- **Notificaciones (opcional):** avisos locales cuando algo va a caducar. Se generan en el propio dispositivo, solo incluyen el nombre de la entrada y se ocultan en la pantalla de bloqueo.
- **Huella o cara (opcional):** Bóveda nunca recibe tu huella ni tu cara. Android la verifica y, solo entonces, libera una llave guardada en el chip de seguridad del teléfono que abre tu bóveda.
- **PIN (opcional, Android):** se guarda únicamente como un envoltorio cifrado de la llave de tu bóveda en este teléfono; nunca se sincroniza ni entra en las copias de seguridad.

### Tus derechos

Todo está en tu dispositivo y bajo tu control: puedes exportar o borrar tus datos desde **Ajustes** en cualquier momento. Si usas la nube, puedes pedir el borrado de tu cuenta escribiendo al contacto de abajo.

### Menores

Bóveda no está dirigida a menores de 13 años.

### Cambios

Publicaremos aquí cualquier cambio de esta política, con su fecha.

### Contacto

Abre una incidencia en [github.com/morghullis/boveda-releases/issues](https://github.com/morghullis/boveda-releases/issues)

---

## English

Bóveda is an end-to-end encrypted password and secrets manager developed by Pedro Antonio Monzon ("we").

### What data we handle

- **Your vault** (passwords, API keys, environment variables, notes and other entries) is encrypted **on your device** with AES-256-GCM, using a key derived from your master password with Argon2id. We never see your master password or your vault's contents.
- **We do not collect** personal data, analytics, advertising IDs or usage logs. The app has no ads and no third-party tracking SDKs.

### Where it is stored

- In the app's private storage on your device, always encrypted.
- **Android:** if Google backup is enabled on your phone, the system may include your **encrypted** vault in that backup so it can be restored when you reinstall. Google cannot read it because it does not have your master password. You can turn this off in Android's backup settings.
- **Backups you export:** backup files (also encrypted) go wherever you choose.

### Internet connections

- **Breach check (optional, only when you start it in "Health"):** the **first 5 characters of the SHA-1 hash** of each password are sent to [Have I Been Pwned](https://haveibeenpwned.com/Passwords) (k-anonymity). Neither the password nor its full hash ever leaves your device.
- **Cloud sync (optional, when available):** if you turn it on, our server stores your email address (for the account) and your **already encrypted** entries. The server cannot decrypt them.
- **Links:** opening an entry's website opens it in your browser.
- **Service logos:** they ship inside the app and are never downloaded, so no one can tell which accounts you have.
- **Sharing:** you send the encrypted package through the channel you choose (email, chat, file) and the code through another. It never goes through our servers and is unreadable without the code.

### Android permissions

- **Camera (optional):** only to scan a two-factor QR code when you ask. The image is processed on the phone and is never stored or sent.
- **Notifications (optional):** local alerts when something is about to expire. They are generated on the device, only include the entry's name and are hidden on the lock screen.
- **Fingerprint or face (optional):** Bóveda never receives your fingerprint or face. Android verifies it and only then releases a key stored in the phone's security chip that opens your vault.
- **PIN (optional, Android):** stored only as an encrypted wrapper of your vault key on this phone; it is never synced or included in backups.

### Your rights

Everything lives on your device and under your control: you can export or delete your data from **Settings** at any time. If you use the cloud, you can request deletion of your account by writing to the contact below.

### Children

Bóveda is not directed at children under 13.

### Changes

Any change to this policy will be published here, with its date.

### Contact

Open an issue at [github.com/morghullis/boveda-releases/issues](https://github.com/morghullis/boveda-releases/issues)
