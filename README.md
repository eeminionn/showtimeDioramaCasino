# Diorama de Casino – Fabricación Digital (UDD)

## 👤 Autor

**Emilio Abarca**  
**Curso:** Fabricación Digital – Diseño de Interacción Digital  
**Institución:** Universidad del Desarrollo (UDD)  
**Fecha de entrega:** 3 de julio de 2025  

---

## 🎞️ Demo del Diorama en funcionamiento

<img src="Fotos/resultadoFinal/DemoRuleta.gif" alt="Demo Ruleta" width="500"/>

---

## 📌 Etapas del Proyecto

### Etapa 1: Idear y Modelar

- Conceptualización de ruleta y elementos de casino.
- Modelado y texturizado en Blender de:
  - Ruleta
  - Dados
  - Fichas de póker
  - Cartas

<h4>🎨 Renders</h4>
<img src="Fotos/resultadoFinal/RenderFicha.png" alt="Render ficha" width="400"/>
<img src="Fotos/resultadoFinal/RenderRuleta.jpg" alt="Render ruleta" width="400"/>

---

### Etapa 2: Prototipado y Manufactura Inicial

- Impresión de primeras fichas y dados para prueba de escala.
- Rediseño y ajustes.
- Impresión final de ruleta y accesorios.

**Perfil de impresión 3D:**
- Altura de capa: 0.12 mm  
- Velocidad: 80 mm/s  
- Soportes: tipo árbol  
- Infill: 10% patrón giroide  
- Impresora: Ender 3 V3 SE  
- Material: PLA  

<h4>🧱 Piezas impresas y prototipos</h4>
<img src="Fotos/resultadoFinal/zoomPiezas.JPG" alt="Piezas 1" width="400"/>
<img src="Fotos/resultadoFinal/zoomPiezas2.JPG" alt="Piezas 2" width="400"/>
<img src="Fotos/resultadoFinal/fotoPrincipalDiorama.JPG" alt="Vista general" width="500"/>

---

### ⚙️ Etapa 3: Test Mecánicos y Electrónica

- Componentes:
  - Arduino Nano  
  - TB6612FNG (puente H)  
  - Motor DC N20 600 RPM  
  - Batería LiPo 7.4V 1200 mAh  
- PCB:
  - Diseñada en Eagle
  - Mecanizada en CNC Othermill Pro

<h4>🔧 Fabricación electrónica (PCB)</h4>
<img src="Fotos/resultadoFinal/PCB1.png" alt="PCB1" width="400"/>
<img src="Fotos/resultadoFinal/PCB2.png" alt="PCB2" width="400"/>
<img src="Fotos/resultadoFinal/PCB3.png" alt="PCB3" width="400"/>
<img src="Fotos/resultadoFinal/ProcesoOthermill1.jpeg" alt="Othermill 1" width="400"/>
<img src="Fotos/resultadoFinal/ProcesoOthermill2.jpg" alt="Othermill 2" width="400"/>

---

### Etapa 4: Ensamblaje Físico

- Ruleta sobre base de madera CNC.
- Mesa tipo póker forrada en terciopelo verde (cubre electrónica).
- Posicionamiento de dados, fichas y cartas.

<h4>🪵 Ensamblaje de la base de madera</h4>
<img src="Fotos/resultadoFinal/cncMadera1.jpg" alt="CNC Madera" width="400"/>
<img src="Fotos/resultadoFinal/ProcesoBaseDeMadera1.jpg" alt="Base madera 1" width="400"/>
<img src="Fotos/resultadoFinal/ProcesoBaseDeMadera2.jpg" alt="Base madera 2" width="400"/>
<img src="Fotos/resultadoFinal/ProcesoBaseDeMadera3.jpg" alt="Base madera 3" width="400"/>

<h4>🪙 Ensamblaje de ruleta</h4>
<img src="Fotos/resultadoFinal/ProcesoRuleta1.jpg" alt="Ruleta ensamblaje 1" width="400"/>
<img src="Fotos/resultadoFinal/ProcesoRuleta2.jpg" alt="Ruleta ensamblaje 2" width="400"/>

---

### 🖌️ Etapa 5: Post-Procesado

- Ruleta: pintada con acrílico dorado, decorada con vinilos de colores (rojo, negro, verde).
- Fichas y cartas: decoradas con vinilo cortado.
- Dados: puntos pintados con acrílico negro.
- Base de madera: lijada y barnizada.
- Detalles adicionales pintados a mano.

<h4>✂️ Corte de vinilo (negro, rojo y verde)</h4>

Para lograr los detalles gráficos y cromáticos en las piezas del diorama, se utilizó vinilo adhesivo de colores rojo, negro y verde.

**Proceso de corte:**
1. **Extracción de caras desde Fusion 360** usando el plugin **ShaperUtilities** para generar archivos SVG desde las superficies donde iría el vinilo.
2. **Configuración en Leonardo Design Studio**: importación de SVG, ajuste de escala y definición del punto cero (0,0).
3. **Corte con plóter modelo "Romeo"**, sobre superficie de salvacorte.
4. **Aplicación manual del vinilo** sobre las piezas impresas 3D.

<img src="Fotos/resultadoFinal/PlotterDeCorte1.jpg" alt="Corte de vinilo" width="400"/>

<h4>🪵 Lijado y detalles de la base</h4>
<img src="Fotos/resultadoFinal/zoomMadera.JPG" alt="Zoom madera" width="400"/>

---

### 📄 Etapa 6: Documentación

- Memoria PDF
- Lámina de fabricación digital
- Planos CAD (DWG/DXF)
- Fichas técnicas por pieza

#### Ficha Técnica

| Pieza           | Proceso | Material     | Peso [g] | Tiempo [min] | Parámetros impresión   | Post-Proceso                                           |
|----------------|---------|--------------|----------|--------------|-------------------------|--------------------------------------------------------|
| Ruleta         | 3DP     | PLA          | 87       | 540          | 0.12 mm, 80 mm/s        | Pintura acrílica + vinilo (SVG desde Fusion, plóter)   |
| Dados          | 3DP     | PLA          | 10       | 40           | 0.12 mm, 80 mm/s        | Pintura negra                                          |
| Cartas         | 3DP     | PLA          | 8        | 30           | 0.12 mm, 80 mm/s        | Vinilo (SVG desde Fusion 360, corte en plóter Romeo)   |
| Fichas         | 3DP     | PLA          | 15       | 45           | 0.12 mm, 80 mm/s        | Vinilo decorativo (corte desde SVG, plóter Romeo)      |
| PCB            | CNC     | FR1          | -        | 30           | Fresa 0.8 mm            |                                                        |
| Base de Madera | CNC     | MDF 10 mm    | -        | 4            | Fresa 6 mm              | Lijado, barnizado                                      |

---

##  Presentación Final

<img src="Fotos/resultadoFinal/DioramaFinalPresentacion.jpg" alt="Diorama Final" width="600"/>

---

## 🛡️ Derechos de autor y propiedad de los modelos

Todos los modelos 3D, componentes electrónicos, diseño de PCB, imágenes, renders y fotografías presentes en este repositorio fueron **diseñados, modelados y fabricados por Emilio Abarca** como parte del proyecto final del curso **Fabricación Digital** de la carrera **Diseño en Interacción Digital** (UDD, 2025).

Cualquier uso, reproducción o distribución de estos materiales debe contar con la debida atribución al autor.

---
