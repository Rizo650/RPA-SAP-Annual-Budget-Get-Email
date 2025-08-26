# SAP Annual Budget - Get Email (UiPath RPA)

This RPA project automates the retrieval of **Annual Budget emails** from different departments in real-time, classifies them into 3 types (**HO, BU, SU**), and saves the attachments into a shared folder for further processing.  

This is the first part of the **SAP Annual Budget Automation**, followed by the Compile process.

---

## 📌 Project Description

The bot continuously monitors incoming emails containing the subject **"Annual Budget"**, validates the sender/department, and saves attachments into the designated department folder.  
The structured output will later be used by the **SAP Annual Budget Compile** automation.

---

## ✨ Key Features

- Real-time monitoring of incoming emails  
- Filters emails with subject containing **"Annual Budget"**  
- Classifies attachments by department (**HO, BU, SU**)  
- Saves files to designated shared folders  
- Logging and error handling for missing/invalid files  
- Built with **UiPath REFramework** for robustness  

---

## 📂 Project Structure

| Folder/File        | Description                                                   |
|--------------------|---------------------------------------------------------------|
| `Main.xaml`        | Entry point of the automation                                |
| `GetFromEmail.xaml`| Workflow to extract and save email attachments               |
| `Data/`            | Configurations and other supporting files                    |
| `Data/Output/`     | Output folder for downloaded attachments                     |
| `project.json`     | UiPath project metadata                                      |
| `README.md`        | This documentation                                           |

---

## 🚀 How to Run

1. Open `Main.xaml` in UiPath Studio.  
2. Configure your email account (Outlook/Exchange/SMTP as required).  
3. Update the `Config.xlsx` or arguments if needed for folder paths.  
4. Run the process manually or deploy to **UiPath Orchestrator** for unattended execution.  
5. Check the `Data/Output/` subfolders (**HO, BU, SU**) for saved attachments.  

---

## 📋 Requirements

- UiPath Studio (Enterprise, v22.10 or higher)  
- Outlook/Exchange mailbox access  
- Access to the designated shared folder  
- SMTP/Outlook configured for notifications (if enabled)  

---

## 📬 Contact

For questions, improvements, or collaboration:  

- Email: **fadillah650@gmail.com**  
- LinkedIn: [Enrico Naufal Fadilla](https://linkedin.com/in/enrico-naufal-fadilla-54338a256)  
