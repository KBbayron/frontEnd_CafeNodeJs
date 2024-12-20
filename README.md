# Frontend
nota: 
Actualmente tengo Angular 18 instalado en mi maquina.

## INICIAR CON ANGULAR 12 SI YA HAY OTRA VERSION GLOBAL
### Configurar Node.js para usar OpenSSL legacy
Como tengo Angular 18, una verison mas actualizada, necesito algoritmos de hash que no hay en versiones recientes:

1. export NODE_OPTIONS=--openssl-legacy-provider
2. npm install @angular/cli@12 --save-dev
3. npx --ignore-existing -p @angular/cli@12 ng serve

## Crear carpeta de servicios

5. ng g s src/app/services/user

## crear el componente singup

6. ng g c src/app/singup
