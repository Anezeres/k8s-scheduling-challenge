# Kubernetes Party Lab 🎉
¡Bienvenidos al Kubernetes Party Lab! Este proyecto es una simulación divertida y educativa que utiliza Kubernetes para organizar una fiesta temática donde los Pods (invitados) deben cumplir con ciertas reglas para unirse a las diferentes salas de fiestas (namespaces). Cada sala tiene requisitos específicos, como taints, tolerations y node affinity, que los Pods deben respetar para ser programados correctamente.

# 🎯 Objetivo del Proyecto
El objetivo de este proyecto es aprender y practicar conceptos avanzados de Kubernetes, como:

- Namespaces: Para aislar recursos en diferentes "salas de fiestas".
- Taints y Tolerations: Para restringir qué Pods pueden ser programados en ciertos nodos.
- Node Affinity: Para asegurar que los Pods se programen en nodos con etiquetas específicas.
- Annotations: Para agregar metadatos adicionales a los recursos.

A través de esta simulación, los participantes podrán entender cómo estos conceptos funcionan en un entorno real de Kubernetes y cómo se aplican en la gestión de recursos y la programación de cargas de trabajo.

# 🛠️ Conceptos Clave
- Namespaces
Los namespaces son una forma de dividir y aislar recursos en un clúster de Kubernetes. En este proyecto, cada sala de fiestas es un namespace que representa un entorno independiente donde los Pods pueden desplegarse.

- Taints y Tolerations
Los taints son restricciones que se aplican a los nodos para evitar que ciertos Pods se programen en ellos. Los tolerations son configuraciones que se agregan a los Pods para permitirles ser programados en nodos con taints específicos. En este proyecto, los taints representan las reglas de entrada a cada sala, y los tolerations son las "invitaciones" que los Pods necesitan para unirse.

- Node Affinity
El node affinity es una regla que permite a los Pods especificar en qué nodos prefieren ser programados, basándose en las etiquetas de los nodos. En este proyecto, el node affinity asegura que los Pods solo se programen en nodos que coincidan con el estilo musical de la sala.

- Annotations
Las annotations son metadatos que se pueden agregar a los recursos de Kubernetes para proporcionar información adicional. En este proyecto, las annotations se utilizan para incluir detalles como el nombre del estudiante y sus preferencias musicales.

# 🚀 Cómo Funciona el Proyecto
- Creación de Salas (Namespaces): Cada sala de fiestas se crea como un namespace en Kubernetes, lo que permite aislar los recursos y configuraciones específicas de cada sala.

- Configuración de Restricciones (Taints): Se aplican taints a los nodos para restringir el acceso a las salas. Solo los Pods con las tolerations correctas pueden ser programados en estos nodos.

- Configuración de Invitaciones (Tolerations): Los Pods deben configurarse con las tolerations adecuadas para poder unirse a las salas que les corresponden.

- Preferencias Musicales (Node Affinity): Los Pods pueden configurarse con node affinity para asegurar que solo se programen en nodos que coincidan con el estilo musical de la sala.

- Documentación y Anotaciones: Cada Pod incluye annotations con información adicional, como el nombre del estudiante y sus preferencias musicales.

# 📜 Conclusión
El Kubernetes Party Lab es una forma creativa y práctica de aprender conceptos avanzados de Kubernetes. A través de esta simulación, los participantes pueden entender cómo funcionan los namespaces, taints, tolerations, node affinity y annotations en un entorno real. Este proyecto no solo refuerza los conocimientos técnicos, sino que también fomenta la colaboración y el trabajo en equipo.

# 🎉 ¡Gracias por Visitar Nuestra Fiesta!
Esperamos que este proyecto te haya ayudado a entender mejor los conceptos de Kubernetes y que hayas disfrutado de esta experiencia única. ¡A programar se ha dicho! 🚀
