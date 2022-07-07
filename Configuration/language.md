# Language 
Terraform language's main purpose is to declare resources . This represents objects .
All the diffrent features are present to accommodate more flexible and convenient resource definition .
```
resource "aws_vpc" "main" {
  cidr_block = var.base_cidr_block
}

<BLOCK TYPE> "<BLOCK LABEL>" "<BLOCK LABEL>" {
  #Block body
  <IDENTIFIER> = <EXPRESSION> #Argument
}
```

# Syntax Consists Of:
* Blocks are containers for objects like resources 
* Arguments assign a value to a name
* Expressions represent a value 
