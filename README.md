# BackTP

> 🇦🇷 Español | 🇺🇸 [English below](#english)

---

## 🇦🇷 Español

Un plugin para [TShock](https://github.com/Pryaxis/TShock) que guarda tu posición antes de un teleport y te permite volver a ella con `/back`.

###  Características

- Detecta automáticamente teleports por saltos de posición grandes (≥ 120 tiles).
- Guarda la última posición previa al teleport.
- Cooldown de 5 segundos entre usos de `/back`.
- No guarda posición si el jugador está muerto.

###  Requisitos

- TShock v6.1.0+
- Terraria 1.4.5.6
- .NET 9

###  Instalación

1. Descargá el `.dll` desde [Releases](../../releases).
2. Copialo a la carpeta `ServerPlugins` de tu servidor TShock.
3. Reiniciá el servidor.

###  Comandos

| Comando | Descripción | Permiso |
|---------|-------------|---------|
| `/back` | Volvé a tu posición anterior al último teleport. | `backtp.use` |

###  Permisos

Para darle acceso a un grupo:
```
/group addperm <grupo> backtp.use
```

###  Licencia

MIT © Ramiro Arena

---

## 🇺🇸 English <a name="english"></a>

A [TShock](https://github.com/Pryaxis/TShock) plugin that saves your position before a teleport and lets you return to it with `/back`.

###  Features

- Automatically detects teleports via large position jumps (≥ 120 tiles).
- Saves the last position prior to a teleport.
- 5-second cooldown between `/back` uses.
- Does not save position if the player is dead.

###  Requirements

- TShock v6.1.0+
- Terraria 1.4.5.6
- .NET 9

###  Installation

1. Download the `.dll` from [Releases](../../releases).
2. Copy it to your TShock server's `ServerPlugins` folder.
3. Restart the server.

###  Commands

| Command | Description | Permission |
|---------|-------------|------------|
| `/back` | Return to your position before the last teleport. | `backtp.use` |

###  Permissions

To grant access to a group:
```
/group addperm <group> backtp.use
```

###  License

MIT © Ramiro Arena
