---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
weight: 0 # Reihenfolge auf der Startseite
external_link: ""
resources:
    - src: foto01.jpg
      params:
          weight: -100 # Titelbild des Projekts
draft: true
---
| Projekt                | {{ replace .File.ContentBaseName "-" " " | title }} |
| ---------------------- | ----------- |
| Projektnummer          | ?           |
| Gerätezustand          | ?           |
| Vorgehen               | ?           |
| Interessante Dinge     | ?           |
| Reparatur erfolgreich? | ?           |

Was war der Zustand? Was haben wir gemacht? Was war interessant?
