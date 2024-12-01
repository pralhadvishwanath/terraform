Here we are going to learn variables

#resource.tf block
resource "aws_vpc" "webapp_vpc" {
cidr_block = "20.20.0.0/16"
tags = {
  "Name" = "WEBAPP-VPC"
}
}

