# PRD.md

## Contexto y objetivo
GameDate es una app web mobile-first para gamers que quieren conocer personas cercanas para jugar videojuegos juntos en la vida real. El problema que busca resolver es que muchos jugadores no tienen una forma simple de encontrar otros gamers en su ciudad con intereses similares.

El objetivo del MVP es permitir que los usuarios descubran jugadores cercanos, hagan match mediante un sistema tipo swipe y puedan iniciar una conversación para quedar y jugar.

## Usuario objetivo
Gamers jóvenes adultos (principalmente entre 20 y 30 años), generalmente no profesionales, que quieren conocer gente en su ciudad con intereses de videojuegos similares y potencialmente también generar conexiones sociales o románticas.

## Caso de uso principal
Un usuario se registra en la aplicación, crea su perfil gamer subiendo fotos y seleccionando sus juegos y plataforma.  
Después descubre jugadores cercanos mediante un sistema de swipe.  
Si dos usuarios se gustan mutuamente, se genera un match y pueden iniciar un chat para conocerse y eventualmente quedar para jugar.

## Alcance

### In scope
- Registro y creación de cuenta de usuario
- Perfil gamer con fotos y datos básicos
- Descubrimiento de jugadores cercanos
- Sistema de swipe tipo Tinder
- Sistema de match cuando ambos usuarios hacen like
- Chat básico entre usuarios que han hecho match
- Soporte de geolocalización
- Soporte multilenguaje (inglés y español)
- Registro de encuentros o citas para jugar

### Out of scope
- Videollamadas dentro de la app
- Sistemas de ranking o competitividad
- Algoritmos avanzados de recomendación
- Moderación avanzada de contenido
- Notificaciones push
- Sistemas de pago

## Requisitos funcionales

FR-01: El usuario puede crear una cuenta mediante autenticación básica.

FR-02: El usuario puede crear y editar un perfil gamer con:
- foto de perfil o fotos
- lista de juegos
- plataforma de juego
- ciudad o ubicación

FR-03: El sistema puede mostrar perfiles de jugadores cercanos al usuario.

FR-04: El usuario puede indicar interés o rechazo mediante un sistema de swipe (like / skip).

FR-05: Cuando dos usuarios se dan like mutuamente, el sistema crea un match.

FR-06: Los usuarios con match pueden iniciar una conversación mediante un chat básico.

FR-07: El sistema debe permitir subir y mostrar fotos en los perfiles.

FR-08: El sistema debe soportar geolocalización para mostrar jugadores cercanos.

FR-09: La aplicación debe permitir cambiar entre idioma inglés y español.

FR-10: Los usuarios pueden registrar que han quedado para jugar (evento o cita derivada de un match).

## Requisitos no funcionales
- Mobile-first UX optimizada para dispositivos móviles.
- Tiempo de carga rápido en conexiones móviles normales.
- Autenticación segura y protección básica de datos de usuario.
- Compatibilidad con navegadores modernos móviles.
- Interfaz simple y clara enfocada en el flujo principal del producto.

## Métrica de éxito
- Número de matches generados entre usuarios.
- Número de usuarios que suben fotos a su perfil.
- Número de conversaciones iniciadas después de un match.
- Número de encuentros o citas registradas entre usuarios.

## Dependencias y riesgos
- Dependencia de geolocalización para el descubrimiento de usuarios cercanos.
- Necesidad de una masa crítica de usuarios para generar matches.
- Riesgo de perfiles incompletos que reduzcan el engagement.

## Open questions / Suposiciones
- Se asume un único tipo principal de usuario (gamer social no profesional).
- Se asume que el chat inicial será simple (solo mensajes de texto).
- No se define aún un sistema de moderación más avanzado.
- No se define aún el diseño exacto del registro de eventos o citas.