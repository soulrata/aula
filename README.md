# Asignación de Aulas

Una aplicación web responsiva para configurar aulas y asignar asientos de forma interactiva. La herramienta permite:

- **Configurar aulas** ingresando:
  - **Número de Aula**
  - **Tipo de Dispositivo:** (seleccionable entre _PC_ o _Tablet_)
  - **Referente de Aula**
  - **Cantidad de Asientos**

- **Asignar asientos** en una interfaz visual en la que se muestra una tabla de asientos, que se adapta automáticamente para dispositivos móviles. Al tocar una celda se alterna su estado, indicando si el asiento está marcado o no.

- **Prevención de pérdidas:** Se muestra una advertencia si se intenta recargar o cerrar la página para evitar la pérdida accidental de la configuración.

## Características

- **Interfaz de configuración:** Agrega y quita aulas con un formulario dinámico.
- **Interfaz de asignación:** Genera tablas de asientos para cada aula configurada.
- **Diseño responsivo:** La interfaz se adapta a dispositivos de escritorio, tablet y móvil. En móviles se aprovecha el ancho disponible mediante el uso de _aspect-ratio_ para mantener las celdas cuadradas y facilitar su selección.
- **Selección de dispositivo:** Se utiliza un desplegable con las opciones _PC_ y _Tablet_ para garantizar la entrada de datos consistentes.
- **Advertencia de cierre:** Se activa un aviso para evitar recargar o cerrar la página accidentalmente.

## Tecnologías Utilizadas

- **HTML5** para la estructura.
- **CSS3** para la presentación y estilos personalizados.
- **JavaScript** y **jQuery** para la interacción y lógica de la aplicación.

## Uso

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/soulrata/aula.git
