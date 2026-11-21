<div align="center">

```text
__________      ___.   .__                                     .__        __          
\______   \ ____\_ |__ |  |   _______  ___   ______ ___________|__|______/  |_  ______
 |       _//  _ \| __ \|  |  /  _ \  \/  /  /  ___// ___\_  __ \  \____ \   __\/  ___/
 |    |   (  <_> ) \_\ \  |_(  <_> >    <   \___ \\  \___|  | \/  |  |_> >  |  \___ \ 
 |____|_  /\____/|___  /____/\____/__/\_ \ /____  >\___  >__|  |__|   __/|__| /____  >
        \/           \/                 \/      \/     \/         |__|             \/
```

# ⚠️ Roblox Executors & Scripts: Consequences and Risks
### Ejecutores y Scripts en Roblox: Consecuencias y Riesgos

![Status](https://img.shields.io/badge/Docs-Educational%20%26%20Informational-0A66C2?style=for-the-badge&logo=github)
![Languages](https://img.shields.io/badge/Languages-English%20%7C%20Espa%C3%B1ol-2EA44F?style=for-the-badge)
![Risk Level](https://img.shields.io/badge/Risk%20Level-Critical-D73A49?style=for-the-badge&logo=shield)
![Platform](https://img.shields.io/badge/Platform-Roblox-000000?style=for-the-badge&logo=roblox)

<p>
  <a href="#-english-documentation">🇺🇸 Read in English</a> •
  <a href="#-documentación-en-español">🇪🇸 Leer en Español</a> •
  <a href="#-quick-risk-matrix--matriz-rápida-de-riesgos">📊 Risk Matrix</a> •
  <a href="#-safe-alternatives--alternativas-seguras">🛡️ Safe Alternatives</a>
</p>

</div>

---

> [!IMPORTANT]
> **Disclaimer / Aviso:** This repository is strictly for informational and educational purposes. It documents the technical, account, and cybersecurity consequences associated with running third-party script executors in Roblox.  
> **Aviso:** Este repositorio tiene fines exclusivamente informativos y educativos. Documenta las consecuencias técnicas, de cuenta y de ciberseguridad asociadas con el uso de *executors* de scripts de terceros en Roblox.

---

## 📊 Quick Risk Matrix | Matriz Rápida de Riesgos

| Category / Categoría | Severity / Severidad | Primary Impact / Impacto Principal | Reversible? / ¿Reversible? |
| :--- | :---: | :--- | :---: |
| 🔨 **Account Enforcement / Sanciones** | 🔴 **Critical / Crítica** | Permanent account termination & ban waves / Cierre permanente y oleadas de baneo | ❌ No |
| 🦠 **Malware & Info-Stealers** | 🔴 **Critical / Crítica** | Credential theft, RATs, session hijacking / Robo de credenciales, troyanos y sesiones | ⚠️ Difficult / Difícil |
| 💥 **Client Instability / Inestabilidad** | 🟠 **High / Alta** | Crashes, memory corruption, broken updates / Cierres inesperados y fallos por parches | ✅ Yes / Sí |
| 🎮 **Gameplay Disruption / Impacto en Juego** | 🟡 **Medium / Media** | Server kicks, desync, ruined lobbies / Expulsiones, desincronización y partidas dañadas | ✅ Yes / Sí |

---

## 🇺🇸 English Documentation

Using third-party script executors to inject custom code into the Roblox client carries severe technical, security, and account-related consequences.

> [!CAUTION]
> **Permanent Account Loss:** Roblox enforces automated client-tampering detection and delayed ban waves. Even if a script works temporarily, your account can still be flagged and terminated later.

### 🔹 1. Account Moderation & Bans
- **📜 Terms of Use Violations:** Injecting unauthorized code or modifying client memory directly violates Roblox's Terms of Use and Community Standards.
- **🔨 Escalating Enforcement:** Penalties range from warnings and temporary suspensions to permanent account termination across linked accounts.
- **💎 Permanent Asset Loss:** A terminated account loses all Robux balances, limited items, game passes, developer earnings, and years of progress.

### 🔹 2. Malware & Cybersecurity Threats
- **☣️ Untrusted Binaries:** Executors and obfuscated script hubs are distributed outside official channels and frequently bundle trojans, info-stealers, keyloggers, and hidden crypto-miners.
- **🛡️ Antivirus Bypass Risks:** Many tools instruct users to disable Windows Defender or real-time protection, leaving the entire operating system exposed to actual malware.
- **🔑 Session & Token Hijacking:** Malicious scripts or loaders can steal browser cookies, Discord tokens, or saved passwords if executed without strict sandboxing.

### 🔹 3. Stability, Updates & Detection
- **💥 Frequent Client Crashes:** Weekly Roblox client updates regularly break memory offsets, hooks, and UI injections, causing crashes and corrupted states.
- **🚨 Anti-Tamper & Sanity Checks:** Client integrity checks and server-side validations detect abnormal velocity, teleportation, and unauthorized RemoteEvent calls.

### 🔹 4. Ecosystem & Gameplay Impact
- **📉 Broken Multiplayer Lobbies:** Exploits degrade server performance and ruin fair gameplay for other players.
- **🔒 Server-Side Authority:** Core systems (currency, inventory, combat damage, progression) are validated on the server, making most client-side modifications temporary or ineffective.

<details>
<summary><b>📌 Summary Checklist Before Running Any Unknown Tool</b></summary>
<br>

- Never disable Windows Defender or antivirus software for third-party executables.
- Never paste obfuscated code you cannot inspect into tools with elevated permissions.
- Keep all script testing strictly inside **Roblox Studio** using official APIs.

</details>

---

## 🇪🇸 Documentación en Español

El uso de *executors* de scripts de terceros para inyectar código personalizado en el cliente de Roblox conlleva graves consecuencias técnicas, de seguridad y para la cuenta.

> [!CAUTION]
> **Pérdida Permanente de la Cuenta:** Roblox utiliza detección automática de alteración del cliente y oleadas de baneo diferidas. Aunque un script funcione temporalmente, la cuenta puede quedar marcada y ser suspendida días o semanas después.

### 🔹 1. Moderación y Baneos de Cuenta
- **📜 Infracción de los Términos de Uso:** Inyectar código no autorizado o modificar la memoria del cliente incumple directamente los Términos de Uso y Normas de la Comunidad de Roblox.
- **🔨 Sanciones Progresivas y Oleadas:** Las medidas van desde advertencias y suspensiones temporales hasta el cierre permanente de la cuenta principal y cuentas vinculadas.
- **💎 Pérdida Total de Recursos:** Un baneo permanente implica perder saldo de Robux, objetos limitados, pases comprados y todo el historial o progreso acumulado.

### 🔹 2. Riesgos de Malware y Ciberseguridad
- **☣️ Ejecutables No Verificados:** Muchos *executors* y hubs de scripts ofuscados se distribuyen fuera de tiendas oficiales y suelen ocultar troyanos, *info-stealers*, *keyloggers* o mineros ocultos.
- **🛡️ Desactivar el Antivirus:** Con frecuencia se pide desactivar Windows Defender o la protección en tiempo real, dejando todo el sistema operativo expuesto a amenazas reales.
- **🔑 Robo de Sesiones y Credenciales:** Un ejecutable o carga maliciosa puede comprometer cookies del navegador, tokens de sesión o contraseñas guardadas en el equipo.

### 🔹 3. Inestabilidad, Parches y Detección
- **💥 Caídas Constantes del Cliente:** Las actualizaciones semanales de Roblox cambian direcciones de memoria y rompen inyecciones o interfaces, generando cierres inesperados (*crashes*).
- **🚨 Sistemas Antitampa y Validaciones:** Tanto el cliente como el servidor verifican integridad, velocidad anormal, teletransportes y llamadas irregulares a `RemoteEvents`.

### 🔹 4. Impacto en el Juego y el Ecosistema
- **📉 Partidas Dañadas:** Los scripts alteran la experiencia multijugador, afectan el rendimiento de la sala y perjudican a otros jugadores.
- **🔒 Control del Lado del Servidor:** Los sistemas críticos (monedas, inventario, daño y progreso) se validan en el servidor, por lo que los cambios locales suelen desincronizarse o no tener efecto real.

<details>
<summary><b>📌 Lista Rápida de Prevención</b></summary>
<br>

- Nunca desactives Windows Defender ni tu antivirus para ejecutar archivos externos.
- Evita ejecutar código fuertemente ofuscado cuyo origen o comportamiento no puedas auditar.
- Realiza todas tus pruebas de scripts, interfaces y mecánicas exclusivamente dentro de **Roblox Studio**.

</details>

---

## 🛡️ Safe Alternatives | Alternativas Seguras

> [!TIP]
> **Build Legitimately / Desarrolla de Forma Legítima:** Everything related to UI design, Luau scripting, animations, sound effects, and game mechanics can be built, tested, and published safely using official Roblox tools.

| Tool / Herramienta | English Description | Descripción en Español |
| :--- | :--- | :--- |
| **Roblox Studio** | Official IDE to write, debug, and test Luau scripts, custom UIs, and physics safely. | Entorno oficial para escribir, depurar y probar scripts en Luau, interfaces y físicas de forma segura. |
| **Creator Hub Docs** | Official documentation for Client-Server architecture, `RemoteEvents`, and security. | Documentación oficial sobre arquitectura Cliente-Servidor, `RemoteEvents` y seguridad. |
| **Luau Official Site** | Language reference, type checking, and performance optimization guides. | Referencia oficial del lenguaje, tipado y guías de optimización de rendimiento. |

---

<div align="center">
  <sub>📚 Maintained for educational awareness on Roblox client security & safe Luau development.</sub><br>
  <sub>📚 Mantenido con fines educativos sobre seguridad del cliente en Roblox y desarrollo seguro en Luau.</sub>
</div>
