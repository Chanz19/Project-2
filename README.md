# DOM Operations:

    >> DOM: Document Object Model
    >> Its a representation of a web tree

HTML Boiler Plate:
    <html>
        <head>
            <title></title>
        </head>
        <body>
             <h1></h1>
        </body>
    </html>

DOM Representation:
                              html
                head                       body
                  title                    h1


Day One => One Day

const data = {
    name: "Chanz",
    age: 34
}
undefined
console.log(data)
VM240:1 {name: 'Chanz', age: 34}
undefined
console.log({data})
VM323:1 {data: {...}}data: {name: 'Chanz', age: 34}[[Prototype]]: Object
undefined
console.log({...data})
VM423:1 {name: 'Chanz', age: 34}
undefined
console.log({...data, company: "Taccan"})
VM662:1 {name: 'Chanz', age: 34, company: 'Taccan'}