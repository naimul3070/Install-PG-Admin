# Install-PG-Admin
# With pgAdmin you can manage PostgreSQL database servers, from version 9.2 using an intuitive and powerful web interface. We have guides on installing pgAdmin 4 on other platforms.


# Step 1: And pgAdmin4 repository toUbuntu 20.04|18.04

    sudo curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add

![image](https://user-images.githubusercontent.com/50922314/159623316-2a6997ee-020c-4732-9795-985537e19ce9.png)


# Use the next command given to add pgAdmin repository in your Ubuntu system:

    sudo sh -c 'echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list'

![image](https://user-images.githubusercontent.com/50922314/159623346-4758ce65-9d7a-452b-80aa-24fb35f026c5.png)


# You can check the contents of the repository file created using the following command:

    cat /etc/apt/sources.list.d/pgadmin4.list

    deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/bullseye pgadmin4 main

![image](https://user-images.githubusercontent.com/50922314/159623406-4eda2c25-f81c-44ec-962b-df409c1eb4e2.png)


# Step 2: Install pgAdmin4 on Ubuntu 20.04|18.04

    sudo apt update
    sudo apt install pgadmin4


![image](https://user-images.githubusercontent.com/50922314/159623431-ab4ce2d7-0bde-4573-86c7-db4359712bff.png)


Hit the y key to continue with the installation ofpgAdmin4 on Ubuntu 20.04/18.04:

![image](https://user-images.githubusercontent.com/50922314/159623503-358c5c34-a70b-41c3-8ebc-30f8004780f9.png)

# Now from Files you can ger acces to you pg admin control panel

![image](https://user-images.githubusercontent.com/50922314/159623667-00016a2a-9d4c-41ae-84d6-569df285b89e.png)




