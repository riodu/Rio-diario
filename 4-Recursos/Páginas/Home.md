
</br>

---
# <p align="center"> Home</p>

---

</br>

> [!info]- Pendientes
> > ```dataview
>>TABLE
>>	status AS Estado, tags AS Tags, type AS Tipo
>>FROM "1-Entrada" or "2-Proyectos" or "3-Áreas"
>>WHERE status != "Completado"
>>and type != ""
>>```
>>

> [!multi-column]
>
> > [!sumary|left] [[Home]] 
>>
>>
>>> [!blank-container]
>>> `ris:Inbox` [[Entradas|Inbox]]
>>
>>> [!blank-container]
>>> `ris:Check` [[4-Recursos/Páginas/Tareas|Tareas]]
>>
>>> [!blank-container]
>>> `ris:Folder` [[4-Recursos/Páginas/Universidad|Universidad]]
>> ---
>>> [!blank-container]
>>> `ris:Folder2` [[Proyectos]]
>>
>>> [!blank-container]
>>> `ris:ContrastDrop2` [[Áreas]]
>>
>>> [!blank-container]
>>> `ris:Database2` [[Recursos]]
>>
>>> [!blank-container]
>>> `ris:Archive` [[Archivos]]
>> ---
>>> [!blank-container]
>>> `ris:Database` [[4-Recursos/Páginas/Database|Database]]
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
>>>WHERE estado != "completado"
>>>AND momento = "entrada"
>>>```
> >
> > > [!tip] Espacios
> > >>[!sumary|float-center] <p align="center"> 137 </p>
> > >>
>>>>> [!blank-container|float-left]
>>>> [![lightbulb icon|80](https://img.icons8.com/ios/100/FFFFFF/pencil.png) <br/> <p align="center">Escribir </p>](4-Recursos/Páginas/Escribir)
>>>> 
>>>>> [!blank-container|float-left]
>>>> [![macbook icon|80](https://img.icons8.com/ios/250/FFFFFF/body.png) <br/> <p align="center">Personal </p>](4-Recursos/Páginas/Personal)
>>>>
>>>>> [!blank-container|float-right]
>>>> [![brain icon|80](https://img.icons8.com/ios/250/FFFFFF/book.png) <br/> <p align="center">Aprender</p>](4-Recursos/Páginas/Aprender)
>>>>
>>>>> [!blank-container|float-right]
>>>> [![brain icon|80](https://img.icons8.com/ios/250/FFFFFF/time.png) <br/> <p align="center">Sentidos</p>](4-Recursos/Páginas/Sentidos)

</br>

---

</br>


