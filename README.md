# AWS IAM Tutorial Series: Roles and Permissions (Part 2)
![AWS Banner](https://github.com/KLavallais/KLavallais/blob/assets/aws-banner.png?raw=true)

## Introduction

Welcome back to the second part of our **AWS IAM Tutorial Series**. In Part 1, we covered **users** and **user groups**, focusing on the basics of managing IAM users and permissions in AWS. Now, in **Part 2**, we’ll dive into **roles** and how they allow for dynamic, temporary access control.

This tutorial demonstrates how to create roles, assign them to users, and manage permissions in AWS IAM. I use **Jim Doe** as our example user to show how to temporarily elevate permissions, which can be a vital tool for system administrators. If you’re ready to take your IAM knowledge to the next level, let’s get started!

---

## Summary of the Video

In this tutorial, I walk through the process of creating and assigning **roles** in AWS IAM. Roles are a critical tool for providing temporary permission elevation, and I demonstrate how to:
- **Create an AWS role with administrator access**, providing full access to AWS services.
- **Assign the role to a user**, in this case, **Jim Doe**, to showcase how roles can give users temporary elevated permissions.
- **Switch roles within the AWS Management Console**, showing the difference in permissions when a role is applied versus using user groups alone.
- **Live demonstrations**: I illustrate what happens when Jim Doe, who initially has no permissions, is granted the admin role and suddenly gains full access to AWS services like **EC2** and **Lambda**.

I also cover IAM best practices, such as how roles can be used in scenarios where you might need to temporarily elevate permissions for specific tasks without permanently modifying the user’s permissions.

---

[![Watch the video](https://github.com/KLavallais/KLavallais/blob/assets/AWS%20Series%20Part%202.png)](https://youtu.be/0ZagQprOqDI)

---

## Tools/Programs Used:
- **AWS IAM (Identity and Access Management)**: Used to create and manage roles and assign them to users.
- **AWS Lambda**: Demonstrates full access to Lambda once the role is assigned.
- **AWS EC2**: Shows what happens when a user without permissions tries to access EC2 before being assigned a role.
- **AWS Management Console**: Used for role creation, assignment, and switching between roles.

---

## Skills Demonstrated:
- **Role Creation in AWS IAM**: I show how to create roles, such as an **Administrator Role** with full AWS access, and how to apply those roles to users.
- **Switching Roles**: Demonstrated the process of switching roles for a user in the AWS Management Console to give temporary permissions for tasks.
- **Inline Policy Management**: Explored how to create inline policies using JSON to further customize a user’s permissions.
- **Practical Demonstration of Permission Changes**: By assigning and switching roles, we observed real-time changes in what **Jim Doe** could access (from no access to full admin privileges).
- **AWS Security Best Practices**: While simplifying things for the demonstration, I discussed the importance of using auto-generated passwords, requiring password changes, and best practices for handling sensitive access in a secure manner.

---

## Demonstrated Expertise in IAM/PAM

Through the concepts covered in both Part 1 and Part 2 of this AWS IAM series, I have demonstrated a deep understanding of Identity and Access Management (IAM) and Privileged Access Management (PAM) in cloud environments. By effectively managing users, user groups, permissions, and roles, I have showcased the following core competencies:

- **Expert Role and Permission Management**: My ability to create, assign, and switch roles in real-time demonstrates a comprehensive grasp of how to control user access dynamically. This is a key function in any modern cloud infrastructure where flexibility and security must go hand-in-hand.
  
- **Efficient User Management**: From creating individual user accounts to grouping them into logical user groups with defined permissions, I have proven my ability to maintain organized and secure user management, critical to protecting cloud assets.

- **Granular Control Through Policies**: The use of inline policies with JSON further highlights my proficiency in fine-tuning access controls, ensuring that users and roles have precisely the permissions they need—no more, no less.

- **Practical Application of IAM Principles**: By walking through real-world scenarios such as creating users, assigning roles, and switching permissions, I have demonstrated how to effectively manage access in an AWS environment, a key component of IAM/PAM strategies.

In summary, the skills demonstrated in this series showcase my expertise in using AWS IAM to its fullest potential. Whether it’s setting up user groups, roles, or managing permissions, I am well-equipped to handle the complexities of modern identity and access management, ensuring both security and operational efficiency.

---

Thank you for watching and following along in Part 2 of the AWS IAM tutorial series. I hope the skills and techniques demonstrated here provided valuable insights into the power of roles and permissions in AWS. If you haven’t already, be sure to check out [Part 1](https://github.com/KLavallais/AWSIAM1) to learn the foundational aspects of creating and managing users and user groups in AWS IAM. Have a great day!


