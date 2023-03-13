REQUIREMENTS = 
argon2-cffi (nos permite encriptar las contraseñas)
djoser (nos proporciona un sistema para autenticarnos)
djangorestframework_simplejwt (nos permite hacer login con un token JWT)
django-storages (nos permite trabajar con AWS)
PyJWT (refererente tokens --> jwt)
social-auth-app-django y social-auth-core(Esto es para hacer login con google, facebook etc)


Nota: Siempre que agregamos un nuevo modelo de usuario tenemos que reacer la base de datos (este modelo se hace al inicio del proyecto 
	django) ya que la base de datos puede fallar

1. Migramos el proyecto de b_v1 a uno nuevo.
2. Para hacer este blog vamos a utilizar https://djoser.readthedocs.io/en/latest/ (djoser nos permite hacer autenticacion
	con restframework django (uno de los mejores sistemas de autenticacion que hay))
3. Ahora en la terminal de django ejecutamos pip install djoser, pip install djangorestframework_simplejwt==4.8.0, 
	pip install social-auth-app-django==4.0.0, 1, 
	
	(en el momento en que el usuario haga login el servidor responde con un TOKEN_JWT (token de acceso)
	este token cada vez que refrescamos la pagina el token se borra y tenemos por seguridad volver a llamar al token)

	(este token lo debemos guardar en el local storage o en los cookies
	entonces cuando queramos hacer algo en la pagina que requiera que estemos autenticados podemos revisar en alguno de estos
	lugares tenemos el token de acceso para posteriormente enviar el token de acceso al servidor y validar si podemos
	continuar con lo que ibamos a hacer)

	(y asi no tenemos que hacer autenticacion cada vez que cerramos la pantalla o el sitio)

	(Configuramos en core)

4. 
5. 
6. 
7. 
8. 
9. 
10. 
11. 
12. 
13. 
14. 
15. 
16. 
17. 
18. 
19. 
20. 
21. 
