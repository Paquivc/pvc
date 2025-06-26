---
attachments: [Clipboard_2025-06-25-09-51-53.png]
title: Ramas (arbolito) GIT
created: '2025-06-24T12:17:19.459Z'
modified: '2025-06-25T10:30:31.316Z'
---

# Ramas (arbolito) GIT

- git flow -> flujo del git
![](@attachment/Clipboard_2025-06-25-09-51-53.png)
- git branch "rama" -> Crea una rama
- git checkout "rama" -> Cambiar de rama
- git checkout -b NOMBRE -> crear una rama nueva
- git merge rama -> Fusionar ramas
- Pasos para fusionar:
  - git checkout rama_destino
  - git merge rama_a_fusionar
  - git git commit -m "Rama Fusionada"
  - git push --set -upstream origin NOMBRE -> sincroniza 1 a 1 el remoto del origen. Se hace 1 vez, al ppio.
  

  
