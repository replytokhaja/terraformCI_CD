provider "aws" {

}

resource "aws_instance" "dev" {
    ami = "ami-08970251d20e940b0"
    instance_type = "t2.micro"
    key_name = "aws_key"
    tags = {
      Name = "dev"
    }
}
