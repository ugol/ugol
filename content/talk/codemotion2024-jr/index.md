---
title: Lesson learned dallo sviluppo di JR, un tool di generazione dati sintetica in go
summary: JR @ Codemotion, Milan 2024
tags:
- jr
- kafka
- streaming
- ai
- synthetic
date: "2024-10-22T00:00:00Z"

image:
  caption: JR
  focal_point: Smart
---

JR è il tool open source più avanzato per la generazione di dati sintetici di alta qualità, specificamente progettato per gli sviluppatori che lavorano con applicazioni di streaming ed intelligenza artificiale. JR supporta la localizzazione dei dati, l’iniezione controllata di fault, la customizzazione tramite scripting in Python, Lua o WASM e molto altro, fornendo un controllo senza precedenti nella simulazione di scenari reali.
Gli autori ci mostreranno esempi pratici per affrontare i problemi più comuni nella generazione di dati sintetici, dimostrando come JR possa diventare un alleato fondamentale nello sviluppo di applicazioni di streaming ed AI corrette, resilienti e scalabili.
In questo tool, oltre ad una breve presentazione del tool, vedremo gli "internals" di JR:

- Come generare codice Go in Go
- Come creare plugin in Go
- Vantaggi e svantaggi del template system di Go
