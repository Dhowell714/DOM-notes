# DOM - Document Object Model
Add javascript to html file - <script src="app.js"></script>

# DOM is the data representation of the objects that comprise the structure and content of a document on the web. It contains but is not limited to:
    - Document
    - Head
        - Meta Tags
        - Link Tags
    - Body
        - Nav
        - Header
        - Div's
        - H1's and so on .....
    - And any of their attributes

# Create element example:
#    let h1tag = document.createElement("h1")
#    h1tag.style.color = "blue"
#    h1tag.innerText = "Good Evening, Mr.Doyle!"
#    document.body.appendChild(h1tag)

See User's computer:
    let info = navigator.oscpu
    console.log(info)

# Access Elements using getElementById:
#    let listTitle = document.getElementById("listTitle")
#    console.log(listTitle)
#    listTitle.innerText = "Insert Title here"

# Accessing elements using querySelector

    Most versatile of all selectors
        - accesses first element if there's more than one
        - returns null if no element is found
        - access by element name, .class, or #id

#   let listItem = document.querySelector("ul li")
#    console.log(listItem)
#    listItem.style.textAlign = "center"

