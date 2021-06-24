# libGDX-code
setup vscode libgdx desktop java game
requirement:

* jdk 8, for compile
* jdk 11 for Language Server on vscode
* vscode


- Unix:
run "./gradlew desktop:run" over a terminal

- Windows:
run "./gradlew.bat desktop:run" over a terminal

Note:

* Compile whit jdk 11 will give this error: "Illegal reflective access by org.lwjgl.LWJGLUtil$3 (file:/.gradle/caches/modules-2/files-2.1/org.lwjgl.lwjgl/lwjgl/2.9.3/3df168ac74e4a8c96562cdff24ad352e255bf89c/lwjgl-2.9.3.jar) to method java.lang.ClassLoader.findLibrary(java.lang.String)"

* Language Server requires JDK 11+ to launch itself