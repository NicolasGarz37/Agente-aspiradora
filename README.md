# Agente aspiradora NetLogo
## Agentes inteligentes
Un agente es una entidad que percibe su ambiente a través de sensores y actúa mediante actuadores.

## Requisitos
- Descargar Netlogo

## Características
- La aspiradora se mueve **solo en direcciones ortogonales** (arriba, abajo, izquierda y derecha).
- **Limpia la basura** cuando pasa sobre un cuadro sucio.
- Tiene **batería limitada**, reduciéndose con cada movimiento o limpieza.
- Cuando la batería llega a **0**, la aspiradora se **detiene**.

## Descripción
Este proyecto en NetLogo simula una aspiradora inteligente que se mueve en un ambiente [m* n]editable, limpiando basura mientras tenga batería. La aspiradora solo se desplaza en direcciones ortogonales (arriba, abajo, izquierda y derecha), detecta la suciedad en su camino y la elimina. Su batería se reduce con cada movimiento o limpieza, y cuando llega a 0, la aspiradora se detiene. Además, se muestra el nivel de batería sobre la aspiradora en color negro para un mejor seguimiento.

## Uso
1. Cargue el código en Netlogo o abra el archivo, copie y pegue el código en el área de edición
2. Crea los siguientes botones:
  - **Botón `setup`** → Genera el mundo, coloca la basura y crea la aspiradora.  
  - **Botón `go`** → Inicia la simulación. La aspiradora se moverá limpiando hasta quedarse sin batería.
3. Puede modificar el ambiente [m n] y la batería que tendra la aspiradora
## Ejemplo de salida esperada
![image](https://github.com/user-attachments/assets/46f0963d-3d06-4461-b9f9-e71cb97f9c21)

## Archivos disponibles
- Agente arpiradora.nlogo 
