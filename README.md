PMDM-ANDROID-CALCULADORAIRPF
Este proyecto es una aplicación Android desarrollada en Kotlin, como parte de las actividades del módulo de Programación Multimedia y Dispositivos Móviles (PMDM). La aplicación permite a los usuarios calcular el Impuesto sobre la Renta de las Personas Físicas (IRPF) en España, ingresando su salario bruto anual y otros datos relevantes.

🧠 Descripción
La aplicación proporciona una interfaz sencilla donde los usuarios pueden ingresar su salario bruto anual y otros datos necesarios para calcular el IRPF. Al presionar el botón de cálculo, la aplicación muestra el resultado del IRPF estimado.

📁 Estructura del Proyecto
pgsql
Copiar
Editar
PMDM-ANDROID-CALCULADORAIRPF/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── calculadorairpf/
│   │   │   │               └── MainActivity.kt
│   │   │   └── res/
│   │   │       ├── layout/
│   │   │       │   └── activity_main.xml
│   │   │       └── values/
│   │   │           └── strings.xml
├── build.gradle.kts
├── settings.gradle.kts
├── gradle/
├── gradlew
├── gradlew.bat
├── .gitignore
└── .gitattributes
MainActivity.kt: Clase principal que maneja la lógica del cálculo del IRPF.

activity_main.xml: Diseño de la interfaz de usuario con campos de entrada para el salario y un botón para calcular el IRPF.

strings.xml: Contiene los textos utilizados en la aplicación.

🚀 Instrucciones de Ejecución
Clonar el repositorio:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PMDM-ANDROID-CALCULADORAIRPF.git
Abrir en Android Studio:

Abre Android Studio y selecciona "Open an existing project". Navega hasta la carpeta del proyecto clonado y ábrela.

Compilar y ejecutar:

Una vez abierto el proyecto, haz clic en el botón "Run" o utiliza el atajo Shift + F10 para compilar y ejecutar la aplicación en un emulador o dispositivo físico.

🛠️ Tecnologías Utilizadas
Kotlin: Lenguaje de programación principal.

Android SDK: Herramientas y bibliotecas para el desarrollo de aplicaciones Android.

Android Studio: Entorno de desarrollo integrado (IDE) recomendado.

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

👨‍💻 Autor
Iván Núñez Rodríguez - GitHub
