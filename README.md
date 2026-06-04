Repositorio de documentación do proxecto Explora Map, traballo de fin de ciclo (TFG) sobre cartograf?a colaborativa con software libre.

Contido do repositorio
docs/
??? diagrams/
?   ??? backend/
?   ?   ??? arquitectura_backend.drawio
?   ?   ??? arquitectura_backend.png
?   ??? erd/
?   ?   ??? erd_conceptual_chen.drawio
?   ?   ??? erd_conceptual_chen.png
?   ??? frontend/
?   ?   ??? arquitectura_frontend.drawio
?   ?   ??? arquitectura_frontend.png
?   ??? gantt/
?   ?   ??? diagrama-gantt.png
?   ??? uml/
?       ??? clases/
?           ??? modelo_clases.drawio
?           ??? modelo_clases.drawio.png
??? wireframes/          # Mockups de interface (Moqups)
??? gu?a de estilos/     # Gu?a de estilos
??? memoria.pdf          # Memoria técnica
??? README.md

Sobre o proxecto

Explora Map é unha aplicación web de mapas colaborativos constru?da ?ntegramente sobre tecnolox?as libres. Permite crear e xestionar mapas personalizados, p?blicos ou privados, con marcadores, categor?as visuais, historial de cambios e un sistema de colaboración por roles e convites.

A aplicación est? despregada en https://explora-mapa.eu sobre infraestrutura europea (Hetzner, Alema?a) e adopta un enfoque de privacy by design: sen rastrexadores externos, sen cookies de terceiros e con minimización de datos persoais.

Diagramas inclu?dos

- Diagrama de descrición da arquitectura do backend. Estrutura: Controller ? Service ? Repository ? BD.
- Diagrama de descrición da arquitectura do frontend. Estrutura: p?xinas, compo?entes, stores e servizos
- Diagrama ENtidade-Relación Conceptual coa notación de Chen. 
- Diagrama UML de clases do dominio.
- Diagrama de Gantt. Planificación en sprints do proxecto

Repositorios relacionados

- Frontend: SPA React + Leaflet
- Backend: API REST Spring Boot
- Deploy: configuración de Docker e intraestrutura

Licenza

Este proxecto est? publicado baixo licenza MIT License. Consulta o ficheiro LICENSE para m?is información.