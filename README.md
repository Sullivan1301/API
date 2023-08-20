# API
Learning to write APIs
paths:
  /Student:
    get:
      x-readme-description: Obtenez des informations sur les étudiants existants
      tags:
        - Student
      summary: Mettez à jour un étudiant existant
      description: Mettez à jour un étudiant existant par ID
      operationId: updateStudent
      # ...
    post:
      x-readme-description: Ajoutez un nouvel étudiant à l'école
      tags:
        - Student
      summary: Ajoutez un nouvel étudiant à l'école
      description: Ajoutez un nouvel étudiant à l'école
      operationId: addStudent
      # ...
