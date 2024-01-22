
</br>

---
# <p align="center"> Proyectos</p>

---

</br>

> [!info]- Pendientes
> > ```dataview
>>TABLE
>>	status AS Estado, tags AS Tags, type AS Tipo
>>FROM "2-Proyectos" or #proyecto 
>>WHERE status = "Pendiente"
>>AND type = "Proyecto"
>>AND name != "<% tp.file.title %>"
>>```
>

> [!multi-column]
>
> > [!sumary|left]  [[4-Recursos/Páginas/Home|Home]]
> </br>
>>
>>> [!blank-container]
>>> `ris:Folder2` [[Entradas]]
>>
>>> [!blank-container]
>>> `ris:ContrastDrop2` [[Proyectos]]
>>
>>> [!blank-container]
>>> `ris:Inbox` [[Áreas]]
>>
>>> [!blank-container]
>>> `ris:Database2` [[Recursos]]
>>
>>> [!blank-container]
>>> `ris:Archive` [[Archivos]]
>
> > [!multi-column|pw6]
> >
> > > [!tldr]- Acciones
>>> ```button
>>> name Nueva Entrada
>>>type command
>>> action QuickAdd: Nueva Entrada
>>> ```
>>>```button
>>> name Nueva Área
>>>type command
>>> action QuickAdd: Nueva Área
>>> ```
>>>```button
>>> name Nuevo Recurso
>>>type command
>>> action QuickAdd: Nuevo Recurso
>>> ```
>>>```button
>>> name Nuevo Proyecto
>>>type command
>>> action QuickAdd: Nuevo Proyecto
>>> ```
> >
> > > [!info]- Recordatorios
> > > ```dataview
>>>TABLE
>>>	estado, tags, momento
>>>FROM "1-Entrada"
>>>WHERE moment = "Proyectos"
>>>```
> >
> > > [!tip] Proyectos
> > > ```dataview
>>>TABLE
>>>	status AS Estado, tags AS Tags, type AS Tipo
>>>FROM "2-Proyectos" or #proyecto 
>>>WHERE status = "Andando"
>>>AND name != "<% tp.file.title %>"
>>>```

</br>

---

</br>




