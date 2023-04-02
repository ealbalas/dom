# dom
Properties : used to get and set objects
 - innerHTML
 - style
 - firstChild

Methods : used to perform functions
 - click()
 - appendChild()
 - setAttribute()

 The HTML file is a tree. We can change objects by diving into it using properites such as 'firstElementChild' and 'innerHTML' and then change the object through it

#142
 To change the third item in the list from 'Third' to 'Emad' you can enter this into the console:
 'document.firstElementChild.lastElementChild.firstElementChild.nextElementSibling.nextElementSibling.nextElementSibling.lastElementChild.innerHTML = "Emad";'

#143
 When we search for "li" using 'getElementsByTagName()' the system will return an array. We can not modify all items at once. To select an item we can use the brackets like any normal array. Then we can use the properites to find the thing we want to change and set it accordingly. Its also important to mention even if there is only one element we still have to specify the index to change anything.

 When using the querySelector() we can search using item type, id, or class. 
  - for type just enter it in quotes ("")
  - for id have # infront so it looks for id ("#id")
  - for class have . infront so it looks for class (".class")

  We can even specify even more combining the selectors. To select the reference in the list object is done like this ("li a")
  To select the list with class item (li.a) and to select a id with reference (#list a)
  If multiple objects have the same class or tag with you selectors then it will only return the first object. If you want to get all objects then you need to used a different function called querySelectorAll()

  querySelector is used more cause you can be specific.