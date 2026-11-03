Jorge Andrés Ruiz López

Rol en el equipo: 

```mermaid
flowchart TD
  A[Deploy to production] --> B{is it friday?};
  B --Yes--> C{Do not deploy};
  B --No--> D{Deploy};
  C ----> E{Enjoy your weekend!};
  D ----> E{Enjoy your weekend!};
