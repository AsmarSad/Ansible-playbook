# Ansible-playbook

1. Instal ansible to your linux machine

```bash
pip install ansible
```

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/eb0ebd4e-e059-442d-b9b4-e2b00bb36fd6/image.png)

---

I created ssh key to connect digital ocean

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/53f16a04-a5fd-417e-b49a-016a3b08d2a5/image.png)

Then took public key and pasted it to digital ocean

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/44d116a6-3b3b-466b-87bb-b1b4ea2ecaa0/image.png)

tea_ssh_key

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/543dff1d-6d37-488f-8066-48394272aa42/image.png)

1. Navigate to your project directory
    
    ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/d11a7fa8-8957-4bce-884b-3680eef75e0a/image.png)
    
2. Create vault file (secret.yml) for keeping secret values

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/d92dc845-a694-4928-a7dc-2a9c69512e52/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/057f92a0-79df-4c08-a5f9-c5457f78a12f/975affef-4ff2-4422-b245-681d49e9ca83/image.png)

Run ansible

```bash
┌──(root㉿kali)-[~/tea-project]
└─# ansible-playbook main.yml --ask-vault-pass

```
