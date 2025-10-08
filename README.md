# salario-minimo
Una actividad acerca del salario mínimo en México
PASO 1: Crear una Cuenta en ngrok
1.1 Acceder al sitio web

Abre tu navegador
Ve a: https://dashboard.ngrok.com/signup
Verás la página de registro

1.2 Opciones de registro
Puedes registrarte de 3 formas diferentes:
Opción A: Con Google (Más rápido ⚡)

Haz clic en el botón "Sign up with Google"
Selecciona tu cuenta de Google
Autoriza el acceso
¡Listo! Tu cuenta se crea automáticamente

Opción B: Con GitHub

Haz clic en el botón "Sign up with GitHub"
Inicia sesión en GitHub si no lo estás
Autoriza ngrok
Tu cuenta se crea automáticamente

Opción C: Con correo electrónico

Ingresa tu correo electrónico en el campo
Crea una contraseña segura
Haz clic en "Sign up"
Revisa tu correo y confirma tu cuenta haciendo clic en el enlace de verificación

1.3 Verificación

Si usaste Google o GitHub: ¡Ya estás dentro! ✅
Si usaste email: Revisa tu bandeja de entrada (y spam) y confirma tu correo


🔑 PASO 2: Obtener tu AuthToken
2.1 Acceder al Dashboard

Una vez que hayas iniciado sesión, serás redirigido automáticamente al dashboard
Si no es así, ve a: https://dashboard.ngrok.com/

2.2 Encontrar tu AuthToken

En el menú lateral izquierdo, busca y haz clic en "Your Authtoken" o "Getting Started"
También puedes ir directamente a: https://dashboard.ngrok.com/get-started/your-authtoken

2.3 Copiar el AuthToken

Verás una sección que dice "Your Authtoken"
Debajo encontrarás un código largo que se ve así:

   2abc3dEfGh4IJklMnOpqR5sTuv6_Esteesfalso

Haz clic en el botón "Copy" 📋 o selecciona todo el texto y cópialo manualmente
📊 Plan Gratuito de ngrok
Con la cuenta gratuita tienes:

✅ 1 túnel activo a la vez
✅ 40 conexiones por minuto
✅ URLs aleatorias (cambian cada vez)
✅ Suficiente para proyectos educativos

Limitaciones:

❌ No puedes tener dominios personalizados
❌ El enlace cambia cada vez que reinicias
❌ Solo un túnel simultáneo

🔄 ¿Qué pasa si cierras Colab?
Cuando cierras tu notebook de Google Colab o detienes la ejecución:

El túnel de ngrok se cierra automáticamente
El enlace deja de funcionar
Nadie más podrá acceder a tu aplicación

Para volver a compartir:

Ejecuta nuevamente las celdas de código
Se generará un nuevo enlace diferente
Comparte el nuevo enlace


🆘 SOLUCIÓN DE PROBLEMAS
Problema 1: "Token inválido"
Causa: El token está mal copiado o tiene espacios extra
Solución:

Ve nuevamente a ngrok dashboard
Copia otra vez el token completo
Asegúrate de NO incluir espacios antes o después
Pega entre las comillas correctamente

Problema 2: "Failed to establish tunnel"
Causa: Problemas de conexión o el puerto está ocupado
Solución:

Verifica tu conexión a internet
Reinicia el runtime de Colab: Runtime > Restart runtime
Ejecuta nuevamente todo el código

Problema 3: No aparece el enlace
Causa: La celda no terminó de ejecutar o hubo un error
Solución:

Revisa si hay mensajes de error en rojo
Verifica que instalaste pyngrok: !pip install pyngrok
Ejecuta paso por paso cada celda

Problema 4: El enlace abre pero dice "Application error"
Causa: Streamlit no se está ejecutando correctamente
Solución:

Verifica que ejecutaste: !streamlit run app.py --server.port 8501 &
Espera 10-15 segundos después de ejecutar
Refresca el enlace en tu navegador


📌 RESUMEN RÁPIDO
Para empezar:

🌐 Crear cuenta en https://dashboard.ngrok.com/signup
🔑 Copiar tu AuthToken desde el dashboard
💻 Pegar el token en tu código de Colab
▶️ Ejecutar y compartir el enlace generado

Recuerda:

Tu token es personal y secreto 🔐
El enlace cambia cada vez que reinicias ♻️
Funciona solo mientras Colab esté ejecutándose ⚡


📚 RECURSOS ADICIONALES
Documentación oficial de ngrok:

https://ngrok.com/docs

Dashboard de ngrok:

https://dashboard.ngrok.com/

Soporte:

https://ngrok.com/support

Esto fue para p¡obtener tu token sigue el instructivo
--------------------------------------------------------------------------------------------------------------------------------
Para continuar en google drive crea una carpeta que diga
CIENCIA DE DATOS y suelta el xls de salario minimo ahí
-----------------------------------------------------------------------------------------------------

Los espacios largos entre lineas de código es que son otros bloques
No te olvides de cambiar el authoken donde dice que va ahí, entre las comillas, por favor no las borres

al final ve y haz click en el link que da el codigo para ver tu aplicacion
Suerte
