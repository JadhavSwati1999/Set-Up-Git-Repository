# Set-Up-Git-Repository
Set Up Git Repository
set up a Git repository for amazon linux 2 ec2 server:

1. Create Amazon Linux 2 EC2 instance
2. ssh into EC2 instace

```
ssh -i
```

1. Install git package using yum on Amazon Linux 2 server.

```
sudo yum install git
```

1. To create a respository

```
mkdir myproject
cd myproject
git init
```

This will create a default branch as master.

If you want to create a bare repository.

1. Create a directory with .git extention**What is bare repository?**A bare Git repos­i­to­ry is typ­i­cal­ly used as a Remote Repos­i­to­ry that is shar­ing a repos­i­to­ry among sev­er­al dif­fer­ent peo­ple. You don’t do work right inside the remote repos­i­to­ry so there’s no Work­ing Tree (the files in your project that you edit), just bare repos­i­to­ry data.
    
    ```
    mkdir myproject/project-1.git
    cd myproject/project-1.git
    git init --bare
    ```
    

**to create git repository with branch**

```
git init -b <BRANCH_NAME>
```

This will create a custom branch.
