# SmartARB Setup Guide

## Components Required

- **Copilot Studio**
- **Environment Variables**
  - SharePoint Site  
  - SharePoint List (**ProjectSubmission**) to store ProjectDetails  
- **Connection References**
  - SharePoint  
  - Word Online  
- **Cloud Flows**
- **Database → SharePoint**
  - **SharePoint Document Library** (**ProjectSubmissions**) to store dynamically generated Word documents  
  - Store the ARB document template (**ARB.docx**) in the "Documents" library  
  - **SharePoint List: ProjectSubmission** with the following columns:  

    | Column Name         | Type                          |
    |---------------------|-----------------------------|
    | **Description**     | Multiple lines of text      |
    | **Department**      | Single line of text         |
    | **Stakeholders**    | Single line of text         |
    | **UserCount**       | Number                      |
    | **Authentication**  | Single line of text         |
    | **Technology**      | Single line of text         |
    | **PowerPlatformTools** | Single line of text      |
    | **Database**        | Single line of text         |
    | **API Integration** | Single line of text         |
    | **DataFeed**        | Single line of text         |
    | **Compliance**      | Single line of text         |
    | **Auditable**       | Boolean                     |
    | **ExpectedStartDate** | Date                      |
    | **LicenseDetails**  | Single line of text         |
    | **Support**         | Single line of text         |
    | **Status**          | Choice (Submitted, Under Review, Approved) |

---

## Installation Steps

1. **Download** the SmartARB zip file from this GitHub repository.  
2. **Go to the Power Apps Maker Portal:** [https://make.powerapps.com/](https://make.powerapps.com/)  
3. **Ensure** you are in a Power Platform environment where you have solution import permissions.  
4. **Navigate** to "Solutions".  
5. **Click** "Import solution".  
6. **Browse** and select the downloaded `.zip` file.  
7. **Click** "Next" and then "Import".  
8. **Wait** for the solution import to complete successfully.  

---

Once imported, configure environment variables and test the solution. 🎯
