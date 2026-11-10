# GitHub publication guide

1. Review the README, findings, screenshot gallery and evidence limitations. Confirm permission to share the selected lab screenshots.
2. Use only this repository directory. Keep the sibling private archive and academic source folder outside Git.
3. Create an empty GitHub repository named `techshield-cybersecurity-assessment` after approving the public content. Start private if you want an additional review stage.
4. From this directory, run the commands below, replacing YOUR-USERNAME with your account name.

```sh
git init
git add .
git diff --cached --stat
git diff --cached
git commit -m "Add TechShield cybersecurity assessment portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/techshield-cybersecurity-assessment.git
git push -u origin main
```

5. Check GitHub rendering, image links and repository visibility. Pin the repository on your profile when ready.

Suggested description — Authorized cybersecurity lab assessment covering Nmap, Greenbone, DVWA, exploitation validation and NTFS forensics.

Suggested topics — cybersecurity, penetration-testing, vulnerability-assessment, nmap, openvas, dvwa, digital-forensics, capstone.

Suggested LinkedIn summary — Completed a cybersecurity capstone covering network discovery, vulnerability assessment, web application testing and digital forensics. The portfolio documents evidence-supported findings, remediation priorities and assessment limitations.

No license is applied automatically because source-material redistribution rights have not been established. Review rights before selecting a license. Publication is a user-controlled step after package approval.
