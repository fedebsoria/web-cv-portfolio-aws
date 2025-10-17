# Personal Portfolio and Web CV

Welcome to my personal portfolio repository. This project serves not only as my calling card but also as a practical demonstration of my skills in creating and managing cloud infrastructure using AWS services.

**Visit the live site:** [https://portfolio.federicosoria.work](https://portfolio.federicosoria.work)

---

### About This Project

The goal was to deploy a static website securely, scalably, and with high performance, following industry best practices. The entire infrastructure was configured manually to demonstrate a deep understanding of each service involved.

### Technology Stack

* **Frontend**: HTML5, CSS3, JavaScript
* **Cloud Infrastructure**:
    * **Storage**: AWS S3
    * **CDN & SSL**: AWS CloudFront & AWS Certificate Manager (ACM)
    * **DNS & Edge Security**: Cloudflare (Proxy, WAF, Rate Limiting)

### Key Infrastructure Features

* **Serverless Architecture**: Cost-effective and no server management required.
* **Security**: The S3 bucket is **private** and only accessible through CloudFront thanks to **Origin Access Control (OAC)**.
* **Performance**: Content is distributed globally through the CloudFront network, ensuring low load times.
* **WAF Protection**: Cloudflare rules are used to mitigate bots and denial-of-service attacks through **Rate Limiting**.

➡️ **[For a detailed technical breakdown, see the infrastructure documentation here](./infrastructure/README.md)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Portfolio Personal y CV Web

Bienvenido al repositorio de mi portfolio personal. Este proyecto no solo sirve como mi carta de presentación, sino también como una demostración práctica de mis habilidades en la creación y gestión de infraestructura cloud utilizando servicios de AWS.

**Visita la web en vivo:** [https://portfolio.federicosoria.work](https://portfolio.federicosoria.work)

---

### Sobre este Proyecto

El objetivo era desplegar un sitio web estático de forma segura, escalable y con un alto rendimiento, siguiendo las mejores prácticas de la industria. Toda la infraestructura ha sido configurada manualmente para demostrar un conocimiento profundo de cada servicio implicado.

### Stack Tecnológico

* **Frontend**: HTML5, CSS3, JavaScript
* **Infraestructura Cloud**:
    * **Almacenamiento**: AWS S3
    * **CDN y SSL**: AWS CloudFront y AWS Certificate Manager (ACM)
    * **DNS y Seguridad Perimetral**: Cloudflare (Proxy, WAF, Rate Limiting)

### Características Clave de la Infraestructura

* **Arquitectura Serverless**: Coste-eficiente y sin necesidad de gestionar servidores.
* **Seguridad**: El bucket de S3 es **privado** y solo accesible a través de CloudFront gracias al **Origin Access Control (OAC)**.
* **Rendimiento**: El contenido se distribuye globalmente a través de la red de CloudFront, garantizando tiempos de carga bajos.
* **Protección WAF**: Se utilizan las reglas de Cloudflare para mitigar bots y ataques de denegación de servicio mediante **limitación de peticiones (Rate Limiting)**.

➡️ **[Para un desglose técnico detallado, consulta la documentación de la infraestructura aquí](./infrastructure/README.md)**
