# Open Source Instead of Outsource your Database


## 🎬 Getting Started

### 🤘 Install Appwrite 
Follow our simple [Installation Guide](https://appwrite.io/docs/installation) to get Appwrite up and running in no time. You can either deploy Appwrite on your local machine or, on any cloud provider of your choice. 

> Note: If you setup Appwrite on your local machine, you will need to create a public IP so that your hosted frontend can access it.
  
We need to make a few configuration changes to your Appwrite server. 

1. Create a new project named **todos** in the Appwrite Console.

2. Add a new Web App in Appwrite and enter the endpoint of your website (`localhost, <project-name>.vercel.app etc`)
![Create Web App](https://user-images.githubusercontent.com/20852629/113019434-3c27c900-919f-11eb-997c-1da5a8303ceb.png)

3. Create a new collection named **todos** with the following properties
* **Attributes**
 
Add the following attributes to the collection. 
> Make sure that your Attribute ID exactly matches the key in the images

<p align="center">
  <img width="744" alt="Content Attribute" src="https://user-images.githubusercontent.com/29069505/155617343-6ff674b3-9809-42ac-8175-0f76271b1189.png">
</p>

<p align="center">
  <img width="744" alt="IsComplete Attribute" src="https://user-images.githubusercontent.com/29069505/155617393-f30270af-aa07-4392-a7b2-75b8ce9c60da.png">
</p>

* **Permissions**

Add the following permissions to your collections. These permissions ensure that only registered users can access the collection.

<p align="center">
<img src="https://user-images.githubusercontent.com/20852629/113019801-99bc1580-919f-11eb-9a94-13b1529cb925.png" alt="Collection Permissions" width="400"/>
</p>

## Install

```sh
yarn
```

## Development

From your terminal:

```sh
npm run dev
```
