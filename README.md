# **Just in Time Access Management App**

## **Overview**

This app allows developers to temporary access servers and databases in the **production** environment with more secure and reduce risk of unauthorized access.

---

## **Features**

### 1. **Workflow**
- Developers request access to specific production environments.
- Superiors (Team leaders, managers...) approve or reject requests.
- System tracks the access duration and revokes it when the time expires.

### 2. **Request Access**
- Developers create request access with infos:
  - **Reason**.  
  - **Duration** (Min 1 hour, max 8 hours).  
  - **Other resources** (server names, databases, ...).
- Developers update request to complete or fail
- Developers may cancel request (before approved)

### 3. **Approval Process**
- Superiors receive real-time notifications of access requests.
- Superiors can approve or reject requests
- Superiors can add comments or feedback during approval.  

### 4. **System Tracking**
- The system automatically grants access for the specified duration when approved.
- Warning when time is running out: send notifications to developer
- Revoke access automatically when time is expired.
- Sent notification to superiors when developers complete request
- Log action of all developers, superiors or system
- Bug statistics

### 5. **Other features (Optional)**
- Superiors grant approval permission for other people.
- Performance statistics of developers

---

## **Conclusion**

The **Just in Time Access Management App** reduces downtime, enhances productivity, and enforces strict security measures.
