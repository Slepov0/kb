## How to work with Postgres docker container 

#### To connect to Postgres container

```bash
sudo docker exec -it <dbName> bash
```



![image-20220824165926588](\image-20220824165926588.png)

#### Create database:

```bash
create database cdmsapp

```

#### Create user with password:

```bash
create user postgres with encrypted password 'postgres'
```

#### Change user's password:

```bash
alter user postgres with password='NEW_PASSWORD'
```

#### Assignee user with database

```bash
grant all privileges on database <dbName>  to <userName>
```

![image-20220824170706577](\image-20220824170706577.png)

![image-20220824170746085](\image-20220824170746085.png)

## Linux usual terminal commands

#### **`pwd`**  command 

Print your current directory 

#### **`ls`** command 

Shows list of contents of your current directory

#### **`cd`** command

This command refers to "**c**hange **d**irectory"  and uses for switching directory

#### **`cp`** command

Uses for copy files 

#### **`rm`** command

Uses for removing file

#### **`rm`** command



#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command
#### **`rm`** command