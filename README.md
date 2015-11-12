# sascha10k-content-router
<sascha10k-content-router> is a "DOM-Loader" and router. By providing a javascript object, that defines files 
and names for the routes, it enables you to build Single-Page-Applications in the easiest manner. 

How to use:
1. Create a global variable in javscript containing your routes.
2. Add the <sascha10k-content-router> tag where you want to display the content.

Example:

First define your routes.
    var myRoute = [{
        nameid: "start",
        file: "start.html"
    },
    {
        nameid: "about",
        file: "about.html"
    }]
    
