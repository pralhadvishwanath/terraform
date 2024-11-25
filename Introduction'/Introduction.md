resource "aws_vpc" "myapp_network" {
  cidr_block = "10.20.0.0/16"
  tags = {
    "Name" = "MY-Pralhad-APP-VPC"
  }
}
