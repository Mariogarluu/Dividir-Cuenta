# Dividir Cuenta 💰

¡Bienvenido a **Dividir Cuenta**!  
Esta aplicación Android, desarrollada en **Kotlin** con **Jetpack Compose**, facilita el proceso de dividir cuentas entre varias personas de manera rápida, sencilla y eficiente.

## 🚀 Características

- **División automática:** Divide el total de una cuenta entre varios comensales
- **Cálculo de propina:** Añade propina con porcentaje ajustable (0% - 25%)
- **Redondeo inteligente:** Opción para redondear el total con propina
- **Cálculo en tiempo real:** Resultados instantáneos al presionar "Calcular"
- **Interfaz moderna:** UI intuitiva desarrollada con Jetpack Compose
- **100% Kotlin:** Código limpio y moderno

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Kotlin
- **UI Framework:** Jetpack Compose
- **Plataforma:** Android
- **Arquitectura:** Material Design 3
- **Min SDK:** 34
- **Target SDK:** 36

## 📋 Requisitos

- Android Studio (versión recomendada: Hedgehog o superior)
- Android SDK 34 o superior
- JDK 11 o superior
- Dispositivo o emulador con Android 14 o superior

## 📲 Instalación y uso

### Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Mariogarluu/Dividir-Cuenta.git
   ```
2. Abre el proyecto con Android Studio
3. Espera a que Gradle sincronice las dependencias
4. Conecta un dispositivo Android o inicia un emulador
5. Haz clic en "Run" o presiona `Shift + F10`

### Cómo usar la app

1. **Ingresa el monto total:** Escribe el total de la cuenta en el campo "Cantidad"
2. **Número de comensales:** Indica cuántas personas van a dividir la cuenta
3. **Propina (opcional):**
   - Activa el switch "Redondear propina"
   - Ajusta el porcentaje de propina usando el slider (0% - 25%)
4. **Calcula:** Presiona el botón "Calcular"
5. **Resultado:** La app mostrará:
   - El total a pagar (con propina si aplica)
   - El monto que debe pagar cada persona

### Ejemplo

```
Cantidad: 1000
Comensales: 4
Propina: 15%
Redondear: Sí

Resultado:
Total a pagar: $1150.00
Cada uno paga: $287.50
```

## 🎨 Capturas de pantalla

_Próximamente: Screenshots de la aplicación_

## 🏗️ Estructura del proyecto

```
app/src/main/java/com/example/dividircuentas/
├── MainActivity.kt          # Actividad principal y lógica de UI
└── ui/theme/               # Temas y estilos de Compose
    ├── Color.kt
    ├── Theme.kt
    └── Type.kt
```

## 🧪 Testing

El proyecto incluye tests unitarios e instrumentados:

```bash
# Tests unitarios
./gradlew test

# Tests instrumentados (requiere dispositivo/emulador)
./gradlew connectedAndroidTest
```

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar la app o quieres reportar un bug:

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

## 📧 Contacto

Desarrollado con ❤️ por [Mariogarluu](https://github.com/Mariogarluu)

¿Preguntas o sugerencias? ¡Abre un issue!
