# Motivo del sistema
Sistema desarrollado para cumplir con las especificaciones de placeToplay.

# Instalacion

Para instalar este sistema tener en cuenta estos pasos:

- Tener instalado las últimas versiones de composer, php, laravel, soap module (en su defecto habilitarla en el servidor).
- Utilizar git clone para copiar el repositorio en algún lugar de su equipo.
- Tener instalado apache y mysql.
- Estando en el mismo directorio del sistema, realizar:
    - composer install (descarga los modulos necesarios de laravel)
    - cp .env-example .env (copia el archivo y lo convierte a .env) si utiliza windows copie el archivo y cree otro con el mismo contenido que se llame .env
    - Utilizar el comando php artisan key:generate
    - Cree una base de datos llamada "data", usuario: root clave: 1234, en caso de no poderla crear exactamente igual, puede dirigirse al archivo .env y cambiar los parametros.
    - Correr el comando php artisan migrate 
    - Finalmente correr php artisan serve, ir al navegador dirigirse a localhost:8000, si todo sale bien deberia aparecer la página para poder iniciar sesión o crear cuenta, cree una cuenta para poder empezar.
    
# Funcionamiento 


Una vez creada la cuenta

- Iniciar sesión, puede dirigirse a la parte superior derecha para realizar transacción, sigue todos los pasos y llena el formulario, si desea que el vendedor sea el mismo comprador le puede dar en persona, debe elegir en los bancos "Banco union colombiana"
- Una vez realizado todo el proceso llega a la página de placeToplay, crear la cuenta, copiar su correo en el espacio indicado, dar siguiente.
- Finalmente hacer los pasos estipulados por placeToplay.


