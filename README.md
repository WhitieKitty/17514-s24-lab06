# s24-rec06

The "draw" function seems to duplicate itself. How would you refactor it so that we don't need to rewrite the functionality everytime we introduce a new file type?

Somewhere inside the "draw function", the code seems to be explicitly creating an array of Lines and feeding it to the shape. How would you refactor it so that we don't need to expose and rely on such information inside our Drawing class?