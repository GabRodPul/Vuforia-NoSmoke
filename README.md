# NoSmoke
Proyecto AR con Unity + Vuforia para concienciar sobre el consumo de tabaco, con la colaboración de [Zahira Suárez](https://github.com/ZahiraSuarez).
Realizado como tareas introductorias de RA en el módulo de Realidad virtual y realidad aumentada del curso de especialización de Videojuegos y Realidad Virtual.

# Índice:
- [Descargas](#Descargas)
- [Código fuente](#Código)
- [Info](#Info)
- [Demos](#Demos)
- [Vídeos técnicos](#Técnico)
- [Cómo probar](#Probar)

# Descargas
- Elige la versión que mejor se adapte a tu teléfono [aquí](https://drive.google.com/drive/folders/1DO2Vrsq8HbsHCYTXZ5imVwWCBahq1Oek?usp=drive_link). \ \
También puedes utilizar estos QR: \
- ARM7: \
  ![QR](public/images/nosmoke-qr-arm7.png)
- ARM64: \
  ![QR](public/images/nosmoke-qr-arm64.png)


# Código fuente
Debido a las limitaciones de espacio de GitHub, el código fuente reside en Google Drive en forma de .unitypackage.
Puede descargarlo [aquí](https://drive.google.com/drive/folders/1DO2Vrsq8HbsHCYTXZ5imVwWCBahq1Oek?usp=sharing).

# Info
Haga click [aquí](https://github.com/GabRodPul/Vuforia-NoSmoke/blob/main/public/Producto%20Mínimo%20Viable%20-%20Zahira%20y%20Gabriel.pdf) para leer el documento del Producto Mínimo Viable.

## Tarea01
Esta tarea sirvió de introducción al desarrollo de experiencias de Vuforia en Unity. La aplicación resultante de esta tarea funciona con 3 imágenes distinas, mostrando una disposición de modelos y eslogan única para cada una.

## Tarea02
Esta tarea sirvió de continuación para la anterior. Aquí hicimos uso de Polycam para escanear un objeto del mundo real que una vez enfocado, enseñará modelos 3D alrededor de este objeto.

# Demos

- Tarea01: \ ![](public/videos/nosmoke-t01-reel-demo.mp4)
- Tarea02: \ ![](public/videos/nosmoke-t02-reel-demo.mp4)

# Probar
Para probar el proyecto necesitas descargar el src, elegir una versión de Unity adecuada para Vuforia (nosotros utilizamos la 2022.3.11f), el SDK de Android para tu versión de Unity, el SDK de Vuforia y una licencia de Vuforia.
Pasos:
- Importar SDK Vuforia
- Aceptar Acuerdo de usuario
- Introducir licencia
- Importar el package del src
- Haz build para Android (nosotros usamos Oreo 8.0)
