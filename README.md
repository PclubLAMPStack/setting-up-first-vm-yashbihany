[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/MNKuYdJP)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11037941&assignment_repo_type=AssignmentRepo)

# To setup a Kernel based Virtual Machine

I first installed centOS iso file from the link provided and vmware workstation player application from the vmware site.Following steps helped me to install a non-GUI virtual machine :
1)Open the vmware player->Create a New Virtual Machine->Select location of the iso file in ur system->create a new account(with personalised information)->Specify Disk capacity(around 20-40 gb) and also select the Split virtual disk into multiple files->click on Finish.
2)after the vm startup you will be prompted with the gnome help center(i think u can remove gnome from their help center as well but i didnt have any clue). So just bashed the terminal with these commands :
>sudo yum update(to update my package list)<br>
>yum remove gnome*(which removes all the groups named gnome which is responsible for the gui)<br>

I then restarted the vmware<br>
Virtual Machine with only command line was setup. 
