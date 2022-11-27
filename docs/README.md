# Store-theme Natalia-Alkosto-Store 

NataliaAlkostoStore es una tienda de tecnología basada en la tienda oficial de Alkosto.

Preview
![image](https://user-images.githubusercontent.com/55117122/204119463-b0be341d-5bc4-4ae8-8c78-c0f017a733db.png)
![image](https://user-images.githubusercontent.com/55117122/204119466-d9092602-861f-4eab-af6f-a273134ab9b3.png)
![image](https://user-images.githubusercontent.com/55117122/204119477-e8516a17-a3d6-42b7-a287-d79a7b3cd10d.png)
![image](https://user-images.githubusercontent.com/55117122/204119487-49d38295-4835-4627-8d38-6497a65cb951.png)
![image](https://user-images.githubusercontent.com/55117122/204119495-c7e2aad3-9388-4043-9bae-35e6300ccb6b.png)
![image](https://user-images.githubusercontent.com/55117122/204119508-2c1d8e8f-a5c8-4ac2-8928-3de7a798efed.png)
![image](https://user-images.githubusercontent.com/55117122/204119539-33088be8-c54e-4eee-a2dc-596cae6a26ec.png)

## Configuración

### Paso 1 - Configuración Básica

Acceda a la guía de configuración básica de VTEX IO y siga todos los pasos indicados.

Al final de la configuración, debe tener instalada la interfaz de línea de comandos de VTEX (Toolbelt) junto con un espacio de trabajo de desarrollador en el que puede trabajar.

### Paso 2 - Clonación del repositorio

[Clone]este repositorio en sus archivos locales para poder comenzar a trabajar en él de manera efectiva.

Luego, acceda al directorio del repositorio usando su terminal.

### Paso 3 - Editar el Manifest.json

Una vez en el directorio del repositorio, es hora de editar el manifest.json de la plantilla Minimum Boilerplate.

Una vez en el archivo, debes remplazar los valores de vendor y account. vendor es el nombre de la cuenta que estas trabajando, nuestro partner y account es el nombre que elijas para tu tienda. Por ejemplo:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}
```

### Paso 4 - Instalar apps necesarias

Para usar Store Framework y trabajar en el tema de su tienda, es necesario tener instalados `vtex.store-sitemap` y `vtex.store`.

Ejecute `vtex list` y verifique si esas aplicaciones ya están instaladas. 

Si no lo están, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 - Desinstalar el store-theme predeterminado

Al ejecutar `vtex list`, puede verificar si algún tema está instalado.

Es común tener ya instalado un `vtex.store-theme` cuando inicia el proceso de desarrollo frontal de la tienda. 

Por lo tanto, si lo encuentra en la lista de aplicaciones, copie su nombre y utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme
```

### Paso 6 - Ejecute un preview de la tienda

Entonces ha llegado el momento de cargar todos los cambios que realizó en sus archivos locales a la plataforma. Para eso, use el comando vtex link.

Si el proceso se ejecuta sin errores, se mostrará el siguiente mensaje: App linked successfully. Luego, ejecute el comando vtex browse para abrir una ventana del navegador con su tienda vinculada.

Esto le permitirá ver los cambios aplicados en tiempo real, a través de la cuenta y el espacio de trabajo en el que está trabajando.

Dependencies

"vtex.store": "2.x",
"vtex.store-header": "2.x",
"vtex.product-summary": "2.x",
"vtex.store-footer": "2.x",
"vtex.store-components": "3.x",
"vtex.styleguide": "9.x",
"vtex.slider": "0.x",
"vtex.carousel": "2.x",
"vtex.shelf": "1.x",
"vtex.menu": "2.x",
"vtex.minicart": "2.x",
"vtex.product-details": "1.x",
"vtex.product-kit": "1.x",
"vtex.search-result": "3.x",
"vtex.login": "2.x",
"vtex.my-account": "1.x",
"vtex.flex-layout": "0.x",
"vtex.rich-text": "0.x",
"vtex.store-drawer": "0.x",
"vtex.locale-switcher": "0.x",
"vtex.product-quantity": "1.x",
"vtex.product-identifier": "0.x",
"vtex.product-specification-badges": "0.x",
"vtex.product-review-interfaces": "1.x",
"vtex.telemarketing": "2.x",
"vtex.order-placed": "2.x",
"vtex.stack-layout": "0.x",
"vtex.tab-layout": "0.x",
"vtex.responsive-layout": "0.x",
"vtex.slider-layout": "0.x",
"vtex.iframe": "0.x",
"vtex.breadcrumb": "1.x",
"vtex.sticky-layout": "0.x",
"vtex.add-to-cart-button": "0.x",
"vtex.modal-layout": "0.x",
"vtex.search": "1.x",
"vtex.b2b-organizations": "1.x",
"vtex.store-link": "0.x",
"vtex.css-handles": "0.x",
"vtex.product-list": "0.x",
"vtex.store-icons": "0.x",
"vtex.store-image": "0.x",
"vtex.disclosure-layout": "1.x",
"vtex.product-price": "1.x",
"vtex.checkout-summary": "0.x",
"vtex.overlay-layout": "0.x",
"vtex.product-highlights": "2.x",
"itgloberspartnercl.whatsapp-button": "0.x",
"itgloberspartnercl.bullets-diagramation": "0.x",
"itgloberspartnercl.add-to-cart-info": "0.x",
"itgloberspartnercl.custom-department-search": "0.x",
"itgloberspartnercl.pdf-reader": "0.x",
"itgloberspartnercl.quick-order": "0.x"

PeerDependencies

"vtex.wish-list": "1.x",
"vtex.reviews-and-ratings": "3.x",
"vtex.mega-menu": "2.x"
Custom Apps (Componentes que deben instalarse en la tienda)
"itgloberspartnercl.whatsapp-button": "0.x",
"itgloberspartnercl.bullets-diagramation": "0.x",
"itgloberspartnercl.add-to-cart-info": "0.x",
"itgloberspartnercl.custom-department-search": "0.x",
"itgloberspartnercl.pdf-reader": "0.x",
"itgloberspartnercl.quick-order": "0.x",
"itgloberspartnercl.special-diagramation": "0.x"

Contributors

Yurley Natalia Londoño Roldán
