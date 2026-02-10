# OS-Patches-Deployment-Guide.md
Step by Step of os patches deployment on support247

# Deploying Missing OS Patches by Policy - ITSupport247 Guide

## Prerequisites
- Active ConnectWise + ITSupport247 RMM access
- Administrative permissions for patch deployment

## Step-by-Step Instructions

### 1. Access ITSupport247 Dashboard
Log in to ConnectWise → Click "Asio"
(/login.png)

Navigate to the **ITSupport247 dashboard**.

### 2. Navigate to Automation
Dashboard → Find "Automation" section


Locate the **Automation** module in the main dashboard.

(/select.png)

### 3. Schedule Patch Deployment
Right panel → Hover over clock icon → Click
(/clock.png)

- Choose **"Run Now"** or **"Schedule"** deployment
- Select **target devices/groups** for patch deployment
- Click **"Run"** to save and execute the scheduled task
(/run.png)

### 4. Monitor Results
View deployment status, success rates, and logs


Results appear in the Automation history and reporting sections.

## Best Practices
✅ Weekly deployment (Patch Tuesday aligned)
✅ Test on pilot group first
✅ Schedule during off-peak hours
✅ Monitor compliance reports post-deployment


## Expected Outcomes
- Automatic detection of missing OS patches
- Policy-based deployment across targets
- Compliance reporting and audit trail
