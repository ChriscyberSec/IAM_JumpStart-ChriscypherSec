# Hello, I am Chris

A Cybersecurity enthusiast with profound interest in technology and dedicated to solving cybersecurity problems

## Objective
Building practical SOC skills through hands-on SIEM detection engineering and IAM implementation  from log pipelines to access governance.

### Skills Learned
- User Provisioning & Deprovisioning : managing account lifecycle (onboarding, role changes, offboarding) to prevent orphaned or stale accounts that attackers can exploit.
- Role-Based Access Control (RBAC) & Least Privilege Enforcement : designing and auditing access policies so users only have the permissions needed for their role.
- Multi-Factor Authentication (MFA) Implementation & Management : configuring and enforcing MFA across systems to reduce credential-based attack risk.
- Access Reviews & Privileged Account Auditing : conducting periodic reviews of user/admin permissions and flagging excessive or unused privileges (especially privileged/admin accounts).
- Active Directory / Azure AD (Entra ID) Administration — managing users, groups, GPOs, and conditional access policies within on-prem or cloud directory services.

### Tools Used

- AWS IAM — managing users, roles, policies, and permissions boundaries across AWS environments
- Microsoft Entra ID (Azure AD) — cloud identity management, conditional access, and SSO administration
- Active Directory (AD DS) — on-premises directory services, Group Policy, and domain-level access control
- Okta — identity federation, SSO, and lifecycle management across SaaS applications
- CyberArk — privileged access management (PAM), securing and auditing privileged/admin credentials

  ## Project 1 : Hands-On AWS Project: Enforcing Least Privilege with IAM Policies

## Steps 1: Created  a Sandbox S3 Bucket (The Resource)

<img width="935" height="350" alt="AWS-bucket" src="https://github.com/user-attachments/assets/d576b26f-4f0f-4490-aa7c-0f92b3b5987d" />

## Two S3 bucket resources created specifically for the Development and Production Teams

<img width="609" height="447" alt="AWS" src="https://github.com/user-attachments/assets/c0f1518e-01e3-437e-9395-fc9d670d66eb" />

## Step 2: Wrote Custom Least-Privilege JSON Policies

## Policy A: Software Engineer Policy(as jmpstart-iam-software-poliy)

<img width="609" height="447" alt="AWS-policy2" src="https://github.com/user-attachments/assets/b9adf2f4-33df-4c47-824d-1c21df0f2da7" />



## Policy B : Database Administrator Policy(as jmpstart-iam-DBA-policy)

<img width="758" height="416" alt="AWS-policiez" src="https://github.com/user-attachments/assets/245b4026-1eae-4cbf-b4f7-a7fd86768768" />

## Step 3: Created User Groups and Assign Personas
Following best practices, I had to assign these policies to Groups, not individual users.

<img width="750" height="415" alt="AWS-group-policiez" src="https://github.com/user-attachments/assets/ca381357-f98e-4307-8f15-4e3780e2906d" />

## Created two users and added them to their specific groups

<img width="737" height="388" alt="AWS-userz" src="https://github.com/user-attachments/assets/ffb85b7e-b158-4d13-b5a2-c18b93b4fd56" />

## Checked each users privileges and certain permissions they have within shared resources

<img width="944" height="419" alt="AWS-Tommy-DB" src="https://github.com/user-attachments/assets/0b5fc69b-467f-4f03-bb17-4a77bb06c820" />







*Ref 1: Network Diagram*
