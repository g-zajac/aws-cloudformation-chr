<a href="http://gz.technology" target="_blank">![logo](doc/logo.png)</a>

# AWS Cloudformation template to create Mikrotik CHR

This project is about deploying on AWS an infrastructure with VPC, public subnet and spinning up a EC2 instance with Mikrotik CHR from custom image.

## Built With
* [Atom](https://atom.io) - An amazing text editor

## Usage / Prerequisites
Run the template in AWS console or in CLI:
Clone the repository to a local folder
```bash
aws cloudformation create-stack --stack-name CHR --template-body file://chr_cf_template.yml
```

## License
This project is licensed under [MIT license](http://opensource.org/licenses/mit-license.php)

## Project status
- code in develpoment stage under tests
