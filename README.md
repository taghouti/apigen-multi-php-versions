1. `git clone https://github.com/gharlan/apigen.git`
2. `sudo mv apigen /opt/`
3. `sudo ln -s /opt/apigen/apigen.php /bin/apigen`
4. `echo "sudo rm -rf /opt/lampp && sudo ln -s /opt/lampp72 /opt/lampp" > /opt/php72`
5. `sudo chmod -R 777 /opt/php72`
6. `echo "sudo rm -rf /opt/lampp && sudo ln -s /opt/lampp56 /opt/lampp" > /opt/php56`
7. `sudo chmod -R 777 /opt/php56`
8. `apigen -s /opt/lampp72/htdocs/mind_kernel -d /home/tagh/docs --debug --exclude /opt/lampp72/htdocs/mind_kernel/application/third_party/,/opt/lampp72/htdocs/mind_kernel/system --title "Mind Kernel" --source-code --download --wipeout`
