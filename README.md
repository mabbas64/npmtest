# npmtest
test NPM

;; Start Powershell as Admin, then type:
Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
npm install -g npm-windows-upgrade
 
;;now always use below command to update npm:
npm-windows-upgrade -p -v latest
