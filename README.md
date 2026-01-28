# WhatsApp Block for XIAOMI
Welcome to WhatFsoc!!!

---
![IMAGE](https://github.com/cybber91/whatFsocForXiaomi/blob/main/cmd/zs.png)

## Descripcion
Aprobecha una vulnerabilidad en las versiones > 22.2 de Whatsapp, solo explotable ejecutando el scripts desde los modelos de XIAOMI en termux debido a la funcion que traen estos dispositivos de cerrar secciones en segundo plano despues de un tiempo activa, mientras el scripts se ejecuta sucede una salida 1 de error en el script por el cierre abrupto de la seccion y se reporta como comportamiento anomalo en la cuenta del numero telefonico target introducido.
   
## Features
- Bloqueo de Whatsapp permanente y cierre de todas las secciones
- Solo para ejecutable en Xiaomi Termux 

## Installation

Steps to install the project, including prerequisites:

```bash
# Clone the repository
git clone https://github.com/cybber91/whatFsocForXiaomi

# Navigate into the directory
cd whatFsocForXiaomi

# Execute
bash whatFsoc.sh
