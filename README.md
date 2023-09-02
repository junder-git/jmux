# jmux - ((tmux wrapper)) 
Current limmitations are on the amount of tmux panes (not windows) you can fit verticaly set to four...  

## To install jmux run below two commands)
### Run this only once to add line to your ~./bashrc) 
echo "source ~/jmux.sh" >> ~/.bashrc
### Run this as many times you like to update the jmux wrapper)
curl -o ~/jmux.sh https://raw.githubusercontent.com/jabl3s/jmux/main/jmux.sh && source ~/.bashrc && jmux  
### After doing the above the shortcut below is now available from now on whenever an update is ready
jmux update
## jmux command sudo command example)
e.g.) jmux command [number_of_panes] 'echo "yourpassword" | sudo -S apt get update'
## A jmux connect example)
1.e.g.) jmux connect ubuntu@192.168.1.1 ubuntu@192.168.1.2 ubuntu@192.168.1.3 ubuntu@192.168.1.4  
2.e.g.) jmux command 4 echo "wassup from tmux"    
![Alt text](/assets/images/image-1.png)  
  





