---
date: {{ .Date }}
draft: false
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
description: "Resumen breve del articulo"
categories:
  - contexto
tags:
  - analisis
---

Escribe aqui el contenido del articulo.
