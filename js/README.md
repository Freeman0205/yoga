# creating-tabs

This code allows you to use tabs so that when you click on them, certain content appears that corresponds to this tab, the rest of the content is hidden. Interaction takes place using an eventListener.

Данный код позволяет использовать табы, что бы при клике на них появлялся определенный контент, соответствующий данному табу, отсальной контент скрывается. Взаимодействие происходит с помощью обработчика событий.

let tab = document.querySelectorAll('.info-header-tab'),  //  ('.class_tabs')  
let info = document.querySelector('.info-header'),    //  ('.Parent_class_tabs') (Родительский класс) 
let tabContent = document.querySelectorAll('.info-tabcontent'); //   ('.Info_content_class') (Непосредственно контент связываемый с табами)
