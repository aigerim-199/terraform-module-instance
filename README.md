# terraform-module-instance

```hcl
module "instance" {
  source  = "aigerim-199/instance/module"
  version = "2.0.0"
  instance_type = "t2.micro"  # Replace with your values
  instance_name = "Hello"     # Replace with your values
}

#!/bin/bash

sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2
sudo systemctl enable apache2
```