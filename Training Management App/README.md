
# Employee Training Management System

## 📌 Project Overview
The **Employee Training Management System** is a **Power Platform** solution designed to streamline employee training assignments, track attendance, and automate notifications. It leverages **Power Apps, SharePoint, and Power Automate** to enhance HR efficiency in managing training programs.

## 🚀 Features
### 🔹 **Power Apps**
1. **Main Screen**  
   - Navigation buttons to access:
     - Assign Training  
     - View Assignments  
     - Employee List  
     - Training Programs  

   ![Screenshot_8-2-2025_16194_make powerapps com](https://github.com/user-attachments/assets/73271dc5-8114-4e78-b596-6ff4b1cf633b)


2. **Assign Training**  
   - Dropdowns to select an **Employee** and **Training Program** (filtered by department).  
   - Button to **assign training** (writes to the Training Assignments List).  

   ![Screenshot_8-2-2025_162026_make powerapps com](https://github.com/user-attachments/assets/04346a00-25b3-41cb-8181-bbc2ef9b6a85)


3. **View Assignments**  
   - Gallery displaying **all assignments** with filters for:  
     - Employee Name  
     - Status  
     - Department  
   - Button to update status (e.g., **Mark as Completed** or **Overdue**).  

   ![Screenshot_8-2-2025_16220_make powerapps com](https://github.com/user-attachments/assets/41d4bc59-1ba0-4602-b513-4252a89c6188)


4. **Employee List**  
   - Displays a **searchable** list of employees.  

 ![Screenshot_8-2-2025_16232_make powerapps com](https://github.com/user-attachments/assets/90ae1472-ac26-417e-bb6e-5a73fa75314a)



5. **Training Programs**  
   - Displays all training programs.  
   - Button to **create/edit training programs**.  

  ![Screenshot_8-2-2025_162357_make powerapps com](https://github.com/user-attachments/assets/502cd58c-30b2-43ad-bdc1-7adbc3ee0e3e)


---

### 🔹 **Power Automate Flows**
1. **Training Assignment Notification**  
   - **Trigger:** When a new training is assigned.  
   - **Action:** Send an email to the employee with details (program name, date, trainer, etc.).  

 ![Screenshot_8-2-2025_165226_make powerapps com](https://github.com/user-attachments/assets/a6596508-5e58-4522-bc3f-341e125f2063)
  ![Screenshot_8-2-2025_165256_make powerapps com](https://github.com/user-attachments/assets/685d5cd3-778b-4256-8af2-57be807d2d06)
  ![Screenshot_8-2-2025_165316_make powerapps com](https://github.com/user-attachments/assets/c2d7c382-ac7c-46a5-9340-c0346a11453d)


2. **Overdue Training Reminder**  
   - **Trigger:** Daily check for overdue training.  
   - **Action:** Send reminder emails to employees. 

 ![Screenshot_8-2-2025_164248_make powerapps com](https://github.com/user-attachments/assets/19a96698-2e35-4864-9c8e-6f5f4ef5b266)
  ![Screenshot_8-2-2025_164559_make powerapps com](https://github.com/user-attachments/assets/b4181215-4712-4736-b3a2-202f318b054c)


3. **Training Completion Acknowledgment**  
   - **Trigger:** When training is marked **Completed**.  
   - **Action:** Send an email confirming completion.  

   ![Screenshot_8-2-2025_16318_make powerapps com](https://github.com/user-attachments/assets/5a7500ff-b630-4726-bfea-b3f458f85343)


4. **Upcoming Training Reminder**  
   - **Trigger:** Daily check for training scheduled in the next 3 days.  
   - **Action:** Send reminder emails to assigned employees.  

 ![Screenshot_8-2-2025_163951_make powerapps com](https://github.com/user-attachments/assets/d3a3826a-4ea9-4272-8957-4c4f57789395)




---

## 📂 **SharePoint Structure**
The system utilizes **three SharePoint lists** to store data:

### **1️⃣ Employees List**
Stores employee details.  
- **Columns:**
  - Employee ID (Text)
  - Name (Text)
  - Department (Choice)
  - Job Title (Text)
  - Email (Text)

### **2️⃣ Training Programs List**
Stores available training programs.  
- **Columns:**
  - Program ID (Text)
  - Program Name (Text)
  - Department (Lookup from Employees List)
  - Trainer Name (Text)
  - Date (Date)

### **3️⃣ Training Assignments List**
Tracks employee training assignments.  
- **Columns:**
  - Assignment ID (Auto-generated ID)
  - Employee (Lookup from Employees List)
  - Training Program (Lookup from Training Programs List)
  - Status (Choice: Assigned, Completed, Overdue)
  - Completion Date (Date)



## 🔧 **Other Features**
✅ **CRUD Operations for:**
- Employees  
- Training Programs  
- Training Assignments  



## 📬 Contact
For questions, feedback, or issues, please reach out via:  
📧 **samiberhanu12@gmail.com **  

