# hello-world
repositorio para consultar perfil del usuario y empezar la actividad de mi primer proyecto android
# Archivo de configuración de Gradle a nivel de proyecto.
# Usuarios de IDE (por ejemplo, Android Studio):
# La configuración de Gradle configurada a través del IDE *anulará*
# cualquier configuración especificada en este archivo.
# Para obtener más detalles sobre cómo configurar su entorno de desarrollo, visite
# http://www.gradle.org/docs/current/userguide/build_environment.html
# Especifica los argumentos JVM utilizados para el proceso daemon.
# Esta configuración es especialmente útil para ajustar la configuración de memoria.
org.gradle.jvmargs=-Xmx2048m -Dfile.encoding=UTF-8
# Cuando se configura, Gradle se ejecutará en modo paralelo en fase de incubación.
# Esta opción solo debe usarse con proyectos desacoplados. Para más detalles, visite
# http://www.gradle.org/docs/current/userguide/multi_project_builds.html#sec:decoupled_projects
# org.gradle.parallel=true
# Estructura de paquetes de AndroidX para aclarar qué paquetes se incluyen con el
# sistema operativo Android y cuáles se empaquetan con el APK de su aplicación
# https://developer.android.com/topic/libraries/support-library/androidx-rn
android.useAndroidX=true
# Estilo de código Kotlin para este proyecto: "official" u "obsolete":
kotlin.code.style=official
# Habilita la creación de espacios de nombres (namespacing) para la clase R de cada biblioteca,
# de modo que su clase R incluya solo los recursos declarados en la propia biblioteca y ninguno de las dependencias de la biblioteca,
# lo que reduce el tamaño de la clase R para esa biblioteca
android.nonTransitiveRClass=true
..
