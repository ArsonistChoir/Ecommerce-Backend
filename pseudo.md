Server.js
Import and sync sequelize

Models
Define column for tags, product tags, products, catagory.
Use seeds for reference

Product.js
Import sequelize and config
Intialize table by extending through sequalize (what and how?)
Setup rule (think we did that on mini proj.)

Models>Index.js
// Products belongsTo Category (What connect them?)

// Categories have many Products (I'm assuming have many is a command?)

// Products belongToMany Tags (through ProductTag) (Is Products and Tags gonna borrow from each other)

// Tags belongToMany Products (through ProductTag)