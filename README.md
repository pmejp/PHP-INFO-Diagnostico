# Php@JCPJ-Info - @JCPJ Business Intelligence system requirements checker


Php@JCPJInfo is a PHP script that allows you to test if your current environment fullfills @JCPJ's requirements, and offers suggestions for improvements.

This script allows you to quickly test the environement where you want to install @JCPJ Business Intelligence.

The default credentials for displaying the results are:

* Login: JCPJ
* Password: JCPJ

You can set server env vars to override them:

* `JCPJ_INFO_LOGIN`
* `JCPJ_INFO_PASSWORD`


It tests:
	
* PHP & MySQL Version
* Apache modules
* PHP Extensions
* PHP Configuration
* MySQL Configuration
* Directories Configuration

## License

This tool is released under the MIT License.
