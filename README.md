# Pautas Basicas

## Descripción del proyecto
Este proyecto está programado en React y debe ser mantenido en este lenguaje a menos que la institución cambie su currícula en diseño web, Por la razon de que año a año se busca que los propios programadores sean estudiantes de la Institucion los cuales hayan sido capacitados en el lenguaje dado en clase

## Cómo clonar e inicializar el proyecto

### Si no se tiene una clave SSH ejecutar:

```
ssh-keygen -t rsa
```

En una con sola PowerShell ejecutar:

```
cat ~/.ssh/id_rsa.pub
```
Copiar lo que aparece en consola

### Agregar la SSH-KEY en Github. 
 
1. En la barra lateral izquierda, haz clic en "SSH and GPG keys".

2. Haz clic en "New SSH key" o "Add SSH key", dependiendo de tu versión de Github.

3. En el campo "Title", ingresa un nombre descriptivo para la clave.

4. En el campo "Key", pega la clave pública SSH que copiaste anteriormente.

5. Haz clic en "Add SSH key" o "Save SSH key", dependiendo de tu versión de Github.


### Para clonar el proyecto con SSH, es necesario ejecutar el siguiente comando en la terminal:

```
git clone git@github.com:LucaCarbonelAnima/Frontend-Anima-Esports.git
```

### Para inicializar el proyecto en React, es necesario instalar todas las dependencias con el siguiente comando:

```
npm install
```


Además, se deben utilizar las normas ES6 para React. Para más información, se puede visitar el siguiente enlace: https://reactjs.org/docs/javascript-environment-requirements.html

Es importante mencionar que no se pueden hacer rebases a la rama principal (main) sin la aprobación de un code review de un compañero de mayor jerarquía.

## Reporte de errores
Los errores deben ser reportados en el respectivo tablero de Jira para que algún compañero pueda tomarlo y solucionarlo.

## Convención de nombres de las branches
Las branches deben estar compuestas por AW/[NroTicket]/[TipoDeTarea].

### Los distintos tipos de tarea pueden ser:

**Update**: Actualización de código depercado o pequeños cambios de código posterior

**Fix**: Arreglo de errores

**Styles**: Agregar estilos a código anteriormente hecho

**Implementation**: Código nuevo agregado sin antecedentes previos

Es importante mencionar que el nombre de la branch debe estar escrito en minúsculas y separado por guiones. Además, el número de ticket debe corresponder al Nro de Ticket en Jira

