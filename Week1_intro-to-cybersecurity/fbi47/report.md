In February 2024, Change Healthcare (a division of UnitedHealth Group) was hit by a massive ransomware attack launched by the BlackCat/ALPHV group. The attackers gained access via a Citrix portal account which did not have multi factor authentication enabled. Once inside, they moved laterally over about nine days, stealing data before deploying ransomware across many systems, disrupting healthcare applications. 

Who was affected
The breach impacted over 100 million people, making it one of the largest healthcare data breaches in U.S. history. The data stolen included sensitive healthcare and medical information from patients and other details managed by Change Healthcare’s systems. 

How it could have been prevented
1.	Enable multi factor authentication (MFA) on all external access points (like portal accounts) to reduce risk of credential misuse.
2.	Limit or monitor access privileges, especially for systems with external entry points, so compromise of one account doesn't allow broad lateral movement.
3.	Regular security audits and penetration testing of remote access systems (such as VPNs or Citrix portals) to find misconfigurations.
4.	Strong network segmentation so that if one part is compromised, attackers can’t easily move to critical data stores.
5.	Continuous monitoring and quick detection to spot unusual behavior so intrusions are detected before large scale exfiltration or ransomware deployment.

