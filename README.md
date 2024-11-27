# dns-hardlan
Un sistema de DNS descentralizado que permita a los usuarios registrar, consultar y gestionar dominios de forma segura utilizando blockchain. Este proyecto garantizaría resistencia a ataques como el DNS spoofing o el DNS hijacking.

Proyecto: DNS Seguro y Descentralizado Basado en Blockchain

Visión:
Crear un sistema de DNS descentralizado y seguro, accesible para todos, que aproveche blockchain para proteger dominios contra ataques y garantizar la privacidad, la transparencia y la resistencia a la censura.
1. Objetivos del Proyecto

    Seguridad:
        Proteger registros de dominios contra ataques como DNS spoofing y DNS hijacking.
        Garantizar la integridad y la disponibilidad de los registros en la red.

    Descentralización:
        Eliminar puntos únicos de fallo utilizando blockchain y tecnologías distribuidas.

    Accesibilidad:
        Proporcionar una interfaz sencilla para que cualquier persona o entidad pueda registrar y gestionar dominios.

    Impacto Comunitario:
        Desarrollar un proyecto libre y de código abierto que beneficie a la comunidad global.

2. Funcionalidades Iniciales

    Registro de Dominios:
        Permitir a los usuarios registrar dominios únicos (ejemplo: miweb.dns).
        Asociar una dirección IP al dominio registrado.

    Resolución de Dominios:
        Crear un mecanismo que traduzca dominios en direcciones IP consultando la blockchain.

    Interfaz de Usuario:
        Plataforma web sencilla para registrar, consultar y gestionar dominios.

    Consulta de Blockchain:
        API o nodo público para permitir la integración con otros sistemas.

3. Tecnología Sugerida

    Blockchain:
        Polygon: Red Ethereum de bajo costo con alta velocidad y compatibilidad con contratos inteligentes.
        Alternativa: Ethereum para mayor adopción global.

    Almacenamiento Distribuido:
        IPFS: Para almacenar información adicional como registros TXT o descripciones asociadas al dominio.

    Frontend:
        React.js para crear una interfaz de usuario amigable.

    Backend:
        Node.js para manejar las conexiones y consultas entre usuarios y la blockchain.

    Contratos Inteligentes:
        Solidity para implementar el registro y la resolución de dominios.
