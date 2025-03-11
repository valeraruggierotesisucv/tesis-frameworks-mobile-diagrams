# Comparación y Evaluación de cinco Frameworks Web de Backend

## Descripción Aplicación
Es una aplicación móvil diseñada para la gestión de eventos e interacción entre usuarios. Incluye funcionalidades esenciales como la administración de eventos, la conexión entre usuarios y características sociales, tales como seguidores, notificaciones y comentarios.

## Implementación
Aplicación móvil implementada en 3 frameworks de desarrollo móvil distintos:
- React Native: https://github.com/valeraruggierotesisucv/reactNative-app
- Flutter: https://github.com/valeraruggierotesisucv/flutter-app
- Ionic: https://github.com/valeraruggierotesisucv/ionic-app

## Metodología
La aplicación esta requisitada y diseñada usando la metodología RUP. Al ser una metodología dirigida por casos de uso, se podrá realizar una traza desde los requisitos, hasta el código implementado en cada framework. Esta trazabiliad permite verificar la transformación de los requisitos en elementos de modelo sucesores, resultantes del análisis y diseño, implementación, pruebas y despliegue. De esta manera se podrá comparar cada framework y las aplicaciones resultantes de manera más efectiva.

| <img src="img/trazabilidadCasosUsoDisciplinas.png" width=80% style="background-color:white;"><br><sub>Trazabilidad de Requisitos por disciplinas</sub> |
| :---: |

## Requisitos
Dada la extensión de los casos de uso, estos fueron organizados por paquetes

![paquetes](Requisitos/Casos%20de%20Uso/diagramas/UseCaseDiagramPackages.svg)


### Autenticación
![modelo caso de uso usuario no registrado](Requisitos/Casos%20de%20Uso/diagramas/UseCaseDiagramAutentication.svg)

### Manejo de Eventos
![modelo caso de uso usuario registrado](Requisitos/Casos%20de%20Uso/diagramas/UseCaseDiagramEventsManagement.svg)

### Interacciones Sociales
![modelo caso de uso usuario administrador](Requisitos/Casos%20de%20Uso/diagramas/UseCaseDiagramSocialInteractions.svg)

### Manejo de Usuarios
![modelo caso de uso usuario administrador](Requisitos/Casos%20de%20Uso/diagramas/UseCaseDiagramUserManagement.svg)

### Especificaciones de casos de uso
La descripción de cada caso de uso lo podrá ver en: [Especificaciones de los casos de uso](Requisitos/Casos%20de%20Uso/UseCasesSpecification.md)

### Prototipo de pantallas
Los prototipos de las pantallas las podrá ver en: [Prototipo en Figma](https://www.figma.com/design/DONtPlkrGIl6SPWpOyRAzo/Eventify?node-id=2-197&t=Ajn1pEIF9eLvgRg2-1)

## Modelo de Análisis

### Diagrama de clases de análisis
#### Autenticación
![diagrama de clases de autenticación](Análisis/Clases%20de%20Análisis/diagramas/analysisClassDiagramAuthentication.svg)

#### Manejo de Eventos
![diagrama de clases de manejo de eventos](Análisis/Clases%20de%20Análisis/diagramas/analysisClassDiagramEventsManagements.svg)

#### Interacciones Sociales
![diagrama de clases de interacciones sociales](Análisis/Clases%20de%20Análisis/diagramas/analysisClassDiagramSocialInteractions.svg)

#### Manejo de Usuarios
![diagrama de clases de manejo de usuarios](Análisis/Clases%20de%20Análisis/diagramas/analysisClassDiagramUserManagement.svg)

### Arquitectura de análisis
![arquitectura de análisis](Análisis/Paquetes%20de%20Análisis/diagramas/analysisPackageDiagram.svg)

### Realización de análisis de casos de uso

#### Diagrama de clases de análisis de UC6 – Publicar Evento
![Diagrama de clases de análisis de UC6](Análisis/Clases%20de%20Análisis/UC6%20Análisis/diagramas/analysisClassDiagramUC6.svg)

#### Diagrama de colaboración de análisis de UC6 – Publicar Evento
![Diagrama de colaboración de análisis de UC6](Análisis/Clases%20de%20Análisis/UC6%20Análisis/diagramas/analysisClassDiagramUC6.svg)

## Modelo de Diseño Framework React Native

### Arquitectura de Sistema
![arquitectura de sistema de Framework React Native](Diseño/React%20Native/diagramas/architecture_design.svg)

### Caso de Estudio UC6 - Publicar Evento

#### Diagrama de Clases de Diseño
![Diagrama de Clases de Diseño Simplificado UC6 - React Native](Diseño/React%20Native/UC%206%20Diseño/diagramas/DesignClassDiagramMinified.svg)

#### Diagrama de Secuencia
![Diagrama de Secuencia UC6 - React Native](Diseño/React%20Native/UC%206%20Diseño/diagramas/InteractionSequenceDiagram.svg)

#### Trazabilidad con Clases de Análisis
![Trazabilidad con Clases de Análisis UC6 - React Native](Diseño/React%20Native/UC%206%20Diseño/diagramas/TraceAnalysisClassDiagram.svg)


## Modelo de Diseño Framework Flutter

### Arquitectura de Sistema
![arquitectura de sistema de Framework Flutter](Diseño/Flutter/diagramas/architecture_design.svg)

### Caso de Estudio UC6 - Publicar Evento

#### Diagrama de Clases de Diseño
![Diagrama de Clases de Diseño UC6 - Flutter](Diseño/Flutter/UC%206%20Diseño/diagramas/DesignClassDiagram.svg)

#### Diagrama de Secuencia
![Diagrama de Secuencia UC6 - Flutter](Diseño/Flutter/UC%206%20Diseño/diagramas/InteractionSequenceDiagram.svg)

#### Trazabilidad con Clases de Análisis
![Trazabilidad con Clases de Análisis UC6 - Flutter](Diseño/Flutter/UC%206%20Diseño/diagramas/TraceAnalysisClassDiagram.svg)


## Modelo de Diseño Framework Ionic

### Arquitectura de Sistema
![arquitectura de sistema de Framework Ionic](Diseño/Ionic/diagramas/architecture_design.svg)

### Caso de Estudio UC6 - Publicar Evento

#### Diagrama de Clases de Diseño
![Diagrama de Clases de Diseño UC6 - Ionic](Diseño/Ionic/UC%206%20Diseño/diagramas/DesignClassDiagram.svg)

#### Diagrama de Secuencia
![Diagrama de Secuencia UC6 - Ionic](Diseño/Ionic/UC%206%20Diseño/diagramas/InteractionSequenceDiagram.svg)

#### Trazabilidad con Clases de Análisis
![Trazabilidad con Clases de Análisis UC6 - Ionic](Diseño/Ionic/UC%206%20Diseño/diagramas/TraceAnalysisClassDiagram.svg)
