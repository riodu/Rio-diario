
</br>

---
# <p align="center"> <% tp.file.title %></p>

---

</br>


> [!multi-column]
>
> > [!sumary|left]  [[4-Recursos/Páginas/Home|Home]]
> </br>
>>
>>> [!blank-container]
>>> `ris:Folder2` [[Proyectos]]
>>
>>> [!blank-container]
>>> `ris:ContrastDrop2` [[Áreas]]
>>
>>> [!blank-container]
>>> `ris:Inbox` [[Entradas]]
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
> > > [!info]- Inbox
> > > ```dataview
>>>TABLE
>>>	estado, tags, momento
>>>FROM "<% tp.file.folder(relative=false)%>"
>>>WHERE type = "<% tp.file.title %>"
>>>```
> >
> > > [!tip] <% tp.file.title %>
> > > - ### Project A
> > > 	- completed
> > > - ### Project B
> > > 	- ongoing



