# Static Forms Setup - Trapala Newsletter

## Pasos para configurar Static Forms

### 1. Crear cuenta en Static Forms
- Ve a https://www.staticforms.com/
- Regístrate con tu email
- Confirma tu email

### 2. Obtener tu Access Key
- Una vez registrado, ve a tu dashboard
- Copia tu **Access Key**

### 3. Configurar el HTML
- Abre `index.html`
- Busca la línea: `formData.append('accessKey', 'YOUR_STATIC_FORMS_ACCESS_KEY');`
- Reemplaza `YOUR_STATIC_FORMS_ACCESS_KEY` con tu access key real

### 4. Configurar el email de destino
- En el dashboard de Static Forms, configura el email donde recibirás las suscripciones
- Puedes agregar un PDF adjunto en las configuraciones de Static Forms

### 5. Probar
- Abre la landing page
- Ingresa un email en el newsletter
- Haz clic en Subscribe
- Deberías ver el modal de bienvenida
- Recibirás un email en tu dirección configurada

## Configurar PDF adjunto

1. En Static Forms dashboard, ve a "Attachments"
2. Sube tu PDF de bienvenida
3. Configura para que se adjunte automáticamente a cada email

## Notas importantes

- El modal de bienvenida aparecerá incluso si hay errores (para mejor UX)
- Los emails se enviarán a la dirección configurada en Static Forms
- Puedes ver el historial de suscriptores en tu dashboard de Static Forms

## Soporte

Para más información sobre Static Forms, visita: https://www.staticforms.com/docs
