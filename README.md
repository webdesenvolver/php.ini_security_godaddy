# php.ini_security_godaddy

## como melhorar a seguraça do php com o php.ini?
  coloque o abaixo no final do seu php.ini incluindo os comentarios  e reinicie o php  <br>
	<br>
;>=== Start of PHP Selector Custom Options ===<br>
log_errors=Off<br>
session.use_strict_mode = 1<br>
assert.active = 0<br>
disable_functions = exec,passthru,shell_exec,system,proc_open,popen,assert,pcntl_exec<br>
auto_prepend_file = /home/pasta_user/public_html/_appadmin/firewall.desenvolvedor.org/firewall.php<br>
;<=== End of PHP Selector Custom Options =====<br>
