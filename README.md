# Anygrabber

## Descripción

Anygrabber es una herramienta que detecta conexiones establecidas de AnyDesk y obtiene información detallada de la dirección IP remota de cada conexión. Utiliza varias bibliotecas de Python para obtener detalles como el país, la región, la ciudad, el ISP y más, proporcionando una manera visualmente atractiva de presentar esta información en la consola.

### Características

- **Detección de conexiones AnyDesk**: Monitorea las conexiones establecidas de AnyDesk en tiempo real.
- **Obtención de información de IP**: Utiliza la API de `ip-api.com` para obtener detalles sobre la dirección IP remota.
- **Interfaz visual**: Presenta la información en la consola con un banner estilizado y colores.
- **Compatibilidad multiplataforma**: Funciona tanto en Windows como en Linux.

### Dependencias

- Python 3.x
- `psutil`: Para obtener información de las conexiones de red y procesos.
- `colorama`: Para manejar los colores en la consola.
- `requests`: Para realizar solicitudes HTTP a la API de `ip-api.com`.
- `pystyle`: Para estilos adicionales en la consola.

### Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/J-S-RAID/Anygrabber.git
   cd Anygrabber
