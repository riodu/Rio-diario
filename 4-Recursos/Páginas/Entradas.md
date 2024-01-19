
</br>

---
# <p align="center"> Entradas</p>

---

</br>

> [!info]- Pendientes
> > ```dataview
>>TABLE
>>	estado, tags, momento
>>FROM "1-Entrada"
>>WHERE estado = "Pendiente"
>>AND momento = "Entrada"
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
>>>WHERE moment = "Entrada"
>>>```
> >
> > > [!tip] Entradas
> > > ```dataview
>>>TABLE
>>>	estado, tags, momento
>>>FROM "1-Entrada"
>>>WHERE momento = "Entrada"
>>>AND estado = "Andando"
>>>```

</br>

---

</br>




