# TMPOS — descargas oficiales

La versión más reciente es **v7.0.76**. Los instaladores se generaron con GitHub Actions y están disponibles en la [release v7.0.76](https://github.com/tmpos/tmpos-publico/releases/tag/v7.0.76).

| Sistema | Descargar | Comprobar SHA-256 |
| --- | --- | --- |
| Windows 10/11, 64 bits | [TMPOS.Setup.7.0.76.exe](https://github.com/tmpos/tmpos-publico/releases/download/v7.0.76/TMPOS.Setup.7.0.76.exe) | [Archivo `.sha256`](https://github.com/tmpos/tmpos-publico/releases/download/v7.0.76/TMPOS.Setup.7.0.76.exe.sha256) |
| Linux Debian/Ubuntu, amd64 | [TMPOS-7.0.76-x64.deb](https://github.com/tmpos/tmpos-publico/releases/download/v7.0.76/TMPOS-7.0.76-x64.deb) | [Archivo `.sha256`](https://github.com/tmpos/tmpos-publico/releases/download/v7.0.76/TMPOS-7.0.76-x64.deb.sha256) |
| macOS Catalina 10.15 o posterior, Intel x64 | [TMPOS-7.0.76-catalina-x64.zip](https://github.com/tmpos/tmpos-publico/releases/download/v7.0.76/TMPOS-7.0.76-catalina-x64.zip) | [Archivo `.sha256`](https://github.com/tmpos/tmpos-publico/releases/download/v7.0.76/TMPOS-7.0.76-catalina-x64.zip.sha256) |

En Linux, después de descargar los dos archivos, ejecuta `sha256sum -c TMPOS-7.0.76-x64.deb.sha256` y luego `sudo apt install ./TMPOS-7.0.76-x64.deb`. El paquete no es compatible con ARM64.

En macOS, extrae el ZIP y copia **TMPOS.app** a **Aplicaciones**. La aplicación no está firmada ni notarizada; si macOS bloquea la primera apertura, utiliza clic derecho → **Abrir**. El instalador de Windows tampoco está firmado digitalmente.

## Libro 3D con fotos existentes

En Inventario → Accesorios, selecciona entre las fotos ya cargadas una portada y una contraportada y activa **Libro 3D en la tienda web**. El producto se muestra con grosor y se puede girar en todas direcciones. Los cantos sin fotografía se dibujan como papel y las demás fotos siguen en la galería.

## Vista 360° anterior

En Inventario → Accesorios, carga de 4 a 36 fotos tomadas alrededor del producto, ordénalas y activa la vista de 360°. En la tienda web, el cliente puede girar el accesorio arrastrando la imagen o con los controles.

## Versión web

El mismo build v7.0.76 está publicado en [Pruebas](https://api.tmposystem.com/system-apps/pruebas/) y en [TMPOS Online](https://api.tmposystem.com/sistema/app/).

Este repositorio distribuye los instaladores. Las notas y archivos de versiones anteriores están en [Releases](https://github.com/tmpos/tmpos-publico/releases).