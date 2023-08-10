# 🐛 [FB App Debugger](https://integrationdbg.io/fbappdebugger)

*Utility for testing and debugging your facebook integration.*

 - TODO add screenshots

### Features

- minimal requirements (PHP8 + Composer)
- debug using app id and app secret or using an access token
- debug on localhost using php built-in web server: `php -S localhost:8000 fbappdebugger.php`
- portable across hosts
- request history
- file-based database
- comprehensive contextual help

### Getting started (Setup)

Replace `<username>` and `<password>` with credentials received via order email, to configure composer autorization:
```shell
composer config http-basic.setup.integrationdbg.io <username> <password>
```

Run create-project to download and install the package requirements: 
```shell
composer create-project integrationdbg/fbappdebugger fbappdebugger
```

### Basic usage

### Advanced usage
