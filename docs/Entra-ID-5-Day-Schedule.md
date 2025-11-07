# Microsoft Entra ID: 5-Day Intensive Learning Program
## Detailed Schedule & Activities

> **💡 Tip**: Use the [Interactive Schedule Timeline](../labs/schedule-timeline.html) to track your progress visually with checkboxes and time tracking!

---

## 📅 **PRE-WORK (Complete Before Day 1)**

### Setup Tasks (1-2 hours)
**Goal**: Have your lab environment ready before starting

#### Account Setup
1. **Azure Free Account** (30 min)
   - Visit: https://azure.microsoft.com/free/
   - Sign up with personal email
   - Verify phone number
   - Note: You'll get $200 credit for 30 days

2. **Microsoft 365 Developer Program** (30 min)
   - Visit: https://developer.microsoft.com/microsoft-365/dev-program
   - Join the program (free)
   - Set up instant sandbox with E5 licenses
   - You'll get 25 user licenses for testing

3. **Bookmark Essential Portals** (15 min)
   - Entra Admin Center: https://entra.microsoft.com
   - Azure Portal: https://portal.azure.com
   - Microsoft 365 Admin: https://admin.microsoft.com
   - Graph Explorer: https://developer.microsoft.com/graph/graph-explorer
   - My Apps: https://myapps.microsoft.com

4. **Install Tools** (15 min)
   - Install Microsoft Authenticator on your phone
   - Install PowerShell 7+ (if not already installed)
   - Consider installing VS Code for scripting

---

## 🌅 **DAY 1: FOUNDATIONS & IDENTITY FUNDAMENTALS**
**Total Time: 6-8 hours**

### Morning Session (9:00 AM - 12:30 PM) - 3.5 hours

#### 9:00 - 10:00 AM: Understanding Microsoft Entra ID (60 min)
**Activity: Reading & Video**

**Read:**
- [ ] What is Microsoft Entra? 
  https://learn.microsoft.com/entra/fundamentals/what-is-entra
- [ ] Entra product family overview
- [ ] Why the rebrand from Azure AD matters

**Watch:**
- [ ] "What is Microsoft Entra ID" (HTMD video series)
  https://www.anoopcnair.com/free-entra-training-videos-start-learning-entra-id/

**Key Takeaways to Write Down:**
- List 5 products in the Entra family
- Explain Zero Trust in your own words
- Describe the difference between authentication and authorization

---

#### 10:00 - 10:15 AM: Break ☕

---

#### 10:15 - 11:45 AM: Core Identity Concepts (90 min)
**Activity: Microsoft Learn Module**

**Complete This Module:**
- [ ] "Introduction to Microsoft Entra"
  https://learn.microsoft.com/training/paths/describe-capabilities-of-microsoft-identity-access/

**Topics Covered:**
- Identity principals (users, groups, devices, apps)
- Directory structure and tenants
- Licensing tiers (Free, P1, P2, Suite)
- Authentication vs authorization
- Identity protection basics

**Hands-On Exercise:**
- Log into your Entra admin center
- Explore the dashboard
- Navigate through different sections
- Take screenshots of key areas

---

#### 11:45 AM - 12:30 PM: Lab Environment Exploration (45 min)
**Activity: Guided Exploration**

**Tasks:**
1. Open Entra admin center (https://entra.microsoft.com)
2. Navigate through all main sections:
   - [ ] Identity (Users, Groups, External Identities)
   - [ ] Applications (Enterprise apps, App registrations)
   - [ ] Protection (Conditional Access, Identity Protection)
   - [ ] Identity Governance
   - [ ] Monitoring & health

3. Open your Microsoft 365 tenant:
   - [ ] Create 5 test users manually
   - [ ] Note down their UPNs

**Document Your Findings:**
- What's your tenant ID?
- What's your primary domain?
- What licenses are assigned?

---

### 🍽️ Lunch Break (12:30 - 1:30 PM)

---

### Afternoon Session (1:30 PM - 5:00 PM) - 3.5 hours

#### 1:30 - 3:00 PM: User & Group Management Lab (90 min)
**Activity: Hands-On Lab**

**Follow This Lab:**
- [ ] AZ-104 Lab 01: Manage Entra ID Identities
  https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_01-Manage_Entra_ID_Identities.html

**Create in Your Tenant:**
1. **Users** (30 min)
   - [ ] 10 individual users (use naming convention: TestUser01-10)
   - [ ] Set profiles (job title, department, location)
   - [ ] Assign various licenses
   - [ ] Practice bulk user import via CSV

2. **Groups** (30 min)
   - [ ] 3 Security Groups (IT-Admins, Marketing, Sales)
   - [ ] 2 Microsoft 365 Groups
   - [ ] 1 Dynamic Group based on department
   - [ ] Add members to groups

3. **Document** (30 min)
   - Take screenshots of your groups
   - Export user list to CSV
   - Create an organizational chart

---

#### 3:00 - 3:15 PM: Break ☕

---

#### 3:15 - 4:30 PM: RBAC & Administrative Roles (75 min)
**Activity: Interactive Learning**

**Complete:**
- [ ] "Manage Microsoft Entra Identities" module
  https://learn.microsoft.com/training/modules/manage-azure-active-directory-identities/

**Hands-On:**
1. **Explore Built-in Roles** (30 min)
   - [ ] Navigate to Roles and administrators
   - [ ] Review Global Administrator role
   - [ ] Review User Administrator role
   - [ ] Review Application Administrator role
   - [ ] Check who has privileged roles

2. **Assign Roles** (30 min)
   - [ ] Create a test admin user
   - [ ] Assign User Administrator role
   - [ ] Test permissions by logging in as that user
   - [ ] Create Helpdesk Administrator role assignment
   - [ ] Document what each role can do

3. **Administrative Units** (15 min)
   - [ ] Create an administrative unit for "Marketing"
   - [ ] Add users and groups to it
   - [ ] Understand delegation scenarios

---

#### 4:30 - 5:00 PM: Day 1 Review & Documentation (30 min)
**Activity: Knowledge Consolidation**

**Create Your Study Notes:**
- [ ] Write a 1-page summary of what you learned
- [ ] List 10 new terms and their definitions
- [ ] Draw a diagram showing:
  - Tenant structure
  - User/group hierarchy
  - Role assignments

**Prepare Questions:**
- Write down any unclear concepts
- Note what you want to explore deeper tomorrow

**End of Day 1 Checkpoint:**
✅ Can create and manage users and groups  
✅ Understand tenant structure  
✅ Know the difference between roles  
✅ Comfortable navigating Entra admin center  

---

## 🔐 **DAY 2: AUTHENTICATION & SECURITY**
**Total Time: 6-8 hours**

### Morning Session (9:00 AM - 12:30 PM) - 3.5 hours

#### 9:00 - 9:30 AM: Day 1 Review & Warm-up (30 min)
**Activity: Quick Recap**

- [ ] Review your notes from Day 1
- [ ] Log into Entra admin center
- [ ] Verify all your test users still exist
- [ ] Quick quiz: Name 5 built-in roles

---

#### 9:30 - 11:00 AM: Authentication Methods Deep Dive (90 min)
**Activity: Reading & Configuration**

**Read Documentation:** (45 min)
- [ ] Authentication methods overview
  https://learn.microsoft.com/entra/identity/authentication/
- [ ] MFA concepts and deployment
- [ ] Passwordless authentication options
- [ ] FIDO2 security keys
- [ ] Windows Hello for Business

**Watch:** (20 min)
- [ ] Microsoft Mechanics: MFA and Passwordless Auth
  Search YouTube: "Microsoft Mechanics MFA"

**Hands-On Setup:** (25 min)
- [ ] Enable your own user for MFA
- [ ] Configure Microsoft Authenticator app
- [ ] Register your phone number
- [ ] Test MFA by signing out and back in
- [ ] Explore authentication methods in your profile

**Key Concepts to Master:**
- What methods are available? (App, SMS, Call, FIDO2, Certificate)
- What's the difference between MFA and passwordless?
- What's the recommended authentication method?

---

#### 11:00 - 11:15 AM: Break ☕

---

#### 11:15 AM - 12:30 PM: Multi-Factor Authentication Lab (75 min)
**Activity: Hands-On Configuration**

**Lab Tasks:**

1. **Configure MFA Policies** (30 min)
   - [ ] Navigate to Protection > Authentication methods
   - [ ] Review authentication methods policy
   - [ ] Enable methods: Microsoft Authenticator, SMS, Voice
   - [ ] Create user groups for MFA testing
   - [ ] Enable per-user MFA for test users

2. **Self-Service Password Reset (SSPR)** (30 min)
   - [ ] Navigate to Password reset
   - [ ] Enable SSPR for your test group
   - [ ] Configure authentication methods (require 2)
   - [ ] Configure notifications
   - [ ] Test SSPR flow as a user
   - [ ] Check audit logs

3. **Password Protection** (15 min)
   - [ ] Enable custom banned password list
   - [ ] Add 10 company-specific terms
   - [ ] Enable password protection for Windows Server AD
   - [ ] Test password policy by creating new user

**Documentation:**
- Take screenshots of your configurations
- Note down any error messages
- Document the user experience

---

### 🍽️ Lunch Break (12:30 - 1:30 PM)

---

### Afternoon Session (1:30 PM - 5:00 PM) - 3.5 hours

#### 1:30 - 2:45 PM: Conditional Access Fundamentals (75 min)
**Activity: Interactive Learning**

**Read Documentation:** (30 min)
- [ ] Conditional Access overview
  https://learn.microsoft.com/entra/identity/conditional-access/overview
- [ ] Common Conditional Access policies
- [ ] What are conditions? (users, apps, locations, devices, risks)
- [ ] What are controls? (grant, block, session)

**Watch Video:** (20 min)
- [ ] "Conditional Access Explained" (Microsoft Mechanics)
  YouTube: "Microsoft Conditional Access"

**Study Common Scenarios:** (25 min)
- [ ] Require MFA for admins
- [ ] Require MFA for all users
- [ ] Block legacy authentication
- [ ] Require compliant device
- [ ] Require approved app
- [ ] Block access from untrusted locations

**Plan Your Policies:**
- Write down 3 policies you'd implement in production
- Consider your organization's needs

---

#### 2:45 - 3:00 PM: Break ☕

---

#### 3:00 - 4:30 PM: Build Conditional Access Policies Lab (90 min)
**Activity: Hands-On Policy Creation**

**Important: Work in Report-Only Mode First!**

**Create These Policies:**

1. **Policy 1: Require MFA for Admins** (20 min)
   - [ ] Navigate to Protection > Conditional Access
   - [ ] Create new policy: "CA001-Require-MFA-Admins"
   - [ ] Users: Select all admin roles
   - [ ] Cloud apps: All cloud apps
   - [ ] Conditions: Any location
   - [ ] Grant: Require MFA
   - [ ] Enable in Report-only mode
   - [ ] Test and review what-if results

2. **Policy 2: Block Legacy Authentication** (20 min)
   - [ ] Create: "CA002-Block-Legacy-Auth"
   - [ ] Users: All users (exclude break-glass account)
   - [ ] Cloud apps: All cloud apps
   - [ ] Conditions: Client apps = Legacy authentication clients
   - [ ] Access controls: Block
   - [ ] Enable in Report-only mode

3. **Policy 3: Require Compliant Device for M365** (20 min)
   - [ ] Create: "CA003-Require-Compliant-Device"
   - [ ] Users: All users
   - [ ] Cloud apps: Office 365
   - [ ] Grant: Require device to be marked as compliant
   - [ ] Report-only mode

4. **Policy 4: Risk-Based Sign-In Protection** (20 min)
   - [ ] Create: "CA004-Sign-In-Risk-Policy"
   - [ ] Users: All users
   - [ ] Conditions: Sign-in risk = Medium or High
   - [ ] Grant: Require MFA
   - [ ] Report-only mode

5. **Test Your Policies** (10 min)
   - [ ] Use the What If tool
   - [ ] Simulate different scenarios
   - [ ] Review potential impact

**Documentation:**
- Screenshot each policy configuration
- Document the logic behind each policy
- Note any conflicts or overlaps

---

#### 4:30 - 5:00 PM: Identity Protection Introduction (30 min)
**Activity: Exploration & Setup**

**Explore Identity Protection:**
- [ ] Navigate to Protection > Identity Protection
- [ ] Review risk detections types
- [ ] Check risky users dashboard
- [ ] Check risky sign-ins dashboard
- [ ] Configure risk policies:
  - User risk policy
  - Sign-in risk policy

**Simulate a Risk:**
- [ ] Use Tor Browser to sign in (triggers anomaly)
- [ ] Or use VPN from different country
- [ ] Check if it appears in risky sign-ins
- [ ] Investigate the detection

**Day 2 Checkpoint:**
✅ MFA configured and tested  
✅ SSPR enabled  
✅ 4 Conditional Access policies created  
✅ Identity Protection explored  
✅ Understand risk-based access  

---

## 🏢 **DAY 3: ENTERPRISE INTEGRATION & HYBRID IDENTITY**
**Total Time: 6-8 hours**

### Morning Session (9:00 AM - 12:30 PM) - 3.5 hours

#### 9:00 - 9:30 AM: Review & Prep (30 min)
**Activity: Security Concepts Review**

**Quick Quiz:**
- [ ] What's the difference between authentication and authorization?
- [ ] Name 3 MFA methods
- [ ] What does a Conditional Access policy need?
- [ ] When should you use report-only mode?

**Today's Goals:**
- Understand enterprise app integration
- Learn Single Sign-On (SSO)
- Explore hybrid identity scenarios
- Connect external applications

---

#### 9:30 - 11:00 AM: Enterprise Applications Overview (90 min)
**Activity: Reading & Exploration**

**Read Documentation:** (45 min)
- [ ] Enterprise applications overview
  https://learn.microsoft.com/entra/identity/enterprise-apps/
- [ ] Single sign-on options (SAML, OIDC, Password)
- [ ] Application Proxy for on-prem apps
- [ ] Five steps to integrate apps
  https://learn.microsoft.com/entra/fundamentals/five-steps-to-full-application-integration

**Understand SSO Protocols:** (30 min)
- SAML 2.0 (most legacy apps)
- OpenID Connect / OAuth 2.0 (modern apps)
- Password-based SSO (apps without federation)
- Linked SSO (just a link)
- Header-based (via App Proxy)

**Explore Enterprise Apps:** (15 min)
- [ ] Navigate to Applications > Enterprise applications
- [ ] Browse the gallery (2600+ pre-integrated apps)
- [ ] Check what apps are already there
- [ ] Review consent and permissions

---

#### 11:00 - 11:15 AM: Break ☕

---

#### 11:15 AM - 12:30 PM: SSO Configuration Lab (75 min)
**Activity: Hands-On App Integration**

**Lab: Add Gallery Apps with SSO**

1. **Add Salesforce** (20 min)
   - [ ] Enterprise apps > New application
   - [ ] Search for "Salesforce"
   - [ ] Add Salesforce
   - [ ] Configure SAML-based SSO
   - [ ] Assign users/groups
   - [ ] Test SSO (use developer account if you have one)

2. **Add Slack** (20 min)
   - [ ] Add Slack from gallery
   - [ ] Configure SSO
   - [ ] Set up provisioning (optional)
   - [ ] Assign test users
   - [ ] Document configuration steps

3. **Add AWS** (20 min)
   - [ ] Add Amazon Web Services
   - [ ] Configure SAML SSO
   - [ ] Understand role-based access
   - [ ] Review trust relationship

4. **Test My Apps Portal** (15 min)
   - [ ] Log in as test user
   - [ ] Visit https://myapps.microsoft.com
   - [ ] Verify apps appear
   - [ ] Test SSO to apps
   - [ ] Customize app collections

**Documentation:**
- Screenshot each app configuration
- Note any challenges
- Document the end-user experience

---

### 🍽️ Lunch Break (12:30 - 1:30 PM)

---

### Afternoon Session (1:30 PM - 5:00 PM) - 3.5 hours

#### 1:30 - 2:30 PM: Hybrid Identity Concepts (60 min)
**Activity: Study Session**

**Read Documentation:** (40 min)
- [ ] Hybrid identity overview
  https://learn.microsoft.com/entra/identity/hybrid/
- [ ] Microsoft Entra Connect overview
- [ ] Authentication options:
  - Password Hash Synchronization (PHS)
  - Pass-Through Authentication (PTA)
  - Federation with AD FS
- [ ] Cloud Sync vs Entra Connect

**Watch Video:** (20 min)
- [ ] "Hybrid Identity with Entra Connect" (Microsoft Learn)
  Search: "Microsoft Entra Connect overview"

**Key Questions to Answer:**
- When would you use hybrid identity?
- What gets synchronized?
- What are the authentication options?
- PHS vs PTA vs Federation - pros/cons?

---

#### 2:30 - 3:30 PM: Microsoft 365 Integration Deep Dive (60 min)
**Activity: M365 Exploration**

**Explore M365 Integration:** (30 min)
- [ ] Open Microsoft 365 admin center (https://admin.microsoft.com)
- [ ] Navigate to Azure Active Directory
- [ ] See how it links to Entra admin center
- [ ] Check user licenses
- [ ] Review Security & Compliance center

**Key M365 Services Using Entra ID:**
- [ ] Exchange Online (email)
- [ ] SharePoint Online (document management)
- [ ] Microsoft Teams (collaboration)
- [ ] OneDrive (file storage)
- [ ] Power Platform (low-code apps)

**Configure M365 Access:** (30 min)
- [ ] Set up Conditional Access for M365
- [ ] Configure SharePoint external sharing
- [ ] Set up Teams guest access
- [ ] Review compliance settings

---

#### 3:30 - 3:45 PM: Break ☕

---

#### 3:45 - 5:00 PM: Microsoft Graph API & PowerShell (75 min)
**Activity: Automation Basics**

**Introduction to Microsoft Graph:** (30 min)
- [ ] Open Graph Explorer (https://developer.microsoft.com/graph/graph-explorer)
- [ ] Sign in with your account
- [ ] Run sample queries:
  - GET /me (your profile)
  - GET /users (all users)
  - GET /groups (all groups)
  - GET /applications (all apps)
- [ ] Explore the Graph documentation

**PowerShell Basics:** (45 min)

**Install Microsoft Graph PowerShell:**
```powershell
# Open PowerShell as Administrator
Install-Module Microsoft.Graph -Scope CurrentUser
```

**Connect and Run Commands:**
```powershell
# Connect to Microsoft Graph
Connect-MgGraph -Scopes "User.Read.All", "Group.Read.All"

# Get all users
Get-MgUser -All

# Get a specific user
Get-MgUser -UserId "user@domain.com"

# Get all groups
Get-MgGroup -All

# Create a new user
$PasswordProfile = @{
    Password = "ComplexPassword123!"
}
New-MgUser -DisplayName "API Test User" `
    -MailNickname "apitest" `
    -UserPrincipalName "apitest@yourdomain.onmicrosoft.com" `
    -PasswordProfile $PasswordProfile `
    -AccountEnabled

# Add user to group
New-MgGroupMember -GroupId "group-id" -DirectoryObjectId "user-id"
```

**Practice Tasks:**
- [ ] List all users with PowerShell
- [ ] Create 5 users with PowerShell
- [ ] Add them to a group
- [ ] Export user list to CSV
- [ ] Delete the test users

**Day 3 Checkpoint:**
✅ Understand enterprise app integration  
✅ Configured SSO for multiple apps  
✅ Understand hybrid identity  
✅ Can use Microsoft Graph  
✅ Basic PowerShell automation  

---

## 🔐 **DAY 4: GOVERNANCE & ADVANCED FEATURES**
**Total Time: 6-8 hours**

### Morning Session (9:00 AM - 12:30 PM) - 3.5 hours

#### 9:00 - 9:30 AM: Review & Security Check (30 min)
**Activity: Review Progress**

**Review Past 3 Days:**
- [ ] Check all your policies are still in place
- [ ] Verify users and groups
- [ ] Test SSO to apps
- [ ] Review sign-in logs for patterns

**Today's Focus:**
- Identity Governance
- Privileged Identity Management
- Advanced Entra Suite features
- Production-ready configurations

---

#### 9:30 - 11:00 AM: Identity Governance Concepts (90 min)
**Activity: Reading & Understanding**

**Read Documentation:** (60 min)
- [ ] Entra ID Governance overview
  https://learn.microsoft.com/entra/id-governance/
- [ ] Entitlement management
- [ ] Access packages
- [ ] Access reviews
- [ ] Lifecycle workflows
- [ ] Terms of use

**Key Concepts to Master:**
- What is identity governance?
- What problems does it solve?
- What are access packages?
- What are access reviews?
- What are lifecycle workflows?

**Watch Video:** (30 min)
- [ ] "Identity Governance Overview" (Microsoft)
  YouTube: Search "Microsoft Entra ID Governance"

---

#### 11:00 - 11:15 AM: Break ☕

---

#### 11:15 AM - 12:30 PM: Entitlement Management Lab (75 min)
**Activity: Hands-On Configuration**

**Setup Access Packages:**

1. **Create a Catalog** (15 min)
   - [ ] Navigate to Identity Governance > Entitlement management
   - [ ] Create new catalog: "IT Resources"
   - [ ] Add resources:
     - Groups
     - Applications
     - SharePoint sites

2. **Create Access Package** (30 min)
   - [ ] Create "Marketing Tools Access"
   - [ ] Add resources:
     - Marketing Security Group
     - Adobe Creative Cloud app
     - SharePoint Marketing site
   - [ ] Configure policies:
     - Who can request? (All users)
     - Require approval?
     - Manager approval
     - Expiration: 90 days
     - Enable recurrence
   - [ ] Set up notifications

3. **Test Access Request Flow** (20 min)
   - [ ] Log in as test user
   - [ ] Go to https://myaccess.microsoft.com
   - [ ] Request access to package
   - [ ] Approve as manager
   - [ ] Verify access granted

4. **Configure Access Review** (10 min)
   - [ ] Create quarterly review for "Marketing Tools Access"
   - [ ] Managers review their team members
   - [ ] Auto-remove access if not approved

---

### 🍽️ Lunch Break (12:30 - 1:30 PM)

---

### Afternoon Session (1:30 PM - 5:00 PM) - 3.5 hours

#### 1:30 - 2:30 PM: Privileged Identity Management (PIM) (60 min)
**Activity: Study & Setup**

**Read Documentation:** (30 min)
- [ ] PIM overview
  https://learn.microsoft.com/entra/id-governance/privileged-identity-management/
- [ ] Just-In-Time (JIT) access
- [ ] Approval workflows
- [ ] Access reviews for privileged roles
- [ ] PIM alerts

**Key Concepts:**
- Eligible vs Active assignments
- Activation process
- Maximum activation duration
- MFA on activation
- Justification requirements

**Watch:** (15 min)
- [ ] "PIM Explained" (Microsoft Security)
  YouTube: "Microsoft PIM"

**Setup PIM:** (15 min)
- [ ] Navigate to Identity Governance > Privileged Identity Management
- [ ] Configure role settings for Global Administrator
- [ ] Set activation maximum duration (4 hours)
- [ ] Require MFA on activation
- [ ] Require justification

---

#### 2:30 - 3:30 PM: PIM Hands-On Lab (60 min)
**Activity: Practice JIT Access**

**Lab Tasks:**

1. **Make Role Eligible** (20 min)
   - [ ] Create test admin user
   - [ ] Assign User Administrator role as ELIGIBLE (not active)
   - [ ] Set assignment duration: 30 days
   - [ ] Configure role settings:
     - Activation max: 8 hours
     - Require MFA
     - Require approval (optional)
     - Require ticket number

2. **Activate Role** (20 min)
   - [ ] Log in as test user
   - [ ] Navigate to PIM
   - [ ] Request activation of User Administrator
   - [ ] Provide justification
   - [ ] Complete MFA
   - [ ] Wait for approval (if required)
   - [ ] Verify activation

3. **Monitor PIM Activity** (20 min)
   - [ ] Check PIM alerts
   - [ ] Review audit logs
   - [ ] Check role activation history
   - [ ] Set up notifications for privileged role changes

**Documentation:**
- Screenshot the activation process
- Document the user experience
- Note any challenges

---

#### 3:30 - 3:45 PM: Break ☕

---

#### 3:45 - 5:00 PM: Advanced Entra Suite Features (75 min)
**Activity: Exploration**

**Explore Extended Entra Family:**

1. **Entra Domain Services** (15 min)
   - [ ] Read about managed domain services
   - [ ] When to use it? (legacy apps needing LDAP/Kerberos)
   - [ ] How it integrates with Entra ID
   - Documentation: https://learn.microsoft.com/entra/identity/domain-services/

2. **Entra Verified ID** (20 min)
   - [ ] Read about decentralized identity
   - [ ] Understand verifiable credentials
   - [ ] Review use cases (diplomas, certifications)
   - Documentation: https://learn.microsoft.com/entra/verified-id/

3. **Entra Private Access** (20 min)
   - [ ] Understanding Zero Trust Network Access
   - [ ] How it replaces VPN
   - [ ] Quick Assist setup (if available)
   - Documentation: https://learn.microsoft.com/entra/global-secure-access/

4. **Entra Internet Access** (20 min)
   - [ ] Secure web gateway
   - [ ] Microsoft 365 traffic optimization
   - [ ] Threat protection
   - Review capabilities

**Take Notes:**
- Which features would benefit your organization?
- What problems do they solve?
- What's the licensing requirement?

**Day 4 Checkpoint:**
✅ Understand identity governance  
✅ Created and tested access packages  
✅ Configured PIM and tested JIT access  
✅ Familiar with advanced Entra features  
✅ Know the complete Entra suite  

---

## 🚀 **DAY 5: PRODUCTION READINESS & CAPSTONE**
**Total Time: 6-8 hours**

### Morning Session (9:00 AM - 12:30 PM) - 3.5 hours

#### 9:00 - 9:45 AM: Monitoring & Reporting (45 min)
**Activity: Logs and Analytics**

**Explore Monitoring Tools:**

1. **Sign-In Logs** (15 min)
   - [ ] Navigate to Monitoring > Sign-in logs
   - [ ] Filter by:
     - User
     - Application
     - Status (success/failure)
     - Conditional Access result
   - [ ] Export logs
   - [ ] Create filters for risky sign-ins

2. **Audit Logs** (15 min)
   - [ ] Navigate to Audit logs
   - [ ] Filter by activity type
   - [ ] Review changes made in past 7 days
   - [ ] Export for compliance

3. **Diagnostic Settings** (15 min)
   - [ ] Set up Log Analytics workspace
   - [ ] Configure diagnostic settings
   - [ ] Send logs to Log Analytics
   - [ ] Create workbook

---

#### 9:45 - 11:00 AM: Security Monitoring Deep Dive (75 min)
**Activity: Advanced Monitoring**

**Configure Azure Monitor:** (30 min)
- [ ] Create Log Analytics workspace
- [ ] Connect Entra ID to Log Analytics
- [ ] Write KQL queries:
  ```kql
  // Failed sign-ins by user
  SigninLogs
  | where ResultType != 0
  | summarize FailedLogins = count() by UserPrincipalName
  | order by FailedLogins desc
  
  // Conditional Access failures
  SigninLogs
  | where ConditionalAccessStatus == "failure"
  | project TimeGenerated, UserPrincipalName, AppDisplayName, ConditionalAccessPolicies
  
  // Risky sign-ins
  SigninLogs
  | where RiskLevelDuringSignIn != "none"
  | project TimeGenerated, UserPrincipalName, Location, RiskLevelDuringSignIn
  ```

**Create Dashboards:** (30 min)
- [ ] Build monitoring dashboard
- [ ] Add key metrics:
  - Total sign-ins (success/failure)
  - MFA usage rate
  - Conditional Access impact
  - Risky sign-ins
  - Privileged role activations

**Set Up Alerts:** (15 min)
- [ ] Create alert for failed sign-ins > 10 in 5 minutes
- [ ] Alert for new privileged role assignment
- [ ] Alert for risky user detected

---

#### 11:00 - 11:15 AM: Break ☕

---

#### 11:15 AM - 12:30 PM: Best Practices & Production Planning (75 min)
**Activity: Strategy Session**

**Review Best Practices:**

1. **Security Best Practices** (25 min)
   - [ ] Read: Security best practices for Entra ID
     https://learn.microsoft.com/entra/architecture/
   - [ ] Zero Trust framework
   - [ ] Break-glass accounts
   - [ ] Privileged account strategy
   - [ ] Monitoring requirements

2. **Deployment Planning** (25 min)
   - [ ] Read: Deployment plans
     Download from GitHub: https://aka.ms/deploymentplans
   - [ ] MFA rollout plan
   - [ ] Conditional Access rollout
   - [ ] SSPR deployment
   - [ ] Change management

3. **Architecture Design** (25 min)
   - [ ] Review reference architectures
   - [ ] Hybrid identity design
   - [ ] Multi-tenant considerations
   - [ ] Disaster recovery planning
   - [ ] Backup strategies

**Create Your Checklist:**
- [ ] Pre-production checklist
- [ ] Go-live checklist
- [ ] Post-deployment tasks
- [ ] Monitoring and maintenance plan

---

### 🍽️ Lunch Break (12:30 - 1:30 PM)

---

### Afternoon Session (1:30 PM - 5:00 PM) - 3.5 hours

#### 1:30 - 3:30 PM: Capstone Project (120 min)
**Activity: End-to-End Implementation**

**Scenario: Design Complete Identity Solution for Fictional Company**

**Company Profile:**
- Name: Contoso Corporation
- 500 employees
- 5 office locations (US, UK, Germany, Japan, Australia)
- Uses Microsoft 365
- Has on-premises Active Directory
- Needs to secure access to:
  - M365 apps
  - Salesforce
  - AWS
  - Custom internal apps
- Compliance requirements: SOC2, GDPR

**Your Task: Design & Implement**

1. **Architecture Design** (30 min)
   - [ ] Draw architecture diagram
   - [ ] Hybrid identity strategy (Entra Connect)
   - [ ] Authentication method (PHS recommended)
   - [ ] Licensing requirements
   - [ ] Network requirements

2. **Security Implementation** (40 min)
   - [ ] Create 5 Conditional Access policies:
     1. Require MFA for all users
     2. Require MFA for admins (all locations)
     3. Block legacy auth
     4. Require compliant device for M365
     5. Block access from non-trusted countries
   - [ ] Configure Identity Protection policies
   - [ ] Set up PIM for admin roles

3. **Governance Setup** (30 min)
   - [ ] Design 3 access packages:
     - Sales Department Access
     - Engineering Access
     - Executive Access
   - [ ] Configure lifecycle workflows
   - [ ] Set up quarterly access reviews

4. **Application Integration** (20 min)
   - [ ] Plan SSO for 5 apps
   - [ ] Document integration steps
   - [ ] User provisioning strategy

**Deliverables:**
- Architecture diagram
- Policy documentation
- Deployment timeline
- Risk assessment
- Cost estimate

---

#### 3:30 - 3:45 PM: Break ☕

---

#### 3:45 - 4:45 PM: Latest Features & What's Next (60 min)
**Activity: Staying Current**

**Review 2025 Updates:** (30 min)
- [ ] Read: What's New in Microsoft Entra
  https://learn.microsoft.com/entra/fundamentals/whats-new
- [ ] Recent features:
  - API-driven provisioning (GA)
  - Passkey profiles
  - Security Copilot integration
  - Conditional Access optimization agent
  - Custom OIDC providers

**Future Roadmap:** (15 min)
- [ ] Visit Microsoft 365 Roadmap
  https://www.microsoft.com/microsoft-365/roadmap
- [ ] Filter by "Azure AD" or "Identity"
- [ ] Note upcoming features

**Community & Continued Learning:** (15 min)
- [ ] Join Microsoft Tech Community
  https://techcommunity.microsoft.com/category/identity
- [ ] Subscribe to Identity blog
  https://devblogs.microsoft.com/identity/
- [ ] Follow Microsoft Entra on YouTube
- [ ] Consider SC-300 certification path

---

#### 4:45 - 5:00 PM: Final Review & Reflection (15 min)
**Activity: Knowledge Assessment**

**Self-Assessment:**

Rate yourself (1-5) on:
- [ ] Understanding of Entra ID fundamentals
- [ ] User and group management skills
- [ ] MFA and authentication configuration
- [ ] Conditional Access policy creation
- [ ] Enterprise app integration (SSO)
- [ ] Identity governance concepts
- [ ] PIM implementation
- [ ] Monitoring and troubleshooting
- [ ] PowerShell/Graph API basics
- [ ] Architecture design skills

**What You've Accomplished:**
✅ Complete understanding of Microsoft Entra ID
✅ Hands-on experience with all major features
✅ Built production-ready configurations
✅ Created comprehensive capstone project
✅ Ready to implement in real environment

**Next Steps:**
1. Review your capstone project
2. Clean up your test environment (or keep for practice)
3. Join community forums
4. Consider SC-300 certification
5. Apply learnings to your organization
6. Stay current with monthly updates

---

## 📊 **Post-5-Day Follow-Up Activities**

### Week After Completion

**Day 6-7: Consolidation** (2-4 hours)
- [ ] Review all documentation
- [ ] Create personal reference guide
- [ ] Organize screenshots and notes
- [ ] Build personal lab environment guide

**Day 8-10: Deep Dive Topics** (Pick 2-3)
- [ ] B2B Collaboration deep dive
- [ ] Application Proxy setup
- [ ] Advanced PowerShell automation
- [ ] Azure AD Connect detailed study
- [ ] Device management with Intune
- [ ] Entra External ID

**Day 11-14: Practice & Experiment**
- [ ] Build test scenarios
- [ ] Break and fix exercises
- [ ] Advanced Graph API queries
- [ ] Custom reporting dashboards

---

## 🎯 **Success Metrics Checklist**

After 5 days, you should be able to:

### ✅ **Foundational Skills**
- [ ] Explain Entra ID to technical and non-technical audiences
- [ ] Navigate Entra admin center confidently
- [ ] Create and manage users, groups, and roles
- [ ] Understand licensing and feature availability

### ✅ **Security Skills**
- [ ] Configure MFA and passwordless authentication
- [ ] Build effective Conditional Access policies
- [ ] Implement risk-based access controls
- [ ] Set up identity protection

### ✅ **Integration Skills**
- [ ] Configure SSO for enterprise applications
- [ ] Understand hybrid identity options
- [ ] Use Microsoft Graph API
- [ ] Write basic PowerShell scripts

### ✅ **Governance Skills**
- [ ] Create and manage access packages
- [ ] Set up access reviews
- [ ] Implement PIM for privileged access
- [ ] Configure lifecycle workflows

### ✅ **Operational Skills**
- [ ] Monitor sign-ins and audit logs
- [ ] Create dashboards and reports
- [ ] Troubleshoot common issues
- [ ] Plan enterprise deployments

---

## 💡 **Tips for Success**

### **Do's:**
- ✅ Take detailed notes
- ✅ Create screenshots of every configuration
- ✅ Test everything as end user
- ✅ Ask questions in community forums
- ✅ Take breaks when needed
- ✅ Practice with real scenarios
- ✅ Stay hydrated and rested

### **Don'ts:**
- ❌ Skip the hands-on labs
- ❌ Rush through concepts
- ❌ Forget to document your work
- ❌ Enable policies in production without testing
- ❌ Skip the capstone project
- ❌ Neglect security best practices
- ❌ Try to memorize everything (understand concepts)

---

## 📚 **Daily Checklist Template**

Print this and use for each day:

```
Date: ___________  Day: ___________

Morning Goals:
[ ] _______________________
[ ] _______________________
[ ] _______________________

Afternoon Goals:
[ ] _______________________
[ ] _______________________
[ ] _______________________

Key Learnings:
1. _______________________
2. _______________________
3. _______________________

Questions/Challenges:
1. _______________________
2. _______________________

Tomorrow's Prep:
[ ] _______________________
[ ] _______________________

Energy Level: ☆☆☆☆☆
Understanding: ☆☆☆☆☆
Confidence: ☆☆☆☆☆
```

---

## 🎓 **Congratulations!**

By completing this 5-day intensive program, you've gained:
- Comprehensive knowledge of Microsoft Entra ID
- Hands-on experience with enterprise identity management
- Skills to implement secure access solutions
- Foundation for Microsoft certifications
- Confidence to manage production environments

**You're now ready to secure identity and access in the modern enterprise!**

**Keep Learning. Stay Secure. 🚀**

---

*Program Version: 1.0*
*Last Updated: November 2025*
*Based on latest Microsoft Entra releases*
