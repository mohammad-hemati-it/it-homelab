# Active Directory Lab

Domain controller and client setup on ESXi running inside VMware Workstation.

## Environment

- Domain: mohammad.local
- Domain Controller: srv_widow (Windows Server)
- Client: client_win
- Hypervisor: ESXi (nested in VMware Workstation)

## What I Built

- AD DS installation and domain promotion
- Client joined to the domain
- File sharing with permission configuration
- Backup of the DC with Veeam Backup & Replication

## Steps
در ابتدا در ویندوز سرور اکتیو دایرکتوری را با نام mohammad.local ایجاد کردم و در ان ویندوز دیگرم را عضو دامین کردم بعد از ان فایلی را در درون ویندوز سرورفایلی به اشتراک گزاشتم و روی آن ntfs premission های مختلف را تست کردم و با ویندوز دیگرم به عنوان کلاینت این قابلیت هارا تست کردم

## Screenshots

TODO

## Problems and Solutions
برای عضو دامین کردن ویندوزکلاینت به مشکل خوردم که فهمیدم رنجی که برای دامین در نظر گرفته شده 192.168.201.0 هست که با رنج در نظر گرفته شده برای ویندوز کلاینت یکسان هست که با عوض کردن رنج مشکل حل شد
