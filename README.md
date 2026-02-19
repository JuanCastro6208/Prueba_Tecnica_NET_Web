# SaludoApp - Aplicación Web en Blazor Server

## Descripción

**SaludoApp** es una aplicación web desarrollada con Blazor Server que permite al usuario ingresar su nombre y recibir un saludo personalizado en pantalla.

El proyecto cumple con los requerimientos funcionales solicitados e incluye validación de campo, manejo de eventos y contador de clics como funcionalidad adicional.

---

## Objetivo

Crear una aplicación web básica en Blazor que permita:

- Ingresar un nombre.
- Mostrar un saludo personalizado.
- Validar que el campo no esté vacío.
- Implementar buenas prácticas básicas en Blazor.

---

## Tecnologías Utilizadas

- Blazor Server (.NET 8)
- ASP.NET Core
- C#
- Bootstrap (estilos básicos)

---

## Requerimientos Funcionales Implementados

✔ Campo de texto con `@bind` para enlazar datos  
✔ Botón **"Saludar"** con evento `@onclick`  
✔ Mensaje dinámico: `Hola, [Nombre]!`  
✔ Validación usando `string.IsNullOrWhiteSpace()`  
✔ Contador de clics (Bonus)  
✔ Mensaje en color personalizado (Bonus)  

---

## Estructura Relevante del Proyecto

```
SaludoApp/
│
├── Components/
│   ├── Pages/
│   │   └── Home.razor
│   ├── Layout/
│   ├── App.razor
│   └── Routes.razor
│
├── Program.cs
└── SaludoApp.csproj
```

---

## Implementación Técnica

La lógica principal se encuentra en:

```
Components/Pages/Home.razor
```

### Características Clave

- Uso de `@bind` para enlazar el input con la variable `nombre`.
- Método `Saludar()` dentro de `@code`.
- Validación previa antes de mostrar el saludo.
- Renderizado condicional con `@if`.
- Contador de clics dinámico.
- Uso de clases Bootstrap para estilo visual.

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/JuanCastro6208/Prueba_Tecnica_NET_Web.git
```

2. Abrir el proyecto en Visual Studio 2022 o superior.

3. Ejecutar el proyecto:

```bash
dotnet run
```

4. Abrir en el navegador:

```
https://localhost:xxxx
```

---

## Validación del Proyecto

✔ Proyecto configurado correctamente como Blazor Server  
✔ Página principal configurada en `Home.razor` con ruta `/`  
✔ RenderMode configurado como `InteractiveServer`  
✔ No requiere base de datos  
✔ Código claro y organizado  

El proyecto cumple completamente con los criterios de evaluación solicitados.

---

## Autor

Proyecto desarrollado para prueba tecnica de fundamentos en Blazor Server.
