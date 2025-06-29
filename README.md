# php.ini_security_godaddy

## como melhorar a seguraça do php com o php.ini?
coloque o abaixo no final do seu php.ini e reinicie o php<>
;>=== Start of PHP Selector Custom Options ===
log_errors=Off
;<=== End of PHP Selector Custom Options =====
session.use_strict_mode = 1
assert.active = 0
disable_functions = exec,passthru,shell_exec,system,proc_open,popen,assert,pcntl_exec
