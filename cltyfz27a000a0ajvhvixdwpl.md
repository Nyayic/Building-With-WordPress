---
title: "How to Install WordPress via XAMPP"
datePublished: Tue Mar 19 2024 14:00:13 GMT+0000 (Coordinated Universal Time)
cuid: cltyfz27a000a0ajvhvixdwpl
slug: how-to-install-wordpress-via-xampp
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1710727759350/ab9b09bb-2023-4b7d-9dd0-213d910e9997.png
tags: wordpress, xampp, how-to-install-wordpress

---

Installing WordPress via XAMPP is a great way to set up a local development environment for building and testing websites. Here's a beginner's installation guide:

## **Step 1: Download XAMPP**

Go to the Apache Friends website and download the latest version of XAMPP for your operating system (Windows, macOS, or Linux).

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710728534463/8c9ea65c-aa74-4f66-8f45-085131bba362.png align="center")

Follow the installation instructions provided by XAMPP to install it on your computer. Make sure to remember the installation directory, as you'll need it later. The Default directory is normally `c:/xampp`

## **Step 2: Start XAMPP and Start Apache and MySQL**

Once installed, start the XAMPP control panel.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710728386024/ee89fe9e-f0fd-481e-8862-238ee843dda3.png align="center")

Start both the Apache and MySQL modules by clicking on the "Start" button next to each.

## **Step 3: Download WordPress**

Go to the [WordPress official website](https://wordpress.org/download/) and download the latest version of WordPress.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710728787287/547aae86-57fb-43be-bac0-6a3300f1d217.png align="center")

Extract the WordPress zip file to a folder directory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710729689978/d8b0a467-aa05-4e6b-9fbf-b25c61e683c6.png align="center")

Copy the extracted files to the xampp folder. Typically, this would be in the `htdocs` folder.

%[https://youtu.be/dA6MqJAaS-M] 

## **Step 4: Create a Database for WordPress**

Open your web browser and go to http://localhost/phpmyadmin/.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710730857658/fefacc6f-3fe0-4f6a-b983-6f61d0e3ddfb.png align="center")

Click on the "Databases" tab and create a new database. Give it a name, e.g.,`mysite`.

## **Step 5: Configure WordPress**

Open your web browser and go to http://localhost/mysite (or whatever folder you extracted WordPress into).

Choose a Language of your choice and click "Continue".

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731051249/62a9d87c-e50b-4000-8ca1-30eafca7bcd7.png align="center")

WordPress will prompt you to create a `wp-config.php` file. Click on the "Let's go" button.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731209636/0e615a97-c2d3-4f24-b04d-4ff24841b2a9.png align="center")

1. Enter the database information:
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731414492/96b3f7c3-37e5-4515-9836-b76124bd46ae.png align="center")
    
    * Database Name: Enter the name of the database you created earlier (e.g., `mysite`).
        
    * Username: By default, it's `root`.
        
    * Password: Leave it blank (unless you've set a password for your MySQL root user).
        
    * Database Host: Enter [`localhost`](http://localhost).
        
    * Table Prefix: You can leave it as the default `wp_` or change it if you prefer.
        
2. Click on the "Submit" button, and WordPress will create the `wp-config.php` file.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731505631/14a3918c-9003-42e2-bae7-04e5521a859a.png align="center")
    
3. Click on the "Run the Installation" button.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731784716/7e6be9cb-e8aa-47dc-9d72-c3edfeacc735.png align="center")
    
4. Fill in the required information for your WordPress site, such as Site Title, Username, Password, and Email Address.
    
5. Click on the "Install WordPress" button.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731833088/b5abcfb4-cada-467b-844a-88df54c7ee1a.png align="center")
    
6. Once the installation is complete, you can log in to your WordPress dashboard using the credentials you provided.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710731904507/d8b57891-7b13-4b5d-bbee-53709d2410fd.png align="center")
    

## **Step 6: Access Your WordPress Site**

Go to [http://localhost/mysite/wp-admin/](http://localhost/wordpress/wp-admin/) to access your WordPress dashboard. Log in using the username and password you set during the installation.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710732025386/c0711dd0-9963-4bdf-94c0-8416d366f061.png align="center")

Congratulations! You have successfully installed WordPress via XAMPP on your computer. Now you can start building and testing your website locally.