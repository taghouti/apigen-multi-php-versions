`git clone https://github.com/gharlan/apigen.git && `
`sudo mv apigen /opt/ && `
`sudo ln -s /opt/apigen/apigen.php /bin/apigen && `
`echo "sudo rm -rf /opt/lampp && sudo ln -s /opt/lampp72 /opt/lampp" > /opt/php72 && `
`sudo chmod +x /opt/php72 && `
`echo "sudo rm -rf /opt/lampp && sudo ln -s /opt/lampp56 /opt/lampp" > /opt/php56 && `
`sudo chmod +x /opt/php56 && `
`sudo ln -s /opt/php72 /bin && `
`sudo ln -s /opt/php56 /bin && `
`apigen -s /opt/lampp72/htdocs/mind_kernel -d /home/tagh/docs --debug --exclude /opt/lampp72/htdocs/mind_kernel/application/third_party/,/opt/lampp72/htdocs/mind_kernel/system --title "Mind Kernel" --source-code --download --wipeout`
