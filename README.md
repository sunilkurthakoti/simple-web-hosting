# **Simple Web Hosting on Azure Blob Storage**

Deploying a static website using **Azure Blob Storage**.

---

## **1. Azure Blob Storage**

### **Service Purpose**

Azure Blob Storage hosts your static website files.

### **Steps**

1. **Create a Storage Account**  
   - Go to **Azure Portal** → **Storage Accounts** → **Create**.

![Screenshot (38)](https://github.com/user-attachments/assets/0b4bb383-b6ab-4501-a77f-d99e1b69f1ad)


2. **Enable Static Website Hosting**  
   - In your storage account, go to **Static Website**.
   - Set:  
     - **Index Document**: `index.html`  
     - **Error Document**: `error.html` (optional)

3. **Get the Primary Endpoint**  
   - Example: `https://sunilwebstorage.z13.web.core.windows.net`
  
![Screenshot (39)](https://github.com/user-attachments/assets/f1f9ec95-2cde-44e4-a345-802f78076138)


---

## **2. Upload Website Files**

### **Service Purpose**

Upload static files like `index.html` and `error.html` to your storage account.


### **Steps**

1. **Go to the `$web` Container**  
   - In your storage account, open the **`$web`** container.

2. **Upload Files**  
   - Upload `index.html` and `error.html`.
  
![Screenshot (40)](https://github.com/user-attachments/assets/48c74d4f-5090-444c-9445-5c794c394993)

---

## **3. Access Your Website**

### **Service Purpose**

View your static website through the primary endpoint.

### **Steps**

1. **Visit the Primary Endpoint**  
   - Open the URL: `https://sunilwebstorage.z13.web.core.windows.net`
  
![Screenshot (43)](https://github.com/user-attachments/assets/b046c0a9-3954-46b6-8446-b61238cd09d0)


---
